#### Test 807613749c91828_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-17 10:22:09.617  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:22:09.637  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 10:22:09.643  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 10:22:09.721  1496  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-17 10:22:09.722  1496  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 10:22:09.722  1496  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:22:09.723  1496  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-17 10:22:09.758  3700  3700 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-17 10:22:09.759  3700  3700 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-17 10:22:09.760  3700  3700 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-17 10:22:10.283  3951  3951 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-17 10:22:10.288  3951  3951 D AndroidRuntime: CheckJNI is OFF
08-17 10:22:10.332  3951  3951 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-17 10:22:10.383  3951  3951 I Radio-JNI: register_android_hardware_Radio DONE
08-17 10:22:10.406  3951  3951 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-17 10:22:10.410   873   884 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 10:22:10.444  2020  2395 W SearchService: Abort, client detached.
08-17 10:22:10.447  2020  2020 I HotwordDetector: Closing mic
08-17 10:22:10.448  2020  2328 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@95cbf4c
08-17 10:22:10.452  2020  2343 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-17 10:22:10.455  3951  3951 D AndroidRuntime: Shutting down VM
08-17 10:22:10.475   873  2134 I ActivityManager: Start proc 3960:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-17 10:22:10.499   376  2346 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-17 10:22:10.503   376  2346 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-17 10:22:10.508   376  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-17 10:22:10.512  2020  2342 I MicroRecognitionRnrImpl: Detection finished
08-17 10:22:10.513  2020  2334 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-17 10:22:10.564  3960  3960 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-17 10:22:10.587  3960  3960 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-17 10:22:10.597  3960  3960 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 3549-3555)
08-17 10:22:10.598  3960  3960 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 10:22:10.611  3960  3960 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f62a252}
08-17 10:22:10.612  3960  3960 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 10:22:10.612  3960  3960 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 10:22:10.619  3960  3960 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-17 10:22:10.620  3960  3960 E SysUtils: ApplicationContext is null in ApplicationStatus
08-17 10:22:10.632  3960  3960 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-17 10:22:10.641  3960  3960 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 10:22:10.641  3960  3960 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 10:22:10.641  3960  3960 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 10:22:10.641  3960  3960 I Adreno  : Build Date                       : 10/20/15
08-17 10:22:10.641  3960  3960 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 10:22:10.641  3960  3960 I Adreno  : Local Branch                     : M14
08-17 10:22:10.641  3960  3960 I Adreno  : Remote Branch                    : 
08-17 10:22:10.641  3960  3960 I Adreno  : Remote Branch                    : 
08-17 10:22:10.641  3960  3960 I Adreno  : Reconstruct Branch               : 
,08-17 10:22:10.719   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b95b86:true
,08-17 10:22:10.781  3960  3960 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-17 10:22:10.783   873  1302 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-17 10:22:10.799  3960  3960 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-17 10:22:10.877  3960  3999 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-17 10:22:10.890  3960  3985 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-17 10:22:10.946  3960  3999 I OpenGLRenderer: Initialized EGL, version 1.4
,08-17 10:22:11.009   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +553ms
,08-17 10:22:11.021  1875  1875 I Keyboard.Facilitator: onFinishInput()
,08-17 10:22:11.119  3960  3960 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3960
,08-17 10:22:11.294   873  1368 I ActivityManager: Killing 3195:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,08-17 10:22:11.321  3960  3960 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 10:22:11.326   873  1368 I ActivityManager: Killing 3146:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-17 10:22:11.541  3960  4002 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1698760400
,08-17 10:22:11.555  3960  4002 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 10:22:11.555  3960  4002 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 10:22:11.555  3960  4002 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 10:22:11.555  3960  4002 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 10:22:11.555  3960  4002 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-17 10:22:11.555  3960  4002 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@edf4936 added. We now have 1 listener(s)
,08-17 10:22:11.574  3960  4002 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-17 10:22:11.580  3960  4002 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 10:22:11.582  3960  4002 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 10:22:11.583  3960  4002 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 10:22:11.592  3960  4002 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 10:22:11.592  3960  4002 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 10:22:11.592  3960  4002 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 10:22:11.592  3960  4002 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-17 10:22:11.592  3960  4002 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 10:22:11.592  3960  4002 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 10:22:11.592  3960  4002 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 10:22:11.592  3960  4002 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 10:22:11.592  3960  4002 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 10:22:11.592  3960  4002 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 10:22:11.592  3960  4002 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 10:22:11.592  3960  4002 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 10:22:11.592  3960  4002 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 10:22:11.592  3960  4002 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 10:22:11.592  3960  4002 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@404930d added. We now have 1 listener(s)
08-17 10:22:11.592  3960  4002 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:22:11.597   873  1303 D WifiService: New client listening to asynchronous messages
,08-17 10:22:11.599  3960  4002 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 10:22:11.599  3960  4002 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-17 10:22:11.600  3960  4002 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-17 10:22:11.601  3960  4002 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-17 10:22:11.602  3960  4002 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 10:22:11.605  3960  4002 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:22:11.606  3960  4002 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-17 10:22:11.612  3960  4002 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-17 10:22:11.612  3960  4002 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:22:11.612  3960  4002 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:22:11.612  3960  4002 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:22:11.612  3960  4002 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:22:11.612  3960  4002 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:22:11.612  3960  4002 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:22:11.612  3960  4002 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:22:11.612  3960  4002 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:22:11.612  3960  4002 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 10:22:11.612  3960  4002 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:22:11.613  3960  4002 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 10:22:11.779  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:22:11.784  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:22:11.786  3960  3960 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 10:22:12.171  3960  3970 I art     : Background sticky concurrent mark sweep GC freed 72980(6MB) AllocSpace objects, 17(1116KB) LOS objects, 26% free, 24MB/32MB, paused 721us total 146.137ms
,08-17 10:22:12.890  3960  4012 W jxcore-log: Initializing JXcore engine
,08-17 10:22:12.890  3960  4012 W jxcore-log: JXcore engine is ready
,08-17 10:22:12.925  4012  4012 W Thread-358: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-17 10:22:12.925  4012  4012 W Thread-358: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9532]" dev="sockfs" ino=9532 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-17 10:22:12.925  4012  4012 W Thread-358: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-17 10:22:12.925  4012  4012 W Thread-358: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27683]" dev="sockfs" ino=27683 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-17 10:22:12.939  3960  4012 W jxcore-log: Starting JXcore engine
,08-17 10:22:13.016  3960  4012 W jxcore-log: Platform android
08-17 10:22:13.016  3960  4012 W jxcore-log: 
,08-17 10:22:13.016  3960  4012 W jxcore-log: Process ARCH arm
08-17 10:22:13.016  3960  4012 W jxcore-log: 
,08-17 10:22:13.236  3960  4012 I jxcore-log: JXcore Cordova bridge is ready!
08-17 10:22:13.236  3960  4012 I jxcore-log: 
08-17 10:22:13.236  3960  4012 W jxcore-log: JXcore engine is started
,08-17 10:22:13.249  3960  4002 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-17 10:22:13.257  3960  3960 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 10:22:16.089  3244  4018 V KeepSync: Connecting to GoogleApiClient
,08-17 10:22:16.090   873  1966 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-17 10:22:16.146  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:22:16.148  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:22:16.165  1496  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-17 10:22:16.165  1496  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-17 10:22:16.165  1496  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:22:16.165  1496  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:22:16.179  1703  4019 V BaseAuthAsyncOperation: access token request failed
08-17 10:22:16.180  3244  4018 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-17 10:22:16.234  1496  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-17 10:22:16.234  1496  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-17 10:22:16.234  1496  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 10:22:16.234  1496  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:22:16.251  3244  4018 E KeepSync: IOException
08-17 10:22:16.251  3244  4018 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-17 10:22:16.251  3244  4018 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-17 10:22:16.251  3244  4018 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-17 10:22:16.251  3244  4018 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-17 10:22:16.251  3244  4018 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-17 10:22:16.251  3244  4018 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-17 10:22:16.251  3244  4018 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-17 10:22:16.251  3244  4018 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-17 10:22:16.251  3244  4018 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-17 10:22:16.251  3244  4018 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-17 10:22:16.251  3244  4018 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-17 10:22:16.251  3244  4018 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-17 10:22:16.251  3244  4018 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-17 10:22:16.251  3244  4018 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-17 10:22:16.251  3244  4018 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 10:22:16.251  3244  4018 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 10:22:16.251  3244  4018 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-17 10:22:16.251  3244  4018 E KeepSync: 	... 10 more
08-17 10:22:16.252  3244  4018 W KeepSync: Sync result 2
,08-17 10:22:16.263   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 128905, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 10:22:29.790  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 10:22:29.790  3960  4012 I jxcore-log: 
,08-17 10:22:29.793  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 10:22:29.793  3960  4012 I jxcore-log: 
,08-17 10:22:29.806  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:22:29.806  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:22:29.806  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:22:29.806  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:22:29.806  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:22:29.806  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:22:29.806  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:22:29.806  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:22:29.808  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:22:29.810  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 10:22:29.810  3960  4012 I jxcore-log: 
,08-17 10:22:29.811  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 10:22:29.811  3960  4012 I jxcore-log: 
,08-17 10:22:29.996  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:22:30.004  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:22:30.010  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:22:30.050  1496  3160 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-17 10:22:30.050  1496  3160 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-17 10:22:30.050  1496  3160 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 10:22:30.050  1496  3160 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:22:30.068  3700  3700 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-17 10:22:30.068  3700  3700 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-17 10:22:30.068  3700  3700 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-17 10:22:30.185  3960  4012 I jxcore-log: Running unit tests
08-17 10:22:30.185  3960  4012 I jxcore-log: 
,08-17 10:22:30.186  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 10:22:30.186  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266aa0 added. We now have 2 listener(s)
,08-17 10:22:30.187  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 10:22:30.187  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:22:30.187  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 10:22:30.187  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 10:22:30.188  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c985659 added. We now have 2 listener(s)
,08-17 10:22:30.188  3960  4012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:22:30.188  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 10:22:30.190  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:22:30.198  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:22:30.198  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:22:30.198  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:22:30.198  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:22:30.198  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:22:30.198  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:22:30.198  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:22:30.198  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:22:30.201  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:22:30.201  3960  4012 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 10:22:30.202  3960  4012 D ExecuteNativeTests: Running unit tests
,08-17 10:22:30.208  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:22:30.215  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:22:30.263  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 10:22:30.263  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef added. We now have 3 listener(s)
,08-17 10:22:30.264  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 10:22:30.265  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:22:30.265  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 10:22:30.265  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:22:30.265  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc added. We now have 3 listener(s)
08-17 10:22:30.265  3960  4012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:22:30.265  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 10:22:30.267  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:22:30.278  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:22:30.278  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:22:30.278  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:22:30.278  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:22:30.278  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:22:30.278  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:22:30.278  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:22:30.278  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:22:30.282  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:22:30.283  3960  4012 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 10:22:30.293  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:22:30.295  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:22:30.295  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 10:22:30.295  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 10:22:30.295  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 10:22:30.296  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 10:22:30.302  3960  4012 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-17 10:22:30.304  3960  4012 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-17 10:22:30.304  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-17 10:22:30.305  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 10:22:30.305  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 10:22:30.305  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 10:22:30.305  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:22:30.306  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:22:30.306  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:22:30.306  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 10:22:30.306  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:22:30.306  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 10:22:30.306  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 10:22:30.307  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef removed from the list
,08-17 10:22:30.307  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:30.307  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc removed from the list
08-17 10:22:30.307  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:22:30.307  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:30.308  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:30.308  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:30.309  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:22:30.309  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:22:30.309  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:30.310  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:30.311  3960  4012 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-17 10:22:30.312  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:22:30.312  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:22:30.312  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:22:30.312  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:30.312  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:30.312  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:30.313  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
,08-17 10:22:30.313  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:30.313  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:30.313  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:22:30.313  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:22:30.313  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:30.313  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:30.313  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:30.314  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:22:30.314  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:22:30.314  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:22:30.314  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:30.320  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-17 10:22:30.320  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-17 10:22:30.320  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 10:22:30.320  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-17 10:22:30.320  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 10:22:30.320  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 10:22:30.320  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 10:22:30.320  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-17 10:22:30.320  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 10:22:30.320  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 10:22:30.320  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 10:22:30.321  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-17 10:22:30.321  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 10:22:30.321  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 10:22:30.321  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-17 10:22:30.321  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 10:22:30.321  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 10:22:30.321  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 10:22:30.321  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-17 10:22:30.321  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 10:22:30.321  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 10:22:30.321  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-17 10:22:30.321  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 10:22:30.321  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-17 10:22:30.321  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 10:22:30.322  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-17 10:22:30.322  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 10:22:30.322  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 10:22:30.322  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 10:22:30.322  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-17 10:22:30.322  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 10:22:30.322  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:22:30.322  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:22:30.322  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:22:30.322  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 10:22:30.322  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:30.322  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:30.322  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
08-17 10:22:30.322  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:22:30.323  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:30.323  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:22:30.323  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:30.323  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:30.323  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:22:30.323  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:30.324  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:22:30.324  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:22:30.324  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:30.324  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:30.325  3960  4012 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 10:22:30.326  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:22:30.332  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:22:30.332  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:22:30.332  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:22:30.332  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:22:30.332  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:22:30.332  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:22:30.332  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:22:30.332  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:22:30.334  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:22:30.334  3960  4012 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:22:30.335  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 10:22:30.335  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 10:22:30.335  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 10:22:30.335  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:22:30.335  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 10:22:30.338  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:22:30.340  3960  4012 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 10:22:30.340  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 10:22:30.340  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:22:30.345  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 10:22:30.346  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 10:22:30.347  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 10:22:30.349  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-17 10:22:30.352  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-17 10:22:30.352  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 10:22:30.353  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 10:22:30.353  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 10:22:30.354  3960  4012 D BluetoothAdapter: STATE_ON
,08-17 10:22:30.358  2622  2634 D BtGatt.GattService: registerClient() - UUID=329c5d66-da81-411f-96c0-ff0fefc75fe3
08-17 10:22:30.359  2622  2647 D BtGatt.GattService: onClientRegistered() - UUID=329c5d66-da81-411f-96c0-ff0fefc75fe3, clientIf=5
08-17 10:22:30.360  3960  3972 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 10:22:30.360  2622  2635 D BtGatt.GattService: start scan with filters
08-17 10:22:30.363  2622  2657 D BtGatt.ScanManager: handling starting scan
08-17 10:22:30.363  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 10:22:30.364  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 10:22:30.364  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 10:22:30.364  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 10:22:30.365  2622  2657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
,08-17 10:22:30.366  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 10:22:30.367  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 10:22:30.367  3960  3960 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 10:22:30.368  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 10:22:30.372  2622  2647 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 10:22:30.372  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:30.372  2622  2657 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 10:22:30.373  3960  4012 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 10:22:30.377  2622  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 10:22:30.377  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:30.377  2622  2657 D BtGatt.ScanManager: Starting BLE batch scan
08-17 10:22:30.377  2622  2657 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 10:22:30.384  2622  2647 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 10:22:30.384  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:30.391  2622  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 10:22:30.391  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:30.869  3960  3960 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-17 10:22:30.869  3960  3960 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 10:22:30.870  3960  3960 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 10:22:31.899  2622  2622 D BtGatt.ScanManager: awakened up at time 144856
,08-17 10:22:31.903  2622  2657 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:22:31.928  2622  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
08-17 10:22:31.928  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:31.928  2622  2647 D BtGatt.GattService: current time is 144886097463
08-17 10:22:31.929  2622  2647 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -89, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -64, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -85, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-17 10:22:31.930  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-17 10:22:31.931  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-17 10:22:31.931  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-17 10:22:31.932  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-17 10:22:33.434  2622  2622 D BtGatt.ScanManager: awakened up at time 146391
,08-17 10:22:33.436  2622  2657 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:22:33.470  2622  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-17 10:22:33.470  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:33.471  2622  2647 D BtGatt.GattService: current time is 146428583555
08-17 10:22:33.472  2622  2647 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -93, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -80, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -68, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-17 10:22:33.473  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-17 10:22:33.474  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-17 10:22:33.475  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-17 10:22:33.475  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-17 10:22:34.971  2622  2622 D BtGatt.ScanManager: awakened up at time 147928
,08-17 10:22:34.973  2622  2657 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:22:34.985  2622  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 10:22:34.986  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:35.383  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:22:35.383  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:22:35.384  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 10:22:35.384  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:35.384  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-17 10:22:35.385  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 10:22:35.385  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 10:22:35.385  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 10:22:35.386  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 10:22:35.388  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 10:22:35.393  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 10:22:35.396  3960  4012 D BluetoothAdapter: STATE_ON
,08-17 10:22:35.399  2622  2772 D BtGatt.GattService: stopScan() - queue size =1
,08-17 10:22:35.401  2622  2634 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 10:22:35.403  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:22:35.403  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 10:22:35.403  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 10:22:35.404  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-17 10:22:35.404  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 10:22:35.408  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 10:22:35.409  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 10:22:35.409  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 10:22:35.410  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 10:22:35.411  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 10:22:35.414  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 10:22:35.414  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:22:35.414  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 10:22:35.414  3960  3960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:22:35.415  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
,08-17 10:22:35.415  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:22:35.415  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:35.415  3960  3960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 10:22:35.415  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:22:35.415  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:35.415  3960  3960 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 10:22:35.421  2622  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 10:22:35.422  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:35.422  2622  2657 D BtGatt.ScanManager: stopping BLe Batch
,08-17 10:22:35.438  2622  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 10:22:35.438  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:22:35.438  2622  2657 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:22:35.456  2622  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 10:22:35.456  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:35.917  3960  3960 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 10:22:36.872   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-17 10:22:36.880  1875  1875 I Keyboard.Facilitator: onFinishInput()
,08-17 10:22:36.897   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 10:22:36.897   873   893 I Adreno  : Build Date                       : 10/20/15
08-17 10:22:36.897   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 10:22:36.897   873   893 I Adreno  : Local Branch                     : M14
08-17 10:22:36.897   873   893 I Adreno  : Remote Branch                    : 
08-17 10:22:36.897   873   893 I Adreno  : Remote Branch                    : 
08-17 10:22:36.897   873   893 I Adreno  : Reconstruct Branch               : 
,08-17 10:22:36.946   281  4000 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (209 us)
,08-17 10:22:37.588  3960  3960 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 10:22:37.588  3960  3960 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-17 10:22:37.620   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-17 10:22:37.622  3960  3960 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3357138 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@8b659a6, 16908290=android.view.AbsSavedState$1@8b659a6}, android:focusedViewId=100}]}]
,08-17 10:22:37.622  3960  3960 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-17 10:22:37.622  3960  3960 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-17 10:22:37.623  3960  3960 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-17 10:22:37.629   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-17 10:22:37.632   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-17 10:22:37.632   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
08-17 10:22:37.633   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-17 10:22:37.680   873   882 I art     : Background partial concurrent mark sweep GC freed 22676(1520KB) AllocSpace objects, 6(132KB) LOS objects, 33% free, 28MB/43MB, paused 851us total 103.827ms
,08-17 10:22:37.869   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-17 10:22:37.874   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-17 10:22:37.875   873  1329 D SurfaceControl: Excessive delay in setPowerMode(): 242ms
,08-17 10:22:37.880   873   893 I DreamManagerService: Entering dreamland.
,08-17 10:22:37.881   873   893 I PowerManagerService: Dozing...
,08-17 10:22:37.882   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-17 10:22:37.959   376  1310 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-17 10:22:37.960   376  1310 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-17 10:22:37.975  1924  4029 D NfcService: Discovery configuration equal, not updating.
,08-17 10:22:37.978   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 10:22:38.000   873  1302 E native  : do suspend false
,08-17 10:22:38.023   873  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 10:22:38.037   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 10:22:38.050   873  1302 E native  : do suspend true
,08-17 10:22:38.095   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-17 10:22:38.095   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-17 10:22:38.485   873  1302 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-17 10:22:40.417  3960  4012 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 10:22:40.422  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:22:40.437  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:22:40.437  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:22:40.437  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:22:40.437  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:22:40.437  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:22:40.437  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:22:40.437  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:22:40.437  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:22:40.444  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:22:40.444  3960  4012 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 10:22:40.445  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 10:22:40.445  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 10:22:40.445  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 10:22:40.446  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:22:40.446  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 10:22:40.455  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:22:40.458  3960  4012 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 10:22:40.459  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 10:22:40.464  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:22:40.472  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 10:22:40.474  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 10:22:40.475  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 10:22:40.486  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 10:22:40.486  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 10:22:40.487  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 10:22:40.489  3960  4012 D BluetoothAdapter: STATE_ON
,08-17 10:22:40.497  2622  2772 D BtGatt.GattService: registerClient() - UUID=db9a2083-5ec4-49d7-bfd7-851861590f35
,08-17 10:22:40.498  2622  2647 D BtGatt.GattService: onClientRegistered() - UUID=db9a2083-5ec4-49d7-bfd7-851861590f35, clientIf=5
,08-17 10:22:40.500  3960  3972 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 10:22:40.501  2622  4027 D BtGatt.GattService: start scan with filters
,08-17 10:22:40.512  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 10:22:40.513  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 10:22:40.513  2622  2657 D BtGatt.ScanManager: handling starting scan
,08-17 10:22:40.513  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 10:22:40.513  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 10:22:40.524  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 10:22:40.524  2622  2647 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 10:22:40.525  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 10:22:40.525  3960  3960 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 10:22:40.524  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:22:40.526  2622  2657 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 10:22:40.532  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 10:22:40.541  3960  4012 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 10:22:40.544  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:22:40.544  3960  4012 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 10:22:40.544  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:22:40.544  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 10:22:40.544  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:22:40.544  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-17 10:22:40.544  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 10:22:40.544  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 10:22:40.544  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 10:22:40.544  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 10:22:40.545  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 10:22:40.545  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 10:22:40.546  3960  4012 D BluetoothAdapter: STATE_ON
08-17 10:22:40.546  2622  2772 D BtGatt.GattService: stopScan() - queue size =1
,08-17 10:22:40.547  2622  4027 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 10:22:40.547  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:22:40.547  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 10:22:40.547  2622  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 10:22:40.547  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 10:22:40.548  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 10:22:40.548  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 10:22:40.547  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:40.549  2622  2657 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 10:22:40.549  2622  2657 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 10:22:40.549  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 10:22:40.550  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 10:22:40.550  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 10:22:40.550  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 10:22:40.550  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:22:40.551  3960  3960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:22:40.551  3960  3960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:22:40.551  3960  3960 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 10:22:40.552  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:40.552  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:40.552  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:22:40.552  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
08-17 10:22:40.552  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:22:40.552  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:40.552  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:22:40.552  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:40.553  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:40.553  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:40.554  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:22:40.554  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:22:40.554  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:22:40.554  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:40.555  3960  4012 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 10:22:40.560  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:22:40.565  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:22:40.565  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:22:40.565  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:22:40.565  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:22:40.565  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:22:40.565  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:22:40.565  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:22:40.565  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:22:40.567  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:22:40.568  3960  4012 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:22:40.569  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 10:22:40.569  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 10:22:40.570  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 10:22:40.570  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:22:40.570  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 10:22:40.570  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:22:40.572  2622  2647 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 10:22:40.572  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:40.573  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:22:40.574  3960  4012 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 10:22:40.574  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 10:22:40.579  2622  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 10:22:40.579  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 10:22:40.579  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:40.580  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 10:22:40.580  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 10:22:40.585  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 10:22:40.585  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 10:22:40.585  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 10:22:40.585  2622  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 10:22:40.585  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:22:40.585  2622  2657 D BtGatt.ScanManager: stopping BLe Batch
08-17 10:22:40.586  3960  4012 D BluetoothAdapter: STATE_ON
,08-17 10:22:40.589  2622  2635 D BtGatt.GattService: registerClient() - UUID=6ff3927b-2832-4f6f-bc8a-6b0e680fa195
,08-17 10:22:40.589  2622  2647 D BtGatt.GattService: onClientRegistered() - UUID=6ff3927b-2832-4f6f-bc8a-6b0e680fa195, clientIf=5
,08-17 10:22:40.589  3960  3972 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 10:22:40.590  2622  2634 D BtGatt.GattService: start scan with filters
08-17 10:22:40.591  2622  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 10:22:40.591  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:22:40.591  2622  2657 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:22:40.593  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 10:22:40.594  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 10:22:40.594  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 10:22:40.594  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 10:22:40.597  2622  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 10:22:40.597  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:40.598  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 10:22:40.598  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 10:22:40.598  2622  2657 D BtGatt.ScanManager: handling starting scan
,08-17 10:22:40.598  3960  3960 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 10:22:40.600  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 10:22:40.602  3960  4012 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 10:22:40.604  2622  2647 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 10:22:40.604  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:22:40.604  2622  2657 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 10:22:40.609  2622  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 10:22:40.609  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:22:40.609  2622  2657 D BtGatt.ScanManager: Starting BLE batch scan
08-17 10:22:40.609  2622  2657 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 10:22:40.618  2622  2647 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 10:22:40.618  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:40.623  2622  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 10:22:40.623  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:41.100  3960  3960 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-17 10:22:41.101  3960  3960 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 10:22:41.101  3960  3960 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 10:22:42.130  2622  2622 D BtGatt.ScanManager: awakened up at time 155087
,08-17 10:22:42.133  2622  2657 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:22:42.170  2622  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-17 10:22:42.170  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:22:42.170  2622  2647 D BtGatt.GattService: current time is 155128174835
,08-17 10:22:42.171  2622  2647 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -84, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -97, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -80, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -79, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -90, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
08-17 10:22:42.171  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-17 10:22:42.171  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-17 10:22:42.172  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-17 10:22:42.172  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-17 10:22:42.172  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-17 10:22:42.172  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-17 10:22:43.677  2622  2622 D BtGatt.ScanManager: awakened up at time 156634
,08-17 10:22:43.681  2622  2657 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:22:43.729  2622  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-17 10:22:43.729  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:43.730  2622  2647 D BtGatt.GattService: current time is 156687279667
,08-17 10:22:43.731  2622  2647 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -80, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -92, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -84, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -96, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -82, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -93, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-17 10:22:43.732  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-17 10:22:43.733  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-17 10:22:43.733  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-17 10:22:43.734  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-17 10:22:43.735  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-17 10:22:43.736  2622  2647 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-17 10:22:45.230  2622  2622 D BtGatt.ScanManager: awakened up at time 158188
,08-17 10:22:45.233  2622  2657 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:22:45.244  2622  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 10:22:45.244  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:45.603  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:22:45.604  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 10:22:45.604  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 10:22:45.604  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:45.604  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-17 10:22:45.605  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 10:22:45.605  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 10:22:45.605  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 10:22:45.605  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 10:22:45.606  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 10:22:45.606  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 10:22:45.609  3960  4012 D BluetoothAdapter: STATE_ON
,08-17 10:22:45.611  2622  2635 D BtGatt.GattService: stopScan() - queue size =1
,08-17 10:22:45.613  2622  2634 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 10:22:45.614  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 10:22:45.615  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 10:22:45.615  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 10:22:45.615  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 10:22:45.616  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 10:22:45.620  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 10:22:45.620  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 10:22:45.620  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 10:22:45.621  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 10:22:45.623  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:22:45.625  3960  3960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:22:45.625  3960  3960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 10:22:45.629  3960  3960 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 10:22:45.631  2622  2647 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 10:22:45.631  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:22:45.631  2622  2657 D BtGatt.ScanManager: stopping BLe Batch
,08-17 10:22:45.643  2622  2647 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 10:22:45.643  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:45.644  2622  2657 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:22:45.655  2622  2647 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 10:22:45.655  2622  2647 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:22:46.130  3960  3960 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 10:22:46.131  3960  3960 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:22:46.131  3960  3960 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 10:22:46.376  3767  4034 I BooksSync: Starting books sync for 61035162, extras: ade
,08-17 10:22:46.404  3767  4037 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-17 10:22:46.417  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:22:46.419  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:22:46.448  1496  3160 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 10:22:46.448  1496  3160 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-17 10:22:46.449  1496  3160 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:22:46.449  1496  3160 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:22:46.502  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:22:46.505  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:22:46.542  1496  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 10:22:46.542  1496  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-17 10:22:46.542  1496  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 10:22:46.542  1496  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:22:46.577  3767  4037 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-17 10:22:46.579  3767  4034 E BooksSync: Soft error
08-17 10:22:46.579  3767  4034 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 10:22:46.579  3767  4034 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-17 10:22:46.579  3767  4034 E BooksSync: Sync error
08-17 10:22:46.579  3767  4034 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 10:22:46.579  3767  4034 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-17 10:22:46.579  3767  4034 I BooksSync: Finished books sync
,08-17 10:22:46.595   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 129483, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 10:22:46.617  1496  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 10:22:46.618  1496  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-17 10:22:46.618  1496  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 10:22:46.620  1496  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-17 10:22:46.651  3180  4036 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-17 10:22:46.651  3180  4036 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at jdm.a(PG:82)
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at jcs.o(PG:406)
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at jcn.a(PG:1379)
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at jcs.i(PG:143)
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at blb.a(PG:3937)
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at czp.a(PG:18188)
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at czp.a(PG:9081)
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at czq.run(PG:1686)
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 10:22:46.651  3180  4036 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at jdj.a(PG:4091)
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at jdj.a(PG:1125)
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at jdm.a(PG:77)
08-17 10:22:46.651  3180  4036 E HttpOperation: 	... 12 more
08-17 10:22:46.651  3180  4036 E HttpOperation: Caused by: faj: BadAuthentication
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at fal.a(PG:38)
08-17 10:22:46.651  3180  4036 E HttpOperation: 	at jdj.a(PG:4089)
08-17 10:22:46.651  3180  4036 E HttpOperation: 	... 14 more
,08-17 10:22:46.714  1496  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-17 10:22:46.714  1496  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 10:22:46.714  1496  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:22:46.714  1496  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:22:46.735  3180  4036 E HttpOperation: [getmobileexperiments] Unexpected exception
08-17 10:22:46.735  3180  4036 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at jdm.a(PG:82)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at jcs.o(PG:406)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at jcn.a(PG:1379)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at jcs.i(PG:143)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at hec.a(PG:42)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at hee.a(PG:102)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at czr.a(PG:65)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at kka.a(PG:108)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at czp.a(PG:19176)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at czp.a(PG:9081)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at czq.run(PG:1686)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 10:22:46.735  3180  4036 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at jdj.a(PG:4091)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at jdj.a(PG:1125)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at jdm.a(PG:77)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	... 15 more
08-17 10:22:46.735  3180  4036 E HttpOperation: Caused by: faj: BadAuthentication
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at fal.a(PG:38)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	at jdj.a(PG:4089)
08-17 10:22:46.735  3180  4036 E HttpOperation: 	... 17 more
08-17 10:22:46.736  3180  4036 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-17 10:22:46.736  3180  4036 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at jdm.a(PG:82)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at jcs.o(PG:406)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at jcn.a(PG:1379)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at jcs.i(PG:143)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	,at hec.a(PG:42)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at hee.a(PG:102)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at czr.a(PG:65)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at kka.a(PG:108)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at czp.a(PG:19176)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at czp.a(PG:9081)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at czq.run(PG:1686)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at jdj.a(PG:4091)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at jdj.a(PG:1125)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at jdm.a(PG:77)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	... 15 more
08-17 10:22:46.736  3180  4036 E ExperimentLoader: Caused by: faj: BadAuthentication
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at fal.a(PG:38)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	at jdj.a(PG:4089)
08-17 10:22:46.736  3180  4036 E ExperimentLoader: 	... 17 more
,08-17 10:22:46.824  1860  2805 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-17 10:22:46.894   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 134657, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 10:22:50.203  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:22:50.418  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:22:50.425  1496  4040 I VacuumService: Vacuum at: now=1471422170425 tag=VacuumService
,08-17 10:22:50.489  1496  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-17 10:22:50.489  1496  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 10:22:50.490  1496  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 10:22:50.490  1496  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:22:50.519  3700  3700 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-17 10:22:50.520  3700  3700 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-17 10:22:50.520  3700  3700 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-17 10:22:50.579  1496  4041 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-17 10:22:50.581  1496  4041 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-17 10:22:50.623  1496  4041 W Uploader:  no longer exists, so no auth token.
,08-17 10:22:50.626  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:22:50.626  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:22:50.626  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:22:50.626  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:50.626  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.626  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:22:50.627  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
08-17 10:22:50.627  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:50.627  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:50.627  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:22:50.627  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.628  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.628  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:50.630  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:22:50.630  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:22:50.630  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:50.630  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:50.631  3960  4012 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-17 10:22:50.631  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:22:50.631  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:22:50.632  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:22:50.632  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:50.632  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.632  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.632  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
08-17 10:22:50.632  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:50.632  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:50.632  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:22:50.633  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.633  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.633  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:22:50.633  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.634  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:22:50.635  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:22:50.635  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:50.635  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:50.636  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 10:22:50.636  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:22:50.637  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:22:50.637  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:22:50.637  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 10:22:50.637  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.637  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:50.637  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
08-17 10:22:50.637  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:22:50.637  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:50.637  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:22:50.638  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.638  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:50.638  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:22:50.638  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:50.640  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 10:22:50.641  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:22:50.641  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:50.641  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:50.643  3960  4012 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-17 10:22:50.644  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:22:50.644  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:22:50.644  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:22:50.644  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:50.645  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:22:50.645  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.645  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
,08-17 10:22:50.645  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:22:50.646  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:50.646  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:22:50.646  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.646  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.647  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.647  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.649  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:22:50.650  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:22:50.650  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:50.650  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:50.652  3960  4012 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-17 10:22:50.653  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:22:50.653  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:22:50.653  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:22:50.653  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:50.654  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.654  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.654  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
08-17 10:22:50.654  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:50.655  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:50.655  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:22:50.655  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.655  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.655  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:22:50.656  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.660  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:22:50.661  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:22:50.661  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:50.661  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:50.662  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 10:22:50.662  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 10:22:50.662  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 10:22:50.663  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-17 10:22:50.663  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 10:22:50.663  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 10:22:50.663  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 10:22:50.663  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 10:22:50.664  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 10:22:50.664  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:22:50.665  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:22:50.665  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:22:50.666  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:50.666  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:22:50.666  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.666  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
08-17 10:22:50.666  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:22:50.667  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:50.667  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:22:50.667  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.667  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.667  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-17 10:22:50.668  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.671  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:22:50.671  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:22:50.672  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:22:50.672  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:50.678  3960  4012 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-17 10:22:50.679  3960  4012 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 10:22:50.679  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-17 10:22:50.684  3960  4012 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-17 10:22:50.684  3960  4012 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-17 10:22:50.685  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 10:22:50.685  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 10:22:50.685  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 10:22:50.685  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 10:22:50.685  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-17 10:22:50.685  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 10:22:50.685  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 10:22:50.685  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 10:22:50.685  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 10:22:50.685  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 10:22:50.686  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-17 10:22:50.686  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 10:22:50.686  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 10:22:50.686  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 10:22:50.686  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-17 10:22:50.686  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 10:22:50.686  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 10:22:50.687  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 10:22:50.687  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 10:22:50.687  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-17 10:22:50.688  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-17 10:22:50.688  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-17 10:22:50.689  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-17 10:22:50.690  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-17 10:22:50.690  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 10:22:50.690  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-17 10:22:50.690  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-17 10:22:50.690  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 10:22:50.690  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 10:22:50.690  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-17 10:22:50.690  3960  4012 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 10:22:50.691  3960  4012 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 10:22:50.691  3960  4012 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 10:22:50.691  3960  4012 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-17 10:22:50.691  3960  4012 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 10:22:50.691  3960  4012 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-17 10:22:50.691  3960  4012 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 10:22:50.691  3960  4012 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-17 10:22:50.691  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-17 10:22:50.693  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-17 10:22:50.694  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 10:22:50.694  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-17 10:22:50.695  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 10:22:50.695  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 10:22:50.695  3960  4012 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-17 10:22:50.695  3960  4012 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 10:22:50.695  3960  4012 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-17 10:22:50.696  3960  4047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 422)
08-17 10:22:50.696  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:22:50.696  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:22:50.696  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:22:50.697  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:50.697  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.697  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.697  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-17 10:22:50.697  3960  4047 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 10:22:50.698  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
08-17 10:22:50.698  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:22:50.698  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:50.698  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:22:50.698  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.698  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:50.698  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:22:50.698  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.699  3960  4048 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 422
,08-17 10:22:50.700  3960  4048 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 422)
,08-17 10:22:50.700  2622  2769 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-17 10:22:50.700  3960  4047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 422)
08-17 10:22:50.700  3960  4048 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 422)
,08-17 10:22:50.701  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 10:22:50.701  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:22:50.701  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:50.702  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:50.702  3960  4012 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-17 10:22:50.703  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:22:50.703  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:22:50.703  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:22:50.703  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:50.703  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:22:50.703  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.703  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list,
08-17 10:22:50.704  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:50.704  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:50.704  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:22:50.704  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:22:50.704  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.704  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.704  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.705  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:22:50.705  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:22:50.705  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:50.705  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:50.706  3960  4012 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 10:22:50.706  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:22:50.706  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:22:50.706  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:22:50.706  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:50.706  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.706  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.706  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
08-17 10:22:50.706  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:22:50.706  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:50.706  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:22:50.707  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.707  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.707  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.707  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:50.707  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:22:50.708  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:22:50.708  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:50.708  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:50.708  3960  4012 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 10:22:50.708  3960  4012 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-17 10:22:50.708  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 10:22:50.709  3960  4012 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 10:22:50.709  3960  4012 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 10:22:50.709  3960  4012 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 10:22:50.709  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 10:22:50.709  3960  4012 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-17 10:22:50.709  3960  4012 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 10:22:50.709  3960  4012 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 10:22:50.709  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 10:22:50.709  3960  4012 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 10:22:50.709  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:22:50.709  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:22:50.709  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:22:50.710  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:50.710  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.710  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.710  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
08-17 10:22:50.710  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:22:50.710  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:50.710  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:22:50.710  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.710  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.710  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:50.710  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:50.711  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:22:50.711  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:22:50.711  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:50.711  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:50.712  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:50.712  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:22:50.712  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:50.712  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
08-17 10:22:50.712  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:50.712  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:50.712  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:22:50.712  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:22:50.712  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:50.799   873  1302 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-17 10:22:55.000  1496  4041 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-17 10:22:55.000  1496  4041 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-17 10:22:55.000  1496  4041 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:22:55.000  1496  4041 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:22:55.032  1496  4041 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-17 10:22:55.032  1496  4041 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-17 10:22:55.032  1496  4041 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-17 10:22:55.032  1496  4041 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-17 10:22:55.032  1496  4041 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-17 10:22:55.032  1496  4041 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-17 10:22:55.032  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-17 10:22:55.032  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-17 10:22:55.032  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-17 10:22:55.032  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-17 10:22:55.032  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-17 10:22:55.032  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-17 10:22:55.032  1496  4041 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-17 10:22:55.680   873  2097 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 10:22:55.713  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:22:55.713  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:55.714  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:55.714  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:55.714  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:55.715  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
08-17 10:22:55.715  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:22:55.715  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:22:55.716  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:22:55.716  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:55.717  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:55.717  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:55.717  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
08-17 10:22:55.717  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:55.718  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:55.718  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:22:55.718  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:55.719  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:55.719  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:55.719  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:55.723  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 10:22:55.723  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:22:55.723  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:55.724  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:55.728  3960  4012 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-17 10:22:55.730  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:22:55.732  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-17 10:22:55.734  3960  4012 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-17 10:22:55.734  3960  4012 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 10:22:55.734  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 10:22:55.735  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 10:22:55.735  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:55.735  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-17 10:22:55.735  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 10:22:55.735  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 10:22:55.735  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:55.735  3960  4012 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-17 10:22:55.736  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
,08-17 10:22:55.736  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:22:55.736  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 10:22:55.736  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 10:22:55.736  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 10:22:55.736  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:55.736  3960  3960 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 10:22:55.736  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:55.737  3960  3960 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 10:22:55.737  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 10:22:55.738  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:55.738  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:22:55.738  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:22:55.738  3960  3960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:22:55.738  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:22:55.739  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:55.740  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:55.738  3960  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 10:22:55.740  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:55.740  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
08-17 10:22:55.740  3960  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 10:22:55.741  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:22:55.741  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:55.741  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:22:55.741  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:55.738  3960  3960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:22:55.741  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:55.741  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:55.741  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:55.742  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 10:22:55.741  3960  3960 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 10:22:55.742  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:22:55.742  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:55.742  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:55.743  3960  3960 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 10:22:55.744  3960  4012 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 10:22:55.744  3960  4012 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 10:22:55.744  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-17 10:22:55.746  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 10:22:55.746  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 10:22:55.747  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:22:55.747  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:22:55.748  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:22:55.748  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:55.748  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:55.748  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:55.748  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
08-17 10:22:55.748  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:55.748  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:55.748  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:22:55.748  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:55.748  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:55.748  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:55.749  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:55.750  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:22:55.750  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:22:55.750  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:55.750  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:55.756  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:22:55.756  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:22:55.756  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:22:55.756  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:22:55.756  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:55.756  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:55.757  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
,08-17 10:22:55.757  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:55.757  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:55.757  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:22:55.757  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:55.757  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:55.757  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:55.757  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:22:55.758  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:22:55.758  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:22:55.758  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:22:55.758  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
,08-17 10:22:55.760  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:22:55.761  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:22:55.761  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:22:55.761  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 10:22:55.761  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:55.761  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:55.761  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92b1ef not in the list
08-17 10:22:55.761  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:22:55.761  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:55.761  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:22:55.761  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:22:55.761  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:55.762  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:22:55.762  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:22:55.763  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 10:22:55.763  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:22:55.763  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:22:55.764  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86c4fc not in the list
08-17 10:22:55.765  3960  4012 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-17 10:22:55.765  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 10:22:55.765  3960  4012 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-17 10:22:55.765  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 10:22:55.765  3960  4012 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 10:22:55.765  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-17 10:22:55.769  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 10:22:55.769  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 10:22:55.770  3960  4012 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 10:22:55.770  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 10:22:55.770  3960  4012 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 10:22:55.770  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-17 10:22:55.770  3960  4012 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 10:22:55.770  3960  4012 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 10:22:55.771  3960  4012 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 10:22:55.771  3960  4012 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-17 10:22:55.772  3960  4012 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 10:22:55.772  3960  4012 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 10:22:55.772  3960  4012 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 10:22:55.772  3960  4012 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 10:22:55.774  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:22:55.774  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5f9f4df added. We now have 3 listener(s)
,08-17 10:22:55.774  3960  4012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:22:55.776  3960  4012 D BluetoothAdapter: enable(): BT is already enabled..!
08-17 10:22:55.776   873  1971 D WifiService: setWifiEnabled: true pid=3960, uid=10000
,08-17 10:22:55.776   873  1971 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 10:22:55.823  2622  2740 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-17 10:22:55.824  2622  2740 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-17 10:22:56.243  3960  3960 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 10:22:56.351  1496  4041 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-17 10:22:56.351  1496  4041 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-17 10:22:56.351  1496  4041 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:22:56.351  1496  4041 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:22:56.382  1496  4041 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-17 10:22:56.382  1496  4041 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-17 10:22:56.382  1496  4041 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-17 10:22:56.382  1496  4041 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-17 10:22:56.382  1496  4041 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-17 10:22:56.382  1496  4041 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-17 10:22:56.382  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-17 10:22:56.382  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-17 10:22:56.382  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-17 10:22:56.382  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-17 10:22:56.382  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-17 10:22:56.382  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-17 10:22:56.382  1496  4041 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-17 10:22:56.758  1496  4041 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-17 10:22:56.759  1496  4041 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-17 10:22:56.759  1496  4041 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 10:22:56.759  1496  4041 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:22:56.794  1496  4041 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-17 10:22:56.794  1496  4041 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-17 10:22:56.794  1496  4041 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-17 10:22:56.794  1496  4041 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-17 10:22:56.794  1496  4041 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-17 10:22:56.794  1496  4041 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-17 10:22:56.794  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-17 10:22:56.794  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-17 10:22:56.794  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-17 10:22:56.794  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-17 10:22:56.794  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-17 10:22:56.794  1496  4041 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-17 10:22:56.794  1496  4041 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-17 10:22:56.920  1496  4041 I art     : Waiting for a blocking GC DisableMovingGc
,08-17 10:22:56.933  1496  4041 I art     : WaitForGcToComplete blocked for 12.440ms for cause DisableMovingGc
,08-17 10:22:56.933  1496  4041 I art     : Starting a blocking GC DisableMovingGc
,08-17 10:23:00.781  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 10:23:00.782  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@783652c added. We now have 4 listener(s)
,08-17 10:23:00.782  3960  4012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:23:00.798  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:23:00.799  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@783652c removed from the list
08-17 10:23:00.799  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:23:00.799  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:23:00.800  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:23:00.802  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:23:00.802  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7cdabf5 added. We now have 4 listener(s)
,08-17 10:23:00.803  3960  4012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:23:00.806  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:23:00.807  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7cdabf5 removed from the list
08-17 10:23:00.807  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:23:00.809  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:23:00.809  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:23:00.812  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 10:23:00.812  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1750d8a added. We now have 4 listener(s)
08-17 10:23:00.813  3960  4012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:23:00.820   873  1680 D WifiService: setWifiEnabled: false pid=3960, uid=10000
08-17 10:23:00.820   873  1680 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 10:23:00.832  2622  2643 D BluetoothAdapterState: Current state: ON, message: 23
,08-17 10:23:00.832  2622  2643 D BluetoothAdapterProperties: Setting state to 13
08-17 10:23:00.832  2622  2643 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-17 10:23:00.833  2622  2643 D BluetoothAdapterProperties: onBluetoothDisable()
,08-17 10:23:00.834  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:23:00.836  2622  2643 I BluetoothAdapterState: Entering PendingCommandState
,08-17 10:23:00.840  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:23:00.840  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:23:00.840  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:00.840  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:00.840  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:00.840  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:00.840  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:23:00.840  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:23:00.840  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:23:00.841  2622  2647 D BluetoothAdapterProperties: Scan Mode:20
,08-17 10:23:00.841  2622  2643 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-17 10:23:00.844  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:23:00.844  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:23:00.844  3960  4012 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:23:00.846  2622  2622 D BluetoothMapService: onReceive
,08-17 10:23:00.846  2622  2622 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 10:23:00.846  2622  2622 D BluetoothMapService: STATE_TURNING_OFF
08-17 10:23:00.847  2622  2622 D BluetoothMapService: MAP Service closeService in
08-17 10:23:00.847  2622  2622 D BluetoothMapMasInstance0: MAP Service shutdown
,08-17 10:23:00.847  2622  2622 D ObexServerSockets0: shutdown(block = true)
08-17 10:23:00.848  2622  2622 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-17 10:23:00.848  2622  2781 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-17 10:23:00.849  2622  2782 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-17 10:23:00.850  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:00.851  2622  2769 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-17 10:23:00.852  2622  2622 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 10:23:00.852  2622  2622 I BtOppRfcommListener: stopping Accept Thread
08-17 10:23:00.853  2622  3599 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 10:23:00.854  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:00.854  2622  3599 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 10:23:00.857  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-17 10:23:00.858  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:00.858  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:00.858  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:00.858  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:00.858  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:00.858  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:00.858  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:23:00.858  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:23:00.858  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:23:00.859  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:00.859  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:23:00.862   873  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 10:23:00.862   873  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-17 10:23:00.862   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 10:23:00.863   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 10:23:00.863  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:00.863  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:00.863  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:00.863  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:00.863  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:00.863  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:00.863  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:23:00.863  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:23:00.863  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:23:00.864  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:00.864  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:23:00.866   873   886 I ActivityManager: Start proc 4063:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-17 10:23:00.868  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:00.871  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:00.871  2622  2622 D HeadsetService: Received stop request...Stopping profile...
08-17 10:23:00.875  1361  1373 D BluetoothHeadset: Proxy object disconnected
08-17 10:23:00.875   873   873 D BluetoothHeadset: Proxy object disconnected
,08-17 10:23:00.875  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:23:00.875   873   873 D BluetoothHeadset: Proxy object disconnected
08-17 10:23:00.875   873   873 D BluetoothHeadset: Proxy object disconnected
08-17 10:23:00.876  1935  2120 D BluetoothHeadset: Proxy object disconnected
08-17 10:23:00.878  1361  1361 D HeadsetProfile: Bluetooth service disconnected
08-17 10:23:00.879  2622  2622 D A2dpService: Received stop request...Stopping profile...
08-17 10:23:00.879  2622  2776 D A2dpStateMachine: Exit Disconnected: -1
,08-17 10:23:00.880  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:00.881   873  1302 E native  : do suspend true
08-17 10:23:00.882  1361  1361 D BluetoothA2dp: Proxy object disconnected
08-17 10:23:00.882   873   873 D BluetoothA2dp: Proxy object disconnected
08-17 10:23:00.883  2622  2622 D HidService: Received stop request...Stopping profile...
08-17 10:23:00.883  2622  2622 D HidService: Stopping Bluetooth HidService
08-17 10:23:00.884  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-17 10:23:00.885  1361  1361 D HidProfile: Bluetooth service disconnected
08-17 10:23:00.884  2622  2622 D HealthService: Received stop request...Stopping profile...
08-17 10:23:00.885  2622  2622 V BluetoothAdapterState: isTurningOff()=true
08-17 10:23:00.885  2622  2622 V BluetoothAdapterState: isTurningOn()=false
08-17 10:23:00.885  2622  2622 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:23:00.885  2622  2622 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:23:00.887  2622  2622 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 10:23:00.887  2622  2622 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 10:23:00.887  2622  2647 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-17 10:23:00.887  2622  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 10:23:00.887  2622  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 10:23:00.887  2622  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 10:23:00.888  2622  2647 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-17 10:23:00.888  2622  2622 V BluetoothAdapterState: isTurningOff()=true
,08-17 10:23:00.888  2622  2622 V BluetoothAdapterState: isTurningOn()=false
08-17 10:23:00.888  2622  2622 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:23:00.888  2622  2622 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:23:00.889  2622  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 10:23:00.889  2622  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 10:23:00.890  2622  2740 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 10:23:00.890  2622  2740 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-17 10:23:00.890  2622  2740 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 10:23:00.890  2622  2740 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 10:23:00.890  2622  2647 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-17 10:23:00.891  2622  2622 D PanService: Received stop request...Stopping profile...
08-17 10:23:00.891  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 10:23:00.892  2622  2622 V BluetoothAdapterState: isTurningOff()=true
,08-17 10:23:00.892  2622  2622 V BluetoothAdapterState: isTurningOn()=false
,08-17 10:23:00.892  2622  2622 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 10:23:00.892  1361  1361 D PanProfile: Bluetooth service disconnected
08-17 10:23:00.892  2622  2622 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:23:00.893  2622  2622 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 10:23:00.893  2622  2647 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 10:23:00.893  2622  2622 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-17 10:23:00.893   873  2107 D DhcpClient: Clearing IP address
08-17 10:23:00.894  2622  2622 D BluetoothMapService: Received stop request...Stopping profile...
08-17 10:23:00.894   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-17 10:23:00.894  2622  2622 D BluetoothMapService: stop()
08-17 10:23:00.895  2622  2622 D BluetoothMapAppObserver: deinitObservers()
08-17 10:23:00.895  2622  2622 D BluetoothMapAppObserver: removeReceiver()
08-17 10:23:00.896  1361  1361 D BluetoothMap: Proxy object disconnected
08-17 10:23:00.896  1361  1361 D MapProfile: Bluetooth service disconnected
08-17 10:23:00.897  2622  2622 V BluetoothAdapterState: isTurningOff()=true
08-17 10:23:00.897  2622  2622 V BluetoothAdapterState: isTurningOn()=false
08-17 10:23:00.897   372   871 D CommandListener: Setting iface cfg
08-17 10:23:00.897  2622  2622 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 10:23:00.897  2622  2622 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:23:00.897  2622  2622 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 10:23:00.897  2622  2647 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-17 10:23:00.897  2622  2622 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 10:23:00.898  2622  2622 V BluetoothAdapterState: isTurningOff()=true
08-17 10:23:00.898  2622  2622 V BluetoothAdapterState: isTurningOn()=false
08-17 10:23:00.898  2622  2622 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:23:00.898  2622  2622 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:23:00.898  2622  2622 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-17 10:23:00.898  2622  2622 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 10:23:00.899  2622  2622 D BluetoothMapService: MAP Service closeService in
08-17 10:23:00.899  2622  2622 V BluetoothAdapterState: isTurningOff()=true
08-17 10:23:00.899  2622  2622 V BluetoothAdapterState: isTurningOn()=false
08-17 10:23:00.899  2622  2622 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:23:00.899  2622  2622 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:23:00.899  2622  2643 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-17 10:23:00.900  2622  2643 D BluetoothAdapterProperties: Setting state to 15
08-17 10:23:00.900  2622  2643 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-17 10:23:00.900  2622  2622 D BluetoothMapService: cleanup()
08-17 10:23:00.900  2622  2622 D BluetoothMapService: MAP Service closeService in
08-17 10:23:00.900  2622  2643 I BluetoothAdapterState: Entering BleOnState
08-17 10:23:00.901  1361  2084 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 10:23:00.901   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 10:23:00.902  1361  1379 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 10:23:00.902   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-17 10:23:00.902   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-17 10:23:00.902   873  1302 D WifiStateMachine: Start Disconnecting Watchdog 1
08-17 10:23:00.902  1361  2035 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:23:00.902  1361  1373 D BluetoothMap: onBluetoothStateChange: up=false
08-17 10:23:00.903   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 10:23:00.903   873  1302 E native  : do suspend true
08-17 10:23:00.903  1361  2084 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 10:23:00.905   443   443 E Parcel  : Reading a NULL string not supported here.
08-17 10:23:00.907  1361  1379 D BluetoothPan: onBluetoothStateChange on: false
,08-17 10:23:00.907   873  1304 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-17 10:23:00.907   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:23:00.908   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:23:00.908   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 10:23:00.908  1935  1947 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:23:00.908  2622  2643 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-17 10:23:00.908  2622  2643 D BluetoothAdapterProperties: Setting state to 16
08-17 10:23:00.908  2622  2643 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-17 10:23:00.909  2622  2643 D BluetoothAdapterProperties: onBleDisable
08-17 10:23:00.909  2622  2643 I BluetoothAdapterState: Entering PendingCommandState
,08-17 10:23:00.909  2622  2644 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-17 10:23:00.910  2622  2647 D BluetoothAdapterProperties: Scan Mode:20
08-17 10:23:00.910  2622  2740 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 10:23:00.910  2622  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 10:23:00.912  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:00.912  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:00.912  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:00.912  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:00.912  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:00.912  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:00.912  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:00.912  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:00.912  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:23:00.912  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:00.912  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:23:00.915  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:00.915  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:00.915  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:00.915  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:00.915  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:00.915  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:00.915  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:00.915  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:00.915  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:00.916  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:00.916  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:23:00.918  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:00.919  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:00.919  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:00.919  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:00.919  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:00.919  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:00.919  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:00.919  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:00.919  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:23:00.919  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:00.919  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:23:00.919  1496  3762 V NativeCrypto: Read error: ssl=0xaa220600: I/O error during system call, Connection timed out
08-17 10:23:00.921  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:00.921  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:00.921  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:00.921  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:00.921  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:00.921  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:00.921  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:00.921  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:00.921  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:00.922  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:00.923  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:00.923  1496  3762 V NativeCrypto: SSL shutdown failed: ssl=0xaa220600: I/O error during system call, Broken pipe
08-17 10:23:00.929   873  2129 D DhcpClient: Receive thread stopped
,08-17 10:23:00.940   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 10:23:00.944  4063  4063 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-17 10:23:00.953  4063  4063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 10:23:00.958  1496  1496 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 10:23:00.963   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 10:23:00.963   873  1304 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-17 10:23:00.963   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:23:00.964   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-17 10:23:00.969   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b36b949:true
,08-17 10:23:00.971   873  2135 I ActivityManager: Start proc 4080:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-17 10:23:00.972   873  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-17 10:23:00.976   873   890 D Tethering: MasterInitialState.processMessage what=3
08-17 10:23:00.978  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:00.980  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:00.981  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:23:00.985  2020  2020 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-17 10:23:00.988   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 10:23:00.990  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:00.990  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:00.990  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:00.990  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:00.990  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:23:00.990  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:00.990  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:00.990  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:00.990  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:00.991   873  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 10:23:00.991  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:23:00.991  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:23:00.983  3606  3606 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@edf4936 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-17 10:23:00.993  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:23:00.993  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:00.993  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:00.993  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:00.993  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:23:00.993  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:00.993  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:00.993  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:00.993  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:00.993  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:00.993  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:23:00.994  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:00.995  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:00.995  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:00.995  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:00.995  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:23:00.995  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:00.995  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:00.995  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:00.995  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:00.995  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:00.995  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:23:00.998  1860  2276 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 10:23:01.013  4063  4063 D LocalBluetoothProfileManager: Adding local MAP profile
08-17 10:23:01.015  4063  4063 D BluetoothMap: Create BluetoothMap proxy object
08-17 10:23:01.026   372   871 E Netd    : netlink response contains error (No such file or directory)
08-17 10:23:01.031  4080  4080 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
08-17 10:23:01.034  4063  4063 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-17 10:23:01.051  4063  4063 D DockEventReceiver: finishStartingService: stopping service
,08-17 10:23:01.054   873  1459 I ActivityManager: Killing 3389:com.google.android.gm/u0a78 (adj 15): empty #17
,08-17 10:23:01.113  2622  2647 I bt_hci  : shut_down
,08-17 10:23:01.113  2622  2662 D bt_hwcfg: hw_epilog_process
,08-17 10:23:01.121  2622  2662 I bt_vendor: low_power_mode_cb
,08-17 10:23:01.147  2622  2662 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-17 10:23:01.148  2622  2662 I bt_vendor: epilog_cb
08-17 10:23:01.148  2622  2662 I bt_hci  : epilog_finished_callback
,08-17 10:23:01.153  2622  2647 I bt_hci_h4: hal_close
,08-17 10:23:01.154  2622  2647 I bt_userial_vendor: device fd = 51 close
,08-17 10:23:01.221  4080  4080 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 10:23:01.221  4080  4080 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 10:23:01.221  4080  4080 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 10:23:01.221  4080  4080 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 10:23:01.221  4080  4080 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.r.k.d(PG:583)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 10:23:01.221  4080  4080 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 10:23:01.221  4080  4080 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:23:01.221  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 10:23:01.222  4080  4080 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 10:23:01.222  4080  4080 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:23:01.222  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 10:23:01.252  4063  4063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 10:23:01.263  1496  1496 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 10:23:01.269  4063  4063 D DockEventReceiver: finishStartingService: stopping service
08-17 10:23:01.286   873  1957 I ActivityManager: Killing 3606:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-17 10:23:01.430  4080  4104 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-17 10:23:01.433  2622  2644 D bt_stack_manager: event_shut_down_stack finished.
,08-17 10:23:01.434  2622  2643 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-17 10:23:01.440  1703  1703 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 10:23:01.448  2622  2643 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-17 10:23:01.448  2622  2622 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 10:23:01.449  1703  1703 D SystemUpdateService: onCreate
,08-17 10:23:01.449  2622  2622 D BtGatt.GattService: Received stop request...Stopping profile...
,08-17 10:23:01.449  2622  2622 D BtGatt.GattService: stop()
,08-17 10:23:01.449  2622  2622 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 10:23:01.456  2622  2622 V BluetoothAdapterState: isTurningOff()=false
08-17 10:23:01.457  2622  2622 V BluetoothAdapterState: isTurningOn()=false
08-17 10:23:01.457  2622  2622 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:23:01.457  2622  2622 V BluetoothAdapterState: isBleTurningOff()=true
08-17 10:23:01.457  2622  2643 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-17 10:23:01.457  2622  2643 D BluetoothAdapterProperties: Setting state to 10
08-17 10:23:01.457  2622  2643 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-17 10:23:01.458  2622  2643 I BluetoothAdapterState: Entering OffState
08-17 10:23:01.458  1703  1703 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-17 10:23:01.460   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-17 10:23:01.463  1703  4117 I SystemUpdateService: active receiver: enabled
,08-17 10:23:01.467  1703  4117 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 10:23:01.472  2622  2622 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-17 10:23:01.472  2622  2622 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-17 10:23:01.472  2622  2622 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 10:23:01.472  2622  2644 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-17 10:23:01.473  1703  4117 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-17 10:23:01.473  1703  4117 I SystemUpdateService: now status is 0 (complete)
08-17 10:23:01.473  1703  4117 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 10:23:01.473  1703  4117 I SystemUpdateService: file has been verified
08-17 10:23:01.473  1703  4117 I SystemUpdateService: OTA package size = 12249756
08-17 10:23:01.473  1703  1703 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 10:23:01.476  1703  4117 I SystemUpdateService: showing system update notification
,08-17 10:23:01.480  1703  2505 I iu.UploadsManager: num queued entries: 0
,08-17 10:23:01.480  1703  2505 I iu.UploadsManager: num updated entries: 0
,08-17 10:23:01.481  2622  2644 D bt_stack_manager: event_clean_up_stack finished.
08-17 10:23:01.482  1703  2505 I iu.SyncManager: NEXT; no task
,08-17 10:23:01.486  1703  1703 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 10:23:01.488  1703  1703 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 10:23:01.493  2622  2622 I art     : System.exit called, status: 0
,08-17 10:23:01.493  2622  2622 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 10:23:01.501   873  1368 I ActivityManager: Start proc 4120:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-17 10:23:01.506  1703  1703 D SystemUpdateService: onDestroy
,08-17 10:23:01.511   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b9f05e5:true
,08-17 10:23:01.533   873   883 I ActivityManager: Process com.android.bluetooth (pid 2622) has died
,08-17 10:23:01.539  4120  4120 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-17 10:23:01.541  4120  4120 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:23:01.549  4120  4120 D SprintDMHelper: simOperator: 
,08-17 10:23:01.550  4120  4120 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 10:23:01.575   873  1681 I ActivityManager: Start proc 4132:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-17 10:23:01.693   873  1681 I ActivityManager: Start proc 4147:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-17 10:23:01.697  2854  4146 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-17 10:23:01.700   873   883 I ActivityManager: Killing 2948:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-17 10:23:01.772  4147  4147 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-17 10:23:01.834  4147  4147 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-17 10:23:01.834  4147  4147 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-17 10:23:01.834  4147  4147 I GAv4    :   adb logcat -s GAv4
,08-17 10:23:01.854  4147  4147 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-17 10:23:01.861  4147  4147 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-17 10:23:01.896  4147  4164 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-17 10:23:02.020  4147  4147 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-17 10:23:02.061  4147  4147 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-17 10:23:02.070  4147  4147 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5024-5027)
,08-17 10:23:02.071  4147  4147 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 10:23:02.082  4147  4147 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {56a6be6}
,08-17 10:23:02.083  4147  4147 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 10:23:02.083  4147  4147 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 10:23:02.092  4147  4147 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-17 10:23:02.093  4147  4147 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-17 10:23:02.113  4147  4147 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-17 10:23:02.128  4147  4147 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 10:23:02.128  4147  4147 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 10:23:02.129  4147  4147 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 10:23:02.129  4147  4147 I Adreno  : Build Date                       : 10/20/15
08-17 10:23:02.129  4147  4147 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 10:23:02.129  4147  4147 I Adreno  : Local Branch                     : M14
08-17 10:23:02.129  4147  4147 I Adreno  : Remote Branch                    : 
08-17 10:23:02.129  4147  4147 I Adreno  : Remote Branch                    : 
08-17 10:23:02.129  4147  4147 I Adreno  : Reconstruct Branch               : 
,08-17 10:23:02.199  4147  4147 I NSApplication: Starting up...
,08-17 10:23:02.210  4147  4193 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-17 10:23:02.239   873  1971 I ActivityManager: Start proc 4198:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-17 10:23:02.240   873  1971 I ActivityManager: Killing 1687:android.process.acore/u0a5 (adj 15): empty #17
,08-17 10:23:02.344  4198  4198 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-17 10:23:02.541   873  1968 I ActivityManager: Killing 3846:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-17 10:23:02.629   873   884 I ActivityManager: Start proc 4212:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-17 10:23:02.704  4212  4212 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-17 10:23:02.759  4212  4212 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-17 10:23:02.777   873  1966 I ActivityManager: Killing 3861:com.android.musicfx/u0a18 (adj 15): empty #17
,08-17 10:23:05.848   873  2038 D WifiService: setWifiEnabled: true pid=3960, uid=10000
,08-17 10:23:05.848   873  2038 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 10:23:05.862   873  1302 D WifiConfigStore: Loading config and enabling all networks 
,08-17 10:23:05.874  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:23:05.874  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:05.874  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:05.874  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:05.874  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:05.874  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:05.874  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:05.874  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:05.874  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:23:05.874  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:23:05.875  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:23:05.880  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
,08-17 10:23:05.881  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:05.881  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:05.881  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:05.881  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:05.881  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:05.881  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:05.881  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:05.881  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:23:05.881  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:05.882  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:23:05.885  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:23:05.887  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:05.887  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:05.887  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:05.887  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:05.887  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:05.887  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:05.887  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:05.887  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:23:05.887  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:05.887  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:23:05.896   873  1302 D WifiConfigStore: loaded 0 passpoint configs
,08-17 10:23:05.898   873  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-17 10:23:05.898   873  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-17 10:23:05.899   873  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-17 10:23:05.900   873  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-17 10:23:05.900   873  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-17 10:23:05.900   873  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 10:23:05.920   873  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-17 10:23:05.921   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-17 10:23:05.925   372   871 D CommandListener: Setting iface cfg
,08-17 10:23:05.932   873  1301 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-17 10:23:05.932   873  1301 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 10:23:05.933   873  1302 E native  : do suspend true
,08-17 10:23:05.949   873  1301 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 10:23:05.949   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 10:23:05.950   873  1301 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 10:23:06.615   873  1957 I ActivityManager: Killing 3629:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-17 10:23:07.316   873  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-17 10:23:07.400   873  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.94 rxSuccessRate=12.44 delta 1000 -> 994
,08-17 10:23:07.401   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-17 10:23:07.401   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 10:23:07.422   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 10:23:07.464   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 10:23:07.466  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 10:23:07.891  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 10:23:07.933  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 10:23:07.934  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 10:23:07.943   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 10:23:07.958   873  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 10:23:07.958   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 10:23:07.958   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 10:23:07.983   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 10:23:08.003   372   871 D CommandListener: Setting iface cfg
,08-17 10:23:08.004   873  1302 D WifiStateMachine: Start Dhcp Watchdog 2
,08-17 10:23:08.019   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 10:23:08.059   873  4247 D DhcpClient: Receive thread started
,08-17 10:23:08.148   873  1302 E native  : do suspend false
,08-17 10:23:08.170   873  2107 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 10:23:08.191   873  4247 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172642, domain null
,08-17 10:23:08.192   873  2107 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172642 seconds
,08-17 10:23:08.195   873  2107 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 10:23:08.208   873  4247 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 10:23:08.209   873  2107 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 10:23:08.214   372   871 D CommandListener: Setting iface cfg
,08-17 10:23:08.226   873  2107 D DhcpClient: Scheduling renewal in 86399s
,08-17 10:23:08.228   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 10:23:08.232   873  1302 E native  : do suspend true
,08-17 10:23:08.252   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 10:23:08.254   873  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 10:23:08.255   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-17 10:23:08.259   873  1304 D ConnectivityService: Adding iface wlan0 to network 101
,08-17 10:23:08.266   873  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 10:23:08.339   873  1304 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-17 10:23:08.339   873  1304 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-17 10:23:08.341   873  1304 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-17 10:23:08.343   873  1304 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-17 10:23:08.345   873  1304 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-17 10:23:08.361   873  1304 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 10:23:08.367   873  1304 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-17 10:23:08.367   873  1304 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-17 10:23:08.368   873  1304 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-17 10:23:08.368   873  1304 D ConnectivityService:    accepting network in place of null
08-17 10:23:08.368   873  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-17 10:23:08.368   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 10:23:08.369   873  1304 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 10:23:08.379   873  4246 D NetlinkSocketObserver: NeighborEvent{elapsedMs=181336, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 10:23:08.417   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 10:23:08.453   873  4245 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:801::200e
,08-17 10:23:08.491   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 10:23:08.498   873  1304 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-17 10:23:08.499   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:23:08.503   873  1304 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-17 10:23:08.504   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-17 10:23:08.519  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:23:08.519  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:08.519  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:08.519  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:08.519  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:08.519  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:08.519  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:23:08.519  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:23:08.519  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:23:08.519  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:23:08.520  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:23:08.523  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:23:08.524  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:08.524  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:08.524  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:08.524  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:08.524  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:08.524  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:23:08.524  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:23:08.524  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:23:08.524  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:08.524  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:23:08.529  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:23:08.530  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:08.530  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:08.530  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:08.530  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:08.530  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:08.530  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:23:08.530  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:23:08.530  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:23:08.530  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:08.530  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:23:08.534   873  4245 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 08:23:08 GMT], X-Android-Received-Millis=[1471422188532], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471422188503]}
,08-17 10:23:08.535   873  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-17 10:23:08.535   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-17 10:23:08.535   873  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 10:23:08.538   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 10:23:08.546  2020  2020 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-17 10:23:08.547  1703  1703 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 10:23:08.552  1703  1703 D SystemUpdateService: onCreate
,08-17 10:23:08.554  1703  1703 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 10:23:08.577  1703  4259 I SystemUpdateService: active receiver: enabled
,08-17 10:23:08.580  1703  1703 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 10:23:08.583  1703  2505 I iu.UploadsManager: num queued entries: 0
,08-17 10:23:08.583  1703  2505 I iu.UploadsManager: num updated entries: 0
,08-17 10:23:08.592  1703  1703 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 10:23:08.593  1703  1703 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 10:23:08.595  1703  2505 I iu.SyncManager: NEXT; no task
,08-17 10:23:08.596  1703  4259 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 10:23:08.599  4120  4120 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:23:08.607  1703  4263 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-17 10:23:08.607  1703  4263 W BaseAppContext: Using Auth Proxy for data requests.
,08-17 10:23:08.611  4120  4120 D SprintDMHelper: simOperator: 
,08-17 10:23:08.611  4120  4120 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 10:23:08.622  1703  4259 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-17 10:23:08.622  1703  4259 I SystemUpdateService: now status is 0 (complete)
,08-17 10:23:08.622  1703  4259 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-17 10:23:08.622  1703  4259 I SystemUpdateService: file has been verified
08-17 10:23:08.622  1703  4259 I SystemUpdateService: OTA package size = 12249756
,08-17 10:23:08.623  1703  4263 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-17 10:23:08.643  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:23:08.651  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:23:08.665  1703  4259 I SystemUpdateService: showing system update notification
,08-17 10:23:08.712  1703  1703 D SystemUpdateService: onDestroy
,08-17 10:23:08.715  1496  3160 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-17 10:23:08.715  1496  3160 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-17 10:23:08.715  1496  3160 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:23:08.715  1496  3160 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:23:08.738  1703  4263 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-17 10:23:08.761  2854  4266 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 10:23:08.867  1496  4270 I GCM     : Ack for not saved message 92
,08-17 10:23:09.498   873  1304 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-17 10:23:10.772  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:23:10.821  1496  3160 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-17 10:23:10.821  1496  3160 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 10:23:10.821  1496  3160 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:23:10.821  1496  3160 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:23:10.855   873  1680 D WifiService: setWifiEnabled: false pid=3960, uid=10000
,08-17 10:23:10.855   873  1680 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 10:23:10.884  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-17 10:23:10.889   873  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-17 10:23:10.890   873  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-17 10:23:10.890   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 10:23:10.890   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 10:23:10.907   873  1302 E native  : do suspend true
,08-17 10:23:10.919   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-17 10:23:10.919   873  2107 D DhcpClient: Clearing IP address
,08-17 10:23:10.921   372   871 D CommandListener: Setting iface cfg
,08-17 10:23:10.930   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-17 10:23:10.930   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-17 10:23:10.934   443   443 E Parcel  : Reading a NULL string not supported here.
08-17 10:23:10.934   873  1302 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-17 10:23:10.936  1496  4270 V NativeCrypto: Read error: ssl=0x999c3e00: I/O error during system call, Connection timed out
08-17 10:23:10.942   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 10:23:10.945   873  1302 E native  : do suspend true
,08-17 10:23:10.941  1496  4270 V NativeCrypto: SSL shutdown failed: ssl=0x999c3e00: I/O error during system call, Broken pipe
08-17 10:23:10.949   873  4247 D DhcpClient: Receive thread stopped
08-17 10:23:10.950   873  1304 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-17 10:23:10.950   873   882 I art     : Background partial concurrent mark sweep GC freed 59416(3MB) AllocSpace objects, 6(132KB) LOS objects, 33% free, 29MB/43MB, paused 1.594ms total 116.399ms
,08-17 10:23:10.957  3700  3700 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-17 10:23:10.957  3700  3700 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-17 10:23:10.959  3700  3700 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-17 10:23:10.989   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 10:23:11.012   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 10:23:11.012   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-17 10:23:11.013   873  1304 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-17 10:23:11.013   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:23:11.016   873  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-17 10:23:11.017   873   890 D Tethering: MasterInitialState.processMessage what=3
08-17 10:23:11.024  2020  2020 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-17 10:23:11.032  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:11.032  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:11.032  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:11.032  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:11.032  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:11.032  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:11.032  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:11.032  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:11.032  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:11.032  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:11.033  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:23:11.036  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:23:11.036  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:11.036  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:11.036  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:11.036  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:11.036  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:11.036  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:11.036  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:11.036  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:11.036  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:11.037  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:23:11.038  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:23:11.038  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:11.038  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:11.038  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:11.038  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:11.038  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:11.038  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:11.038  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:11.038  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:11.038  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:11.038  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:23:11.039   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 10:23:11.042  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:23:11.043  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:11.043  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:11.043  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:11.043  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:23:11.043  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:11.043  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:11.043  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:11.043  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:11.043  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:11.043  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:23:11.042  1860  2276 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 10:23:11.043   873  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-17 10:23:11.044  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:11.044  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:11.044  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:11.044  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:11.044  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:23:11.044  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:11.044  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:11.044  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:11.044  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:11.044  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:11.044  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:23:11.044  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:11.044  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:11.044  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:11.044  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:11.044  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:23:11.044  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:11.044  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:11.044  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:11.044  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:11.044  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:11.044  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:23:11.046  1703  1703 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 10:23:11.049  1703  1703 D SystemUpdateService: onCreate
,08-17 10:23:11.052  1703  1703 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 10:23:11.061  1703  1703 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 10:23:11.066  1703  4281 I SystemUpdateService: active receiver: enabled
,08-17 10:23:11.066  1703  2505 I iu.UploadsManager: num queued entries: 0
,08-17 10:23:11.069  1703  1703 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-17 10:23:11.070  1703  1703 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 10:23:11.072  4120  4120 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:23:11.076  4120  4120 D SprintDMHelper: simOperator: 
08-17 10:23:11.076  4120  4120 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 10:23:11.083   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-17 10:23:11.085   873  1304 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-17 10:23:11.101  1703  2505 I iu.UploadsManager: num updated entries: 0
,08-17 10:23:11.106  1703  4281 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 10:23:11.110  2854  4284 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-17 10:23:11.114  1703  2505 I iu.SyncManager: NEXT; no task
,08-17 10:23:11.119  1703  4281 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-17 10:23:11.119  1703  4281 I SystemUpdateService: now status is 0 (complete)
,08-17 10:23:11.119  1703  4281 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 10:23:11.119  1703  4281 I SystemUpdateService: file has been verified
08-17 10:23:11.119  1703  4281 I SystemUpdateService: OTA package size = 12249756
,08-17 10:23:11.123  1703  4281 I SystemUpdateService: showing system update notification
,08-17 10:23:11.134  1703  1703 D SystemUpdateService: onDestroy
,08-17 10:23:15.909   873   890 I ActivityManager: Start proc 4289:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-17 10:23:16.023  4289  4289 D AdapterServiceConfig: Adding HeadsetService
,08-17 10:23:16.024  4289  4289 D AdapterServiceConfig: Adding A2dpService
08-17 10:23:16.024  4289  4289 D AdapterServiceConfig: Adding HidService
,08-17 10:23:16.024  4289  4289 D AdapterServiceConfig: Adding HealthService
08-17 10:23:16.024  4289  4289 D AdapterServiceConfig: Adding PanService
08-17 10:23:16.024  4289  4289 D AdapterServiceConfig: Adding GattService
08-17 10:23:16.025  4289  4289 D AdapterServiceConfig: Adding BluetoothMapService,
,08-17 10:23:16.038  4289  4289 D BluetoothAdapterState: make() - Creating AdapterState
08-17 10:23:16.038   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9a30f3d:true
,08-17 10:23:16.043  4289  4289 I bt_bluedroid: init
,08-17 10:23:16.044  4289  4301 I BluetoothAdapterState: Entering OffState
,08-17 10:23:16.048  4289  4302 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 10:23:16.049  4289  4302 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 10:23:16.049  4289  4302 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 10:23:16.049  4289  4302 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 10:23:16.051  4289  4289 I bt_bluedroid: get_profile_interface socket
,08-17 10:23:16.052  4289  4305 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-17 10:23:16.052  4289  4289 I bt_bluedroid: get_profile_interface sdp
08-17 10:23:16.053  4289  4305 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 10:23:16.055  4289  4300 I bt_bluedroid: config_hci_snoop_log
,08-17 10:23:16.058   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 10:23:16.066  4289  4301 D BluetoothAdapterState: Current state: OFF, message: 0
,08-17 10:23:16.066  4289  4301 D BluetoothAdapterProperties: Setting state to 14
08-17 10:23:16.066  4289  4301 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-17 10:23:16.068  4289  4301 D BluetoothBondStateMachine: make
,08-17 10:23:16.070  4289  4306 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 10:23:16.073  4289  4301 I BluetoothAdapterState: Entering PendingCommandState
,08-17 10:23:16.077  4289  4289 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 10:23:16.085  4289  4289 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
,08-17 10:23:16.086  4289  4289 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 10:23:16.087  4289  4289 D BtGatt.GattService: Received start request. Starting profile...
08-17 10:23:16.087  4289  4289 D BtGatt.GattService: start()
,08-17 10:23:16.087  4289  4289 I bt_bluedroid: get_profile_interface gatt
08-17 10:23:16.088  4289  4289 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
,08-17 10:23:16.088  4289  4289 D BtGatt.AdvertiseManager: advertise manager created
,08-17 10:23:16.094  4289  4289 V BluetoothAdapterState: isTurningOff()=false
,08-17 10:23:16.094  4289  4289 V BluetoothAdapterState: isTurningOn()=false
08-17 10:23:16.094  4289  4289 V BluetoothAdapterState: isBleTurningOn()=true
08-17 10:23:16.094  4289  4289 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:23:16.095  4289  4301 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-17 10:23:16.095  4289  4301 I bt_bluedroid: enable
,08-17 10:23:16.095  4289  4302 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-17 10:23:16.096  4289  4302 I bt_hci  : start_up
,08-17 10:23:16.113  4289  4302 I bt_vendor: alloc value 0xb3a82189
,08-17 10:23:16.114  4289  4302 I bt_vendor: init
08-17 10:23:16.114  4289  4302 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-17 10:23:16.114  4289  4302 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 10:23:16.194  1496  2199 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-17 10:23:16.223  4289  4302 D bt_hci  : start_up starting async portion
,08-17 10:23:16.223  4289  4309 I bt_hci  : event_finish_startup
,08-17 10:23:16.223  4289  4309 I bt_hci_h4: hal_open
,08-17 10:23:16.224  4289  4309 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 10:23:16.235  4289  4309 I bt_userial_vendor: device fd = 51 open
,08-17 10:23:16.263  4289  4309 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 10:23:16.295  4289  4309 D bt_hwcfg: Chipset BCM4354A2
,08-17 10:23:16.295  4289  4309 D bt_hwcfg: Target name = [BCM4354A2]
08-17 10:23:16.296  4289  4309 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 10:23:16.373   873  1304 D ConnectivityService: handlePromptUnvalidated 101
,08-17 10:23:16.967  4289  4309 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-17 10:23:16.968  4289  4309 D bt_hwcfg: Settlement delay -- 100 ms
08-17 10:23:16.969  4289  4309 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 10:23:17.085  4289  4309 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-17 10:23:17.087  4289  4309 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 10:23:17.116  4289  4309 I bt_hwcfg: vendor lib fwcfg completed
,08-17 10:23:17.116  4289  4309 I bt_vendor: firmware callback
,08-17 10:23:17.117  4289  4309 I bt_hci  : firmware_config_callback
,08-17 10:23:17.128  4289  4313 I bt_btu  : btu_task pending for preload complete event
,08-17 10:23:17.128  4289  4313 I bt_btu_task: Bluetooth chip preload is complete
,08-17 10:23:17.128  4289  4313 I bt_btu  : btu_task received preload complete event
,08-17 10:23:17.141  4289  4313 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 10:23:17.141  4289  4313 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-17 10:23:17.141  4289  4313 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 10:23:17.141  4289  4313 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 10:23:17.142  4289  4313 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 10:23:17.142  4289  4313 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 10:23:17.142  4289  4313 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 10:23:17.143  4289  4313 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 10:23:17.143  4289  4313 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 10:23:17.143  4289  4313 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 10:23:17.143  4289  4313 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 10:23:17.144  4289  4313 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 10:23:17.144  4289  4313 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 10:23:17.144  4289  4313 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 10:23:17.144  4289  4313 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 10:23:17.280  4289  4313 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39ffd9d
08-17 10:23:17.280  4289  4313 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39ffd9d 
,08-17 10:23:17.288  4289  4305 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 10:23:17.290  4289  4305 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 10:23:17.291  4289  4305 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 10:23:17.296  4289  4305 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 10:23:17.300  4289  4305 D BluetoothAdapterProperties: Scan Mode:20
,08-17 10:23:17.301  4289  4305 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 10:23:17.301  4289  4305 D bt_hci  : do_postload posting postload work item
,08-17 10:23:17.302  4289  4309 I bt_hci  : event_postload
,08-17 10:23:17.302  4289  4309 I bt_vendor: sco_config_cb
,08-17 10:23:17.302  4289  4309 I bt_hci  : sco_config_callback postload finished.
,08-17 10:23:17.304  4289  4305 D bt_bte_conf: Device ID record 1 : primary
,08-17 10:23:17.304  4289  4305 D bt_bte_conf:   vendorId            = 000f
,08-17 10:23:17.305  4289  4305 D bt_bte_conf:   vendorIdSource      = 0001
08-17 10:23:17.305  4289  4305 D bt_bte_conf:   product             = 1200
08-17 10:23:17.305  4289  4305 D bt_bte_conf:   version             = 1436
08-17 10:23:17.305  4289  4305 D bt_bte_conf:   clientExecutableURL = 
,08-17 10:23:17.305  4289  4305 D bt_bte_conf:   serviceDescription  = 
08-17 10:23:17.306  4289  4305 D bt_bte_conf:   documentationURL    = 
08-17 10:23:17.306  4289  4305 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-17 10:23:17.307  4289  4302 D bt_stack_manager: event_start_up_stack finished
,08-17 10:23:17.307  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:23:17.308  4289  4301 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-17 10:23:17.309  4289  4301 D BluetoothAdapterProperties: Setting state to 15
,08-17 10:23:17.309  4289  4301 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-17 10:23:17.311  4289  4301 I BluetoothAdapterState: Entering BleOnState
08-17 10:23:17.314  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:17.315  4289  4309 I bt_vendor: low_power_mode_cb
,08-17 10:23:17.318  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:17.320  4289  4301 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-17 10:23:17.320  4289  4301 D BluetoothAdapterProperties: Setting state to 11
08-17 10:23:17.320  4289  4301 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-17 10:23:17.325  4289  4289 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
08-17 10:23:17.326  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:23:17.327  4289  4289 D HeadsetService: Received start request. Starting profile...
08-17 10:23:17.328  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:17.329  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:17.331  4289  4289 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 10:23:17.331  4289  4289 D HeadsetStateMachine: make
,08-17 10:23:17.342  4289  4289 D HeadsetStateMachine: max_hf_connections = 1
,08-17 10:23:17.343  4289  4289 I bt_bluedroid: get_profile_interface handsfree
08-17 10:23:17.343  4289  4301 I BluetoothAdapterState: Entering PendingCommandState
08-17 10:23:17.343  4289  4305 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-17 10:23:17.343  4289  4305 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-17 10:23:17.348  4289  4289 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
,08-17 10:23:17.349  4289  4289 D A2dpService: Received start request. Starting profile...
,08-17 10:23:17.350  4289  4289 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 10:23:17.350  4289  4289 I bt_bluedroid: get_profile_interface avrcp
,08-17 10:23:17.355  4289  4289 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 10:23:17.355  4289  4289 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 10:23:17.356  4289  4289 D A2dpStateMachine: make
,08-17 10:23:17.357  4289  4289 I bt_bluedroid: get_profile_interface a2dp
,08-17 10:23:17.358  4289  4305 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 10:23:17.359  4289  4323 D A2dpStateMachine: Enter Disconnected: -2
,08-17 10:23:17.359  4289  4289 I BluetoothHidServiceJni: classInitNative: succeeds
08-17 10:23:17.360  4289  4289 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
,08-17 10:23:17.361  4289  4289 D HidService: Received start request. Starting profile...
08-17 10:23:17.361  4063  4063 D BluetoothInputDevice: Proxy object connected
,08-17 10:23:17.361  4289  4289 I bt_bluedroid: get_profile_interface hidhost
08-17 10:23:17.362  4289  4305 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e13e5
08-17 10:23:17.362  4289  4305 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-17 10:23:17.362  4289  4289 D HidService: setHidService(): set to: null
08-17 10:23:17.362  4063  4063 D HidProfile: Bluetooth service connected
08-17 10:23:17.363  4289  4289 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 10:23:17.363  4289  4289 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
08-17 10:23:17.364  4289  4289 D HealthService: Received start request. Starting profile...
,08-17 10:23:17.365  4289  4289 I bt_bluedroid: get_profile_interface health
,08-17 10:23:17.368  4289  4289 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-17 10:23:17.368  1496  1496 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 10:23:17.370  4289  4289 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
,08-17 10:23:17.371  4289  4289 D PanService: Received start request. Starting profile...
,08-17 10:23:17.371  4063  4063 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 10:23:17.371  4289  4289 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 10:23:17.371  4289  4289 I bt_bluedroid: get_profile_interface pan
08-17 10:23:17.371  4063  4063 D PanProfile: Bluetooth service connected
08-17 10:23:17.372  4289  4305 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 10:23:17.377  4289  4289 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
,08-17 10:23:17.378  4289  4289 D BluetoothMapService: Received start request. Starting profile...
,08-17 10:23:17.378  4289  4289 D BluetoothMapService: start()
,08-17 10:23:17.378  4063  4063 D BluetoothMap: Proxy object connected
,08-17 10:23:17.379  4063  4063 D MapProfile: Bluetooth service connected
,08-17 10:23:17.379  4063  4063 D BluetoothMap: getConnectedDevices()
,08-17 10:23:17.380  4063  4063 D BluetoothMap: Bluetooth is Not enabled
08-17 10:23:17.380  4289  4289 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 10:23:17.381  4289  4289 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-17 10:23:17.381  4289  4289 D BluetoothMapAppObserver: createReceiver()
,08-17 10:23:17.381  4289  4289 D BluetoothMapAppObserver: initObservers()
,08-17 10:23:17.381  4289  4289 D BluetoothMapAppObserver: getEnabledAccountItems()
08-17 10:23:17.385  4289  4289 V BluetoothAdapterState: isTurningOff()=false
,08-17 10:23:17.385  4289  4289 V BluetoothAdapterState: isTurningOn()=true
,08-17 10:23:17.385  4289  4289 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:23:17.385  4289  4289 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:23:17.387  4289  4289 V BluetoothAdapterState: isTurningOff()=false
,08-17 10:23:17.387  4289  4289 V BluetoothAdapterState: isTurningOn()=true
,08-17 10:23:17.387  4289  4289 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 10:23:17.387  4289  4289 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:23:17.387  4289  4289 V BluetoothAdapterState: isTurningOff()=false
08-17 10:23:17.387  4289  4289 V BluetoothAdapterState: isTurningOn()=true
08-17 10:23:17.387  4289  4321 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 10:23:17.387  4289  4289 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:23:17.387  4289  4289 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:23:17.387  4289  4289 V BluetoothAdapterState: isTurningOff()=false
08-17 10:23:17.387  4289  4289 V BluetoothAdapterState: isTurningOn()=true
08-17 10:23:17.387  4289  4289 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 10:23:17.387  4289  4289 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:23:17.388  4289  4289 V BluetoothAdapterState: isTurningOff()=false
08-17 10:23:17.388  4289  4289 V BluetoothAdapterState: isTurningOn()=true
,08-17 10:23:17.388  4289  4289 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 10:23:17.388  4289  4289 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:23:17.388  4289  4289 V BluetoothAdapterState: isTurningOff()=false
08-17 10:23:17.388  4289  4289 V BluetoothAdapterState: isTurningOn()=true
,08-17 10:23:17.388  4289  4289 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:23:17.388  4289  4289 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:23:17.388  4289  4301 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-17 10:23:17.388  4289  4301 D BluetoothAdapterProperties: ScanMode =  20
,08-17 10:23:17.388  4289  4301 D BluetoothAdapterProperties: State =  11
,08-17 10:23:17.389  4289  4301 D BluetoothAdapterProperties: Setting state to 12
08-17 10:23:17.389  4289  4301 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 10:23:17.389  4289  4301 I BluetoothAdapterState: Entering OnState
,08-17 10:23:17.390  4063  4073 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 10:23:17.391  4289  4305 D BluetoothAdapterProperties: Scan Mode:21
,08-17 10:23:17.391  1361  1373 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 10:23:17.391  4289  4305 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 10:23:17.393  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:17.393  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-17 10:23:17.393  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:17.393  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:23:17.393  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:23:17.393  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:17.393  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:17.393  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:17.393   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 10:23:17.394  4063  4074 D BluetoothPan: onBluetoothStateChange on: true
,08-17 10:23:17.394  1361  1379 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 10:23:17.394  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:23:17.397  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:17.397  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:17.397  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:17.397  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:23:17.397  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:23:17.397  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:17.397  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:17.397  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:17.398  1361  2035 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 10:23:17.398  1361  2084 D BluetoothMap: onBluetoothStateChange: up=true
08-17 10:23:17.398  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:23:17.400  1361  1361 D BluetoothA2dp: Proxy object connected
08-17 10:23:17.401  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:17.401  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:17.401  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:17.401  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:23:17.401  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:23:17.401  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:17.401  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:17.401  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:17.402  1361  1361 D BluetoothMap: Proxy object connected
,08-17 10:23:17.402  1361  1361 D MapProfile: Bluetooth service connected
08-17 10:23:17.402  1361  1361 D BluetoothMap: getConnectedDevices()
08-17 10:23:17.403  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:23:17.403  1361  1379 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 10:23:17.404  1361  1361 D BluetoothInputDevice: Proxy object connected
08-17 10:23:17.404  1361  2035 D BluetoothPan: onBluetoothStateChange on: true
08-17 10:23:17.404  1361  1361 D HidProfile: Bluetooth service connected
,08-17 10:23:17.405  4289  4289 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-17 10:23:17.406  4289  4289 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-17 10:23:17.406  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 10:23:17.406  1361  1361 D PanProfile: Bluetooth service connected
,08-17 10:23:17.406   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 10:23:17.407  4289  4289 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 10:23:17.407  4063  4073 D BluetoothMap: onBluetoothStateChange: up=true
08-17 10:23:17.407   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:23:17.407  4063  4074 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 10:23:17.408  4289  4289 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 10:23:17.409   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 10:23:17.409  4289  4289 D ObexServerSockets: Succeed to create listening sockets 
08-17 10:23:17.409  4289  4289 D ObexServerSockets0: startAccept()
08-17 10:23:17.409  4289  4289 D ObexServerSockets0: prepareForNewConnect()
08-17 10:23:17.409   873   873 D BluetoothA2dp: Proxy object connected
08-17 10:23:17.409  1935  1947 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:23:17.411  4289  4289 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-17 10:23:17.411  4289  4289 D BluetoothSdpJni: SDP Create record success - handle: 0
08-17 10:23:17.412  4289  4289 D BluetoothMapService: onReceive
08-17 10:23:17.413  4289  4289 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:23:17.413  4289  4289 D BluetoothMapService: STATE_ON
08-17 10:23:17.413  4289  4328 D ObexServerSockets0: Accepting socket connection...
08-17 10:23:17.413  4063  4063 D LocalBluetoothProfileManager: Adding local A2DP profile
08-17 10:23:17.414  4289  4329 D ObexServerSockets0: Accepting socket connection...
08-17 10:23:17.414   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-17 10:23:17.414  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:17.416  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:17.416  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:17.416  4063  4063 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-17 10:23:17.425  4063  4063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 10:23:17.426  4063  4063 D BluetoothA2dp: Proxy object connected
,08-17 10:23:17.429  1496  1496 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 10:23:17.435  4063  4063 D DockEventReceiver: finishStartingService: stopping service
,08-17 10:23:17.437  1361  1361 D BluetoothPbap: Proxy object connected
08-17 10:23:17.437  1361  1361 D PbapServerProfile: Bluetooth service connected
,08-17 10:23:17.438  4289  4289 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 10:23:17.438  4289  4289 D ObexServerSockets0: prepareForNewConnect()
,08-17 10:23:17.438  4063  4063 D BluetoothPbap: Proxy object connected
08-17 10:23:17.438  4063  4063 D PbapServerProfile: Bluetooth service connected
,08-17 10:23:17.444  4289  4333 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 10:23:17.455  4289  4337 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 10:23:17.455  4289  4337 I BtOppRfcommListener: Accept thread started.
,08-17 10:23:17.495  1361  2035 D BluetoothHeadset: Proxy object connected
08-17 10:23:17.495  1361  1361 D HeadsetProfile: Bluetooth service connected
08-17 10:23:17.495   873   873 D BluetoothHeadset: Proxy object connected
08-17 10:23:17.495   873   873 D BluetoothHeadset: Proxy object connected
,08-17 10:23:17.495   873   873 D BluetoothHeadset: Proxy object connected
,08-17 10:23:17.495  1935  1950 D BluetoothHeadset: Proxy object connected
,08-17 10:23:17.498  1361  1379 D BluetoothHeadset: Proxy object connected
,08-17 10:23:17.498  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-17 10:23:17.505   873   890 D BluetoothHeadset: Proxy object connected
,08-17 10:23:17.507   873   890 D BluetoothHeadset: Proxy object connected
,08-17 10:23:17.510  1935  2120 D BluetoothHeadset: Proxy object connected
,08-17 10:23:17.519  4063  4073 D BluetoothHeadset: Proxy object connected
08-17 10:23:17.520  4063  4063 D HeadsetProfile: Bluetooth service connected
,08-17 10:23:20.870  4289  4301 D BluetoothAdapterState: Current state: ON, message: 23
,08-17 10:23:20.870  4289  4301 D BluetoothAdapterProperties: Setting state to 13
,08-17 10:23:20.871  4289  4301 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-17 10:23:20.872  4289  4301 D BluetoothAdapterProperties: onBluetoothDisable()
,08-17 10:23:20.882  4289  4289 D BluetoothMapService: onReceive
,08-17 10:23:20.882  4289  4289 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 10:23:20.883  4289  4289 D BluetoothMapService: STATE_TURNING_OFF
08-17 10:23:20.887  4289  4289 D BluetoothMapService: MAP Service closeService in
08-17 10:23:20.887  4289  4289 D BluetoothMapMasInstance0: MAP Service shutdown
,08-17 10:23:20.887  4289  4289 D ObexServerSockets0: shutdown(block = true)
08-17 10:23:20.888  4289  4328 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-17 10:23:20.892  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:20.893  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:20.893  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:20.893  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:20.893  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:23:20.893  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:20.893  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:20.893  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:20.893  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:20.896  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:20.896  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:23:20.896  4289  4301 I BluetoothAdapterState: Entering PendingCommandState
,08-17 10:23:20.900  4289  4289 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-17 10:23:20.901  4289  4329 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-17 10:23:20.903  4289  4305 D BluetoothAdapterProperties: Scan Mode:20
08-17 10:23:20.903  4289  4301 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-17 10:23:20.906  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:20.906  4289  4315 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-17 10:23:20.906  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:20.906  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:20.906  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:20.906  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:23:20.906  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:20.906  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:20.906  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:20.906  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:20.906  4289  4289 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-17 10:23:20.907  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:20.907  4289  4289 D HeadsetService: Received stop request...Stopping profile...
,08-17 10:23:20.907  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:23:20.909  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:23:20.910  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:20.910  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:20.910  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:20.910  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:23:20.910  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:23:20.910  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:20.910  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:20.910  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:20.910  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:23:20.910  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:23:20.911  4063  4074 D BluetoothHeadset: Proxy object disconnected
08-17 10:23:20.912  1361  1379 D BluetoothHeadset: Proxy object disconnected
08-17 10:23:20.912  1361  1361 D HeadsetProfile: Bluetooth service disconnected
08-17 10:23:20.912   873   873 D BluetoothHeadset: Proxy object disconnected
08-17 10:23:20.912  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:20.913   873   873 D BluetoothHeadset: Proxy object disconnected
08-17 10:23:20.913   873   873 D BluetoothHeadset: Proxy object disconnected
,08-17 10:23:20.913  1935  1947 D BluetoothHeadset: Proxy object disconnected
08-17 10:23:20.913  4289  4289 I BtOppRfcommListener: stopping Accept Thread
08-17 10:23:20.913  4289  4337 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 10:23:20.914  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:20.914  4289  4337 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 10:23:20.915  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:23:20.917  4289  4289 D A2dpService: Received stop request...Stopping profile...
,08-17 10:23:20.917  4063  4063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 10:23:20.917  4289  4323 D A2dpStateMachine: Exit Disconnected: -1
,08-17 10:23:20.921   873   873 D BluetoothA2dp: Proxy object disconnected
,08-17 10:23:20.921  1361  1361 D BluetoothA2dp: Proxy object disconnected
08-17 10:23:20.922  4289  4289 D HidService: Received stop request...Stopping profile...
08-17 10:23:20.922  4289  4289 D HidService: Stopping Bluetooth HidService
,08-17 10:23:20.921  4063  4063 D HeadsetProfile: Bluetooth service disconnected
,08-17 10:23:20.924  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-17 10:23:20.925  1361  1361 D HidProfile: Bluetooth service disconnected
08-17 10:23:20.925  4289  4289 V BluetoothAdapterState: isTurningOff()=true
08-17 10:23:20.925  4289  4289 V BluetoothAdapterState: isTurningOn()=false
08-17 10:23:20.925  4289  4289 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 10:23:20.925  4289  4289 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:23:20.926  4289  4289 D HealthService: Received stop request...Stopping profile...
08-17 10:23:20.927  4289  4289 D PanService: Received stop request...Stopping profile...
,08-17 10:23:20.928  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 10:23:20.928  1361  1361 D PanProfile: Bluetooth service disconnected
,08-17 10:23:20.929  4289  4289 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-17 10:23:20.930  4289  4289 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 10:23:20.930  4289  4305 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-17 10:23:20.930  4289  4313 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 10:23:20.930  4289  4313 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 10:23:20.930  4289  4313 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 10:23:20.930  4289  4289 D BluetoothMapService: Received stop request...Stopping profile...
08-17 10:23:20.930  4289  4289 D BluetoothMapService: stop()
,08-17 10:23:20.931  4289  4289 D BluetoothMapAppObserver: deinitObservers()
08-17 10:23:20.931  4289  4289 D BluetoothMapAppObserver: removeReceiver()
08-17 10:23:20.932  4289  4305 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-17 10:23:20.932  1361  1361 D BluetoothMap: Proxy object disconnected
08-17 10:23:20.932  1361  1361 D MapProfile: Bluetooth service disconnected
,08-17 10:23:20.934  4063  4063 D DockEventReceiver: finishStartingService: stopping service
08-17 10:23:20.934  4289  4289 V BluetoothAdapterState: isTurningOff()=true
,08-17 10:23:20.934  4289  4289 V BluetoothAdapterState: isTurningOn()=false
08-17 10:23:20.934  4289  4289 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:23:20.934  4289  4289 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:23:20.936  4289  4305 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-17 10:23:20.936  4289  4313 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 10:23:20.936  4289  4313 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 10:23:20.936  4289  4313 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 10:23:20.936  4289  4313 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 10:23:20.936  4289  4289 V BluetoothAdapterState: isTurningOff()=true
08-17 10:23:20.936  4289  4313 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 10:23:20.936  4289  4289 V BluetoothAdapterState: isTurningOn()=false
08-17 10:23:20.936  4289  4313 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 10:23:20.936  4289  4289 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:23:20.937  4289  4289 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:23:20.938  4063  4063 D BluetoothA2dp: Proxy object disconnected
,08-17 10:23:20.938  4063  4063 D BluetoothInputDevice: Proxy object disconnected
,08-17 10:23:20.939  4289  4289 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 10:23:20.939  4289  4305 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 10:23:20.939  4289  4289 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-17 10:23:20.940  4289  4289 V BluetoothAdapterState: isTurningOff()=true
08-17 10:23:20.940  4289  4289 V BluetoothAdapterState: isTurningOn()=false
08-17 10:23:20.940  4289  4289 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 10:23:20.940  4289  4289 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:23:20.940  1496  1496 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 10:23:20.940  4289  4289 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-17 10:23:20.941  4289  4289 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 10:23:20.941  4289  4289 V BluetoothAdapterState: isTurningOff()=true
08-17 10:23:20.941  4289  4289 V BluetoothAdapterState: isTurningOn()=false
08-17 10:23:20.941  4289  4289 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:23:20.941  4289  4289 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:23:20.941  4289  4289 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 10:23:20.942  4289  4289 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 10:23:20.939  4063  4063 D HidProfile: Bluetooth service disconnected
08-17 10:23:20.942  4289  4305 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-17 10:23:20.943  4063  4063 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 10:23:20.943  4063  4063 D PanProfile: Bluetooth service disconnected
08-17 10:23:20.943  4289  4289 D BluetoothMapService: MAP Service closeService in
,08-17 10:23:20.943  4063  4063 D BluetoothMap: Proxy object disconnected
08-17 10:23:20.943  4289  4289 V BluetoothAdapterState: isTurningOff()=true
08-17 10:23:20.943  4063  4063 D MapProfile: Bluetooth service disconnected
08-17 10:23:20.943  4289  4289 V BluetoothAdapterState: isTurningOn()=false
08-17 10:23:20.944  4289  4289 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 10:23:20.944  4289  4289 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:23:20.944  4289  4301 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-17 10:23:20.944  4289  4301 D BluetoothAdapterProperties: Setting state to 15
08-17 10:23:20.944  4289  4289 D BluetoothMapService: cleanup()
08-17 10:23:20.944  4289  4301 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-17 10:23:20.944  4289  4289 D BluetoothMapService: MAP Service closeService in
08-17 10:23:20.945  4063  4073 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 10:23:20.945  4289  4301 I BluetoothAdapterState: Entering BleOnState
,08-17 10:23:20.945  4063  4074 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:23:20.945  1361  2084 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 10:23:20.946  1361  1361 D BluetoothPbap: Proxy object disconnected
08-17 10:23:20.946  1361  1361 D PbapServerProfile: Bluetooth service disconnected
08-17 10:23:20.946   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:23:20.946  4063  4074 D BluetoothPan: onBluetoothStateChange on: false
08-17 10:23:20.947  4063  4063 D BluetoothPbap: Proxy object disconnected
,08-17 10:23:20.947  4063  4063 D PbapServerProfile: Bluetooth service disconnected
08-17 10:23:20.949  1361  1379 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 10:23:20.951  1361  1373 D BluetoothHeadset: onBluetoothStateChange: up=false,
08-17 10:23:20.951  1361  2035 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 10:23:20.951  1361  2084 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 10:23:20.952  1361  1379 D BluetoothPan: onBluetoothStateChange on: false
08-17 10:23:20.952   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:23:20.953  4063  4073 D BluetoothMap: onBluetoothStateChange: up=false
08-17 10:23:20.953   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:23:20.954  4063  4341 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 10:23:20.954   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 10:23:20.955  4063  4074 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 10:23:20.955  1935  1950 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:23:20.955  4289  4301 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-17 10:23:20.955  4289  4301 D BluetoothAdapterProperties: Setting state to 16
,08-17 10:23:20.956  4289  4301 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-17 10:23:20.956  4289  4301 D BluetoothAdapterProperties: onBleDisable
08-17 10:23:20.957  4289  4302 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-17 10:23:20.957  4289  4301 I BluetoothAdapterState: Entering PendingCommandState
08-17 10:23:20.957  4289  4313 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 10:23:20.957  4289  4313 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 10:23:20.959  4289  4305 D BluetoothAdapterProperties: Scan Mode:20
,08-17 10:23:20.961  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:20.962  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:20.964  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:20.965  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:20.966  4063  4063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 10:23:20.966  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:20.967  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:23:20.971  1496  1496 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 10:23:20.974  4063  4063 D DockEventReceiver: finishStartingService: stopping service
,08-17 10:23:21.158  4289  4305 I bt_hci  : shut_down
,08-17 10:23:21.159  4289  4309 D bt_hwcfg: hw_epilog_process
,08-17 10:23:21.160  4289  4309 I bt_vendor: low_power_mode_cb
,08-17 10:23:21.184  4289  4309 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-17 10:23:21.185  4289  4309 I bt_vendor: epilog_cb
08-17 10:23:21.185  4289  4309 I bt_hci  : epilog_finished_callback
,08-17 10:23:21.196  4289  4305 I bt_hci_h4: hal_close
,08-17 10:23:21.197  4289  4305 I bt_userial_vendor: device fd = 51 close
,08-17 10:23:21.333  4289  4302 D bt_stack_manager: event_shut_down_stack finished.
,08-17 10:23:21.334  4289  4301 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-17 10:23:21.340  4289  4301 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-17 10:23:21.340  4289  4289 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 10:23:21.342  4289  4289 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 10:23:21.342  4289  4289 D BtGatt.GattService: stop()
08-17 10:23:21.342  4289  4289 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 10:23:21.348  4289  4289 V BluetoothAdapterState: isTurningOff()=false
,08-17 10:23:21.348  4289  4289 V BluetoothAdapterState: isTurningOn()=false
08-17 10:23:21.348  4289  4289 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:23:21.349  4289  4289 V BluetoothAdapterState: isBleTurningOff()=true
08-17 10:23:21.350  4289  4301 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-17 10:23:21.350  4289  4301 D BluetoothAdapterProperties: Setting state to 10
08-17 10:23:21.351  4289  4301 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-17 10:23:21.352  4289  4301 I BluetoothAdapterState: Entering OffState
,08-17 10:23:21.354   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-17 10:23:21.371  4289  4289 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-17 10:23:21.371  4289  4289 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-17 10:23:21.371  4289  4302 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-17 10:23:21.381  4289  4302 D bt_stack_manager: event_clean_up_stack finished.
,08-17 10:23:21.383  4289  4289 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 10:23:21.387  4289  4289 I art     : System.exit called, status: 0
,08-17 10:23:21.387  4289  4289 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 10:23:21.463   873  2135 I ActivityManager: Process com.android.bluetooth (pid 4289) has died
,08-17 10:23:25.867  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:23:25.868  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:23:25.872  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:23:25.873  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1750d8a removed from the list
,08-17 10:23:25.873  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:23:25.873  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:23:25.874  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:23:25.877  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:23:25.877  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c57a818 added. We now have 4 listener(s)
,08-17 10:23:25.877  3960  4012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:23:25.879  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:23:25.880  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c57a818 removed from the list
,08-17 10:23:25.880  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:23:25.880  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:23:25.880  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:23:25.883  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:23:25.883  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11a1271 added. We now have 4 listener(s)
08-17 10:23:25.883  3960  4012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:23:30.894  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:23:30.946   873   890 I ActivityManager: Start proc 4348:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-17 10:23:31.072  4348  4348 D AdapterServiceConfig: Adding HeadsetService
08-17 10:23:31.072  4348  4348 D AdapterServiceConfig: Adding A2dpService
08-17 10:23:31.072  4348  4348 D AdapterServiceConfig: Adding HidService
08-17 10:23:31.072  4348  4348 D AdapterServiceConfig: Adding HealthService
08-17 10:23:31.073  4348  4348 D AdapterServiceConfig: Adding PanService
08-17 10:23:31.073  4348  4348 D AdapterServiceConfig: Adding GattService
08-17 10:23:31.073  4348  4348 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 10:23:31.086  4348  4348 D BluetoothAdapterState: make() - Creating AdapterState
08-17 10:23:31.086   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4686566:true
,08-17 10:23:31.093  4348  4348 I bt_bluedroid: init
,08-17 10:23:31.093  4348  4360 I BluetoothAdapterState: Entering OffState
,08-17 10:23:31.101  4348  4361 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 10:23:31.101  4348  4361 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 10:23:31.102  4348  4361 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 10:23:31.102  4348  4361 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 10:23:31.108  4348  4348 I bt_bluedroid: get_profile_interface socket
,08-17 10:23:31.110  4348  4348 I bt_bluedroid: get_profile_interface sdp
,08-17 10:23:31.114  4348  4359 I bt_bluedroid: config_hci_snoop_log
08-17 10:23:31.115  4348  4364 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-17 10:23:31.118   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 10:23:31.118  4348  4364 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 10:23:31.134  4348  4360 D BluetoothAdapterState: Current state: OFF, message: 0
,08-17 10:23:31.135  4348  4360 D BluetoothAdapterProperties: Setting state to 14
08-17 10:23:31.135  4348  4360 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-17 10:23:31.140  4348  4360 D BluetoothBondStateMachine: make
,08-17 10:23:31.147  4348  4365 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 10:23:31.156  4348  4360 I BluetoothAdapterState: Entering PendingCommandState
08-17 10:23:31.156  4348  4348 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 10:23:31.163  4348  4348 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
,08-17 10:23:31.165  4348  4348 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 10:23:31.166  4348  4348 D BtGatt.GattService: Received start request. Starting profile...
,08-17 10:23:31.167  4348  4348 D BtGatt.GattService: start()
08-17 10:23:31.167  4348  4348 I bt_bluedroid: get_profile_interface gatt
,08-17 10:23:31.169  4348  4348 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
08-17 10:23:31.169  4348  4348 D BtGatt.AdvertiseManager: advertise manager created
,08-17 10:23:31.185  4348  4348 V BluetoothAdapterState: isTurningOff()=false
,08-17 10:23:31.185  4348  4348 V BluetoothAdapterState: isTurningOn()=false
08-17 10:23:31.186  4348  4348 V BluetoothAdapterState: isBleTurningOn()=true
08-17 10:23:31.186  4348  4348 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:23:31.189  4348  4360 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-17 10:23:31.190  4348  4360 I bt_bluedroid: enable
,08-17 10:23:31.190  4348  4361 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-17 10:23:31.191  4348  4361 I bt_hci  : start_up
,08-17 10:23:31.213  4348  4361 I bt_vendor: alloc value 0xb3a82189
,08-17 10:23:31.214  4348  4361 I bt_vendor: init
08-17 10:23:31.214  4348  4361 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-17 10:23:31.214  4348  4361 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 10:23:31.323  4348  4361 D bt_hci  : start_up starting async portion
,08-17 10:23:31.324  4348  4368 I bt_hci  : event_finish_startup
,08-17 10:23:31.324  4348  4368 I bt_hci_h4: hal_open
08-17 10:23:31.325  4348  4368 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 10:23:31.338  4348  4368 I bt_userial_vendor: device fd = 51 open
,08-17 10:23:31.368  4348  4368 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 10:23:31.399  4348  4368 D bt_hwcfg: Chipset BCM4354A2
,08-17 10:23:31.400  4348  4368 D bt_hwcfg: Target name = [BCM4354A2]
08-17 10:23:31.400  4348  4368 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 10:23:32.238  4348  4368 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-17 10:23:32.240  4348  4368 D bt_hwcfg: Settlement delay -- 100 ms
08-17 10:23:32.240  4348  4368 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 10:23:32.358  4348  4368 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 10:23:32.360  4348  4368 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 10:23:32.387  4348  4368 I bt_hwcfg: vendor lib fwcfg completed
08-17 10:23:32.387  4348  4368 I bt_vendor: firmware callback
08-17 10:23:32.388  4348  4368 I bt_hci  : firmware_config_callback
,08-17 10:23:32.400  4348  4370 I bt_btu  : btu_task pending for preload complete event
08-17 10:23:32.400  4348  4370 I bt_btu_task: Bluetooth chip preload is complete
08-17 10:23:32.401  4348  4370 I bt_btu  : btu_task received preload complete event
,08-17 10:23:32.411  4348  4370 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 10:23:32.411  4348  4370 I         : BTE_InitTraceLevels -- TRC_L2CAP,
08-17 10:23:32.411  4348  4370 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 10:23:32.411  4348  4370 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 10:23:32.412  4348  4370 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 10:23:32.412  4348  4370 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 10:23:32.412  4348  4370 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 10:23:32.413  4348  4370 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 10:23:32.413  4348  4370 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 10:23:32.413  4348  4370 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 10:23:32.413  4348  4370 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 10:23:32.414  4348  4370 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 10:23:32.414  4348  4370 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 10:23:32.414  4348  4370 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 10:23:32.414  4348  4370 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 10:23:32.560  4348  4370 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39ffd9d
,08-17 10:23:32.561  4348  4370 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39ffd9d 
,08-17 10:23:32.574  4348  4364 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 10:23:32.577  4348  4364 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 10:23:32.579  4348  4364 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 10:23:32.588  4348  4364 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 10:23:32.592  4348  4364 D BluetoothAdapterProperties: Scan Mode:20
08-17 10:23:32.592  4348  4364 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 10:23:32.593  4348  4364 D bt_hci  : do_postload posting postload work item
08-17 10:23:32.593  4348  4368 I bt_hci  : event_postload
,08-17 10:23:32.593  4348  4368 I bt_vendor: sco_config_cb
,08-17 10:23:32.593  4348  4368 I bt_hci  : sco_config_callback postload finished.
08-17 10:23:32.597  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:32.598  4348  4364 D bt_bte_conf: Device ID record 1 : primary
08-17 10:23:32.598  4348  4364 D bt_bte_conf:   vendorId            = 000f
08-17 10:23:32.598  4348  4364 D bt_bte_conf:   vendorIdSource      = 0001
08-17 10:23:32.598  4348  4364 D bt_bte_conf:   product             = 1200
08-17 10:23:32.598  4348  4364 D bt_bte_conf:   version             = 1436
08-17 10:23:32.598  4348  4364 D bt_bte_conf:   clientExecutableURL = 
,08-17 10:23:32.598  4348  4364 D bt_bte_conf:   serviceDescription  = 
,08-17 10:23:32.598  4348  4364 D bt_bte_conf:   documentationURL    = 
,08-17 10:23:32.598  4348  4364 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-17 10:23:32.598  4348  4361 D bt_stack_manager: event_start_up_stack finished
08-17 10:23:32.603  4348  4360 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-17 10:23:32.603  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:32.604  4348  4360 D BluetoothAdapterProperties: Setting state to 15
,08-17 10:23:32.604  4348  4360 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-17 10:23:32.606  4348  4360 I BluetoothAdapterState: Entering BleOnState
,08-17 10:23:32.610  4348  4360 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-17 10:23:32.610  4348  4360 D BluetoothAdapterProperties: Setting state to 11
08-17 10:23:32.610  4348  4360 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-17 10:23:32.616  4348  4368 I bt_vendor: low_power_mode_cb
,08-17 10:23:32.618  4348  4348 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
,08-17 10:23:32.623  4348  4348 D HeadsetService: Received start request. Starting profile...
,08-17 10:23:32.626  4348  4348 I BluetoothHeadsetServiceJni: classInitNative: succeeds,
08-17 10:23:32.627  4348  4348 D HeadsetStateMachine: make,
,08-17 10:23:32.627  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:23:32.629  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:23:32.636  4348  4348 D HeadsetStateMachine: max_hf_connections = 1
,08-17 10:23:32.636  4348  4348 I bt_bluedroid: get_profile_interface handsfree
,08-17 10:23:32.636  4348  4364 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-17 10:23:32.637  4348  4364 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-17 10:23:32.637  4348  4360 I BluetoothAdapterState: Entering PendingCommandState
,08-17 10:23:32.643  4348  4348 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
,08-17 10:23:32.644  4348  4348 D A2dpService: Received start request. Starting profile...
,08-17 10:23:32.644  4348  4348 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 10:23:32.645  4348  4348 I bt_bluedroid: get_profile_interface avrcp
,08-17 10:23:32.651  4348  4348 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-17 10:23:32.652  4348  4348 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 10:23:32.652  4348  4348 D A2dpStateMachine: make
,08-17 10:23:32.653  4348  4348 I bt_bluedroid: get_profile_interface a2dp
,08-17 10:23:32.654  4348  4364 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 10:23:32.655  4348  4379 D A2dpStateMachine: Enter Disconnected: -2
,08-17 10:23:32.656  4348  4348 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 10:23:32.659  4348  4348 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
,08-17 10:23:32.661  4348  4348 D HidService: Received start request. Starting profile...
08-17 10:23:32.661  4348  4348 I bt_bluedroid: get_profile_interface hidhost
08-17 10:23:32.661  4348  4348 D HidService: setHidService(): set to: null
,08-17 10:23:32.661  4348  4364 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e13e5
08-17 10:23:32.661  4348  4364 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-17 10:23:32.661  4348  4348 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 10:23:32.662  4348  4348 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
,08-17 10:23:32.663  4348  4348 D HealthService: Received start request. Starting profile...
,08-17 10:23:32.665  4348  4348 I bt_bluedroid: get_profile_interface health
,08-17 10:23:32.668  1496  1496 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 10:23:32.668  4348  4348 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-17 10:23:32.669  4348  4348 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
,08-17 10:23:32.669  4348  4348 D PanService: Received start request. Starting profile...
,08-17 10:23:32.670  4348  4348 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-17 10:23:32.670  4348  4348 I bt_bluedroid: get_profile_interface pan
,08-17 10:23:32.670  4348  4364 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-17 10:23:32.673  4348  4348 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
,08-17 10:23:32.674  4348  4348 D BluetoothMapService: Received start request. Starting profile...
,08-17 10:23:32.674  4348  4348 D BluetoothMapService: start()
,08-17 10:23:32.676  4348  4348 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 10:23:32.677  4348  4348 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER,
08-17 10:23:32.677  4348  4348 D BluetoothMapAppObserver: createReceiver()
,08-17 10:23:32.678  4348  4348 D BluetoothMapAppObserver: initObservers()
08-17 10:23:32.678  4348  4348 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 10:23:32.684  4348  4376 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-17 10:23:32.685  4348  4348 V BluetoothAdapterState: isTurningOff()=false
,08-17 10:23:32.685  4348  4348 V BluetoothAdapterState: isTurningOn()=true
,08-17 10:23:32.685  4348  4348 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:23:32.685  4348  4348 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:23:32.686  4348  4348 V BluetoothAdapterState: isTurningOff()=false
,08-17 10:23:32.686  4348  4348 V BluetoothAdapterState: isTurningOn()=true
,08-17 10:23:32.686  4348  4348 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 10:23:32.687  4348  4348 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:23:32.687  4348  4348 V BluetoothAdapterState: isTurningOff()=false,
,08-17 10:23:32.687  4348  4348 V BluetoothAdapterState: isTurningOn()=true
,08-17 10:23:32.687  4348  4348 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 10:23:32.687  4348  4348 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:23:32.687  4348  4348 V BluetoothAdapterState: isTurningOff()=false
,08-17 10:23:32.687  4348  4348 V BluetoothAdapterState: isTurningOn()=true
08-17 10:23:32.687  4348  4348 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:23:32.687  4348  4348 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:23:32.690  4348  4348 V BluetoothAdapterState: isTurningOff()=false
08-17 10:23:32.690  4348  4348 V BluetoothAdapterState: isTurningOn()=true
,08-17 10:23:32.690  4348  4348 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:23:32.690  4348  4348 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:23:32.690  4348  4348 V BluetoothAdapterState: isTurningOff()=false
,08-17 10:23:32.690  4348  4348 V BluetoothAdapterState: isTurningOn()=true
08-17 10:23:32.690  4348  4348 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:23:32.690  4348  4348 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:23:32.690  4348  4360 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-17 10:23:32.690  4348  4360 D BluetoothAdapterProperties: ScanMode =  20
08-17 10:23:32.690  4348  4360 D BluetoothAdapterProperties: State =  11
08-17 10:23:32.691  4348  4360 D BluetoothAdapterProperties: Setting state to 12
,08-17 10:23:32.691  4348  4360 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 10:23:32.691  4348  4360 I BluetoothAdapterState: Entering OnState
08-17 10:23:32.691  4063  4341 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 10:23:32.692  4348  4364 D BluetoothAdapterProperties: Scan Mode:21
08-17 10:23:32.692  4348  4364 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 10:23:32.694  4063  4074 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:23:32.695  1361  2084 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 10:23:32.697  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:32.697  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:32.697  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:32.697  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:23:32.697  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:23:32.697  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:32.697  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:32.697  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:32.697   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:23:32.697  4063  4341 D BluetoothPan: onBluetoothStateChange on: true
08-17 10:23:32.698  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:23:32.701  1361  1379 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 10:23:32.701  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:32.701  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:32.701  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:32.701  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:23:32.701  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:23:32.701  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:32.701  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:32.701  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:32.703  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:23:32.703  1361  2035 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:23:32.704  1361  1361 D BluetoothA2dp: Proxy object connected
08-17 10:23:32.704  1361  1379 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 10:23:32.704  4348  4348 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 10:23:32.704  4348  4348 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-17 10:23:32.705  1361  2084 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 10:23:32.706  4348  4348 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 10:23:32.707  1361  1361 D BluetoothInputDevice: Proxy object connected
,08-17 10:23:32.707  1361  1361 D HidProfile: Bluetooth service connected
08-17 10:23:32.707  1361  2035 D BluetoothPan: onBluetoothStateChange on: true
08-17 10:23:32.708  4348  4348 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 10:23:32.708  4063  4063 D BluetoothInputDevice: Proxy object connected
08-17 10:23:32.708  4063  4063 D HidProfile: Bluetooth service connected
,08-17 10:23:32.709  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 10:23:32.709  4348  4348 D ObexServerSockets: Succeed to create listening sockets 
,08-17 10:23:32.709  1361  1361 D PanProfile: Bluetooth service connected
08-17 10:23:32.709  4348  4348 D ObexServerSockets0: startAccept()
08-17 10:23:32.709  4348  4348 D ObexServerSockets0: prepareForNewConnect()
,08-17 10:23:32.709   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:23:32.710  4063  4073 D BluetoothMap: onBluetoothStateChange: up=true
08-17 10:23:32.711   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:23:32.711  4348  4348 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-17 10:23:32.711  4063  4341 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 10:23:32.711  4348  4348 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-17 10:23:32.712  4348  4386 D ObexServerSockets0: Accepting socket connection...
08-17 10:23:32.712  4348  4385 D ObexServerSockets0: Accepting socket connection...
08-17 10:23:32.712  1361  1361 D BluetoothMap: Proxy object connected
08-17 10:23:32.713  1361  1361 D MapProfile: Bluetooth service connected
08-17 10:23:32.713  1361  1361 D BluetoothMap: getConnectedDevices()
08-17 10:23:32.713   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 10:23:32.713  4063  4074 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 10:23:32.713   873   873 D BluetoothA2dp: Proxy object connected
08-17 10:23:32.715  1935  1950 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:23:32.717   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-17 10:23:32.717  4348  4348 D BluetoothMapService: onReceive
08-17 10:23:32.718  4348  4348 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 10:23:32.718  4348  4348 D BluetoothMapService: STATE_ON
08-17 10:23:32.719  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:32.720  4063  4063 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 10:23:32.720  4063  4063 D PanProfile: Bluetooth service connected
08-17 10:23:32.720  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:32.721  4063  4063 D BluetoothMap: Proxy object connected
,08-17 10:23:32.721  4063  4063 D MapProfile: Bluetooth service connected
08-17 10:23:32.721  4063  4063 D BluetoothMap: getConnectedDevices()
08-17 10:23:32.722  4063  4063 D BluetoothA2dp: Proxy object connected
08-17 10:23:32.731  4063  4063 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 10:23:32.737  1496  1496 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 10:23:32.740  4063  4063 D DockEventReceiver: finishStartingService: stopping service
,08-17 10:23:32.746  4063  4063 D BluetoothPbap: Proxy object connected
,08-17 10:23:32.746  4063  4063 D PbapServerProfile: Bluetooth service connected
,08-17 10:23:32.747  4348  4348 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 10:23:32.747  4348  4348 D ObexServerSockets0: prepareForNewConnect()
08-17 10:23:32.747  1361  1361 D BluetoothPbap: Proxy object connected
,08-17 10:23:32.747  1361  1361 D PbapServerProfile: Bluetooth service connected
,08-17 10:23:32.756  4348  4391 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 10:23:32.770  4348  4395 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 10:23:32.771  4348  4395 I BtOppRfcommListener: Accept thread started.
,08-17 10:23:32.797   873   890 D BluetoothHeadset: Proxy object connected
,08-17 10:23:32.797  4063  4074 D BluetoothHeadset: Proxy object connected
,08-17 10:23:32.797  4063  4063 D HeadsetProfile: Bluetooth service connected
08-17 10:23:32.798  1361  1373 D BluetoothHeadset: Proxy object connected
08-17 10:23:32.798  1361  1361 D HeadsetProfile: Bluetooth service connected
08-17 10:23:32.798   873   873 D BluetoothHeadset: Proxy object connected
08-17 10:23:32.798   873   873 D BluetoothHeadset: Proxy object connected
08-17 10:23:32.798   873   873 D BluetoothHeadset: Proxy object connected
08-17 10:23:32.798  1935  2120 D BluetoothHeadset: Proxy object connected
,08-17 10:23:32.804  1361  2084 D BluetoothHeadset: Proxy object connected
08-17 10:23:32.804  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-17 10:23:32.810   873   890 D BluetoothHeadset: Proxy object connected
,08-17 10:23:32.810   873   890 D BluetoothHeadset: Proxy object connected
,08-17 10:23:32.816  1935  1947 D BluetoothHeadset: Proxy object connected
,08-17 10:23:35.912  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:35.912  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:35.912  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:35.912  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:23:35.912  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:23:35.912  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:35.912  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:35.912  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:23:35.920  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:23:35.922  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:23:35.922  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11a1271 removed from the list
08-17 10:23:35.923  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:23:35.923  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:23:35.923  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:23:35.926  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:23:35.926  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e1e7856 added. We now have 4 listener(s)
08-17 10:23:35.926  3960  4012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:23:35.930   873  1681 D WifiService: setWifiEnabled: false pid=3960, uid=10000
08-17 10:23:35.931   873  1681 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 10:23:36.921  1875  1904 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-17 10:23:36.921  1875  1904 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-17 10:23:36.971  1496  1496 I ConfigService: onCreate
,08-17 10:23:40.943  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:23:40.945   873  1680 D WifiService: setWifiEnabled: true pid=3960, uid=10000
08-17 10:23:40.945   873  1680 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 10:23:40.959   873  1302 D WifiConfigStore: Loading config and enabling all networks 
,08-17 10:23:40.978  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:40.978  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:40.978  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:40.978  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:40.978  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:23:40.978  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:40.978  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:40.978  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:23:40.984  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:23:40.991   873  1302 D WifiConfigStore: loaded 0 passpoint configs
08-17 10:23:40.992   873  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-17 10:23:40.993  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:40.993  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:40.993  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:40.993  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:40.993  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:23:40.993  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:23:40.993  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:23:40.993  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:23:40.993   873  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-17 10:23:40.995   873  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-17 10:23:40.995   873  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-17 10:23:40.996   873  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-17 10:23:40.996   873  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 10:23:41.000  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:23:41.008   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-17 10:23:41.008   873  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-17 10:23:41.009   372   871 D CommandListener: Setting iface cfg
,08-17 10:23:41.010   873  1301 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
08-17 10:23:41.010   873  1301 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 10:23:41.062   873  1301 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 10:23:41.062   873  1302 E native  : do suspend true
08-17 10:23:41.062   873  1301 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 10:23:41.101   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 10:23:42.050  1496  1496 I ConfigService: onDestroy
,08-17 10:23:42.477   873  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-17 10:23:42.622   873  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=12.81 rxSuccessRate=14.00 delta 1000 -> 994
,08-17 10:23:42.623   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-17 10:23:42.624   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 10:23:42.640   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 10:23:42.686   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 10:23:42.687  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 10:23:43.118  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 10:23:43.162  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 10:23:43.165  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 10:23:43.173   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 10:23:43.189   873  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-17 10:23:43.190   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 10:23:43.190   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 10:23:43.214   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 10:23:43.231   372   871 D CommandListener: Setting iface cfg
,08-17 10:23:43.233   873  1302 D WifiStateMachine: Start Dhcp Watchdog 3
,08-17 10:23:43.241   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 10:23:43.269   873  4405 D DhcpClient: Receive thread started
,08-17 10:23:43.365   873  1302 E native  : do suspend false
,08-17 10:23:43.393   873  2107 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 10:23:43.407   873  4405 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,08-17 10:23:43.408   873  2107 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,08-17 10:23:43.413   873  2107 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 10:23:43.428   873  4405 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 10:23:43.430   873  2107 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 10:23:43.434   372   871 D CommandListener: Setting iface cfg
,08-17 10:23:43.445   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 10:23:43.446   873  2107 D DhcpClient: Scheduling renewal in 86399s
,08-17 10:23:43.448   873  1302 E native  : do suspend true
,08-17 10:23:43.469   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 10:23:43.470   873  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 10:23:43.471   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-17 10:23:43.474   873  1304 D ConnectivityService: Adding iface wlan0 to network 102
,08-17 10:23:43.473   873  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 10:23:43.562   873  1304 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-17 10:23:43.562   873  1304 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-17 10:23:43.569   873  1304 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-17 10:23:43.571   873  1304 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-17 10:23:43.572   873  1304 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-17 10:23:43.583   873  1304 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-17 10:23:43.589   873  1304 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-17 10:23:43.589   873  1304 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-17 10:23:43.589   873  1304 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-17 10:23:43.589   873  1304 D ConnectivityService:    accepting network in place of null
08-17 10:23:43.589   873  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-17 10:23:43.591   873  1304 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 10:23:43.592   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 10:23:43.605   873  4404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=216562, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 10:23:43.657   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 10:23:43.674   873  4403 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.174,2a00:1450:4001:80e::200e
,08-17 10:23:43.692   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 10:23:43.701   873  1304 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-17 10:23:43.702   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:23:43.711   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-17 10:23:43.717   873  1304 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-17 10:23:43.730  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:43.730  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:43.730  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:43.730  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:43.730  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:23:43.730  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:23:43.730  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:23:43.730  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:23:43.734  2020  2020 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-17 10:23:43.736  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:23:43.740  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:43.740  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:43.740  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:43.740  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:43.740  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:23:43.740  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:23:43.740  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:23:43.740  3960  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:23:43.741  1703  1703 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 10:23:43.742  3960  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:23:43.745   873  4403 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 08:23:43 GMT], X-Android-Received-Millis=[1471422223745], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471422223719]}
08-17 10:23:43.747   873  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-17 10:23:43.747   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-17 10:23:43.747   873  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-17 10:23:43.748   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 10:23:43.754  1703  1703 D SystemUpdateService: onCreate
,08-17 10:23:43.757  1703  1703 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 10:23:43.773  1703  4415 I SystemUpdateService: active receiver: enabled
,08-17 10:23:43.776  1703  1703 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 10:23:43.782  1703  2505 I iu.UploadsManager: num queued entries: 0
,08-17 10:23:43.782  1703  2505 I iu.UploadsManager: num updated entries: 0
,08-17 10:23:43.786  1703  1703 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 10:23:43.787  1703  1703 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 10:23:43.788  4120  4120 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:23:43.792  1703  4417 I MDM     : [188] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-17 10:23:43.792  1703  4417 W BaseAppContext: Using Auth Proxy for data requests.
,08-17 10:23:43.794  1703  4417 V GoogleAuthProtoRequest: [188] a.<init>: mAccountName set to: thalitester@gmail.com
,08-17 10:23:43.795  4120  4120 D SprintDMHelper: simOperator: 
08-17 10:23:43.795  4120  4120 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 10:23:43.800  1703  4415 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 10:23:43.809  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:23:43.817  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:23:43.829  1703  2505 I iu.SyncManager: NEXT; no task
,08-17 10:23:43.830  1703  4415 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-17 10:23:43.830  1703  4415 I SystemUpdateService: now status is 0 (complete)
08-17 10:23:43.830  1703  4415 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-17 10:23:43.830  1703  4415 I SystemUpdateService: file has been verified
,08-17 10:23:43.838  1703  4415 I SystemUpdateService: OTA package size = 12249756
,08-17 10:23:43.862  1703  4415 I SystemUpdateService: showing system update notification
,08-17 10:23:43.875  1703  1703 D SystemUpdateService: onDestroy
,08-17 10:23:43.892  1496  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-17 10:23:43.893  1496  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-17 10:23:43.893  1496  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:23:43.893  1496  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:23:43.926  1703  4417 E MDM     : [188] SitrepService.a: Error sending sitrep.
,08-17 10:23:43.947  2854  4420 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 10:23:44.701   873  1304 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-17 10:23:45.968  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:23:45.968  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:45.968  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:45.968  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:45.968  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:23:45.968  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:23:45.968  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:23:45.968  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:23:45.976  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:23:45.977  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:23:45.977  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e1e7856 removed from the list
,08-17 10:23:45.977  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:23:45.978  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:23:45.978  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:23:45.990  3960  4426 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-17 10:23:45.990  3960  4426 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 10:23:48.996  3960  4427 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-17 10:23:48.997  3960  4426 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-17 10:23:48.998  3960  4427 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-17 10:23:48.998  3960  4426 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-17 10:23:48.999  3960  4427 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:23:48.999  3960  4426 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:23:49.001  3960  4427 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-17 10:23:49.001  3960  4426 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:23:49.004  3960  4429 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 453, name: IncomingSocketThread/Sender)
,08-17 10:23:49.010  3960  4427 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-17 10:23:49.010  3960  4426 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-17 10:23:49.014  3960  4430 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 454, name: OutgoingSocketThread/Sender)
,08-17 10:23:49.017  3960  4432 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 456, name: OutgoingSocketThread/Receiver)
08-17 10:23:49.018  3960  4431 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 455, name: IncomingSocketThread/Receiver)
08-17 10:23:49.019  3960  4432 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 456, thread name: OutgoingSocketThread/Receiver)
08-17 10:23:49.019  3960  4431 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 455, thread name: IncomingSocketThread/Receiver)
08-17 10:23:49.019  3960  4431 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-17 10:23:49.019  3960  4432 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-17 10:23:49.019  3960  4431 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 455, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-17 10:23:49.020  3960  4432 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 456, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-17 10:23:51.596   873  1304 D ConnectivityService: handlePromptUnvalidated 102
,08-17 10:23:51.997  3960  4012 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-17 10:23:51.999  3960  4012 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-17 10:23:52.005  3960  4012 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3357138 Bundle[{}]
,08-17 10:23:52.008  3960  4012 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 10:23:52.009  3960  4012 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-17 10:23:52.009  3960  4012 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-17 10:23:52.010  3960  4012 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 10:23:52.010  3960  4012 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-17 10:23:52.011  3960  4012 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 10:23:52.015  3960  4012 I System.out: Running OutgoingSocketThread
,08-17 10:23:52.018  3960  4433 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-17 10:23:52.018  3960  4433 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 10:23:55.027  3960  4434 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-17 10:23:55.028  3960  4434 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-17 10:23:55.028  3960  4434 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:23:55.028  3960  4433 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-17 10:23:55.029  3960  4433 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-17 10:23:55.029  3960  4433 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:23:55.030  3960  4434 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:23:55.031  3960  4433 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-17 10:23:55.034  3960  4434 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-17 10:23:55.036  3960  4436 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 465, name: IncomingSocketThread/Sender)
,08-17 10:23:55.038  3960  4433 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-17 10:23:55.042  3960  4437 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 466, name: OutgoingSocketThread/Sender)
,08-17 10:23:55.044  3960  4438 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 467, name: IncomingSocketThread/Receiver)
,08-17 10:23:55.046  3960  4438 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 467, thread name: IncomingSocketThread/Receiver)
08-17 10:23:55.046  3960  4438 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-17 10:23:55.047  3960  4438 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 467, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-17 10:23:55.048  3960  4439 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 468, name: OutgoingSocketThread/Receiver)
,08-17 10:23:55.050  3960  4439 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 468, thread name: OutgoingSocketThread/Receiver)
08-17 10:23:55.050  3960  4439 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-17 10:23:55.051  3960  4439 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 468, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-17 10:23:58.030  3960  4012 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 477)
,08-17 10:23:58.032  3960  4012 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-17 10:23:58.033  3960  4012 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 478)
,08-17 10:23:58.039  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 10:23:58.039  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@427a0d7 added. We now have 3 listener(s)
,08-17 10:23:58.041  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 10:23:58.041  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:23:58.041  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:23:58.042  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 10:23:58.042  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52b2dc4 added. We now have 4 listener(s)
,08-17 10:23:58.042  3960  4012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:23:58.043  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 10:23:58.047  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:23:58.058  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:23:58.058  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:58.058  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:58.058  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:58.058  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:23:58.058  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:23:58.058  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:23:58.058  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:23:58.065  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:23:58.065  3960  4012 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 10:23:58.066  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:23:58.066  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:23:58.066  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:23:58.066  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 10:23:58.066  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:23:58.066  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:23:58.066  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 10:23:58.066  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@427a0d7 removed from the list
08-17 10:23:58.066  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:23:58.066  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52b2dc4 removed from the list
08-17 10:23:58.070  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:23:58.075  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:23:58.076  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:23:58.076  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:23:58.077  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:23:58.077  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:23:58.080  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 10:23:58.080  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:23:58.080  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:23:58.080  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52b2dc4 not in the list
,08-17 10:23:58.080  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:23:58.080  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:23:58.084  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:23:58.084  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:23:58.085  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:23:58.085  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52b2dc4 not in the list
,08-17 10:23:58.085  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:23:58.085  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:23:58.086  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:23:58.086  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@427a0d7 not in the list
08-17 10:23:58.088  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 10:23:58.088  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a21c3e2 added. We now have 3 listener(s)
,08-17 10:23:58.094  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 10:23:58.094  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:23:58.094  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 10:23:58.095  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:23:58.095  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cdb7373 added. We now have 4 listener(s)
08-17 10:23:58.095  3960  4012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:23:58.097  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 10:23:58.103  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:23:58.118  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:23:58.118  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:23:58.118  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:23:58.118  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:23:58.118  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:23:58.118  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:23:58.118  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:23:58.118  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:23:58.125  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:23:58.126  3960  4012 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 10:23:58.128  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 10:23:58.128  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-17 10:23:58.128  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 10:23:58.129  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:23:58.129  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 10:23:58.132  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:23:58.138  3960  4012 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 10:23:58.138  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 10:23:58.139  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:23:58.151  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 10:23:58.153  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 10:23:58.153  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 10:23:58.166  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 10:23:58.167  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 10:23:58.167  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 10:23:58.169  3960  4012 D BluetoothAdapter: STATE_ON
,08-17 10:23:58.178  4348  4387 D BtGatt.GattService: registerClient() - UUID=924c56fb-3da2-4f2f-b0dc-3174783a11cd
,08-17 10:23:58.181  4348  4364 D BtGatt.GattService: onClientRegistered() - UUID=924c56fb-3da2-4f2f-b0dc-3174783a11cd, clientIf=5
,08-17 10:23:58.183  3960  3972 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 10:23:58.187  4348  4358 D BtGatt.GattService: start scan with filters
,08-17 10:23:58.202  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 10:23:58.202  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 10:23:58.202  4348  4367 D BtGatt.ScanManager: handling starting scan
08-17 10:23:58.203  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 10:23:58.203  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 10:23:58.211  4348  4367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b0dc4c
,08-17 10:23:58.214  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 10:23:58.215  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 10:23:58.215  3960  3960 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 10:23:58.222  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 10:23:58.228  4348  4364 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 10:23:58.228  4348  4364 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:23:58.230  4348  4367 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 10:23:58.234  3960  4012 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 10:23:58.235  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:23:58.235  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 10:23:58.236  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:23:58.236  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-17 10:23:58.236  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 10:23:58.237  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 10:23:58.237  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 10:23:58.237  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 10:23:58.237  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 10:23:58.238  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 10:23:58.240  3960  4012 D BluetoothAdapter: STATE_ON
08-17 10:23:58.242  4348  4358 D BtGatt.GattService: stopScan() - queue size =1
08-17 10:23:58.244  4348  4384 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 10:23:58.246  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 10:23:58.247  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 10:23:58.247  4348  4364 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 10:23:58.247  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 10:23:58.247  4348  4364 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:23:58.247  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 10:23:58.248  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 10:23:58.248  4348  4367 D BtGatt.ScanManager: Starting BLE batch scan
08-17 10:23:58.249  4348  4367 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 10:23:58.251  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 10:23:58.252  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 10:23:58.252  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 10:23:58.252  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 10:23:58.254  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:23:58.257  3960  3960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:23:58.257  3960  3960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:23:58.257  3960  3960 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 10:23:58.268  4348  4364 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 10:23:58.268  4348  4364 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:23:58.276  4348  4364 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 10:23:58.276  4348  4364 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:23:58.289  4348  4364 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 10:23:58.289  4348  4364 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:23:58.290  4348  4367 D BtGatt.ScanManager: stopping BLe Batch
,08-17 10:23:58.300  4348  4364 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 10:23:58.301  4348  4364 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:23:58.301  4348  4367 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:23:58.310  4348  4364 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 10:23:58.310  4348  4364 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:23:58.758  3960  3960 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-17 10:23:58.759  3960  3960 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:23:58.759  3960  3960 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 10:24:01.258  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:24:01.258  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:24:01.259  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:24:01.260  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 10:24:01.260  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:24:01.260  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:24:01.261  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 10:24:01.261  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a21c3e2 removed from the list
,08-17 10:24:01.261  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:24:01.262  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cdb7373 removed from the list
08-17 10:24:01.262  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:24:01.262  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:24:01.264  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:24:01.264  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:24:01.268  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 10:24:01.268  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:24:01.269  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:24:01.269  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cdb7373 not in the list
08-17 10:24:01.269  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:24:01.270  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:24:01.273  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:24:01.273  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:24:01.274  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:24:01.274  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cdb7373 not in the list
08-17 10:24:01.274  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:24:01.274  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:24:01.275  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:24:01.275  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a21c3e2 not in the list
08-17 10:24:01.277  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 10:24:01.278  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c0715c added. We now have 3 listener(s)
,08-17 10:24:01.283  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 10:24:01.284  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:24:01.284  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 10:24:01.285  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:24:01.285  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a27c65 added. We now have 4 listener(s)
08-17 10:24:01.286  3960  4012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:24:01.287  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 10:24:01.293  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-17 10:24:01.303  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:24:01.303  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:24:01.303  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:24:01.303  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:24:01.303  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:24:01.303  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:24:01.303  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:24:01.303  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:24:01.307  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:24:01.308  3960  4012 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:24:01.308  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-17 10:24:01.309  3960  4012 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,08-17 10:24:01.309  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-17 10:24:01.310  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-17 10:24:01.311  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-17 10:24:01.311  3960  4012 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-17 10:24:01.312  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:24:01.314  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:24:01.318  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-17 10:24:01.319  3960  4012 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-17 10:24:01.319  3960  4012 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-17 10:24:01.319  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-17 10:24:01.320  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-17 10:24:01.321  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:24:01.321  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 10:24:01.324  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:24:01.325  3960  3960 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-17 10:24:01.326  3960  4440 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 10:24:01.331  3960  4012 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 10:24:01.331  3960  4440 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-17 10:24:01.331  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 10:24:01.342  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 10:24:01.343  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 10:24:01.344  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 10:24:01.346  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-17 10:24:01.347  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 10:24:01.347  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-17 10:24:01.348  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-17 10:24:01.348  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-17 10:24:01.348  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-17 10:24:01.349  3960  4012 D BluetoothAdapter: STATE_ON
,08-17 10:24:01.354  4348  4358 D BtGatt.GattService: registerClient() - UUID=a99b4f44-190c-484c-b974-73a261ef0155
08-17 10:24:01.355  4348  4364 D BtGatt.GattService: onClientRegistered() - UUID=a99b4f44-190c-484c-b974-73a261ef0155, clientIf=5
08-17 10:24:01.355  3960  3972 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-17 10:24:01.358  4348  4366 D BtGatt.AdvertiseManager: message : 0
,08-17 10:24:01.361  4348  4366 D BtGatt.AdvertiseManager: starting multi advertising
,08-17 10:24:01.374  4348  4364 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-17 10:24:01.383  4348  4364 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-17 10:24:01.385  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-17 10:24:01.386  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 10:24:01.387  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 10:24:01.390  3960  3960 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-17 10:24:01.390  3960  3960 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-17 10:24:01.391  3960  3960 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-17 10:24:01.391  3960  3960 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-17 10:24:01.391  3960  3960 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-17 10:24:01.391  3960  3960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-17 10:24:01.393  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 10:24:01.394  3960  3960 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-17 10:24:01.394  3960  3960 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-17 10:24:01.895  3960  3960 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-17 10:24:01.896  3960  3960 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 10:24:01.896  3960  3960 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 10:24:04.394  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:24:04.395  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-17 10:24:04.395  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 10:24:04.395  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 10:24:04.396  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 10:24:04.396  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 10:24:04.397  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-17 10:24:04.398  3960  4440 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-17 10:24:04.398  3960  4440 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 10:24:04.398  3960  4440 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 10:24:04.399  3960  3960 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 10:24:04.400  3960  4012 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 10:24:04.401  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 10:24:04.402  3960  3960 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 10:24:04.402  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 10:24:04.403  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 10:24:04.403  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 10:24:04.403  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 10:24:04.407  3960  4012 D BluetoothAdapter: STATE_ON
08-17 10:24:04.407  3960  4012 D BluetoothLeScanner: could not find callback wrapper
,08-17 10:24:04.407  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:24:04.407  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-17 10:24:04.409  4348  4366 D BtGatt.AdvertiseManager: message : 1
,08-17 10:24:04.411  4348  4366 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-17 10:24:04.420  4348  4364 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-17 10:24:04.420  4348  4364 D BtGatt.GattService: Client app is not null!
08-17 10:24:04.421  4348  4358 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 10:24:04.422  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 10:24:04.423  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-17 10:24:04.423  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-17 10:24:04.423  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-17 10:24:04.423  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-17 10:24:04.425  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 10:24:04.425  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 10:24:04.426  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 10:24:04.427  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 10:24:04.430  3960  3960 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:24:04.430  3960  3960 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-17 10:24:04.431  3960  3960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:24:04.431  3960  3960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 10:24:04.431  3960  3960 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 10:24:04.432  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:24:04.432  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:24:04.432  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:24:04.433  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 10:24:04.433  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c0715c removed from the list
08-17 10:24:04.434  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:24:04.434  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a27c65 removed from the list
08-17 10:24:04.434  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:24:04.435  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:24:04.436  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:24:04.436  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:24:04.438  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:24:04.438  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:24:04.438  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:24:04.439  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a27c65 not in the list
08-17 10:24:04.439  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:24:04.439  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:24:04.443  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:24:04.443  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:24:04.444  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:24:04.444  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a27c65 not in the list
08-17 10:24:04.444  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:24:04.444  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:24:04.445  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:24:04.445  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c0715c not in the list
08-17 10:24:04.447  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 10:24:04.447  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e3a306 added. We now have 3 listener(s)
,08-17 10:24:04.453  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 10:24:04.453  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:24:04.453  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:24:04.453  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 10:24:04.454  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3c6dc7 added. We now have 4 listener(s)
08-17 10:24:04.454  3960  4012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:24:04.454  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 10:24:04.459  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:24:04.465  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:24:04.465  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:24:04.465  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:24:04.465  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:24:04.465  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:24:04.465  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:24:04.465  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:24:04.465  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:24:04.468  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:24:04.468  3960  4012 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:24:04.468  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 10:24:04.469  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 10:24:04.469  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 10:24:04.469  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:24:04.469  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 10:24:04.471  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:24:04.474  3960  4012 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 10:24:04.474  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 10:24:04.475  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:24:04.479  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 10:24:04.479  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 10:24:04.479  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 10:24:04.484  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 10:24:04.484  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 10:24:04.484  3960  4012 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 10:24:04.485  3960  4012 D BluetoothAdapter: STATE_ON
,08-17 10:24:04.488  4348  4384 D BtGatt.GattService: registerClient() - UUID=0460b2dc-0ed6-4e91-91c2-223cab1ec4b0
,08-17 10:24:04.488  4348  4364 D BtGatt.GattService: onClientRegistered() - UUID=0460b2dc-0ed6-4e91-91c2-223cab1ec4b0, clientIf=5
08-17 10:24:04.489  3960  3972 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 10:24:04.489  4348  4358 D BtGatt.GattService: start scan with filters
,08-17 10:24:04.493  4348  4367 D BtGatt.ScanManager: handling starting scan
08-17 10:24:04.493  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 10:24:04.493  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 10:24:04.493  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 10:24:04.494  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 10:24:04.498  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 10:24:04.499  3960  3960 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 10:24:04.499  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 10:24:04.502  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 10:24:04.505  4348  4364 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 10:24:04.505  4348  4364 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:24:04.505  4348  4367 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 10:24:04.515  4348  4364 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 10:24:04.515  4348  4364 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:24:04.515  4348  4367 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 10:24:04.515  4348  4367 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 10:24:04.532  4348  4364 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 10:24:04.532  4348  4364 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:24:04.541  4348  4364 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 10:24:04.541  4348  4364 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:24:04.767   873  4404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=237723, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-17 10:24:04.933  3960  3960 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 10:24:04.999  3960  3960 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-17 10:24:05.000  3960  3960 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 10:24:05.000  3960  3960 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 10:24:06.051  4348  4348 D BtGatt.ScanManager: awakened up at time 239009
,08-17 10:24:06.056  4348  4367 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:24:06.103  4348  4364 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-17 10:24:06.103  4348  4364 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:24:06.104  4348  4364 D BtGatt.GattService: current time is 239061527028
08-17 10:24:06.105  4348  4364 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -90, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -81, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -85, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -86, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -79, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
,08-17 10:24:06.112  4348  4364 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-17 10:24:06.116  4348  4364 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-17 10:24:06.117  4348  4364 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-17 10:24:06.119  4348  4364 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-17 10:24:06.122  4348  4364 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-17 10:24:06.125  4348  4364 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-17 10:24:07.514  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:24:07.515  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 10:24:07.515  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 10:24:07.516  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:24:07.516  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-17 10:24:07.516  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 10:24:07.517  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 10:24:07.517  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 10:24:07.517  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 10:24:07.518  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 10:24:07.519  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 10:24:07.521  3960  4012 D BluetoothAdapter: STATE_ON
,08-17 10:24:07.524  4348  4377 D BtGatt.GattService: stopScan() - queue size =1
,08-17 10:24:07.528  4348  4384 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 10:24:07.529  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 10:24:07.530  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 10:24:07.530  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 10:24:07.530  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-17 10:24:07.531  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 10:24:07.534  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 10:24:07.535  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 10:24:07.535  3960  4012 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 10:24:07.536  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 10:24:07.538  4348  4348 D BtGatt.ScanManager: awakened up at time 240495
08-17 10:24:07.538  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 10:24:07.543  3960  3960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:24:07.544  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 10:24:07.544  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:24:07.544  3960  3960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:24:07.544  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 10:24:07.544  3960  3960 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 10:24:07.545  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 10:24:07.545  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e3a306 removed from the list
,08-17 10:24:07.545  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:24:07.545  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3c6dc7 removed from the list
08-17 10:24:07.546  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:24:07.547  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:24:07.547  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:24:07.547  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:24:07.548  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:24:07.548  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:24:07.549  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:24:07.549  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3c6dc7 not in the list
,08-17 10:24:07.549  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:24:07.549  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:24:07.550  4348  4364 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 10:24:07.551  4348  4364 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:24:07.551  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:24:07.551  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:24:07.551  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:24:07.551  4348  4367 D BtGatt.ScanManager: stopping BLe Batch
,08-17 10:24:07.551  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3c6dc7 not in the list
,08-17 10:24:07.551  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:24:07.551  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:24:07.551  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:24:07.551  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e3a306 not in the list
08-17 10:24:07.552  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 10:24:07.553  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b17b760 added. We now have 3 listener(s)
08-17 10:24:07.554  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 10:24:07.555  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:24:07.555  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:24:07.555  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 10:24:07.555  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7388419 added. We now have 4 listener(s)
08-17 10:24:07.555  3960  4012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:24:07.555  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 10:24:07.559  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:24:07.563  4348  4364 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 10:24:07.563  4348  4364 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:24:07.564  4348  4367 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:24:07.569  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:24:07.569  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:24:07.569  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:24:07.569  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:24:07.569  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:24:07.569  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:24:07.569  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:24:07.569  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:24:07.573  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:24:07.574  3960  4012 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 10:24:07.574  3960  4012 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-17 10:24:07.574  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:24:07.574  3960  4012 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:24:07.575  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 10:24:07.575  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:24:07.575  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:24:07.575  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 10:24:07.575  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b17b760 removed from the list
08-17 10:24:07.575  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:24:07.575  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7388419 removed from the list
,08-17 10:24:07.578  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:24:07.578  3960  4012 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:24:07.578  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:24:07.579  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-17 10:24:07.579  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:24:07.580  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:24:07.581  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:24:07.581  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:24:07.581  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7388419 not in the list
08-17 10:24:07.581  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:24:07.581  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:24:07.581  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:24:07.583  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:24:07.583  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 10:24:07.583  4348  4364 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-17 10:24:07.583  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:24:07.583  4348  4364 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:24:07.583  3960  4012 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7388419 not in the list,
08-17 10:24:07.583  4348  4364 D BtGatt.GattService: current time is 240541084024
08-17 10:24:07.583  3960  4012 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 10:24:07.584  4348  4364 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-17 10:24:07.583  3960  4012 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:24:07.584  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:24:07.584  4348  4364 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-17 10:24:07.584  3960  4012 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b17b760 not in the list
08-17 10:24:07.585  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-17 10:24:07.585  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 10:24:07.586  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 10:24:07.586  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 10:24:07.586  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only,
08-17 10:24:07.586  3960  4012 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:24:08.046  3960  3960 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 10:24:09.604  3960  4442 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 487, name: My test thread name)
,08-17 10:24:11.602  3960  4012 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 487
08-17 10:24:11.602  3960  4012 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 487, name: My test thread name)
,08-17 10:24:11.608  3960  4443 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 488, name: My test thread name)
,08-17 10:24:11.609  3960  4443 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 488, thread name: My test thread name)
,08-17 10:24:11.609  3960  4443 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 488, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-17 10:24:11.613  3960  4012 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-17 10:24:11.622  3960  4444 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 492, name: My test thread name)
,08-17 10:24:11.623  3960  4444 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 492, thread name: My test thread name): Test exception.
,08-17 10:24:11.624  3960  4444 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 492, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-17 10:24:11.631  3960  4012 I jxcore-log: Total number of executed tests:  82
08-17 10:24:11.631  3960  4012 I jxcore-log: 
,08-17 10:24:11.632  3960  4012 I jxcore-log: Number of passed tests:  82
08-17 10:24:11.632  3960  4012 I jxcore-log: 
,08-17 10:24:11.633  3960  4012 I jxcore-log: Number of failed tests:  0
08-17 10:24:11.633  3960  4012 I jxcore-log: 
,08-17 10:24:11.633  3960  4012 I jxcore-log: Number of ignored tests:  0
08-17 10:24:11.633  3960  4012 I jxcore-log: 
08-17 10:24:11.635  3960  4012 I jxcore-log: Total duration:  101364
08-17 10:24:11.635  3960  4012 I jxcore-log: 
,08-17 10:24:11.641  3960  4012 I jxcore-log: Unit Test app is loaded
08-17 10:24:11.641  3960  4012 I jxcore-log: 
,08-17 10:24:11.655  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.655  3960  4012 I jxcore-log: 
,08-17 10:24:11.656  3960  4442 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 487, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143,
08-17 10:24:11.658  3960  3960 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-17 10:24:11.660  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.660  3960  4012 I jxcore-log: 
,08-17 10:24:11.661  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.661  3960  4012 I jxcore-log: 
08-17 10:24:11.662  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.662  3960  4012 I jxcore-log: 
,08-17 10:24:11.663  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-17 10:24:11.663  3960  4012 I jxcore-log: 
,08-17 10:24:11.665  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 10:24:11.665  3960  4012 I jxcore-log: 
,08-17 10:24:11.667  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.667  3960  4012 I jxcore-log: 
,08-17 10:24:11.669  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.669  3960  4012 I jxcore-log: 
08-17 10:24:11.670  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-17 10:24:11.670  3960  4012 I jxcore-log: 
08-17 10:24:11.671  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 10:24:11.671  3960  4012 I jxcore-log: 
08-17 10:24:11.671  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 10:24:11.671  3960  4012 I jxcore-log: 
08-17 10:24:11.672  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.672  3960  4012 I jxcore-log: 
08-17 10:24:11.675  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.675  3960  4012 I jxcore-log: 
,08-17 10:24:11.677  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.677  3960  4012 I jxcore-log: 
,08-17 10:24:11.680  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 10:24:11.680  3960  4012 I jxcore-log: 
,08-17 10:24:11.683  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 10:24:11.683  3960  4012 I jxcore-log: 
,08-17 10:24:11.686  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 10:24:11.686  3960  4012 I jxcore-log: 
,08-17 10:24:11.688  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:24:11.688  3960  4012 I jxcore-log: 
,08-17 10:24:11.690  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:24:11.690  3960  4012 I jxcore-log: 
,08-17 10:24:11.693  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:24:11.693  3960  4012 I jxcore-log: 
,08-17 10:24:11.696  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 10:24:11.696  3960  4012 I jxcore-log: 
,08-17 10:24:11.698  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 10:24:11.698  3960  4012 I jxcore-log: 
,08-17 10:24:11.700  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 10:24:11.700  3960  4012 I jxcore-log: 
,08-17 10:24:11.703  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.703  3960  4012 I jxcore-log: 
,08-17 10:24:11.704  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.704  3960  4012 I jxcore-log: 
,08-17 10:24:11.705  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.705  3960  4012 I jxcore-log: 
,08-17 10:24:11.706  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 10:24:11.706  3960  4012 I jxcore-log: 
,08-17 10:24:11.707  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 10:24:11.707  3960  4012 I jxcore-log: 
08-17 10:24:11.708  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 10:24:11.708  3960  4012 I jxcore-log: 
,08-17 10:24:11.710  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:24:11.710  3960  4012 I jxcore-log: 
,08-17 10:24:11.710  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:24:11.710  3960  4012 I jxcore-log: 
,08-17 10:24:11.711  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:24:11.711  3960  4012 I jxcore-log: 
,08-17 10:24:11.713  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 10:24:11.713  3960  4012 I jxcore-log: 
08-17 10:24:11.714  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 10:24:11.714  3960  4012 I jxcore-log: 
,08-17 10:24:11.715  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 10:24:11.715  3960  4012 I jxcore-log: 
,08-17 10:24:11.716  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:24:11.716  3960  4012 I jxcore-log: 
,08-17 10:24:11.717  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:24:11.717  3960  4012 I jxcore-log: 
,08-17 10:24:11.718  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 10:24:11.718  3960  4012 I jxcore-log: 
08-17 10:24:11.719  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 10:24:11.719  3960  4012 I jxcore-log: 
,08-17 10:24:11.721  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 10:24:11.721  3960  4012 I jxcore-log: 
,08-17 10:24:11.722  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 10:24:11.722  3960  4012 I jxcore-log: 
,08-17 10:24:11.723  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 10:24:11.723  3960  4012 I jxcore-log: 
,08-17 10:24:11.724  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 10:24:11.724  3960  4012 I jxcore-log: 
08-17 10:24:11.725  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.725  3960  4012 I jxcore-log: 
,08-17 10:24:11.726  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.726  3960  4012 I jxcore-log: 
,08-17 10:24:11.727  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.727  3960  4012 I jxcore-log: 
,08-17 10:24:11.728  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.728  3960  4012 I jxcore-log: 
08-17 10:24:11.729  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.729  3960  4012 I jxcore-log: 
,08-17 10:24:11.730  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 10:24:11.730  3960  4012 I jxcore-log: 
,08-17 10:24:11.731  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.731  3960  4012 I jxcore-log: 
08-17 10:24:11.733  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-17 10:24:11.733  3960  4012 I jxcore-log: 
,08-17 10:24:11.734  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.734  3960  4012 I jxcore-log: 
,08-17 10:24:11.735  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 10:24:11.735  3960  4012 I jxcore-log: 
,08-17 10:24:11.736  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-17 10:24:11.736  3960  4012 I jxcore-log: 
,08-17 10:24:11.737  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:24:11.737  3960  4012 I jxcore-log: 
08-17 10:24:11.738  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 10:24:11.738  3960  4012 I jxcore-log: 
,08-17 10:24:11.743  3960  4012 I jxcore-log: My device name is: motorola-Nexus 6
08-17 10:24:11.743  3960  4012 I jxcore-log: 
,08-17 10:24:14.058  3960  4012 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-17 10:24:14.058  3960  4012 I jxcore-log: 
,08-17 10:24:14.075  3960  4012 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-17 10:24:14.077  3960  4012 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-17 10:24:14.077  3960  4012 I jxcore-log: 
,08-17 10:24:17.632  3244  4446 V KeepSync: Connecting to GoogleApiClient
,08-17 10:24:17.633   873   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-17 10:24:17.705  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:24:17.710  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:24:17.764  1496  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-17 10:24:17.764  1496  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-17 10:24:17.764  1496  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:24:17.765  1496  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:24:17.798  1703  4447 V BaseAuthAsyncOperation: access token request failed
,08-17 10:24:17.800  3244  4446 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-17 10:24:17.865  1496  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-17 10:24:17.865  1496  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-17 10:24:17.865  1496  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 10:24:17.865  1496  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:24:17.884  3244  4446 E KeepSync: IOException
08-17 10:24:17.884  3244  4446 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-17 10:24:17.884  3244  4446 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-17 10:24:17.884  3244  4446 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-17 10:24:17.884  3244  4446 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-17 10:24:17.884  3244  4446 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-17 10:24:17.884  3244  4446 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-17 10:24:17.884  3244  4446 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-17 10:24:17.884  3244  4446 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-17 10:24:17.884  3244  4446 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-17 10:24:17.884  3244  4446 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-17 10:24:17.884  3244  4446 E KeepSync: 	,at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-17 10:24:17.884  3244  4446 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-17 10:24:17.884  3244  4446 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-17 10:24:17.884  3244  4446 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-17 10:24:17.884  3244  4446 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 10:24:17.884  3244  4446 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 10:24:17.884  3244  4446 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-17 10:24:17.884  3244  4446 E KeepSync: 	... 10 more
08-17 10:24:17.884  3244  4446 W KeepSync: Sync result 2
,08-17 10:24:17.896   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 250492, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 10:24:19.134   873  4404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=252090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-17 10:24:39.840   873  4404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=272797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-17 10:24:47.561   873  4404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=280517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-17 10:24:47.995  3767  4449 I BooksSync: Starting books sync for 61035162, extras: ade
,08-17 10:24:48.044  3767  4450 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-17 10:24:48.074  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:24:48.078  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:24:48.113  1496  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-17 10:24:48.113  1496  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-17 10:24:48.113  1496  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 10:24:48.113  1496  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:24:48.146  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:24:48.149  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:24:48.183  1496  3160 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 10:24:48.184  1496  3160 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-17 10:24:48.184  1496  3160 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 10:24:48.184  1496  3160 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:24:48.206  3767  4450 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-17 10:24:48.207  3767  4449 E BooksSync: Soft error
08-17 10:24:48.207  3767  4449 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 10:24:48.207  3767  4449 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-17 10:24:48.207  3767  4449 E BooksSync: Sync error
08-17 10:24:48.207  3767  4449 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 10:24:48.207  3767  4449 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-17 10:24:48.207  3767  4449 I BooksSync: Finished books sync
,08-17 10:24:48.221   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 280277, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 10:25:08.213   873  4404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=301170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-17 10:25:18.161   873  4404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=311117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-17 10:25:18.710  3244  4456 V KeepSync: Connecting to GoogleApiClient
,08-17 10:25:18.711   873  1957 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-17 10:25:18.767  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:25:18.790  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:25:18.861  1496  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-17 10:25:18.861  1496  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-17 10:25:18.861  1496  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:25:18.861  1496  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:25:18.875  1496  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-17 10:25:18.875  1496  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 10:25:18.875  1496  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:25:18.875  1496  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:25:18.921  1703  4459 V BaseAuthAsyncOperation: access token request failed
,08-17 10:25:18.926  3180  4458 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-17 10:25:18.926  3180  4458 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at jdm.a(PG:82)
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at jcs.o(PG:406)
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at jcn.a(PG:1379)
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at jcs.i(PG:143)
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at blb.a(PG:3937)
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at czp.a(PG:18188)
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at czp.a(PG:9081)
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at czq.run(PG:1686)
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 10:25:18.926  3180  4458 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at jdj.a(PG:4091)
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at jdj.a(PG:1125)
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at jdm.a(PG:77)
08-17 10:25:18.926  3180  4458 E HttpOperation: 	... 12 more
08-17 10:25:18.926  3180  4458 E HttpOperation: Caused by: faj: BadAuthentication
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at fal.a(PG:38)
08-17 10:25:18.926  3180  4458 E HttpOperation: 	at jdj.a(PG:4089)
08-17 10:25:18.926  3180  4458 E HttpOperation: 	... 14 more
,08-17 10:25:18.931  3244  4456 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-17 10:25:19.016  1496  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 10:25:19.016  1496  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 10:25:19.016  1496  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:25:19.016  1496  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:25:19.041  3180  4458 E HttpOperation: [getmobileexperiments] Unexpected exception
08-17 10:25:19.041  3180  4458 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at jdm.a(PG:82)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at jcs.o(PG:406)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at jcn.a(PG:1379)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at jcs.i(PG:143)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at hec.a(PG:42)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at hee.a(PG:102)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at czr.a(PG:65)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at kka.a(PG:108)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at czp.a(PG:19176)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at czp.a(PG:9081)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at czq.run(PG:1686)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 10:25:19.041  3180  4458 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at jdj.a(PG:4091)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at jdj.a(PG:1125)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at jdm.a(PG:77)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	... 15 more
08-17 10:25:19.041  3180  4458 E HttpOperation: Caused by: faj: BadAuthentication
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at fal.a(PG:38)
08-17 10:25:19.041  3180  4458 E HttpOperation: 	at jdj.a(PG:4089)
,08-17 10:25:19.041  3180  4458 E HttpOperation: 	... 17 more
08-17 10:25:19.041  3180  4458 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-17 10:25:19.041  3180  4458 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at jdm.a(PG:82)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at jcs.o(PG:406)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at jcn.a(PG:1379)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at jcs.i(PG:143)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at hec.a(PG:42)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at hee.a(PG:102)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at czr.a(PG:65)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at kka.a(PG:108)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at czp.a(PG:19176)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at czp.a(PG:9081)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at czq.run(PG:1686)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at jdj.a(PG:4091)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at jdj.a(PG:1125)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at jdm.a(PG:77)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	... 15 more
08-17 10:25:19.041  3180  4458 E ExperimentLoader: Caused by: faj: BadAuthentication
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at fal.a(PG:38)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	at jdj.a(PG:4089)
08-17 10:25:19.041  3180  4458 E ExperimentLoader: 	... 17 more
,08-17 10:25:19.101  1496  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-17 10:25:19.101  1496  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-17 10:25:19.101  1496  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:25:19.102  1496  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:25:19.121  3244  4456 E KeepSync: IOException,
08-17 10:25:19.121  3244  4456 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-17 10:25:19.121  3244  4456 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152),
08-17 10:25:19.121  3244  4456 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-17 10:25:19.121  3244  4456 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-17 10:25:19.121  3244  4456 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-17 10:25:19.121  3244  4456 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-17 10:25:19.121  3244  4456 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-17 10:25:19.121  3244  4456 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-17 10:25:19.121  3244  4456 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-17 10:25:19.121  3244  4456 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-17 10:25:19.121  3244  4456 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-17 10:25:19.121  3244  4456 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-17 10:25:19.121  3244  4456 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-17 10:25:19.121  3244  4456 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-17 10:25:19.121  3244  4456 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 10:25:19.121  3244  4456 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 10:25:19.121  3244  4456 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-17 10:25:19.121  3244  4456 E KeepSync: 	... 10 more
08-17 10:25:19.121  3244  4456 W KeepSync: Sync result 2
,08-17 10:25:19.135   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 283169, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 10:25:19.177  3767  4462 I BooksSync: Starting books sync for 61035162, extras: ade
,08-17 10:25:19.201   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 290084, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 10:25:19.209  3767  4463 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-17 10:25:19.230  1496  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 10:25:19.230  1496  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-17 10:25:19.230  1496  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:25:19.230  1496  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:25:19.261  1496  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 10:25:19.262  1496  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-17 10:25:19.262  1496  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:25:19.262  1496  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:25:19.273  3767  4463 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-17 10:25:19.274  3767  4462 E BooksSync: Soft error
08-17 10:25:19.274  3767  4462 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 10:25:19.274  3767  4462 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-17 10:25:19.274  3767  4462 E BooksSync: Sync error
08-17 10:25:19.274  3767  4462 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 10:25:19.274  3767  4462 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-17 10:25:19.274  3767  4462 I BooksSync: Finished books sync
,08-17 10:25:19.281   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 311475, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 10:25:38.827   873  4404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=331784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-17 10:25:46.413   873  4404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=339370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 10:25:51.272  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:25:51.274  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:25:51.299  1496  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 10:25:51.299  1496  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-17 10:25:51.299  1496  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 10:25:51.299  1496  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:25:51.318  3180  4475 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-17 10:25:51.318  3180  4475 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at jdm.a(PG:82)
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at jcs.o(PG:406)
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at jcn.a(PG:1379)
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at jcs.i(PG:143)
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at blb.a(PG:3937)
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at czp.a(PG:18188)
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at czp.a(PG:9081)
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at czq.run(PG:1686)
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 10:25:51.318  3180  4475 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at jdj.a(PG:4091)
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at jdj.a(PG:1125)
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at jdm.a(PG:77)
08-17 10:25:51.318  3180  4475 E HttpOperation: 	... 12 more
08-17 10:25:51.318  3180  4475 E HttpOperation: Caused by: faj: BadAuthentication
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at fal.a(PG:38)
08-17 10:25:51.318  3180  4475 E HttpOperation: 	at jdj.a(PG:4089)
08-17 10:25:51.318  3180  4475 E HttpOperation: 	... 14 more
,08-17 10:25:51.351  1496  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 10:25:51.351  1496  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 10:25:51.351  1496  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:25:51.352  1496  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:25:51.364  3180  4475 E HttpOperation: [getmobileexperiments] Unexpected exception
08-17 10:25:51.364  3180  4475 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at jdm.a(PG:82)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at jcs.o(PG:406)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at jcn.a(PG:1379)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at jcs.i(PG:143)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at hec.a(PG:42)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at hee.a(PG:102)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at czr.a(PG:65)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at kka.a(PG:108)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at czp.a(PG:19176)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at czp.a(PG:9081)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at czq.run(PG:1686)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 10:25:51.364  3180  4475 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at jdj.a(PG:4091)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at jdj.a(PG:1125)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at jdm.a(PG:77)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	... 15 more
08-17 10:25:51.364  3180  4475 E HttpOperation: Caused by: faj: BadAuthentication
08-17 10:25:51.364  3180  4475 E HttpOperation: ,	at fal.a(PG:38)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	at jdj.a(PG:4089)
08-17 10:25:51.364  3180  4475 E HttpOperation: 	... 17 more
08-17 10:25:51.364  3180  4475 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-17 10:25:51.364  3180  4475 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at jdm.a(PG:82)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at jcs.o(PG:406)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at jcn.a(PG:1379)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at jcs.i(PG:143)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at hec.a(PG:42)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at hee.a(PG:102)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at czr.a(PG:65)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at kka.a(PG:108)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at czp.a(PG:19176)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at czp.a(PG:9081)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at czq.run(PG:1686)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at jdj.a(PG:4091)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at jdj.a(PG:1125)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at jdm.a(PG:77)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	... 15 more
08-17 10:25:51.364  3180  4475 E ExperimentLoader: Caused by: faj: BadAuthentication
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at fal.a(PG:38)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	at jdj.a(PG:4089)
08-17 10:25:51.364  3180  4475 E ExperimentLoader: 	... 17 more
,08-17 10:25:51.511   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 343908, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 10:25:52.081  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:25:52.126  1496  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-17 10:25:52.127  1496  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-17 10:25:52.127  1496  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:25:52.127  1496  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:25:52.152  1496  1508 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-17 10:25:52.152  1496  1508 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-17 10:25:52.152  1496  1508 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-17 10:25:52.152  1496  1508 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-17 10:25:52.152  1496  1508 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-17 10:25:52.152  1496  1508 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-17 10:25:52.152  1496  1508 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-17 10:25:52.161  3700  3736 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-17 10:25:52.161  3700  3736 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-17 10:25:52.161  3700  3736 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-17 10:25:52.161  3700  3736 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-17 10:25:52.161  3700  3736 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-17 10:25:52.161  3700  3736 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-17 10:25:52.161  3700  3736 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-17 10:26:21.658  3767  4481 I BooksSync: Starting books sync for 61035162, extras: ade
,08-17 10:26:21.688  3767  4482 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-17 10:26:21.703  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:26:21.708  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:26:21.744  1496  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 10:26:21.744  1496  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-17 10:26:21.744  1496  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:26:21.744  1496  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:26:21.777  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:26:21.781  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:26:21.813  1496  3160 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 10:26:21.813  1496  3160 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-17 10:26:21.813  1496  3160 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:26:21.814  1496  3160 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:26:21.833  3767  4482 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-17 10:26:21.834  3767  4481 E BooksSync: Soft error
08-17 10:26:21.834  3767  4481 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 10:26:21.834  3767  4481 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-17 10:26:21.834  3767  4481 E BooksSync: Sync error
08-17 10:26:21.834  3767  4481 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 10:26:21.834  3767  4481 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-17 10:26:21.834  3767  4481 I BooksSync: Finished books sync
,08-17 10:26:21.849   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 372831, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 10:26:27.733   873  4404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=380690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-17 10:26:37.134   873  4404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=390090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 10:26:52.187  3244  4486 V KeepSync: Connecting to GoogleApiClient
,08-17 10:26:52.189   873  1957 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-17 10:26:52.236  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:26:52.240  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:26:52.274  1496  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-17 10:26:52.274  1496  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-17 10:26:52.274  1496  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 10:26:52.274  1496  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:26:52.300  1703  4487 V BaseAuthAsyncOperation: access token request failed
08-17 10:26:52.301  3244  4486 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-17 10:26:52.392  1496  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-17 10:26:52.392  1496  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-17 10:26:52.392  1496  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:26:52.393  1496  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:26:52.417  3244  4486 E KeepSync: IOException
08-17 10:26:52.417  3244  4486 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-17 10:26:52.417  3244  4486 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-17 10:26:52.417  3244  4486 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-17 10:26:52.417  3244  4486 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-17 10:26:52.417  3244  4486 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-17 10:26:52.417  3244  4486 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-17 10:26:52.417  3244  4486 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-17 10:26:52.417  3244  4486 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-17 10:26:52.417  3244  4486 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-17 10:26:52.417  3244  4486 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-17 10:26:52.417  3244  4486 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-17 10:26:52.417  3244  4486 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-17 10:26:52.417  3244  4486 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-17 10:26:52.417  3244  4486 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-17 10:26:52.417  3244  4486 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 10:26:52.417  3244  4486 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 10:26:52.417  3244  4486 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-17 10:26:52.417  3244  4486 E KeepSync: 	... 10 more
08-17 10:26:52.418  3244  4486 W KeepSync: Sync result 2
,08-17 10:26:52.433   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 376724, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 10:26:52.800   873  4404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=405757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-17 10:27:02.134   873  4404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=415090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 10:27:17.867   873  4404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=430823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-17 10:27:22.727  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:27:22.729  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:27:22.760  1496  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-17 10:27:22.760  1496  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-17 10:27:22.761  1496  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:27:22.761  1496  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:27:22.781  3180  4490 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-17 10:27:22.781  3180  4490 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at jdm.a(PG:82)
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at jcs.o(PG:406)
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at jcn.a(PG:1379)
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at jcs.i(PG:143)
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at blb.a(PG:3937)
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at czp.a(PG:18188)
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at czp.a(PG:9081)
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at czq.run(PG:1686)
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 10:27:22.781  3180  4490 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at jdj.a(PG:4091)
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at jdj.a(PG:1125)
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at jdm.a(PG:77)
08-17 10:27:22.781  3180  4490 E HttpOperation: 	... 12 more
08-17 10:27:22.781  3180  4490 E HttpOperation: Caused by: faj: BadAuthentication
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at fal.a(PG:38)
08-17 10:27:22.781  3180  4490 E HttpOperation: 	at jdj.a(PG:4089)
08-17 10:27:22.781  3180  4490 E HttpOperation: 	... 14 more
,08-17 10:27:22.828  1496  2275 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-17 10:27:22.828  1496  2275 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 10:27:22.829  1496  2275 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:27:22.829  1496  2275 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:27:22.846  3180  4490 E HttpOperation: [getmobileexperiments] Unexpected exception
08-17 10:27:22.846  3180  4490 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at jdm.a(PG:82)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at jcs.o(PG:406)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at jcn.a(PG:1379)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at jcs.i(PG:143)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at hec.a(PG:42)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at hee.a(PG:102)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at czr.a(PG:65)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at kka.a(PG:108)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at czp.a(PG:19176)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at czp.a(PG:9081)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at czq.run(PG:1686)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 10:27:22.846  3180  4490 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at jdj.a(PG:4091)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at jdj.a(PG:1125)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at jdm.a(PG:77)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	... 15 more
08-17 10:27:22.846  3180  4490 E HttpOperation: Caused by: faj: BadAuthentication
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at fal.a(PG:38)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	at jdj.a(PG:4089)
08-17 10:27:22.846  3180  4490 E HttpOperation: 	... 17 more
,08-17 10:27:22.846  3180  4490 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-17 10:27:22.846  3180  4490 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at jdm.a(PG:82)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at jcs.o(PG:406)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at jcn.a(PG:1379)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at jcs.i(PG:143)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at hec.a(PG:42)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at hee.a(PG:102)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at czr.a(PG:65)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at kka.a(PG:108)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at czp.a(PG:19176)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at czp.a(PG:9081)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at czq.run(PG:1686)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at jdj.a(PG:4091)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at jdj.a(PG:1125)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at jdm.a(PG:77)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	... 15 more
08-17 10:27:22.846  3180  4490 E ExperimentLoader: Caused by: faj: BadAuthentication
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at fal.a(PG:38)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	at jdj.a(PG:4089)
08-17 10:27:22.846  3180  4490 E ExperimentLoader: 	... 17 more
,08-17 10:27:22.986   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 407966, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,08-17 10:27:27.240   873  4404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=440197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 10:27:46.934   873  4404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=459891, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-17 10:27:49.098  3960  4012 I jxcore-log: TAP version 13
08-17 10:27:49.098  3960  4012 I jxcore-log: 
,08-17 10:27:49.103  3960  4012 I jxcore-log: # setup
08-17 10:27:49.103  3960  4012 I jxcore-log: 
,08-17 10:27:49.230  3960  4012 I jxcore-log: # 1. onPeerLost calls jxcore
08-17 10:27:49.230  3960  4012 I jxcore-log: 
,08-17 10:27:49.615  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 10:27:49.616  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3534ebf added. We now have 3 listener(s)
,08-17 10:27:49.618  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
08-17 10:27:49.618  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:27:49.618  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:27:49.618  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:27:49.618  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@330e98c added. We now have 4 listener(s)
08-17 10:27:49.618  3960  4012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:27:49.619  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 10:27:49.623  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:27:49.634  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-17 10:27:49.634  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:27:49.634  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:27:49.634  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:27:49.634  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:27:49.634  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:49.634  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:27:49.634  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:27:49.640  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:27:49.640  3960  4012 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:27:49.640  3960  4012 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
08-17 10:27:49.640  3960  4012 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,08-17 10:27:49.643  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:27:49.648  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:27:51.644  3960  4012 I jxcore-log: onPeerLost
08-17 10:27:51.644  3960  4012 I jxcore-log: 
,08-17 10:27:51.648  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:51.648  3960  4012 I jxcore-log: 
,08-17 10:27:51.665  3960  4012 I jxcore-log: # teardown
08-17 10:27:51.665  3960  4012 I jxcore-log: 
,08-17 10:27:51.676  3960  4012 I jxcore-log: ok 1 check if callback was fired by onPeerLost
08-17 10:27:51.676  3960  4012 I jxcore-log: 
,08-17 10:27:51.677  3960  4012 I jxcore-log: ok 2 check if peerAvailable is false
08-17 10:27:51.677  3960  4012 I jxcore-log: 
,08-17 10:27:52.638  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 10:27:52.638  3960  4012 I jxcore-log: 
,08-17 10:27:52.642  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 10:27:52.642  3960  4012 I jxcore-log: 
,08-17 10:27:52.650  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:27:52.650  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:27:52.650  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:27:52.650  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:27:52.650  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:27:52.650  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:52.650  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:27:52.650  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:27:52.653  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:27:52.655  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 10:27:52.655  3960  4012 I jxcore-log: 
,08-17 10:27:52.657  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 10:27:52.657  3960  4012 I jxcore-log: 
,08-17 10:27:52.660  3960  4012 I jxcore-log: # setup
08-17 10:27:52.660  3960  4012 I jxcore-log: 
,08-17 10:27:52.661  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:52.661  3960  4012 I jxcore-log: 
,08-17 10:27:52.869  3960  4012 I jxcore-log: # 2. onPeerDiscovered calls jxcore
08-17 10:27:52.869  3960  4012 I jxcore-log: 
,08-17 10:27:53.465  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 10:27:53.465  3960  4012 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20218ea added. We now have 4 listener(s)
,08-17 10:27:53.467  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 10:27:53.467  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:27:53.468  3960  4012 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:27:53.468  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:27:53.468  3960  4012 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7817db added. We now have 5 listener(s)
08-17 10:27:53.468  3960  4012 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:27:53.469  3960  4012 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 10:27:53.473  3960  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:27:53.482  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:27:53.482  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:27:53.482  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:27:53.482  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:27:53.482  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:27:53.482  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:53.482  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:27:53.482  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:27:53.486  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:27:53.487  3960  4012 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:27:53.488  3960  4012 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,08-17 10:27:53.491  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:27:53.494  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:27:54.040   873  4404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=466997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 10:27:55.491  3960  4012 I jxcore-log: onPeerDiscovered
08-17 10:27:55.491  3960  4012 I jxcore-log: 
,08-17 10:27:55.495  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:55.495  3960  4012 I jxcore-log: 
,08-17 10:27:55.509  3960  4012 I jxcore-log: # teardown
08-17 10:27:55.509  3960  4012 I jxcore-log: 
,08-17 10:27:55.516  3960  4012 I jxcore-log: ok 3 check if callback was fired by onPeerDiscovered
08-17 10:27:55.516  3960  4012 I jxcore-log: 
,08-17 10:27:55.517  3960  4012 I jxcore-log: ok 4 check if peerAvailable is true
08-17 10:27:55.517  3960  4012 I jxcore-log: 
,08-17 10:27:55.913  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 10:27:55.913  3960  4012 I jxcore-log: 
,08-17 10:27:55.918  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 10:27:55.918  3960  4012 I jxcore-log: 
,08-17 10:27:55.935  3960  4012 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:27:55.935  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:27:55.935  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:27:55.935  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:27:55.935  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:27:55.935  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:27:55.935  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:27:55.935  3960  4012 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:27:55.941  3960  4012 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:27:55.946  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 10:27:55.946  3960  4012 I jxcore-log: 
,08-17 10:27:55.952  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 10:27:55.952  3960  4012 I jxcore-log: 
,08-17 10:27:55.959  3960  4012 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 10:27:55.959  3960  4012 I jxcore-log: 
,08-17 10:27:56.056  3960  4012 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 10:27:56.056  3960  4012 I jxcore-log: 
,08-17 10:27:56.686  4493  4493 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-17 10:27:56.692  4493  4493 D AndroidRuntime: CheckJNI is OFF
,08-17 10:27:56.735  4493  4493 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-17 10:27:56.785  4493  4493 I Radio-JNI: register_android_hardware_Radio DONE
,08-17 10:27:56.809  4493  4493 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 10:27:56.819   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-17 10:27:56.819   873   886 I ActivityManager: Killing 3960:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-17 10:27:56.938   873   896 W PackageSettings: Skipping PackageSetting{c7514e9 com.example.hello/10273} due to missing metadata
,08-17 10:27:56.947   873  1681 D GraphicsStats: Buffer count: 2
08-17 10:27:56.947   873  1957 I WindowState: WIN DEATH: Window{a55b236 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 10:27:56.949   873  1303 D WifiService: Client connection lost with reason: 4
,08-17 10:27:56.989   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-17 10:27:56.989   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-17 10:27:56.990   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-17 10:27:56.990   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-17 10:27:56.990   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-17 10:27:56.990   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-17 10:27:56.990   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-17 10:27:56.990   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-17 10:27:56.990   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-17 10:27:56.990   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-17 10:27:56.990   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-17 10:27:56.990   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-17 10:27:56.990   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-17 10:27:56.990   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-17 10:27:56.990   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-17 10:27:56.990   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-17 10:27:56.990   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-17 10:27:56.990   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-17 10:27:56.990   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:27:56.990   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:27:56.990   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 10:27:56.990   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-17 10:27:56.991   873   886 I ActivityManager:   Force finishing activity ActivityRecord{5f2935f u0 com.test.thalitest/.MainActivity t2}
,08-17 10:27:56.991   873   896 I art     : Starting a blocking GC Explicit
,08-17 10:27:57.001   873  1971 W ActivityManager: Spurious death for ProcessRecord{9cb4399 0:com.test.thalitest/u0a0}, curProc for 3960: null
,08-17 10:27:57.046   873   896 I art     : Explicit concurrent mark sweep GC freed 22395(1501KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 910us total 53.570ms
,08-17 10:27:57.070   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-17 10:27:57.071  4493  4493 I art     : System.exit called, status: 0
,08-17 10:27:57.071  4493  4493 I AndroidRuntime: VM exiting with result code 0.
08-17 10:27:57.075   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-17 10:27:57.084   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-17 10:27:57.089   873  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-17 10:27:57.092  4348  4348 D BluetoothMapAppObserver: onReceive
08-17 10:27:57.092  4348  4348 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-17 10:27:57.095  1860  2223 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-17 10:27:57.096  3832  3832 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-17 10:27:57.100  1875  1875 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-17 10:27:57.115  1875  4505 I Keyboard.Facilitator.DecoderInitializer: run()
,08-17 10:27:57.121  1875  4505 I Decoder : createOrResetDecoder
,08-17 10:27:57.146   873  1966 I ActivityManager: Start proc 4507:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-17 10:27:57.152  1935  1935 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-17 10:27:57.166  1496  1496 I ConfigService: onCreate
,08-17 10:27:57.181   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-17 10:27:57.203  1951  2052 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-17 10:27:57.203   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-17 10:27:57.204   873   885 E PackageManager: Failed to write settings, restoring backup
08-17 10:27:57.204   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-17 10:27:57.204   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-17 10:27:57.204   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-17 10:27:57.204   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-17 10:27:57.204   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-17 10:27:57.204   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:27:57.204   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:27:57.204   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 10:27:57.208   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-17 10:27:57.208   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-17 10:27:57.208   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system),
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 10:27:57.208   873   886 E DropBoxManagerService: 	... 13 more
08-17 10:27:57.209  1875  4505 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-17 10:27:57.215   873  1459 I ActivityManager: Start proc 4520:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-17 10:27:57.216  1951  2052 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-17 10:27:57.216  1951  2052 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1951
08-17 10:27:57.216  1951  2052 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 10:27:57.216  1951  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 10:27:57.216  1951  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-17 10:27:57.216  1951  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 10:27:57.216  1951  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 10:27:57.216  1951  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-17 10:27:57.216  1951  2052 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-17 10:27:57.216  1951  2052 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-17 10:27:57.216  1951  2052 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 10:27:57.216  1951  2052 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 10:27:57.216  1951  2052 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:27:57.216  1951  2052 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 10:27:57.217   873   883 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3960 uid 10000
,08-17 10:27:57.219   873  1681 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 10:27:57.220   873  4526 E DropBoxManagerService: Can't write: system_app_crash
08-17 10:27:57.220   873  4526 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-17 10:27:57.220   873  4526 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 10:27:57.220   873  4526 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 10:27:57.220   873  4526 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 10:27:57.220   873  4526 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 10:27:57.220   873  4526 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 10:27:57.220   873  4526 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 10:27:57.220   873  4526 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 10:27:57.220   873  4526 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 10:27:57.220   873  4526 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 10:27:57.220   873  4526 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 10:27:57.220   873  4526 E DropBoxManagerService: 	... 5 more
,08-17 10:27:57.224  1951  2052 I Process : Sending signal. PID: 1951 SIG: 9
,08-17 10:27:57.226  1875  1875 I Keyboard.Facilitator: onFinishInput()
,08-17 10:27:57.250  4507  4507 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-17 10:27:57.264  1875  4505 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-17 10:27:57.266  1875  4505 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-17 10:27:57.266  1875  4505 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-17 10:27:57.267  1875  4505 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-17 10:27:57.267  1875  4505 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-17 10:27:57.268  1875  4505 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-17 10:27:57.268  1875  4505 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-17 10:27:57.268  1875  4505 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-17 10:27:57.269  1875  4505 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-17 10:27:57.269  1875  4505 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-17 10:27:57.269  1875  4505 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-17 10:27:57.269  1875  4505 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-17 10:27:57.269  1875  4505 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-17 10:27:57.314   873  1459 I WindowState: WIN DEATH: Window{52af036 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-17 10:27:57.314   873  2038 D GraphicsStats: Buffer count: 1
,08-17 10:27:57.324   873  1968 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1951) has died
08-17 10:27:57.325   873  1968 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-17 10:27:57.327   873  1968 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-17 10:27:57.345   873   886 I ActivityManager: Start proc 4539:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 10:27:57.368  4507  4507 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-17 10:27:57.383  4507  4552 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-17 10:27:57.388   873  2134 I ActivityManager: Start proc 4553:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-17 10:27:57.394  4539  4539 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:27:57.394  4539  4539 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 10:27:57.395  4539  4539 D AndroidRuntime: Shutting down VM
08-17 10:27:57.400  1703  4550 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-17 10:27:57.400  1703  4550 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-17 10:27:57.403  4539  4539 E AndroidRuntime: FATAL EXCEPTION: main
08-17 10:27:57.403  4539  4539 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4539
08-17 10:27:57.403  4539  4539 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.j,ava:482)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 10:27:57.403  4539  4539 E AndroidRuntime: 	... 10 more
08-17 10:27:57.407   873  1681 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-17 10:27:57.408  4539  4539 I Process : Sending signal. PID: 4539 SIG: 9
08-17 10:27:57.408   873  4565 E DropBoxManagerService: Can't write: system_app_crash
08-17 10:27:57.408   873  4565 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-17 10:27:57.408   873  4565 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 10:27:57.408   873  4565 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 10:27:57.408   873  4565 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 10:27:57.408   873  4565 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 10:27:57.408   873  4565 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 10:27:57.408   873  4565 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 10:27:57.408   873  4565 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 10:27:57.408   873  4565 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 10:27:57.408   873  4565 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 10:27:57.408   873  4565 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 10:27:57.408   873  4565 E DropBoxManagerService: 	... 5 more
08-17 10:27:57.414  1703  4550 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-17 10:27:57.415  1703  4550 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-17 10:27:57.426  4553  4553 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-17 10:27:57.430  4507  4536 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:27:57.430  4507  4536 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:27:57.431  4507  4536 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 10:27:57.445  1496  1496 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-17 10:27:57.447  1496  1496 D AndroidRuntime: Shutting down VM
,08-17 10:27:57.447  1496  1496 E AndroidRuntime: FATAL EXCEPTION: main
08-17 10:27:57.447  1496  1496 E AndroidRuntime: Process: com.google.process.gapps, PID: 1496
08-17 10:27:57.447  1496  1496 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-17 10:27:57.447  1496  1496 E AndroidRuntime: 	... 8 more
,08-17 10:27:57.450   873  4568 E DropBoxManagerService: Can't write: system_app_crash
08-17 10:27:57.450   873  4568 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-17 10:27:57.450   873  4568 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 10:27:57.450   873  4568 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 10:27:57.450   873  4568 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 10:27:57.450   873  4568 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 10:27:57.450   873  4568 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 10:27:57.450   873  4568 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 10:27:57.450   873  4568 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 10:27:57.450   873  4568 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 10:27:57.450   873  4568 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 10:27:57.450   873  4568 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 10:27:57.450   873  4568 E DropBoxManagerService: 	... 5 more
,08-17 10:27:57.451  1496  1496 I Process : Sending signal. PID: 1496 SIG: 9
,08-17 10:27:57.456   873  1971 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4539) has died
,08-17 10:27:57.458   873  1971 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-17 10:27:57.471   873   886 I ActivityManager: Start proc 4570:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 10:27:57.477   873  1966 I ActivityManager: Killing 3885:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-17 10:27:57.512  4507  4536 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-17 10:27:57.517   873  1303 D WifiService: Client connection lost with reason: 4
,08-17 10:27:57.523  4507  4552 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:27:57.523  4507  4552 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 10:27:57.523  4507  4552 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-17 10:27:57.523  4507  4552 E AndroidRuntime: Process: android.process.acore, PID: 4507
08-17 10:27:57.523  4507  4552 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:27:57.523  4507  4552 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 10:27:57.524  4507  4536 I Process : Sending signal. PID: 4507 SIG: 9
,08-17 10:27:57.536   873  2038 I ActivityManager: Process com.google.process.gapps (pid 1496) has died
,08-17 10:27:57.536   873  2038 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-17 10:27:57.536   873  2038 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-17 10:27:57.536   873  2038 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
,08-17 10:27:57.558  1703  1703 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-17 10:27:57.563   873  2038 I ActivityManager: Start proc 4582:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-17 10:27:57.566   873  1968 I ActivityManager: Process android.process.acore (pid 4507) has died
08-17 10:27:57.566   873  1968 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 20970ms
,08-17 10:27:57.577   873  4587 E DropBoxManagerService: Can't write: system_app_crash
08-17 10:27:57.577   873  4587 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-17 10:27:57.577   873  4587 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 10:27:57.577   873  4587 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 10:27:57.577   873  4587 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 10:27:57.577   873  4587 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 10:27:57.577   873  4587 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 10:27:57.577   873  4587 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 10:27:57.577   873  4587 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 10:27:57.577   873  4587 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 10:27:57.577   873  4587 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 10:27:57.577   873  4587 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 10:27:57.577   873  4587 E DropBoxManagerService: 	... 5 more

```
