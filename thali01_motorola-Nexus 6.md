#### Test 7989656923d4b17_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-25 16:35:36.625  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 16:35:36.645  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 16:35:36.650  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 16:35:36.735  1519  2883 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-25 16:35:36.736  1519  2883 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-25 16:35:36.736  1519  2883 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 16:35:36.736  1519  2883 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-25 16:35:36.781  3496  3496 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-25 16:35:36.784  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-25 16:35:36.786  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-25 16:35:37.345  3767  3767 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-25 16:35:37.349  3767  3767 D AndroidRuntime: CheckJNI is OFF
08-25 16:35:37.385  3767  3767 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-25 16:35:37.427  3767  3767 I Radio-JNI: register_android_hardware_Radio DONE
08-25 16:35:37.448  3767  3767 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 16:35:37.452   872  1979 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 16:35:37.488  2002  2016 W SearchService: Abort, client detached.
08-25 16:35:37.504  2002  2002 I HotwordDetector: Closing mic
08-25 16:35:37.504  2002  2335 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@55bc104
08-25 16:35:37.504  2002  2346 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-25 16:35:37.506  3767  3767 D AndroidRuntime: Shutting down VM
08-25 16:35:37.535   872  1692 I ActivityManager: Start proc 3777:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-25 16:35:37.563   375  2348 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-25 16:35:37.565   375  2348 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-25 16:35:37.572   375  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-25 16:35:37.574  2002  2345 I MicroRecognitionRnrImpl: Detection finished
08-25 16:35:37.574  2002  2344 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-25 16:35:37.632  3777  3777 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-25 16:35:37.664  3777  3777 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-25 16:35:37.671  3777  3777 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 78-81)
08-25 16:35:37.671  3777  3777 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 16:35:37.703  3777  3777 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ed00e41}
08-25 16:35:37.705  3777  3777 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 16:35:37.706  3777  3777 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 16:35:37.719  3777  3777 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-25 16:35:37.720  3777  3777 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 16:35:37.777  3777  3777 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-25 16:35:37.813  3777  3777 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 16:35:37.813  3777  3777 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 16:35:37.813  3777  3777 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 16:35:37.813  3777  3777 I Adreno  : Build Date                       : 10/20/15
08-25 16:35:37.813  3777  3777 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 16:35:37.813  3777  3777 I Adreno  : Local Branch                     : M14
08-25 16:35:37.813  3777  3777 I Adreno  : Remote Branch                    : 
08-25 16:35:37.813  3777  3777 I Adreno  : Remote Branch                    : 
08-25 16:35:37.813  3777  3777 I Adreno  : Reconstruct Branch               : 
,08-25 16:35:37.905   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7d66e03:true
,08-25 16:35:37.978  3777  3777 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-25 16:35:37.996  3777  3777 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-25 16:35:38.093  3777  3817 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-25 16:35:38.109  3777  3802 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-25 16:35:38.142  3777  3817 I OpenGLRenderer: Initialized EGL, version 1.4
,08-25 16:35:38.223   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +713ms
,08-25 16:35:38.232  1854  1854 I Keyboard.Facilitator: onFinishInput()
,08-25 16:35:38.284  3777  3777 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3777
,08-25 16:35:38.358   872   882 I ActivityManager: Killing 2966:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-25 16:35:38.418   872   882 I ActivityManager: Killing 3183:com.google.android.gm/u0a78 (adj 15): empty #18
,08-25 16:35:38.418  3777  3777 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 16:35:38.609  3777  3819 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1703675600
,08-25 16:35:38.615  3777  3819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 16:35:38.615  3777  3819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 16:35:38.615  3777  3819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 16:35:38.615  3777  3819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 16:35:38.615  3777  3819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-25 16:35:38.615  3777  3819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6cc662c added. We now have 1 listener(s)
,08-25 16:35:38.618  3777  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-25 16:35:38.620  3777  3819 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 16:35:38.621  3777  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:35:38.621  3777  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 16:35:38.626  3777  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 16:35:38.626  3777  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 16:35:38.626  3777  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 16:35:38.626  3777  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-25 16:35:38.626  3777  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 16:35:38.626  3777  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 16:35:38.626  3777  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 16:35:38.626  3777  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 16:35:38.626  3777  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 16:35:38.626  3777  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 16:35:38.626  3777  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 16:35:38.626  3777  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 16:35:38.626  3777  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 16:35:38.626  3777  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-25 16:35:38.626  3777  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40cb4fb added. We now have 1 listener(s)
,08-25 16:35:38.628  3777  3819 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 16:35:38.631   872  1304 D WifiService: New client listening to asynchronous messages
,08-25 16:35:38.632  3777  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 16:35:38.632  3777  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-25 16:35:38.633  3777  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-25 16:35:38.633  3777  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 16:35:38.633  3777  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-25 16:35:38.639  3777  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 16:35:38.640  3777  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-25 16:35:38.652  3777  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-25 16:35:38.652  3777  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:35:38.652  3777  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:38.652  3777  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:38.652  3777  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:35:38.652  3777  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:35:38.652  3777  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:35:38.652  3777  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:35:38.652  3777  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:35:38.652  3777  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 16:35:38.652  3777  3819 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 16:35:38.653  3777  3819 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 16:35:38.655  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:35:38.657  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:35:38.691  3777  3777 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 16:35:39.462  3777  3827 W jxcore-log: Initializing JXcore engine
,08-25 16:35:39.462  3777  3827 W jxcore-log: JXcore engine is ready
,08-25 16:35:39.499  3827  3827 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8940 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-25 16:35:39.499  3827  3827 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10665]" dev="sockfs" ino=10665 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-25 16:35:39.499  3827  3827 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-25 16:35:39.499  3827  3827 W Thread-329: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[24974]" dev="sockfs" ino=24974 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-25 16:35:39.515  3777  3827 W jxcore-log: Starting JXcore engine
,08-25 16:35:39.594  3777  3827 W jxcore-log: Platform android
08-25 16:35:39.594  3777  3827 W jxcore-log: 
,08-25 16:35:39.594  3777  3827 W jxcore-log: Process ARCH arm
08-25 16:35:39.594  3777  3827 W jxcore-log: 
,08-25 16:35:39.834  3777  3827 I jxcore-log: JXcore Cordova bridge is ready!
08-25 16:35:39.834  3777  3827 I jxcore-log: 
,08-25 16:35:39.835  3777  3827 W jxcore-log: JXcore engine is started
,08-25 16:35:39.840  3777  3819 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-25 16:35:39.844  3777  3777 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 16:35:40.493   872  1303 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-25 16:35:44.390  3025  3834 V KeepSync: Connecting to GoogleApiClient
,08-25 16:35:44.391   872  1972 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-25 16:35:44.443  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 16:35:44.445  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 16:35:44.474  1519  2883 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-25 16:35:44.474  1519  2883 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-25 16:35:44.474  1519  2883 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 16:35:44.475  1519  2883 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 16:35:44.505  1726  3835 V BaseAuthAsyncOperation: access token request failed
,08-25 16:35:44.507  3025  3834 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-25 16:35:44.589  1519  3140 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-25 16:35:44.589  1519  3140 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-25 16:35:44.589  1519  3140 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 16:35:44.589  1519  3140 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 16:35:44.609  3025  3834 E KeepSync: IOException
08-25 16:35:44.609  3025  3834 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-25 16:35:44.609  3025  3834 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-25 16:35:44.609  3025  3834 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-25 16:35:44.609  3025  3834 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-25 16:35:44.609  3025  3834 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-25 16:35:44.609  3025  3834 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-25 16:35:44.609  3025  3834 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-25 16:35:44.609  3025  3834 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-25 16:35:44.609  3025  3834 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-25 16:35:44.609  3025  3834 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-25 16:35:44.609  3025  3834 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-25 16:35:44.609  3025  3834 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-25 16:35:44.609  3025  3834 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-25 16:35:44.609  3025  3834 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-25 16:35:44.609  3025  3834 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 16:35:44.609  3025  3834 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 16:35:44.609  3025  3834 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-25 16:35:44.609  3025  3834 E KeepSync: 	... 10 more
,08-25 16:35:44.609  3025  3834 W KeepSync: Sync result 2
,08-25 16:35:44.616   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 126109, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-25 16:35:46.840   872  1872 D NetlinkSocketObserver: NeighborEvent{elapsedMs=129250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-25 16:35:49.779  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 16:35:49.779  3777  3827 I jxcore-log: 
,08-25 16:35:49.782  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 16:35:49.782  3777  3827 I jxcore-log: 
,08-25 16:35:49.795  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:35:49.795  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:49.795  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:49.795  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:35:49.795  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:35:49.795  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:35:49.795  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:35:49.795  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 16:35:49.801  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 16:35:49.804  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 16:35:49.804  3777  3827 I jxcore-log: 
,08-25 16:35:49.806  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 16:35:49.806  3777  3827 I jxcore-log: 
,08-25 16:35:50.297  3777  3827 D executeNativeTests: Running unit tests
,08-25 16:35:50.370  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 16:35:50.370  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da added. We now have 2 listener(s)
,08-25 16:35:50.371  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 16:35:50.371  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 16:35:50.371  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:35:50.371  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:35:50.371  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b added. We now have 2 listener(s)
,08-25 16:35:50.371  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:35:50.372  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 16:35:50.383  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 16:35:50.395  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:35:50.395  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:50.395  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:50.395  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:35:50.395  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:35:50.395  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:35:50.395  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:35:50.395  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 16:35:50.401  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 16:35:50.401  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 16:35:50.405  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 16:35:50.408  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:35:50.410  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 16:35:50.410  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 16:35:50.413  3777  3827 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-25 16:35:50.415  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:35:50.415  3777  3827 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-25 16:35:50.415  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 16:35:50.416  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 16:35:50.416  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 16:35:50.416  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:35:50.417  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:35:50.417  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:35:50.417  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.417  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 16:35:50.417  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:35:50.417  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:35:50.417  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da removed from the list
,08-25 16:35:50.417  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.417  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b removed from the list
08-25 16:35:50.418  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 16:35:50.418  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 16:35:50.418  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 16:35:50.418  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 16:35:50.419  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 16:35:50.419  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:35:50.419  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.419  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.421  3777  3827 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-25 16:35:50.421  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:35:50.421  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 16:35:50.421  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:35:50.422  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.422  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.422  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 16:35:50.422  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.422  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.422  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.422  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:35:50.422  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.422  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.422  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 16:35:50.422  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.424  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:35:50.424  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:35:50.424  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.424  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.429  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 16:35:50.429  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 16:35:50.429  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-25 16:35:50.429  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 16:35:50.429  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 16:35:50.429  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 16:35:50.429  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 16:35:50.429  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 16:35:50.429  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-25 16:35:50.429  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 16:35:50.429  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 16:35:50.429  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 16:35:50.429  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 16:35:50.429  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 16:35:50.429  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 16:35:50.430  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 16:35:50.430  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-25 16:35:50.430  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 16:35:50.430  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 16:35:50.430  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 16:35:50.430  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 16:35:50.430  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 16:35:50.430  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 16:35:50.430  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 16:35:50.430  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-25 16:35:50.430  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 16:35:50.431  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 16:35:50.431  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 16:35:50.431  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 16:35:50.431  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 16:35:50.431  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 16:35:50.431  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:35:50.431  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 16:35:50.431  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:35:50.431  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.431  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.431  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.431  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.431  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.431  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
,08-25 16:35:50.431  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:35:50.431  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.432  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.432  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 16:35:50.432  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.433  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:35:50.433  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:35:50.433  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 16:35:50.433  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.434  3777  3827 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 16:35:50.436  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:35:50.441  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:35:50.441  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:50.441  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:50.441  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:35:50.441  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:35:50.441  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:35:50.441  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:35:50.441  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:35:50.443  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 16:35:50.444  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 16:35:50.444  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 16:35:50.444  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 16:35:50.444  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 16:35:50.444  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:35:50.444  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 16:35:50.450  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:35:50.453  3777  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 16:35:50.453  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 16:35:50.458  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:35:50.459  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 16:35:50.460  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 16:35:50.460  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 16:35:50.462  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-25 16:35:50.467  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-25 16:35:50.467  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 16:35:50.468  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 16:35:50.470  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
,08-25 16:35:50.472  3777  3827 D BluetoothAdapter: STATE_ON
,08-25 16:35:50.482  2649  2659 D BtGatt.GattService: registerClient() - UUID=e2f83ef9-fdff-400a-9c7e-67354df7e208
,08-25 16:35:50.484  2649  2668 D BtGatt.GattService: onClientRegistered() - UUID=e2f83ef9-fdff-400a-9c7e-67354df7e208, clientIf=5
,08-25 16:35:50.485  3777  3789 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 16:35:50.486  2649  2780 D BtGatt.GattService: start scan with filters
,08-25 16:35:50.490  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 16:35:50.491  2649  2671 D BtGatt.ScanManager: handling starting scan
,08-25 16:35:50.491  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 16:35:50.491  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 16:35:50.491  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 16:35:50.494  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 16:35:50.494  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 16:35:50.494  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 16:35:50.495  2649  2671 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
08-25 16:35:50.495  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 16:35:50.500  3777  3827 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 16:35:50.504  2649  2668 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 16:35:50.505  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:35:50.505  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:35:50.505  3777  3827 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 16:35:50.505  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 16:35:50.505  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 16:35:50.505  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.505  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 16:35:50.505  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 16:35:50.505  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 16:35:50.505  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 16:35:50.505  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 16:35:50.506  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 16:35:50.506  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 16:35:50.506  2649  2671 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 16:35:50.509  3777  3827 D BluetoothAdapter: STATE_ON
,08-25 16:35:50.510  2649  2755 D BtGatt.GattService: stopScan() - queue size =1
,08-25 16:35:50.512  2649  2780 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 16:35:50.513  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 16:35:50.513  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 16:35:50.513  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 16:35:50.513  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 16:35:50.514  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 16:35:50.514  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 16:35:50.515  2649  2668 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 16:35:50.515  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:35:50.515  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 16:35:50.515  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 16:35:50.515  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 16:35:50.515  2649  2671 D BtGatt.ScanManager: Starting BLE batch scan
08-25 16:35:50.515  2649  2671 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 16:35:50.516  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:35:50.517  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 16:35:50.517  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 16:35:50.517  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 16:35:50.518  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 16:35:50.518  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.518  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:35:50.518  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.518  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.518  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.518  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:35:50.518  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.518  3777  3827 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 16:35:50.520  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 16:35:50.527  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:35:50.527  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:50.527  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:50.527  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:35:50.527  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:35:50.527  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:35:50.527  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:35:50.527  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 16:35:50.529  2649  2668 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 16:35:50.529  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:35:50.531  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 16:35:50.531  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 16:35:50.531  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 16:35:50.531  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 16:35:50.531  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 16:35:50.531  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:35:50.531  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 16:35:50.534  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:35:50.537  3777  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 16:35:50.537  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 16:35:50.537  2649  2668 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 16:35:50.537  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:35:50.538  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:35:50.546  2649  2668 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 16:35:50.546  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:35:50.546  2649  2671 D BtGatt.ScanManager: stopping BLe Batch
,08-25 16:35:50.547  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 16:35:50.550  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 16:35:50.550  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 16:35:50.554  2649  2668 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 16:35:50.554  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:35:50.555  2649  2671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 16:35:50.563  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 16:35:50.563  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 16:35:50.564  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 16:35:50.565  3777  3827 D BluetoothAdapter: STATE_ON
,08-25 16:35:50.566  2649  2668 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-25 16:35:50.568  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:35:50.574  2649  2780 D BtGatt.GattService: registerClient() - UUID=043d3166-65a3-41cc-8944-553babe9fe79
,08-25 16:35:50.575  2649  2668 D BtGatt.GattService: onClientRegistered() - UUID=043d3166-65a3-41cc-8944-553babe9fe79, clientIf=5
,08-25 16:35:50.576  3777  3788 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 16:35:50.576  2649  2755 D BtGatt.GattService: start scan with filters
,08-25 16:35:50.580  2649  2671 D BtGatt.ScanManager: handling starting scan
,08-25 16:35:50.580  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 16:35:50.580  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 16:35:50.581  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 16:35:50.581  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 16:35:50.586  2649  2668 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 16:35:50.586  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:35:50.587  2649  2671 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 16:35:50.590  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 16:35:50.591  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 16:35:50.591  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 16:35:50.592  2649  2668 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 16:35:50.592  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:35:50.593  2649  2671 D BtGatt.ScanManager: Starting BLE batch scan
08-25 16:35:50.593  2649  2671 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 16:35:50.596  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 16:35:50.599  3777  3827 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 16:35:50.602  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 16:35:50.602  3777  3827 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 16:35:50.603  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
,08-25 16:35:50.603  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 16:35:50.603  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 16:35:50.603  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 16:35:50.603  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 16:35:50.603  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-25 16:35:50.603  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 16:35:50.603  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
08-25 16:35:50.603  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,08-25 16:35:50.603  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 16:35:50.605  3777  3827 D BluetoothAdapter: STATE_ON,
,08-25 16:35:50.605  2649  2755 D BtGatt.GattService: stopScan() - queue size =1
,08-25 16:35:50.607  2649  2668 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 16:35:50.607  2649  2659 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 16:35:50.607  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:35:50.608  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 16:35:50.608  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 16:35:50.608  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 16:35:50.608  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 16:35:50.608  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 16:35:50.609  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 16:35:50.609  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 16:35:50.609  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 16:35:50.609  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 16:35:50.610  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:35:50.611  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 16:35:50.611  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 16:35:50.611  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 16:35:50.611  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 16:35:50.611  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.611  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:35:50.611  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.611  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.611  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.611  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 16:35:50.611  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.611  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.612  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.614  2649  2668 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 16:35:50.614  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:35:50.613  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:35:50.614  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:35:50.614  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.614  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.616  3777  3827 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 16:35:50.619  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 16:35:50.620  2649  2668 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 16:35:50.620  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:35:50.620  2649  2671 D BtGatt.ScanManager: stopping BLe Batch
08-25 16:35:50.628  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:35:50.628  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:50.628  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:50.628  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:35:50.628  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:35:50.628  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:35:50.628  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:35:50.628  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 16:35:50.633  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 16:35:50.633  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 16:35:50.634  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 16:35:50.635  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:35:50.635  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 16:35:50.635  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 16:35:50.636  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 16:35:50.636  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 16:35:50.637  2649  2668 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 16:35:50.637  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:35:50.637  2649  2671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 16:35:50.637  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:35:50.643  3777  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 16:35:50.643  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 16:35:50.648  2649  2668 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-25 16:35:50.648  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 16:35:50.648  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:35:50.648  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 16:35:50.648  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 16:35:50.651  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 16:35:50.652  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 16:35:50.652  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 16:35:50.653  3777  3827 D BluetoothAdapter: STATE_ON
,08-25 16:35:50.655  2649  2659 D BtGatt.GattService: registerClient() - UUID=ba75ebd6-1be8-4727-bade-0c91bd56f52e
,08-25 16:35:50.655  2649  2668 D BtGatt.GattService: onClientRegistered() - UUID=ba75ebd6-1be8-4727-bade-0c91bd56f52e, clientIf=5
08-25 16:35:50.656  3777  3788 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 16:35:50.657  2649  2780 D BtGatt.GattService: start scan with filters
,08-25 16:35:50.659  2649  2671 D BtGatt.ScanManager: handling starting scan
,08-25 16:35:50.660  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 16:35:50.660  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 16:35:50.660  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 16:35:50.660  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 16:35:50.663  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 16:35:50.664  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 16:35:50.665  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 16:35:50.665  2649  2668 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 16:35:50.666  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:35:50.666  2649  2671 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 16:35:50.673  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 16:35:50.676  2649  2668 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-25 16:35:50.676  3777  3827 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 16:35:50.676  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 16:35:50.676  3777  3827 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 16:35:50.676  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:35:50.676  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 16:35:50.676  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 16:35:50.676  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 16:35:50.676  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 16:35:50.676  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 16:35:50.676  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 16:35:50.676  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 16:35:50.676  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 16:35:50.676  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 16:35:50.690  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 16:35:50.676  2649  2671 D BtGatt.ScanManager: Starting BLE batch scan
,08-25 16:35:50.690  3777  3827 D BluetoothAdapter: STATE_ON
,08-25 16:35:50.690  2649  2780 D BtGatt.GattService: stopScan() - queue size =1,
,08-25 16:35:50.690  2649  2671 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 16:35:50.691  2649  2755 D BtGatt.GattService: unregisterClient() - clientIf=5,
,08-25 16:35:50.691  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 16:35:50.691  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 16:35:50.691  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 16:35:50.691  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 16:35:50.691  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 16:35:50.692  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 16:35:50.692  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 16:35:50.692  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 16:35:50.692  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 16:35:50.693  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 16:35:50.694  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 16:35:50.694  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 16:35:50.694  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 16:35:50.694  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 16:35:50.694  3777  3827 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 16:35:50.694  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:35:50.694  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:35:50.694  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.695  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.695  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:35:50.695  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
,08-25 16:35:50.695  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.695  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.695  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:35:50.695  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.696  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.696  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.696  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:35:50.696  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:35:50.696  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.696  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.697  3777  3827 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 16:35:50.697  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:35:50.697  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:35:50.697  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 16:35:50.697  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.698  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.698  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.698  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.698  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 16:35:50.698  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.698  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:35:50.698  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.698  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.698  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.698  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.699  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 16:35:50.699  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:35:50.699  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.699  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.699  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 16:35:50.700  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:35:50.700  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:35:50.700  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:35:50.700  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.700  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.700  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 16:35:50.700  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.700  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.700  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.700  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:35:50.700  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.700  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.700  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 16:35:50.700  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 16:35:50.701  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:35:50.701  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 16:35:50.701  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.701  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.702  3777  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 16:35:50.702  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:35:50.702  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 16:35:50.702  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:35:50.702  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.702  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.702  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.702  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.702  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.702  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.702  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 16:35:50.702  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.702  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.702  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.703  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.704  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:35:50.704  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:35:50.704  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.704  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.704  3777  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 16:35:50.704  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:35:50.704  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:35:50.704  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 16:35:50.705  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.705  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.705  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.705  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.705  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.705  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.705  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:35:50.705  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.705  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.705  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 16:35:50.705  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.706  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:35:50.706  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:35:50.706  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.706  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.707  2649  2668 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 16:35:50.707  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 16:35:50.707  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:35:50.707  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 16:35:50.707  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 16:35:50.708  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 16:35:50.708  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 16:35:50.708  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 16:35:50.708  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:35:50.708  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 16:35:50.708  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:35:50.708  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.708  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.708  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.709  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.709  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.709  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.709  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:35:50.709  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.709  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.709  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 16:35:50.709  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.711  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:35:50.712  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 16:35:50.712  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.712  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.712  3777  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 16:35:50.713  3777  3827 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-25 16:35:50.713  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 16:35:50.713  2649  2668 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 16:35:50.713  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:35:50.717  3777  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 16:35:50.717  3777  3827 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 16:35:50.717  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 16:35:50.717  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-25 16:35:50.717  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 16:35:50.717  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 16:35:50.717  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 16:35:50.717  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 16:35:50.718  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 16:35:50.718  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-25 16:35:50.718  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 16:35:50.718  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 16:35:50.718  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 16:35:50.718  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 16:35:50.718  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 16:35:50.718  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 16:35:50.718  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-25 16:35:50.719  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 16:35:50.719  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 16:35:50.719  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 16:35:50.719  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 16:35:50.719  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-25 16:35:50.719  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 16:35:50.719  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 16:35:50.719  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 16:35:50.719  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 16:35:50.720  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 16:35:50.720  2649  2668 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 16:35:50.720  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:35:50.720  2649  2671 D BtGatt.ScanManager: stopping BLe Batch
08-25 16:35:50.720  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 16:35:50.721  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-25 16:35:50.721  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-25 16:35:50.721  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 16:35:50.721  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 16:35:50.721  3777  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 16:35:50.722  3777  3827 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 16:35:50.723  3777  3827 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 16:35:50.723  3777  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 16:35:50.723  3777  3827 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 16:35:50.723  3777  3827 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-25 16:35:50.723  3777  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 16:35:50.723  3777  3827 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 16:35:50.723  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 16:35:50.725  2649  2668 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 16:35:50.726  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:35:50.727  2649  2671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 16:35:50.728  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 16:35:50.730  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 16:35:50.730  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 16:35:50.731  2649  2668 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 16:35:50.731  2649  2668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:35:50.731  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 16:35:50.732  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-25 16:35:50.732  3777  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
08-25 16:35:50.732  3777  3827 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 16:35:50.732  3777  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 16:35:50.732  3777  3827 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 16:35:50.733  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:35:50.733  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:35:50.733  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:35:50.733  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.733  3777  3840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 16:35:50.733  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.733  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.734  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 16:35:50.735  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.735  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.735  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.735  3777  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
08-25 16:35:50.735  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:35:50.735  3777  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 393)
08-25 16:35:50.736  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 16:35:50.736  3777  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 393)
08-25 16:35:50.736  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.736  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.736  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.737  3777  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
08-25 16:35:50.737  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:35:50.738  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:35:50.738  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.738  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
,08-25 16:35:50.738  3777  3827 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 16:35:50.739  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:35:50.739  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:35:50.739  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:35:50.739  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.739  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.739  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.739  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.739  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 16:35:50.739  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.739  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:35:50.739  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.740  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.740  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.740  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.744  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:35:50.744  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:35:50.744  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 16:35:50.744  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.745  3777  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 16:35:50.746  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 16:35:50.746  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:35:50.746  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:35:50.746  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.746  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.746  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.747  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.747  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 16:35:50.747  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.747  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:35:50.747  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.747  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.747  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.747  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.748  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:35:50.749  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:35:50.749  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.749  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
,08-25 16:35:50.750  3777  3827 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 16:35:50.750  3777  3827 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 16:35:50.750  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 16:35:50.750  3777  3827 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 16:35:50.751  3777  3827 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 16:35:50.751  3777  3827 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 16:35:50.751  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 16:35:50.751  3777  3827 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-25 16:35:50.751  3777  3827 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 16:35:50.751  3777  3827 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 16:35:50.751  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 16:35:50.751  3777  3827 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 16:35:50.752  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:35:50.752  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:35:50.752  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:35:50.752  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 16:35:50.752  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.752  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 16:35:50.752  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.752  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.753  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.753  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 16:35:50.753  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.753  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.753  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.753  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.754  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:35:50.754  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:35:50.754  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.754  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.755  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.755  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.755  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.755  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.755  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.755  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.755  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:35:50.755  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.756  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.756  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.756  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.756  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.756  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.756  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.756  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.756  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:35:50.756  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:35:50.756  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:35:50.756  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.756  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.,BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.757  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.757  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.757  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.757  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.757  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:35:50.757  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.757  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.757  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.757  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.758  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:35:50.758  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:35:50.758  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.758  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.759  3777  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 16:35:50.759  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:35:50.760  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 16:35:50.761  3777  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 16:35:50.761  3777  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 16:35:50.761  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 16:35:50.761  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 16:35:50.761  3777  3777 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 16:35:50.762  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.762  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 16:35:50.762  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 16:35:50.762  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 16:35:50.762  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.762  3777  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 16:35:50.762  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.762  3777  3777 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 16:35:50.762  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.762  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 16:35:50.762  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 16:35:50.762  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 16:35:50.762  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.762  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.762  3777  3842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 16:35:50.763  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 16:35:50.763  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.763  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 16:35:50.763  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 16:35:50.764  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 16:35:50.764  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:35:50.764  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:35:50.764  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:35:50.764  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.764  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.764  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.764  3777  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-25 16:35:50.764  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.764  3777  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 16:35:50.764  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.764  3777  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 16:35:50.765  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.765  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:35:50.765  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.765  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.765  3777  3777 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 16:35:50.765  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.765  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.766  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:35:50.766  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:35:50.766  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.767  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.768  3777  3827 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 16:35:50.768  3777  3827 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 16:35:50.768  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 16:35:50.768  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 16:35:50.768  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:35:50.768  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:35:50.768  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:35:50.768  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.768  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.769  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.769  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.769  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.769  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.769  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:35:50.769  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.769  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.769  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.769  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.771  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:35:50.771  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:35:50.771  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.771  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.775  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:35:50.775  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:35:50.775  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:35:50.775  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.775  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.775  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.775  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.775  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.775  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.775  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:35:50.775  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.776  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.776  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.776  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.777  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:35:50.777  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:35:50.777  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.777  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.778  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:35:50.778  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:35:50.778  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:35:50.778  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:35:50.778  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.778  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.778  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5996da not in the list
08-25 16:35:50.778  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.778  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.779  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:35:50.779  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.779  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.779  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:35:50.779  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:35:50.780  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:35:50.780  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:35:50.780  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:35:50.780  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b7d70b not in the list
08-25 16:35:50.781  3777  3827 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 16:35:50.781  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 16:35:50.781  3777  3827 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 16:35:50.781  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 16:35:50.782  3777  3827 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 16:35:50.782  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 16:35:50.784  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 16:35:50.784  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 16:35:50.785  3777  3827 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 16:35:50.785  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 16:35:50.785  3777  3827 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 16:35:50.785  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 16:35:50.785  3777  3827 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 16:35:50.785  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 16:35:50.786  3777  3827 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 16:35:50.786  3777  3827 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 16:35:50.786  3777  3827 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 16:35:50.786  3777  3827 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 16:35:50.787  3777  3827 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 16:35:50.787  3777  3827 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 16:35:50.788  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:35:50.788  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7115cf5 added. We now have 2 listener(s)
08-25 16:35:50.788  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:35:50.790  3777  3827 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 16:35:50.790   872  1945 D WifiService: setWifiEnabled: true pid=3777, uid=10000
08-25 16:35:50.790   872  1945 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 16:35:50.791  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:35:50.791  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7356a8a added. We now have 3 listener(s)
08-25 16:35:50.791  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 16:35:50.800  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:35:50.800  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8f098fb added. We now have 4 listener(s)
08-25 16:35:50.800  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:35:50.801  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:35:50.801  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a2fcd18 added. We now have 5 listener(s)
08-25 16:35:50.801  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:35:50.803   872  1983 D WifiService: setWifiEnabled: false pid=3777, uid=10000
08-25 16:35:50.803   872  1983 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 16:35:50.809  2649  2664 D BluetoothAdapterState: Current state: ON, message: 23
08-25 16:35:50.809  2649  2664 D BluetoothAdapterProperties: Setting state to 13
08-25 16:35:50.809  2649  2664 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 16:35:50.809  2649  2664 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 16:35:50.810  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:35:50.810  2649  2664 I BluetoothAdapterState: Entering PendingCommandState
08-25 16:35:50.811  2649  2668 D BluetoothAdapterProperties: Scan Mode:20
08-25 16:35:50.812  2649  2664 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-25 16:35:50.812  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:35:50.813  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:35:50.813  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:50.813  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:50.813  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:35:50.813  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:35:50.813  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:35:50.813  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:35:50.813  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:35:50.814  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:35:50.814  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 16:35:50.814  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 16:35:50.814  2649  2649 D HeadsetService: Received stop request...Stopping profile...
08-25 16:35:50.816  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:35:50.819  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:35:50.822  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-2,5 16:35:50.822  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:35:50.822  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:50.822  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:50.822  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:35:50.822  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:35:50.822  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:35:50.822  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:35:50.822  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:35:50.823  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:35:50.823  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 16:35:50.824  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 16:35:50.826   872  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 16:35:50.826  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:35:50.826   872  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-25 16:35:50.826   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 16:35:50.826   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 16:35:50.827   872   885 I ActivityManager: Start proc 3845:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-25 16:35:50.829  1926  1938 D BluetoothHeadset: Proxy object disconnected
08-25 16:35:50.830   872   872 D BluetoothHeadset: Proxy object disconnected
08-25 16:35:50.830   872   872 D BluetoothHeadset: Proxy object disconnected
08-25 16:35:50.830  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:35:50.830   872   872 D BluetoothHeadset: Proxy object disconnected
08-25 16:35:50.830  1362  2026 D BluetoothHeadset: Proxy object disconnected
,08-25 16:35:50.831  1362  1362 D HeadsetProfile: Bluetooth service disconnected
08-25 16:35:50.833  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:35:50.833  2649  2649 D A2dpService: Received stop request...Stopping profile...
08-25 16:35:50.834  2649  2760 D A2dpStateMachine: Exit Disconnected: -1
08-25 16:35:50.835   872  1874 D DhcpClient: Clearing IP address
,08-25 16:35:50.835   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-25 16:35:50.835   872   872 D BluetoothA2dp: Proxy object disconnected
,08-25 16:35:50.836  1362  1362 D BluetoothA2dp: Proxy object disconnected
,08-25 16:35:50.837  2649  2649 D BluetoothMapService: onReceive
,08-25 16:35:50.837  2649  2649 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:35:50.837  2649  2649 D BluetoothMapService: STATE_TURNING_OFF
08-25 16:35:50.837  2649  2649 V BluetoothAdapterState: isTurningOff()=true
08-25 16:35:50.837  2649  2649 V BluetoothAdapterState: isTurningOn()=false
08-25 16:35:50.837  2649  2649 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 16:35:50.837  2649  2649 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 16:35:50.837  2649  2649 D HidService: Received stop request...Stopping profile...
,08-25 16:35:50.837  2649  2649 D HidService: Stopping Bluetooth HidService
,08-25 16:35:50.838   371   870 D CommandListener: Setting iface cfg
,08-25 16:35:50.839  1362  1362 D BluetoothInputDevice: Proxy object disconnected
08-25 16:35:50.839  1362  1362 D HidProfile: Bluetooth service disconnected
08-25 16:35:50.840   872  1875 D DhcpClient: Receive thread stopped
08-25 16:35:50.841  1519  3452 V NativeCrypto: Read error: ssl=0x9b248600: I/O error during system call, Connection timed out
,08-25 16:35:50.842  1519  3452 V NativeCrypto: SSL shutdown failed: ssl=0x9b248600: I/O error during system call, Broken pipe
,08-25 16:35:50.843  2649  2649 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-25 16:35:50.843  2649  2649 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 16:35:50.843  2649  2668 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-25 16:35:50.843  2649  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 16:35:50.843  2649  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 16:35:50.843  2649  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 16:35:50.843  2649  2668 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-25 16:35:50.843  2649  2649 D HealthService: Received stop request...Stopping profile...
08-25 16:35:50.844   872  1303 D WifiStateMachine: Start Disconnecting Watchdog 1
08-25 16:35:50.844   872  1945 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-25 16:35:50.845   872  1867 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-25 16:35:50.845   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 16:35:50.847   404   404 E Parcel  : Reading a NULL string not supported here.
08-25 16:35:50.847   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 16:35:50.847   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-25 16:35:50.849   872  1867 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-25 16:35:50.852   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-25 16:35:50.854   872  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-25 16:35:50.854  2649  2649 D PanService: Received stop request...Stopping profile...
08-25 16:35:50.855  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 16:35:50.855  1362  1362 D PanProfile: Bluetooth service disconnected
,08-25 16:35:50.856   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 16:35:50.857  2649  2649 D BluetoothMapService: Received stop request...Stopping profile...
08-25 16:35:50.857  2649  2649 D BluetoothMapService: stop()
08-25 16:35:50.858  2649  2649 D BluetoothMapAppObserver: deinitObservers()
08-25 16:35:50.858  2649  2649 D BluetoothMapAppObserver: removeReceiver()
08-25 16:35:50.860  1362  1362 D BluetoothMap: Proxy object disconnected
08-25 16:35:50.860  1362  1362 D MapProfile: Bluetooth service disconnected
08-25 16:35:50.860  2649  2649 V BluetoothAdapterState: isTurningOff()=true
,08-25 16:35:50.860  2649  2649 V BluetoothAdapterState: isTurningOn()=false
08-25 16:35:50.860  2649  2649 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 16:35:50.860  2649  2649 V BluetoothAdapterState: isBleTurningOff()=false
08-25 16:35:50.860  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:35:50.860  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-25 16:35:50.860  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:50.860  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:50.860  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:35:50.860  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:35:50.860  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:35:50.860  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:35:50.860  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 16:35:50.861  2649  2668 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-25 16:35:50.861  2649  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 16:35:50.861  2649  2649 I BtOppRfcommListener: stopping Accept Thread
08-25 16:35:50.861  2649  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 16:35:50.861  2649  2737 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 16:35:50.861  2649  2737 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
08-25 16:35:50.861  2649  2737 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 16:35:50.861  2649  3397 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 16:35:50.861  2649  2737 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 16:35:50.861  2649  3397 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 16:35:50.862  2649  2649 V BluetoothAdapterState: isTurningOff()=true
,08-25 16:35:50.862  2649  2649 V BluetoothAdapterState: isTurningOn()=false
08-25 16:35:50.862  2649  2649 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:35:50.862  2649  2649 V BluetoothAdapterState: isBleTurningOff()=false
08-25 16:35:50.862  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:35:50.862  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
08-25 16:35:50.863  2649  2649 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 16:35:50.863  2649  2649 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 16:35:50.863  2649  2668 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 16:35:50.863  2649  2649 V BluetoothAdapterState: isTurningOff()=true
08-25 16:35:50.863  2649  2649 V BluetoothAdapterState: isTurningOn()=false
08-25 16:35:50.863  2649  2649 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:35:50.863  2649  2649 V BluetoothAdapterState: isBleTurningOff()=false
08-25 16:35:50.863  2649  2649 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 16:35:50.863  2649  2668 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-25 16:35:50.863  2649  2649 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 16:35:50.863  2649  2649 V BluetoothAdapterState: isTurningOff()=true
,08-25 16:35:50.864  2649  2649 V BluetoothAdapterState: isTurningOn()=false
08-25 16:35:50.864  2649  2649 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:35:50.864  2649  2649 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 16:35:50.864  2649  2649 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 16:35:50.864  2649  2649 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 16:35:50.864  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 16:35:50.864  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:35:50.864  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:50.864  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:50.864  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:35:50.864  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:35:50.864  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:35:50.864  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:35:50.864  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:35:50.865  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:35:50.865  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:35:50.865  2649  2649 D BluetoothMapService: MAP Service closeService in
,08-25 16:35:50.865   872  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 16:35:50.866  2649  2649 D BluetoothMapMasInstance0: MAP Service shutdown
08-25 16:35:50.866  2649  2649 D ObexServerSockets0: shutdown(block = true)
08-25 16:35:50.866  2649  2781 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4,
08-25 16:35:50.867  2649  2649 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 16:35:50.867  2649  2782 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-25 16:35:50.867  2649  2753 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-25 16:35:50.867  2649  2649 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 16:35:50.868  2649  2649 V BluetoothAdapterState: isTurningOff()=true
08-25 16:35:50.868  2649  2649 V BluetoothAdapterState: isTurningOn()=false,
08-25 16:35:50.868  2649  2649 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:35:50.868  2649  2649 V BluetoothAdapterState: isBleTurningOff()=false
08-25 16:35:50.868  2649  2664 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-25 16:35:50.868  2649  2664 D BluetoothAdapterProperties: Setting state to 15
08-25 16:35:50.868  2649  2664 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 16:35:50.869  2649  2649 D BluetoothMapService: cleanup()
08-25 16:35:50.869  2649  2649 D BluetoothMapService: MAP Service closeService in
08-25 16:35:50.869   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 16:35:50.870  1362  1377 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 16:35:50.871  2649  2664 I BluetoothAdapterState: Entering BleOnState
08-25 16:35:50.872   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 16:35:50.872  1362  1373 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 16:35:50.872  1362  2026 D BluetoothPan: onBluetoothStateChange on: false
08-25 16:35:50.873   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 16:35:50.873   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 16:35:50.873  1926  2206 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 16:35:50.873  1362  1377 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 16:35:50.874  1362  1373 D BluetoothMap: onBluetoothStateChange: up=false
08-25 16:35:50.874  1362  2026 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 16:35:50.875  2649  2664 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-25 16:35:50.875  2649  2664 D BluetoothAdapterProperties: Setting state to 16
,08-25 16:35:50.875  2649  2664 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-25 16:35:50.875  2649  2664 D BluetoothAdapterProperties: onBleDisable
08-25 16:35:50.875  2649  2664 I BluetoothAdapterState: Entering PendingCommandState
08-25 16:35:50.875  2649  2665 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-25 16:35:50.876  2649  2668 D BluetoothAdapterProperties: Scan Mode:20
,08-25 16:35:50.877  2649  2737 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-25 16:35:50.877  2649  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 16:35:50.879  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:35:50.879  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:35:50.879  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:50.879  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:50.879  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:35:50.879  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:35:50.879  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:35:50.879  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:35:50.879  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:35:50.880  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:35:50.884  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:35:50.885  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:35:50.892  2113  2303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 16:35:50.896  3845  3845 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-25 16:35:50.900   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 16:35:50.909  3845  3845 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 16:35:50.913  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 16:35:50.915   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ede9c07:true
,08-25 16:35:50.917   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 16:35:50.918   872  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-25 16:35:50.918   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:35:50.929   872  1374 I ActivityManager: Start proc 3863:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-25 16:35:50.931   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-25 16:35:50.936  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:35:50.938  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:35:50.938  3382  3382 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@e3118f5 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-25 16:35:50.961  3845  3845 D LocalBluetoothProfileManager: Adding local MAP profile
,08-25 16:35:50.963  3845  3845 D BluetoothMap: Create BluetoothMap proxy object
,08-25 16:35:50.967  3863  3863 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-25 16:35:50.971  3845  3845 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-25 16:35:50.978   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-25 16:35:50.979   872  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 16:35:50.985  3845  3845 D DockEventReceiver: finishStartingService: stopping service
,08-25 16:35:50.993   872   883 I ActivityManager: Killing 3382:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-25 16:35:51.079  2649  2668 I bt_hci  : shut_down
,08-25 16:35:51.079  2649  2672 D bt_hwcfg: hw_epilog_process
08-25 16:35:51.080  2649  2672 I bt_vendor: low_power_mode_cb
,08-25 16:35:51.111  2649  2672 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-25 16:35:51.111  2649  2672 I bt_vendor: epilog_cb
08-25 16:35:51.111  2649  2672 I bt_hci  : epilog_finished_callback
,08-25 16:35:51.117  2649  2668 I bt_hci_h4: hal_close
,08-25 16:35:51.117  2649  2668 I bt_userial_vendor: device fd = 51 close
,08-25 16:35:51.205  3863  3863 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 16:35:51.205  3863  3863 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 16:35:51.205  3863  3863 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 16:35:51.205  3863  3863 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 16:35:51.205  3863  3863 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.r.k.d(PG:583)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 16:35:51.205  3863  3863 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 16:35:51.205  3863  3863 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 16:35:51.205  3863  3863 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread$,H.handleMessage(ActivityThread.java:1405)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 16:35:51.205  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 16:35:51.248   872  1965 I ActivityManager: Start proc 3897:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-25 16:35:51.249   872  1965 I ActivityManager: Killing 2450:com.google.android.talk/u0a61 (adj 15): empty #17
,08-25 16:35:51.264  3777  3777 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 16:35:51.284  3863  3884 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-25 16:35:51.298   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b0a8dd0:true
,08-25 16:35:51.347  2649  2665 D bt_stack_manager: event_shut_down_stack finished.
,08-25 16:35:51.347  2649  2664 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 16:35:51.351  2649  2664 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-25 16:35:51.351  2649  2649 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 16:35:51.351  2649  2649 D BtGatt.GattService: Received stop request...Stopping profile...
,08-25 16:35:51.352  2649  2649 D BtGatt.GattService: stop()
08-25 16:35:51.352  2649  2649 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 16:35:51.353  2649  2649 V BluetoothAdapterState: isTurningOff()=false
,08-25 16:35:51.353  2649  2649 V BluetoothAdapterState: isTurningOn()=false
08-25 16:35:51.353  2649  2649 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 16:35:51.353  2649  2649 V BluetoothAdapterState: isBleTurningOff()=true
08-25 16:35:51.353  2649  2664 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-25 16:35:51.353  2649  2664 D BluetoothAdapterProperties: Setting state to 10
,08-25 16:35:51.353  2649  2664 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-25 16:35:51.354  2649  2664 I BluetoothAdapterState: Entering OffState
,08-25 16:35:51.354   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-25 16:35:51.366  2649  2649 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-25 16:35:51.367  2649  2649 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-25 16:35:51.367  2649  2649 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 16:35:51.368  2649  2665 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 16:35:51.372  2649  2665 D bt_stack_manager: event_clean_up_stack finished.
,08-25 16:35:51.380  3897  3897 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-25 16:35:51.381  2649  2649 I art     : System.exit called, status: 0
08-25 16:35:51.381  2649  2649 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 16:35:51.457   872  3093 I ActivityManager: Process com.android.bluetooth (pid 2649) has died
,08-25 16:35:51.472  3897  3897 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-25 16:35:51.497   872  1972 I ActivityManager: Start proc 3924:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-25 16:35:51.529  3924  3924 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-25 16:35:51.664  3924  3941 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-25 16:35:51.664  3924  3941 I Babel_SMS: MmsConfig.loadMmsSettings
,08-25 16:35:51.669  3924  3941 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-25 16:35:51.670  3924  3941 I Babel_SMS: MmsConfig.loadFromDatabase
,08-25 16:35:51.705  3924  3941 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-25 16:35:51.706  3924  3941 I Babel_SMS: MmsConfig.loadFromResources
08-25 16:35:51.707  3924  3941 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-25 16:35:51.708  3924  3941 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-25 16:35:51.743  3924  3924 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 16:35:51.746  3924  3924 I Babel_Crash: startup - clean
,08-25 16:35:51.771  3924  3924 I Babel_telephony: TeleModule.launchCompleted
,08-25 16:35:51.781   872  1982 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-25 16:35:51.791  3924  3924 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-25 16:35:51.799  3924  3924 W Babel   : BAM#gBA: invalid account id: -1
,08-25 16:35:51.799  3924  3924 W Babel   : BAM#gBA: invalid account id: -1
08-25 16:35:51.799  3924  3924 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-25 16:35:51.809  3924  3946 I Babel   : deleted: false for 0
,08-25 16:35:51.820   872  1984 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-25 16:35:51.833  3845  3845 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 16:35:51.885   872  1979 I ActivityManager: Start proc 3949:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-25 16:35:51.887  3845  3845 D DockEventReceiver: finishStartingService: stopping service
,08-25 16:35:51.889  3924  3924 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 16:35:51.963  3924  3924 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-25 16:35:51.970  3924  3924 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 16:35:51.981  3924  3924 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 16:35:51.990  3924  3924 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 16:35:51.995  3924  3924 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 16:35:52.010   872  1982 I ActivityManager: Killing 3550:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-25 16:35:52.059  3949  3949 D AdapterServiceConfig: Adding HeadsetService
08-25 16:35:52.059  3949  3949 D AdapterServiceConfig: Adding A2dpService
08-25 16:35:52.059  3949  3949 D AdapterServiceConfig: Adding HidService
08-25 16:35:52.059  3949  3949 D AdapterServiceConfig: Adding HealthService
08-25 16:35:52.059  3949  3949 D AdapterServiceConfig: Adding PanService
08-25 16:35:52.059  3949  3949 D AdapterServiceConfig: Adding GattService
,08-25 16:35:52.061  3924  3924 I vclib   : onServiceConnected
,08-25 16:35:52.063  3949  3949 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 16:35:52.066   872  1979 I ActivityManager: Killing 3435:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-25 16:35:52.136  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 16:35:52.156  1726  1726 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 16:35:52.165  1726  1726 D SystemUpdateService: onCreate
,08-25 16:35:52.173  1726  1726 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 16:35:52.179  1726  3964 I SystemUpdateService: active receiver: enabled
,08-25 16:35:52.195  1726  3964 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 16:35:52.196  1726  3964 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-25 16:35:52.197  1726  3964 I SystemUpdateService: now status is 0 (complete)
08-25 16:35:52.197  1726  3964 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-25 16:35:52.197  1726  3964 I SystemUpdateService: file has been verified
08-25 16:35:52.198  1726  3964 I SystemUpdateService: OTA package size = 12249756
,08-25 16:35:52.199  1726  1726 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-25 16:35:52.201  1726  2411 I iu.UploadsManager: num queued entries: 0
,08-25 16:35:52.202  1726  2411 I iu.UploadsManager: num updated entries: 0
,08-25 16:35:52.204  1726  2411 I iu.SyncManager: NEXT; no task
,08-25 16:35:52.205  1726  3964 I SystemUpdateService: showing system update notification
,08-25 16:35:52.217  1726  1726 D SystemUpdateService: onDestroy
,08-25 16:35:52.227  1726  1726 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 16:35:52.228  1726  1726 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 16:35:52.260   872  1983 I ActivityManager: Start proc 3966:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver,
,08-25 16:35:52.295  3966  3966 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-25 16:35:52.297  3966  3966 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:35:52.302  3966  3966 D SprintDMHelper: simOperator: 
,08-25 16:35:52.302  3966  3966 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 16:35:52.330   872   883 I ActivityManager: Start proc 3978:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-25 16:35:52.335   872   883 I ActivityManager: Killing 3478:android.process.acore/u0a5 (adj 15): empty #17
,08-25 16:35:52.509   872  1374 I ActivityManager: Start proc 3993:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-25 16:35:52.511  3924  3992 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
08-25 16:35:52.525   872  1374 I ActivityManager: Killing 3628:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-25 16:35:52.619  3993  3993 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-25 16:35:52.699  3993  3993 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-25 16:35:52.699  3993  3993 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-25 16:35:52.699  3993  3993 I GAv4    :   adb logcat -s GAv4
,08-25 16:35:52.717  3993  3993 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-25 16:35:52.726  3993  3993 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-25 16:35:52.748  3993  4010 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-25 16:35:52.863  3993  3993 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-25 16:35:52.897  3993  3993 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-25 16:35:52.905  3993  3993 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5312-5315)
,08-25 16:35:52.906  3993  3993 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 16:35:52.919  3993  3993 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {83b2965}
,08-25 16:35:52.919  3993  3993 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 16:35:52.920  3993  3993 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 16:35:52.930  3993  3993 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-25 16:35:52.932  3993  3993 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 16:35:52.950  3993  3993 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-25 16:35:52.966  3993  3993 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 16:35:52.966  3993  3993 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 16:35:52.966  3993  3993 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 16:35:52.966  3993  3993 I Adreno  : Build Date                       : 10/20/15
08-25 16:35:52.966  3993  3993 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 16:35:52.966  3993  3993 I Adreno  : Local Branch                     : M14
08-25 16:35:52.966  3993  3993 I Adreno  : Remote Branch                    : 
08-25 16:35:52.966  3993  3993 I Adreno  : Remote Branch                    : 
08-25 16:35:52.966  3993  3993 I Adreno  : Reconstruct Branch               : 
,08-25 16:35:53.028  3993  3993 I NSApplication: Starting up...
,08-25 16:35:53.041  3993  4039 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-25 16:35:53.072   872  3093 I ActivityManager: Start proc 4044:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-25 16:35:53.073   872  3093 I ActivityManager: Killing 3644:com.android.musicfx/u0a18 (adj 15): empty #17
,08-25 16:35:53.138  4044  4044 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-25 16:35:53.324   872   882 I ActivityManager: Killing 2229:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-25 16:35:53.816   872  1988 D WifiService: setWifiEnabled: true pid=3777, uid=10000
,08-25 16:35:53.817   872  1988 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 16:35:53.829   872  1303 D WifiConfigStore: Loading config and enabling all networks 
,08-25 16:35:53.839  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:35:53.839  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:35:53.839  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:53.839  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:53.839  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:35:53.839  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:35:53.839  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:35:53.839  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:35:53.839  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:35:53.839  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:35:53.839  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:35:53.842  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:35:53.842  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:35:53.842  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:53.842  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:53.842  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:35:53.842  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:35:53.842  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:35:53.842  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:35:53.842  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:35:53.842  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:35:53.843  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 16:35:53.852   872  1303 D WifiConfigStore: loaded 0 passpoint configs
,08-25 16:35:53.853   872  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-25 16:35:53.854   872  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-25 16:35:53.855   872  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-25 16:35:53.856   872  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-25 16:35:53.856   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-25 16:35:53.856   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 16:35:53.871   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-25 16:35:53.872   872  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.50 rxSuccessRate=12.75 delta 1000 -> 994
,08-25 16:35:53.873   371   870 D CommandListener: Setting iface cfg
08-25 16:35:53.875   872  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-25 16:35:53.875   872  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 16:35:53.881   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-25 16:35:53.881   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 16:35:53.887   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 16:35:53.932   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 16:35:53.934  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 16:35:53.955   872  1302 D WifiNative-HAL: p2pGetDeviceAddress
,08-25 16:35:53.956   872  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 16:35:54.358  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 16:35:54.402  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 16:35:54.403  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 16:35:54.410   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 16:35:54.425   872  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-25 16:35:54.426   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 16:35:54.426   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 16:35:54.460   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 16:35:54.473   371   870 D CommandListener: Setting iface cfg
,08-25 16:35:54.474   872  1303 D WifiStateMachine: Start Dhcp Watchdog 2
,08-25 16:35:54.490   872  1305 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-25 16:35:54.493   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 16:35:54.538   872  4067 D DhcpClient: Receive thread started
,08-25 16:35:54.625   872  1303 E native  : do suspend false
,08-25 16:35:54.645   872  1874 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 16:35:54.658   872  4067 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172686, domain null
,08-25 16:35:54.659   872  1874 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172686 seconds
,08-25 16:35:54.663   872  1874 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 16:35:54.677   872  4067 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 16:35:54.678   872  1874 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 16:35:54.683   371   870 D CommandListener: Setting iface cfg
,08-25 16:35:54.695   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-25 16:35:54.696   872  1874 D DhcpClient: Scheduling renewal in 86399s
,08-25 16:35:54.716   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 16:35:54.719   872  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 16:35:54.719   872  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 16:35:54.721   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 16:35:54.724   872  1305 D ConnectivityService: Adding iface wlan0 to network 101
,08-25 16:35:54.725   872  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 16:35:54.780   872  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-25 16:35:54.780   872  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-25 16:35:54.781   872  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-25 16:35:54.782   872  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-25 16:35:54.783   872  1305 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-25 16:35:54.789   872  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 16:35:54.795   872  1305 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-25 16:35:54.795   872  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-25 16:35:54.795   872  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-25 16:35:54.795   872  1305 D ConnectivityService:    accepting network in place of null
08-25 16:35:54.796   872  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 16:35:54.796   872  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-25 16:35:54.798   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 16:35:54.806   872  4066 D NetlinkSocketObserver: NeighborEvent{elapsedMs=137216, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 16:35:54.837   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 16:35:54.877   872  4065 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-25 16:35:54.887   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 16:35:54.895   872  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 16:35:54.896   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:35:54.903   872  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-25 16:35:54.912   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-25 16:35:54.918  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:35:54.918  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:35:54.918  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:54.918  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:54.918  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:35:54.918  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:35:54.918  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:35:54.918  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:35:54.918  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 16:35:54.918  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:35:54.918  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 16:35:54.922  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 16:35:54.922  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:35:54.922  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:54.922  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:54.922  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:35:54.922  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:35:54.922  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:35:54.922  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:35:54.922  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 16:35:54.922  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 16:35:54.922  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 16:35:54.933  1726  1726 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-25 16:35:54.938  1726  1726 D SystemUpdateService: onCreate
,08-25 16:35:54.941  1726  1726 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 16:35:54.945  1726  4078 I SystemUpdateService: active receiver: enabled
,08-25 16:35:54.951  1726  4078 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 16:35:54.951   872  4065 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 14:35:54 GMT], X-Android-Received-Millis=[1472135754950], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472135754924]}
,08-25 16:35:54.956   872  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 16:35:54.956   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-25 16:35:54.957   872  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 16:35:54.958   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 16:35:54.958  1726  4078 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
08-25 16:35:54.960  1726  4078 I SystemUpdateService: now status is 0 (complete)
08-25 16:35:54.960  1726  4078 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-25 16:35:54.960  1726  4078 I SystemUpdateService: file has been verified
08-25 16:35:54.960  1726  4078 I SystemUpdateService: OTA package size = 12249756
,08-25 16:35:54.968  1726  4078 I SystemUpdateService: showing system update notification
,08-25 16:35:54.971  1726  1726 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 16:35:54.974  1726  2411 I iu.UploadsManager: num queued entries: 0
,08-25 16:35:54.976  1726  2411 I iu.UploadsManager: num updated entries: 0
,08-25 16:35:54.976  1726  1726 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 16:35:54.978  1726  1726 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 16:35:54.980  1726  4083 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-25 16:35:54.980  1726  4083 W BaseAppContext: Using Auth Proxy for data requests.
08-25 16:35:54.982  1726  4083 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
08-25 16:35:54.983  3966  3966 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:35:54.985  1726  2411 I iu.SyncManager: NEXT; no task
,08-25 16:35:54.988  3966  3966 D SprintDMHelper: simOperator: ,
,08-25 16:35:54.988  3966  3966 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 16:35:54.993  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 16:35:54.997  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 16:35:54.999  1726  1726 D SystemUpdateService: onDestroy
,08-25 16:35:55.041  1519  2291 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-25 16:35:55.041  1519  2291 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-25 16:35:55.041  1519  2291 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 16:35:55.041  1519  2291 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 16:35:55.059  1726  4083 E MDM     : [175] SitrepService.a: Error sending sitrep.
,08-25 16:35:55.121  3924  4085 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 16:35:55.895   872  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-25 16:35:56.515   872  3093 I ActivityManager: Killing 3666:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-25 16:35:56.832   872  1692 D WifiService: setWifiEnabled: false pid=3777, uid=10000
,08-25 16:35:56.833   872  1692 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 16:35:56.866  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 16:35:56.872   872  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-25 16:35:56.872   872  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-25 16:35:56.873   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 16:35:56.874   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 16:35:56.895   872  1874 D DhcpClient: Clearing IP address
,08-25 16:35:56.895   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-25 16:35:56.902  1519  4090 V NativeCrypto: Read error: ssl=0x9b248600: I/O error during system call, Connection timed out
,08-25 16:35:56.906  1519  4090 V NativeCrypto: SSL shutdown failed: ssl=0x9b248600: I/O error during system call, Broken pipe
,08-25 16:35:56.909   371   870 D CommandListener: Setting iface cfg
,08-25 16:35:56.911   872  4067 D DhcpClient: Receive thread stopped
,08-25 16:35:56.912   872   883 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
08-25 16:35:56.914   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 16:35:56.914   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-25 16:35:56.914   872  4065 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
08-25 16:35:56.916   872  1303 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-25 16:35:56.917   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 16:35:56.920   404   404 E Parcel  : Reading a NULL string not supported here.
08-25 16:35:56.921   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-25 16:35:56.922   872  4065 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-25 16:35:56.926   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
08-25 16:35:56.929  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:35:56.930  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:35:56.930  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:56.930  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:56.930  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:35:56.930  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:35:56.930  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:35:56.930  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:35:56.930  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 16:35:56.930  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:35:56.930   872  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 16:35:56.930  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:35:56.931   872  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-25 16:35:56.934  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 16:35:56.935  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:35:56.935  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:56.935  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:56.935  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:35:56.935  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:35:56.935  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:35:56.935  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:35:56.935  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 16:35:56.935  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 16:35:56.935  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 16:35:56.939  2113  2303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 16:35:56.969   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 16:35:56.994   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 16:35:56.995   872  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 16:35:56.996   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 16:35:56.998   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-25 16:35:57.004  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 16:35:57.004  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:35:57.004  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:57.004  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:57.004  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:35:57.004  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:35:57.004  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:35:57.004  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:35:57.004  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:35:57.006  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:35:57.006  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:35:57.006  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:35:57.006  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:35:57.006  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:35:57.006  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:35:57.006  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:35:57.006  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:35:57.006  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 16:35:57.015  1726  1726 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 16:35:57.018  1726  1726 D SystemUpdateService: onCreate
,08-25 16:35:57.021  1726  1726 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) },
,08-25 16:35:57.028  1726  1726 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-25 16:35:57.033  1726  2411 I iu.UploadsManager: num queued entries: 0
,08-25 16:35:57.034  1726  4104 I SystemUpdateService: active receiver: enabled
,08-25 16:35:57.036  1726  1726 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 16:35:57.037  1726  1726 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 16:35:57.039  3966  3966 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:35:57.043  3966  3966 D SprintDMHelper: simOperator: 
08-25 16:35:57.043  3966  3966 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 16:35:57.033  1726  2411 I iu.UploadsManager: num updated entries: 0
,08-25 16:35:57.068  3924  4106 I Babel   : connection state changed from CONNECTED to DISCONNECTED,
,08-25 16:35:57.072  1726  4104 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 16:35:57.072  1726  2411 I iu.SyncManager: NEXT; no task
,08-25 16:35:57.080  1726  4104 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-25 16:35:57.080  1726  4104 I SystemUpdateService: now status is 0 (complete)
,08-25 16:35:57.081  1726  4104 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 16:35:57.081  1726  4104 I SystemUpdateService: file has been verified
08-25 16:35:57.081  1726  4104 I SystemUpdateService: OTA package size = 12249756
,08-25 16:35:57.090  1726  4104 I SystemUpdateService: showing system update notification
,08-25 16:35:57.103  1726  1726 D SystemUpdateService: onDestroy
08-25 16:35:57.104   371   870 E Netd    : netlink response contains error (No such file or directory)
08-25 16:35:57.105   872  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 16:35:57.161  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 16:35:57.186  1519  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-25 16:35:57.187  1519  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-25 16:35:57.187  1519  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 16:35:57.187  1519  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 16:35:57.206  3496  3496 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-25 16:35:57.206  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-25 16:35:57.206  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-25 16:35:59.884   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@989ed49:true
08-25 16:35:59.885  3949  3949 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 16:35:59.890  3949  3949 I bt_bluedroid: init
08-25 16:35:59.890  3949  4110 I BluetoothAdapterState: Entering OffState
,08-25 16:35:59.896  3949  4111 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-25 16:35:59.897  3949  4111 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-25 16:35:59.897  3949  4111 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 16:35:59.897  3949  4111 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 16:35:59.899  3949  3949 I bt_bluedroid: get_profile_interface socket
08-25 16:35:59.901  3949  3949 I bt_bluedroid: get_profile_interface sdp
08-25 16:35:59.902  3949  4114 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-25 16:35:59.904  3949  4114 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 16:35:59.906  3949  3959 I bt_bluedroid: config_hci_snoop_log
,08-25 16:35:59.910   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 16:35:59.921  3949  4110 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 16:35:59.922  3949  4110 D BluetoothAdapterProperties: Setting state to 14
08-25 16:35:59.922  3949  4110 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-25 16:35:59.925  3949  4110 D BluetoothBondStateMachine: make
,08-25 16:35:59.929  3949  4115 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 16:35:59.935  3949  3949 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 16:35:59.933  3949  4110 I BluetoothAdapterState: Entering PendingCommandState
,08-25 16:35:59.939  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
,08-25 16:35:59.940  3949  3949 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 16:35:59.941  3949  3949 D BtGatt.GattService: Received start request. Starting profile...
08-25 16:35:59.941  3949  3949 D BtGatt.GattService: start()
,08-25 16:35:59.941  3949  3949 I bt_bluedroid: get_profile_interface gatt
,08-25 16:35:59.942  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
,08-25 16:35:59.942  3949  3949 D BtGatt.AdvertiseManager: advertise manager created
,08-25 16:35:59.953  3949  3949 V BluetoothAdapterState: isTurningOff()=false
,08-25 16:35:59.953  3949  3949 V BluetoothAdapterState: isTurningOn()=false
,08-25 16:35:59.954  3949  3949 V BluetoothAdapterState: isBleTurningOn()=true
,08-25 16:35:59.954  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 16:35:59.954  3949  4110 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-25 16:35:59.955  3949  4110 I bt_bluedroid: enable
,08-25 16:35:59.956  3949  4111 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-25 16:35:59.957  3949  4111 I bt_hci  : start_up
,08-25 16:35:59.976  3949  4111 I bt_vendor: alloc value 0xb3a69189
,08-25 16:35:59.976  3949  4111 I bt_vendor: init
,08-25 16:35:59.976  3949  4111 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-25 16:35:59.976  3949  4111 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 16:36:00.084  3949  4111 D bt_hci  : start_up starting async portion
,08-25 16:36:00.084  3949  4118 I bt_hci  : event_finish_startup
,08-25 16:36:00.084  3949  4118 I bt_hci_h4: hal_open
08-25 16:36:00.085  3949  4118 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 16:36:00.095  3949  4118 I bt_userial_vendor: device fd = 51 open
,08-25 16:36:00.127  3949  4118 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 16:36:00.159  3949  4118 D bt_hwcfg: Chipset BCM4354A2
,08-25 16:36:00.160  3949  4118 D bt_hwcfg: Target name = [BCM4354A2]
,08-25 16:36:00.160  3949  4118 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 16:36:00.857  3949  4118 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 16:36:00.860  3949  4118 D bt_hwcfg: Settlement delay -- 100 ms
08-25 16:36:00.861  3949  4118 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 16:36:00.977  3949  4118 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 16:36:00.979  3949  4118 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 16:36:01.007  3949  4118 I bt_hwcfg: vendor lib fwcfg completed
,08-25 16:36:01.007  3949  4118 I bt_vendor: firmware callback
,08-25 16:36:01.007  3949  4118 I bt_hci  : firmware_config_callback
,08-25 16:36:01.020  3949  4120 I bt_btu  : btu_task pending for preload complete event
,08-25 16:36:01.021  3949  4120 I bt_btu_task: Bluetooth chip preload is complete
,08-25 16:36:01.021  3949  4120 I bt_btu  : btu_task received preload complete event
,08-25 16:36:01.032  3949  4120 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 16:36:01.033  3949  4120 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-25 16:36:01.033  3949  4120 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-25 16:36:01.033  3949  4120 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-25 16:36:01.034  3949  4120 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 16:36:01.034  3949  4120 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 16:36:01.034  3949  4120 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 16:36:01.034  3949  4120 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 16:36:01.035  3949  4120 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 16:36:01.035  3949  4120 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 16:36:01.036  3949  4120 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 16:36:01.036  3949  4120 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 16:36:01.038  3949  4120 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 16:36:01.038  3949  4120 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 16:36:01.038  3949  4120 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 16:36:01.176  3949  4120 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39e6d9d
,08-25 16:36:01.177  3949  4120 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39e6d9d 
,08-25 16:36:01.190  3949  4114 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 16:36:01.191  3949  4114 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 16:36:01.192  3949  4114 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 16:36:01.195  3949  4114 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 16:36:01.199  3949  4114 D BluetoothAdapterProperties: Scan Mode:20
,08-25 16:36:01.201  3949  4114 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 16:36:01.201  3949  4114 D bt_hci  : do_postload posting postload work item
,08-25 16:36:01.201  3949  4118 I bt_hci  : event_postload
,08-25 16:36:01.201  3949  4118 I bt_vendor: sco_config_cb
,08-25 16:36:01.202  3949  4118 I bt_hci  : sco_config_callback postload finished.
08-25 16:36:01.204  3949  4114 D bt_bte_conf: Device ID record 1 : primary,
08-25 16:36:01.204  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:36:01.204  3949  4114 D bt_bte_conf:   vendorId            = 000f
,08-25 16:36:01.205  3949  4114 D bt_bte_conf:   vendorIdSource      = 0001
,08-25 16:36:01.205  3949  4114 D bt_bte_conf:   product             = 1200
08-25 16:36:01.205  3949  4114 D bt_bte_conf:   version             = 1436
,08-25 16:36:01.205  3949  4114 D bt_bte_conf:   clientExecutableURL = 
08-25 16:36:01.205  3949  4114 D bt_bte_conf:   serviceDescription  = 
,08-25 16:36:01.206  3949  4114 D bt_bte_conf:   documentationURL    = 
,08-25 16:36:01.206  3949  4114 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 16:36:01.206  3949  4111 D bt_stack_manager: event_start_up_stack finished
08-25 16:36:01.207  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:36:01.208  3949  4118 I bt_vendor: low_power_mode_cb
,08-25 16:36:01.210  3949  4110 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-25 16:36:01.211  3949  4110 D BluetoothAdapterProperties: Setting state to 15
,08-25 16:36:01.211  3949  4110 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15,
08-25 16:36:01.214  3949  4110 I BluetoothAdapterState: Entering BleOnState
,08-25 16:36:01.217  3949  4110 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-25 16:36:01.218  3949  4110 D BluetoothAdapterProperties: Setting state to 11
08-25 16:36:01.218  3949  4110 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-25 16:36:01.229  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
,08-25 16:36:01.232  3949  3949 D HeadsetService: Received start request. Starting profile...
,08-25 16:36:01.237  3949  3949 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-25 16:36:01.238  3949  3949 D HeadsetStateMachine: make
08-25 16:36:01.238  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:36:01.240  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:36:01.248  3949  3949 D HeadsetStateMachine: max_hf_connections = 1
,08-25 16:36:01.248  3949  3949 I bt_bluedroid: get_profile_interface handsfree
08-25 16:36:01.249  3949  4114 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-25 16:36:01.249  3949  4114 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-25 16:36:01.250  3949  4110 I BluetoothAdapterState: Entering PendingCommandState
,08-25 16:36:01.254  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
,08-25 16:36:01.254  3949  3949 D A2dpService: Received start request. Starting profile...
,08-25 16:36:01.256  3949  3949 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-25 16:36:01.258  3949  3949 I bt_bluedroid: get_profile_interface avrcp
,08-25 16:36:01.266  3949  3949 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 16:36:01.266  3949  3949 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 16:36:01.267  3949  3949 D A2dpStateMachine: make
,08-25 16:36:01.268  3949  3949 I bt_bluedroid: get_profile_interface a2dp
,08-25 16:36:01.269  3949  4114 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 16:36:01.273  3949  4128 D A2dpStateMachine: Enter Disconnected: -2
08-25 16:36:01.274  3949  3949 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 16:36:01.275  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 16:36:01.276  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
,08-25 16:36:01.277  3845  3845 D BluetoothInputDevice: Proxy object connected
,08-25 16:36:01.277  3949  3949 D HidService: Received start request. Starting profile...
08-25 16:36:01.278  3949  3949 I bt_bluedroid: get_profile_interface hidhost
08-25 16:36:01.278  3949  3949 D HidService: setHidService(): set to: null,
08-25 16:36:01.278  3949  4114 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39c83e5
08-25 16:36:01.278  3949  4114 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-25 16:36:01.278  3845  3845 D HidProfile: Bluetooth service connected
08-25 16:36:01.279  3949  3949 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 16:36:01.280  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
,08-25 16:36:01.280  3949  3949 D HealthService: Received start request. Starting profile...
,08-25 16:36:01.282  3949  3949 I bt_bluedroid: get_profile_interface health
,08-25 16:36:01.283  3949  3949 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 16:36:01.284  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
,08-25 16:36:01.285  3845  3845 D BluetoothPan: BluetoothPAN Proxy object connected
,08-25 16:36:01.285  3949  3949 D PanService: Received start request. Starting profile...
08-25 16:36:01.285  3949  3949 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 16:36:01.285  3949  3949 I bt_bluedroid: get_profile_interface pan
08-25 16:36:01.285  3949  4114 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 16:36:01.285  3845  3845 D PanProfile: Bluetooth service connected
08-25 16:36:01.288  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
,08-25 16:36:01.289  3845  3845 D BluetoothMap: Proxy object connected
,08-25 16:36:01.289  3949  3949 D BluetoothMapService: Received start request. Starting profile...
08-25 16:36:01.289  3949  3949 D BluetoothMapService: start()
08-25 16:36:01.289  3845  3845 D MapProfile: Bluetooth service connected
08-25 16:36:01.289  3845  3845 D BluetoothMap: getConnectedDevices()
,08-25 16:36:01.290  3845  3845 D BluetoothMap: Bluetooth is Not enabled
08-25 16:36:01.291  3949  3949 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-25 16:36:01.292  3949  3949 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-25 16:36:01.292  3949  3949 D BluetoothMapAppObserver: createReceiver()
,08-25 16:36:01.293  3949  3949 D BluetoothMapAppObserver: initObservers()
,08-25 16:36:01.293  3949  3949 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 16:36:01.300  3949  4126 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-25 16:36:01.301  3949  3949 V BluetoothAdapterState: isTurningOff()=false
,08-25 16:36:01.301  3949  3949 V BluetoothAdapterState: isTurningOn()=true
08-25 16:36:01.301  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:36:01.301  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 16:36:01.302  3949  3949 V BluetoothAdapterState: isTurningOff()=false
08-25 16:36:01.302  3949  3949 V BluetoothAdapterState: isTurningOn()=true
08-25 16:36:01.303  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:36:01.303  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
08-25 16:36:01.303  3949  3949 V BluetoothAdapterState: isTurningOff()=false
08-25 16:36:01.303  3949  3949 V BluetoothAdapterState: isTurningOn()=true
08-25 16:36:01.303  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:36:01.303  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 16:36:01.303  3949  3949 V BluetoothAdapterState: isTurningOff()=false
08-25 16:36:01.303  3949  3949 V BluetoothAdapterState: isTurningOn()=true
08-25 16:36:01.303  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:36:01.303  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
08-25 16:36:01.304  3949  3949 V BluetoothAdapterState: isTurningOff()=false
,08-25 16:36:01.304  3949  3949 V BluetoothAdapterState: isTurningOn()=true
,08-25 16:36:01.304  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 16:36:01.304  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
08-25 16:36:01.304  3949  3949 V BluetoothAdapterState: isTurningOff()=false
08-25 16:36:01.304  3949  3949 V BluetoothAdapterState: isTurningOn()=true
,08-25 16:36:01.304  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:36:01.304  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 16:36:01.304  3949  4110 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 16:36:01.304  3949  4110 D BluetoothAdapterProperties: ScanMode =  20
,08-25 16:36:01.304  3949  4110 D BluetoothAdapterProperties: State =  11
08-25 16:36:01.305  3949  4114 D BluetoothAdapterProperties: Scan Mode:21
08-25 16:36:01.305  3949  4114 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 16:36:01.306  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:36:01.307  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:36:01.308  3949  4110 D BluetoothAdapterProperties: Setting state to 12
08-25 16:36:01.308  3949  4110 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 16:36:01.308   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 16:36:01.309  3949  4110 I BluetoothAdapterState: Entering OnState
08-25 16:36:01.309  1362  1373 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 16:36:01.309   872   872 D BluetoothA2dp: Proxy object connected
08-25 16:36:01.310   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 16:36:01.310  1362  2026 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 16:36:01.312  1362  1362 D BluetoothInputDevice: Proxy object connected
08-25 16:36:01.312  1362  1373 D BluetoothPan: onBluetoothStateChange on: true
08-25 16:36:01.312  1362  1362 D HidProfile: Bluetooth service connected
08-25 16:36:01.313  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 16:36:01.313  1362  1362 D PanProfile: Bluetooth service connected
,08-25 16:36:01.313   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 16:36:01.313   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 16:36:01.313  3845  3855 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 16:36:01.315  1926  2195 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 16:36:01.315  1362  1377 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 16:36:01.317  1362  1362 D BluetoothA2dp: Proxy object connected
,08-25 16:36:01.317  3845  3858 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 16:36:01.317  3845  3855 D BluetoothPan: onBluetoothStateChange on: true
,08-25 16:36:01.318  1362  1373 D BluetoothMap: onBluetoothStateChange: up=true
08-25 16:36:01.319  1362  1362 D BluetoothMap: Proxy object connected
08-25 16:36:01.319  1362  1362 D MapProfile: Bluetooth service connected
,08-25 16:36:01.319  1362  1362 D BluetoothMap: getConnectedDevices()
,08-25 16:36:01.319  3845  3858 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 16:36:01.320  1362  2026 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 16:36:01.320  3949  3949 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 16:36:01.320  3949  3949 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-25 16:36:01.322   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 16:36:01.324  3949  3949 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 16:36:01.325  3845  3845 D LocalBluetoothProfileManager: Adding local A2DP profile
08-25 16:36:01.326  3949  3949 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 16:36:01.326  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:36:01.326  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:36:01.326  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:36:01.326  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:36:01.326  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:36:01.326  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:36:01.326  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:36:01.326  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 16:36:01.327  3949  3949 D ObexServerSockets: Succeed to create listening sockets 
,08-25 16:36:01.327  3949  3949 D ObexServerSockets0: startAccept()
08-25 16:36:01.327  3949  3949 D ObexServerSockets0: prepareForNewConnect()
,08-25 16:36:01.328  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 16:36:01.329  3949  3949 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-25 16:36:01.329  3949  3949 D BluetoothSdpJni: SDP Create record success - handle: 0
08-25 16:36:01.330  3949  3949 D BluetoothMapService: onReceive
08-25 16:36:01.330  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:36:01.330  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:36:01.330  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:36:01.330  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:36:01.330  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:36:01.330  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:36:01.330  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:36:01.330  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 16:36:01.330  3949  4136 D ObexServerSockets0: Accepting socket connection...
08-25 16:36:01.330  3949  3949 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:36:01.330  3949  3949 D BluetoothMapService: STATE_ON
08-25 16:36:01.331  3949  4137 D ObexServerSockets0: Accepting socket connection...
,08-25 16:36:01.332  3845  3845 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-25 16:36:01.332  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:36:01.338  3845  3845 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 16:36:01.342  3845  3845 D BluetoothA2dp: Proxy object connected
08-25 16:36:01.343  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 16:36:01.352  3845  3845 D DockEventReceiver: finishStartingService: stopping service
,08-25 16:36:01.353  3845  3845 D BluetoothPbap: Proxy object connected
,08-25 16:36:01.353  3845  3845 D PbapServerProfile: Bluetooth service connected
08-25 16:36:01.355  1362  1362 D BluetoothPbap: Proxy object connected
08-25 16:36:01.355  1362  1362 D PbapServerProfile: Bluetooth service connected
,08-25 16:36:01.360  3949  3949 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 16:36:01.360  3949  3949 D ObexServerSockets0: prepareForNewConnect()
,08-25 16:36:01.361  3949  4141 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 16:36:01.375  3949  4145 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 16:36:01.376  3949  4145 I BtOppRfcommListener: Accept thread started.
,08-25 16:36:01.412  1926  1938 D BluetoothHeadset: Proxy object connected
,08-25 16:36:01.412   872   872 D BluetoothHeadset: Proxy object connected
08-25 16:36:01.412   872   872 D BluetoothHeadset: Proxy object connected
,08-25 16:36:01.412   872   872 D BluetoothHeadset: Proxy object connected
08-25 16:36:01.412  1362  1377 D BluetoothHeadset: Proxy object connected
08-25 16:36:01.412  1362  1362 D HeadsetProfile: Bluetooth service connected
08-25 16:36:01.413   872   889 D BluetoothHeadset: Proxy object connected
08-25 16:36:01.413   872   889 D BluetoothHeadset: Proxy object connected
,08-25 16:36:01.415  1926  2206 D BluetoothHeadset: Proxy object connected
,08-25 16:36:01.420  1362  2026 D BluetoothHeadset: Proxy object connected
,08-25 16:36:01.420  1362  1362 D HeadsetProfile: Bluetooth service connected
,08-25 16:36:01.434  3845  3855 D BluetoothHeadset: Proxy object connected
08-25 16:36:01.435  3845  3845 D HeadsetProfile: Bluetooth service connected
,08-25 16:36:02.801   872  1305 D ConnectivityService: handlePromptUnvalidated 101
,08-25 16:36:02.852  3949  4110 D BluetoothAdapterState: Current state: ON, message: 23
,08-25 16:36:02.852  3949  4110 D BluetoothAdapterProperties: Setting state to 13
,08-25 16:36:02.853  3949  4110 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 16:36:02.854  3949  4110 D BluetoothAdapterProperties: onBluetoothDisable()
,08-25 16:36:02.856  3949  4110 I BluetoothAdapterState: Entering PendingCommandState
08-25 16:36:02.861  3949  3949 D BluetoothMapService: onReceive
08-25 16:36:02.861  3949  3949 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:36:02.861  3949  3949 D BluetoothMapService: STATE_TURNING_OFF
,08-25 16:36:02.862  3949  3949 D BluetoothMapService: MAP Service closeService in
08-25 16:36:02.863  3949  3949 D BluetoothMapMasInstance0: MAP Service shutdown
,08-25 16:36:02.863  3949  3949 D ObexServerSockets0: shutdown(block = true)
08-25 16:36:02.864  3949  4136 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-25 16:36:02.867  3949  3949 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-25 16:36:02.868  3949  4137 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-25 16:36:02.871  3949  3949 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 16:36:02.871  3949  4122 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-25 16:36:02.871  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 16:36:02.871  3949  3949 I BtOppRfcommListener: stopping Accept Thread
08-25 16:36:02.871  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:36:02.871  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:36:02.871  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:36:02.871  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:36:02.871  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:36:02.871  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:36:02.871  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:36:02.871  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 16:36:02.872  3949  4145 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-25 16:36:02.872  3949  4145 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 16:36:02.873  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 16:36:02.873  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 16:36:02.875  3949  4114 D BluetoothAdapterProperties: Scan Mode:20
08-25 16:36:02.876  3949  4110 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-25 16:36:02.878  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 16:36:02.878  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:36:02.878  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:36:02.878  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:36:02.878  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:36:02.878  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 16:36:02.878  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:36:02.878  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:36:02.878  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 16:36:02.880  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 16:36:02.880  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 16:36:02.881  3845  3845 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 16:36:02.883  3949  3949 D HeadsetService: Received stop request...Stopping profile...
08-25 16:36:02.885  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:36:02.887  1926  1938 D BluetoothHeadset: Proxy object disconnected
08-25 16:36:02.888  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:36:02.888  3845  3855 D BluetoothHeadset: Proxy object disconnected
08-25 16:36:02.889   872   872 D BluetoothHeadset: Proxy object disconnected
,08-25 16:36:02.889   872   872 D BluetoothHeadset: Proxy object disconnected
08-25 16:36:02.889   872   872 D BluetoothHeadset: Proxy object disconnected
08-25 16:36:02.890  1362  1377 D BluetoothHeadset: Proxy object disconnected
,08-25 16:36:02.891  3949  3949 D A2dpService: Received stop request...Stopping profile...
08-25 16:36:02.892  3949  4128 D A2dpStateMachine: Exit Disconnected: -1
,08-25 16:36:02.894   872   872 D BluetoothA2dp: Proxy object disconnected
,08-25 16:36:02.895  3949  3949 D HidService: Received stop request...Stopping profile...
08-25 16:36:02.895  3949  3949 D HidService: Stopping Bluetooth HidService
,08-25 16:36:02.897  3949  3949 V BluetoothAdapterState: isTurningOff()=true
08-25 16:36:02.897  3949  3949 V BluetoothAdapterState: isTurningOn()=false
08-25 16:36:02.898  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:36:02.898  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 16:36:02.901  3949  3949 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 16:36:02.901  3949  3949 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-25 16:36:02.901  3949  4114 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-25 16:36:02.901  3949  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 16:36:02.901  3949  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 16:36:02.901  3949  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 16:36:02.902  3949  4114 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-25 16:36:02.902  3949  3949 D HealthService: Received stop request...Stopping profile...
,08-25 16:36:02.904  1362  1362 D HeadsetProfile: Bluetooth service disconnected
,08-25 16:36:02.904  1362  1362 D BluetoothA2dp: Proxy object disconnected
08-25 16:36:02.904  1362  1362 D BluetoothInputDevice: Proxy object disconnected
08-25 16:36:02.904  1362  1362 D HidProfile: Bluetooth service disconnected
,08-25 16:36:02.904  3949  3949 D PanService: Received stop request...Stopping profile...
08-25 16:36:02.905  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 16:36:02.906  1362  1362 D PanProfile: Bluetooth service disconnected
,08-25 16:36:02.906  3949  3949 V BluetoothAdapterState: isTurningOff()=true
08-25 16:36:02.906  3949  3949 V BluetoothAdapterState: isTurningOn()=false
08-25 16:36:02.906  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:36:02.906  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
08-25 16:36:02.908  3949  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 16:36:02.909  3949  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 16:36:02.909  3949  4120 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 16:36:02.909  3949  4120 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-25 16:36:02.909  3949  4120 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 16:36:02.909  3949  4120 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 16:36:02.909  3949  4114 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-25 16:36:02.910  3949  3949 D BluetoothMapService: Received stop request...Stopping profile...
08-25 16:36:02.910  3949  3949 D BluetoothMapService: stop()
08-25 16:36:02.910  3949  3949 D BluetoothMapAppObserver: deinitObservers()
08-25 16:36:02.910  3949  3949 D BluetoothMapAppObserver: removeReceiver()
08-25 16:36:02.912  1362  1362 D BluetoothMap: Proxy object disconnected
,08-25 16:36:02.912  1362  1362 D MapProfile: Bluetooth service disconnected
,08-25 16:36:02.914  3949  3949 V BluetoothAdapterState: isTurningOff()=true
08-25 16:36:02.914  3949  3949 V BluetoothAdapterState: isTurningOn()=false
08-25 16:36:02.914  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false,
08-25 16:36:02.914  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 16:36:02.915  3949  3949 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 16:36:02.915  3949  3949 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-25 16:36:02.915  3949  4114 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 16:36:02.917  3845  3845 D DockEventReceiver: finishStartingService: stopping service
08-25 16:36:02.917  3949  3949 V BluetoothAdapterState: isTurningOff()=true
08-25 16:36:02.917  3949  3949 V BluetoothAdapterState: isTurningOn()=false
,08-25 16:36:02.917  3845  3845 D HeadsetProfile: Bluetooth service disconnected
08-25 16:36:02.917  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:36:02.917  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
08-25 16:36:02.918  3845  3845 D BluetoothA2dp: Proxy object disconnected,
08-25 16:36:02.918  3949  3949 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 16:36:02.918  3845  3845 D BluetoothInputDevice: Proxy object disconnected
08-25 16:36:02.918  3845  3845 D HidProfile: Bluetooth service disconnected
,08-25 16:36:02.918  3845  3845 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 16:36:02.918  3845  3845 D PanProfile: Bluetooth service disconnected
08-25 16:36:02.918  3949  3949 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-25 16:36:02.918  3845  3845 D BluetoothMap: Proxy object disconnected
08-25 16:36:02.918  3949  4114 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-25 16:36:02.918  3845  3845 D MapProfile: Bluetooth service disconnected
,08-25 16:36:02.919  3949  3949 V BluetoothAdapterState: isTurningOff()=true
08-25 16:36:02.919  3949  3949 V BluetoothAdapterState: isTurningOn()=false
08-25 16:36:02.919  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:36:02.919  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 16:36:02.919  3949  3949 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 16:36:02.923  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 16:36:02.919  3949  3949 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 16:36:02.924  3949  3949 D BluetoothMapService: MAP Service closeService in
08-25 16:36:02.924  3949  3949 V BluetoothAdapterState: isTurningOff()=true
08-25 16:36:02.924  3949  3949 V BluetoothAdapterState: isTurningOn()=false
08-25 16:36:02.924  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 16:36:02.924  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
08-25 16:36:02.925  3949  3949 D BluetoothMapService: cleanup()
08-25 16:36:02.925  3949  3949 D BluetoothMapService: MAP Service closeService in
08-25 16:36:02.925  3949  4110 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-25 16:36:02.925  3949  4110 D BluetoothAdapterProperties: Setting state to 15
08-25 16:36:02.925  3949  4110 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 16:36:02.927  3949  4110 I BluetoothAdapterState: Entering BleOnState
,08-25 16:36:02.929   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 16:36:02.929  1362  1362 D BluetoothPbap: Proxy object disconnected
,08-25 16:36:02.929  1362  1362 D PbapServerProfile: Bluetooth service disconnected
,08-25 16:36:02.931  3845  3845 D BluetoothPbap: Proxy object disconnected
08-25 16:36:02.931  3845  3845 D PbapServerProfile: Bluetooth service disconnected
,08-25 16:36:02.934  1362  1377 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 16:36:02.934   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 16:36:02.934  1362  1373 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 16:36:02.940  3845  3855 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 16:36:02.941  1362  2026 D BluetoothPan: onBluetoothStateChange on: false
,08-25 16:36:02.943   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 16:36:02.943  3845  3858 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 16:36:02.944   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 16:36:02.944  3845  3855 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 16:36:02.945  1926  2206 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 16:36:02.946  1362  1377 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 16:36:02.947  3845  3858 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 16:36:02.948  3845  3855 D BluetoothPan: onBluetoothStateChange on: false
,08-25 16:36:02.948  1362  1373 D BluetoothMap: onBluetoothStateChange: up=false
08-25 16:36:02.949  3845  3858 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 16:36:02.949  1362  2026 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 16:36:02.950  3949  4110 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-25 16:36:02.950  3949  4110 D BluetoothAdapterProperties: Setting state to 16
,08-25 16:36:02.950  3949  4110 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-25 16:36:02.950  3949  4110 D BluetoothAdapterProperties: onBleDisable
08-25 16:36:02.951  3949  4110 I BluetoothAdapterState: Entering PendingCommandState
08-25 16:36:02.951  3949  4111 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-25 16:36:02.952  3949  4120 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-25 16:36:02.952  3949  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 16:36:02.953  3949  4114 D BluetoothAdapterProperties: Scan Mode:20
08-25 16:36:02.953  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:36:02.954  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:36:02.955  3845  3845 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 16:36:02.956  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:36:02.957  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:36:02.959  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 16:36:02.962  3845  3845 D DockEventReceiver: finishStartingService: stopping service
,08-25 16:36:03.153  3949  4114 I bt_hci  : shut_down
,08-25 16:36:03.153  3949  4118 D bt_hwcfg: hw_epilog_process
08-25 16:36:03.155  3949  4118 I bt_vendor: low_power_mode_cb
,08-25 16:36:03.175  3949  4118 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-25 16:36:03.175  3949  4118 I bt_vendor: epilog_cb
,08-25 16:36:03.175  3949  4118 I bt_hci  : epilog_finished_callback
,08-25 16:36:03.186  3949  4114 I bt_hci_h4: hal_close
,08-25 16:36:03.187  3949  4114 I bt_userial_vendor: device fd = 51 close
,08-25 16:36:03.319  3949  4111 D bt_stack_manager: event_shut_down_stack finished.
,08-25 16:36:03.320  3949  4110 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 16:36:03.326  3949  4110 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-25 16:36:03.327  3949  3949 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 16:36:03.329  3949  3949 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 16:36:03.329  3949  3949 D BtGatt.GattService: stop()
08-25 16:36:03.330  3949  3949 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 16:36:03.334  3949  3949 V BluetoothAdapterState: isTurningOff()=false
,08-25 16:36:03.334  3949  3949 V BluetoothAdapterState: isTurningOn()=false
,08-25 16:36:03.335  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:36:03.335  3949  3949 V BluetoothAdapterState: isBleTurningOff()=true
08-25 16:36:03.336  3949  4110 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-25 16:36:03.337  3949  4110 D BluetoothAdapterProperties: Setting state to 10
08-25 16:36:03.337  3949  4110 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-25 16:36:03.338  3949  4110 I BluetoothAdapterState: Entering OffState
08-25 16:36:03.339   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-25 16:36:03.352  3949  3949 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-25 16:36:03.352  3949  3949 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-25 16:36:03.352  3949  4111 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 16:36:03.355  3949  4111 D bt_stack_manager: event_clean_up_stack finished.
08-25 16:36:03.355  3949  3949 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 16:36:03.357  3949  3949 I art     : System.exit called, status: 0,
08-25 16:36:03.357  3949  3949 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 16:36:03.420   872   882 I ActivityManager: Process com.android.bluetooth (pid 3949) has died,
,08-25 16:36:05.848  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:36:05.848  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 16:36:07.825   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-25 16:36:07.838  1854  1854 I Keyboard.Facilitator: onFinishInput()
,08-25 16:36:07.859   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 16:36:07.859   872   892 I Adreno  : Build Date                       : 10/20/15
08-25 16:36:07.859   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 16:36:07.859   872   892 I Adreno  : Local Branch                     : M14
08-25 16:36:07.859   872   892 I Adreno  : Remote Branch                    : 
08-25 16:36:07.859   872   892 I Adreno  : Remote Branch                    : 
08-25 16:36:07.859   872   892 I Adreno  : Reconstruct Branch               : 
,08-25 16:36:07.909   280   299 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (218 us)
,08-25 16:36:08.598  3777  3777 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-25 16:36:08.598  3777  3777 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-25 16:36:08.637   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-25 16:36:08.638  3777  3777 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@189f61f Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@c07a556, 16908290=android.view.AbsSavedState$1@c07a556}, android:focusedViewId=100}]}]
08-25 16:36:08.638  3777  3777 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-25 16:36:08.640  3777  3777 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-25 16:36:08.640  3777  3777 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-25 16:36:08.650   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-25 16:36:08.656   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-25 16:36:08.656   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
08-25 16:36:08.657   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-25 16:36:08.856  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 16:36:08.856  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a25c9d7 added. We now have 6 listener(s)
08-25 16:36:08.857  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 16:36:08.860  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 16:36:08.861  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8e0a2c4 added. We now have 7 listener(s)
08-25 16:36:08.861  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 16:36:08.862  3777  3827 I System.out: IsBluetoothEnabled
,08-25 16:36:08.874  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:36:08.885   280   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-25 16:36:08.889   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-25 16:36:08.890   872  1331 D SurfaceControl: Excessive delay in setPowerMode(): 235ms
,08-25 16:36:08.929   872   889 I ActivityManager: Start proc 4160:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-25 16:36:08.930   872   892 I DreamManagerService: Entering dreamland.
,08-25 16:36:08.931   872   892 I PowerManagerService: Dozing...
,08-25 16:36:08.932   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-25 16:36:09.001   375  1275 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-25 16:36:09.001   375  1275 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-25 16:36:09.008   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 16:36:09.016   872  1303 E native  : do suspend false
,08-25 16:36:09.025  1909  4173 D NfcService: Discovery configuration equal, not updating.
,08-25 16:36:09.046  4160  4160 D AdapterServiceConfig: Adding HeadsetService
,08-25 16:36:09.046  4160  4160 D AdapterServiceConfig: Adding A2dpService
,08-25 16:36:09.047  4160  4160 D AdapterServiceConfig: Adding HidService
,08-25 16:36:09.047  4160  4160 D AdapterServiceConfig: Adding HealthService,
08-25 16:36:09.047  4160  4160 D AdapterServiceConfig: Adding PanService
08-25 16:36:09.048  4160  4160 D AdapterServiceConfig: Adding GattService
,08-25 16:36:09.048  4160  4160 D AdapterServiceConfig: Adding BluetoothMapService
08-25 16:36:09.048   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 16:36:09.050   872  1303 E native  : do suspend true
,08-25 16:36:09.062   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f639241:true
,08-25 16:36:09.062  4160  4160 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 16:36:09.066  4160  4160 I bt_bluedroid: init
08-25 16:36:09.066  4160  4175 I BluetoothAdapterState: Entering OffState
,08-25 16:36:09.071  4160  4176 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-25 16:36:09.072  4160  4176 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 16:36:09.072  4160  4176 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-25 16:36:09.072  4160  4176 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 16:36:09.074  4160  4160 I bt_bluedroid: get_profile_interface socket
,08-25 16:36:09.075  4160  4179 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 16:36:09.075  4160  4160 I bt_bluedroid: get_profile_interface sdp
08-25 16:36:09.077  4160  4179 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 16:36:09.135   375  1312 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-25 16:36:09.135   375  1312 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
08-25 16:36:09.140  4160  4171 I bt_bluedroid: config_hci_snoop_log
,08-25 16:36:09.145   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 16:36:09.158  4160  4175 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 16:36:09.158  4160  4175 D BluetoothAdapterProperties: Setting state to 14
,08-25 16:36:09.159  4160  4175 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-25 16:36:09.161  4160  4175 D BluetoothBondStateMachine: make
,08-25 16:36:09.166  4160  4182 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 16:36:09.176  4160  4175 I BluetoothAdapterState: Entering PendingCommandState
,08-25 16:36:09.178  4160  4160 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 16:36:09.187  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
,08-25 16:36:09.188  4160  4160 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 16:36:09.189  4160  4160 D BtGatt.GattService: Received start request. Starting profile...
,08-25 16:36:09.190  4160  4160 D BtGatt.GattService: start()
08-25 16:36:09.190  4160  4160 I bt_bluedroid: get_profile_interface gatt
08-25 16:36:09.193  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
08-25 16:36:09.194  4160  4160 D BtGatt.AdvertiseManager: advertise manager created
,08-25 16:36:09.201  4160  4160 V BluetoothAdapterState: isTurningOff()=false
,08-25 16:36:09.201  4160  4160 V BluetoothAdapterState: isTurningOn()=false
08-25 16:36:09.201  4160  4160 V BluetoothAdapterState: isBleTurningOn()=true
08-25 16:36:09.202  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 16:36:09.202  4160  4175 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-25 16:36:09.203  4160  4175 I bt_bluedroid: enable
08-25 16:36:09.203  4160  4176 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-25 16:36:09.204  4160  4176 I bt_hci  : start_up
,08-25 16:36:09.222  4160  4176 I bt_vendor: alloc value 0xb3a79189
,08-25 16:36:09.223  4160  4176 I bt_vendor: init
08-25 16:36:09.223  4160  4176 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-25 16:36:09.224  4160  4176 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 16:36:09.331  4160  4176 D bt_hci  : start_up starting async portion,
08-25 16:36:09.332  4160  4186 I bt_hci  : event_finish_startup
,08-25 16:36:09.332  4160  4186 I bt_hci_h4: hal_open
08-25 16:36:09.332  4160  4186 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 16:36:09.343  4160  4186 I bt_userial_vendor: device fd = 51 open
,08-25 16:36:09.374  4160  4186 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 16:36:09.406  4160  4186 D bt_hwcfg: Chipset BCM4354A2
,08-25 16:36:09.406  4160  4186 D bt_hwcfg: Target name = [BCM4354A2]
08-25 16:36:09.407  4160  4186 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 16:36:10.071  4160  4186 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 16:36:10.072  4160  4186 D bt_hwcfg: Settlement delay -- 100 ms
08-25 16:36:10.073  4160  4186 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 16:36:10.189  4160  4186 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-25 16:36:10.190  4160  4186 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 16:36:10.220  4160  4186 I bt_hwcfg: vendor lib fwcfg completed
,08-25 16:36:10.221  4160  4186 I bt_vendor: firmware callback
08-25 16:36:10.221  4160  4186 I bt_hci  : firmware_config_callback
,08-25 16:36:10.234  4160  4188 I bt_btu  : btu_task pending for preload complete event
,08-25 16:36:10.234  4160  4188 I bt_btu_task: Bluetooth chip preload is complete
08-25 16:36:10.234  4160  4188 I bt_btu  : btu_task received preload complete event
,08-25 16:36:10.244  4160  4188 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 16:36:10.245  4160  4188 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 16:36:10.245  4160  4188 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-25 16:36:10.245  4160  4188 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 16:36:10.245  4160  4188 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 16:36:10.246  4160  4188 I         : BTE_InitTraceLevels -- TRC_A2D
,08-25 16:36:10.246  4160  4188 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 16:36:10.246  4160  4188 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 16:36:10.246  4160  4188 I         : BTE_InitTraceLevels -- TRC_GAP
,08-25 16:36:10.247  4160  4188 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 16:36:10.247  4160  4188 I         : BTE_InitTraceLevels -- TRC_SDP
,08-25 16:36:10.247  4160  4188 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 16:36:10.247  4160  4188 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 16:36:10.248  4160  4188 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-25 16:36:10.248  4160  4188 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 16:36:10.382  4160  4188 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39f6d9d
,08-25 16:36:10.383  4160  4188 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39f6d9d 
,08-25 16:36:10.407  4160  4179 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 16:36:10.408  4160  4179 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 16:36:10.409  4160  4179 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 16:36:10.412  4160  4179 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 16:36:10.421  4160  4179 D BluetoothAdapterProperties: Scan Mode:20
,08-25 16:36:10.421  4160  4179 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 16:36:10.422  4160  4179 D bt_hci  : do_postload posting postload work item
,08-25 16:36:10.423  4160  4186 I bt_hci  : event_postload
,08-25 16:36:10.423  4160  4186 I bt_vendor: sco_config_cb
,08-25 16:36:10.423  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:36:10.423  4160  4186 I bt_hci  : sco_config_callback postload finished.
,08-25 16:36:10.425  4160  4179 D bt_bte_conf: Device ID record 1 : primary
08-25 16:36:10.426  4160  4179 D bt_bte_conf:   vendorId            = 000f
08-25 16:36:10.426  4160  4179 D bt_bte_conf:   vendorIdSource      = 0001
08-25 16:36:10.426  4160  4179 D bt_bte_conf:   product             = 1200
,08-25 16:36:10.427  4160  4179 D bt_bte_conf:   version             = 1436
,08-25 16:36:10.427  4160  4179 D bt_bte_conf:   clientExecutableURL = 
,08-25 16:36:10.427  4160  4179 D bt_bte_conf:   serviceDescription  = 
,08-25 16:36:10.427  4160  4179 D bt_bte_conf:   documentationURL    = 
,08-25 16:36:10.428  4160  4179 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 16:36:10.429  4160  4176 D bt_stack_manager: event_start_up_stack finished
08-25 16:36:10.432  4160  4186 I bt_vendor: low_power_mode_cb
08-25 16:36:10.432  4160  4175 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-25 16:36:10.433  4160  4175 D BluetoothAdapterProperties: Setting state to 15
08-25 16:36:10.433  4160  4175 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-25 16:36:10.433  4160  4175 I BluetoothAdapterState: Entering BleOnState
,08-25 16:36:10.438  4160  4175 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-25 16:36:10.438  4160  4175 D BluetoothAdapterProperties: Setting state to 11
,08-25 16:36:10.438  4160  4175 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-25 16:36:10.453  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
,08-25 16:36:10.453  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:36:10.454  4160  4160 D HeadsetService: Received start request. Starting profile...
08-25 16:36:10.460  4160  4160 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 16:36:10.460  4160  4160 D HeadsetStateMachine: make
,08-25 16:36:10.467  4160  4175 I BluetoothAdapterState: Entering PendingCommandState
,08-25 16:36:10.472  4160  4160 D HeadsetStateMachine: max_hf_connections = 1
,08-25 16:36:10.472  4160  4160 I bt_bluedroid: get_profile_interface handsfree
08-25 16:36:10.473  4160  4179 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-25 16:36:10.474  4160  4179 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-25 16:36:10.477  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
,08-25 16:36:10.478  4160  4160 D A2dpService: Received start request. Starting profile...
,08-25 16:36:10.479  4160  4160 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-25 16:36:10.480  4160  4160 I bt_bluedroid: get_profile_interface avrcp
,08-25 16:36:10.487  4160  4160 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 16:36:10.488  4160  4160 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 16:36:10.488  4160  4160 D A2dpStateMachine: make
,08-25 16:36:10.489  4160  4160 I bt_bluedroid: get_profile_interface a2dp
,08-25 16:36:10.489  4160  4179 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 16:36:10.495  4160  4196 D A2dpStateMachine: Enter Disconnected: -2
,08-25 16:36:10.496  4160  4160 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 16:36:10.497  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
,08-25 16:36:10.498  4160  4160 D HidService: Received start request. Starting profile...
,08-25 16:36:10.498  4160  4160 I bt_bluedroid: get_profile_interface hidhost
,08-25 16:36:10.498  4160  4160 D HidService: setHidService(): set to: null
08-25 16:36:10.499  4160  4179 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d83e5
08-25 16:36:10.499  4160  4179 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-25 16:36:10.499  4160  4160 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 16:36:10.501  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
,08-25 16:36:10.502  4160  4160 D HealthService: Received start request. Starting profile...
,08-25 16:36:10.504  4160  4160 I bt_bluedroid: get_profile_interface health
,08-25 16:36:10.505  4160  4160 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 16:36:10.506  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
,08-25 16:36:10.507  4160  4160 D PanService: Received start request. Starting profile...
,08-25 16:36:10.508  4160  4160 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 16:36:10.508  4160  4160 I bt_bluedroid: get_profile_interface pan
08-25 16:36:10.509  4160  4179 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 16:36:10.515  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 16:36:10.516  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
,08-25 16:36:10.517  4160  4160 D BluetoothMapService: Received start request. Starting profile...
,08-25 16:36:10.517  4160  4160 D BluetoothMapService: start()
,08-25 16:36:10.522  4160  4160 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-25 16:36:10.523  4160  4160 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-25 16:36:10.524  4160  4160 D BluetoothMapAppObserver: createReceiver()
,08-25 16:36:10.526  4160  4160 D BluetoothMapAppObserver: initObservers()
,08-25 16:36:10.526  4160  4160 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 16:36:10.535  4160  4160 V BluetoothAdapterState: isTurningOff()=false
,08-25 16:36:10.535  4160  4160 V BluetoothAdapterState: isTurningOn()=true
08-25 16:36:10.535  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:36:10.535  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 16:36:10.538  4160  4160 V BluetoothAdapterState: isTurningOff()=false
,08-25 16:36:10.538  4160  4160 V BluetoothAdapterState: isTurningOn()=true
08-25 16:36:10.538  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:36:10.539  4160  4194 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 16:36:10.539  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
08-25 16:36:10.539  4160  4160 V BluetoothAdapterState: isTurningOff()=false
08-25 16:36:10.539  4160  4160 V BluetoothAdapterState: isTurningOn()=true
,08-25 16:36:10.539  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:36:10.539  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
08-25 16:36:10.539  4160  4160 V BluetoothAdapterState: isTurningOff()=false
08-25 16:36:10.539  4160  4160 V BluetoothAdapterState: isTurningOn()=true
08-25 16:36:10.539  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:36:10.539  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
08-25 16:36:10.540  4160  4160 V BluetoothAdapterState: isTurningOff()=false
,08-25 16:36:10.540  4160  4160 V BluetoothAdapterState: isTurningOn()=true
08-25 16:36:10.540  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:36:10.540  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 16:36:10.543  4160  4160 V BluetoothAdapterState: isTurningOff()=false
08-25 16:36:10.543  4160  4160 V BluetoothAdapterState: isTurningOn()=true
08-25 16:36:10.543  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
08-25 16:36:10.543  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
08-25 16:36:10.543  4160  4175 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 16:36:10.544  4160  4175 D BluetoothAdapterProperties: ScanMode =  20
08-25 16:36:10.544  4160  4175 D BluetoothAdapterProperties: State =  11
,08-25 16:36:10.550  4160  4179 D BluetoothAdapterProperties: Scan Mode:21
08-25 16:36:10.550  4160  4179 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 16:36:10.550  4160  4175 D BluetoothAdapterProperties: Setting state to 12
08-25 16:36:10.551  4160  4175 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 16:36:10.551   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 16:36:10.553  4160  4175 I BluetoothAdapterState: Entering OnState
,08-25 16:36:10.554  1362  1377 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 16:36:10.557  4160  4160 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 16:36:10.558  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:36:10.558  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:36:10.558  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:36:10.558  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:36:10.558  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:36:10.558  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:36:10.558  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:36:10.558  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 16:36:10.558  4160  4160 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-25 16:36:10.558   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 16:36:10.559  1362  1373 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 16:36:10.561  4160  4160 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 16:36:10.562  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 16:36:10.565  3845  4155 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 16:36:10.566  4160  4160 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 16:36:10.568  1362  2026 D BluetoothPan: onBluetoothStateChange on: true
,08-25 16:36:10.568  4160  4160 D ObexServerSockets: Succeed to create listening sockets 
08-25 16:36:10.568  4160  4160 D ObexServerSockets0: startAccept()
08-25 16:36:10.569  4160  4160 D ObexServerSockets0: prepareForNewConnect()
,08-25 16:36:10.572   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 16:36:10.572  3845  3855 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 16:36:10.573   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 16:36:10.573  3845  3858 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 16:36:10.575  4160  4160 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-25 16:36:10.575  4160  4202 D ObexServerSockets0: Accepting socket connection...
08-25 16:36:10.575  4160  4160 D BluetoothSdpJni: SDP Create record success - handle: 0
08-25 16:36:10.576  4160  4203 D ObexServerSockets0: Accepting socket connection...
,08-25 16:36:10.576  1926  2046 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 16:36:10.578  1362  1377 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 16:36:10.578   872   872 D BluetoothA2dp: Proxy object connected
08-25 16:36:10.580  1362  1362 D BluetoothA2dp: Proxy object connected
08-25 16:36:10.581  3845  4155 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 16:36:10.582  1362  1362 D BluetoothInputDevice: Proxy object connected
08-25 16:36:10.583  1362  1362 D HidProfile: Bluetooth service connected
,08-25 16:36:10.583  3845  3858 D BluetoothPan: onBluetoothStateChange on: true
,08-25 16:36:10.584  1362  1373 D BluetoothMap: onBluetoothStateChange: up=true
08-25 16:36:10.585  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected,
08-25 16:36:10.586  1362  1362 D PanProfile: Bluetooth service connected
,08-25 16:36:10.586  3845  3855 D BluetoothMap: onBluetoothStateChange: up=true
08-25 16:36:10.587  1362  1362 D BluetoothMap: Proxy object connected
,08-25 16:36:10.587  1362  1362 D MapProfile: Bluetooth service connected
08-25 16:36:10.587  1362  1362 D BluetoothMap: getConnectedDevices()
,08-25 16:36:10.588  1362  1377 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 16:36:10.590   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-25 16:36:10.591  4160  4160 D BluetoothMapService: onReceive
,08-25 16:36:10.591  4160  4160 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 16:36:10.591  4160  4160 D BluetoothMapService: STATE_ON
08-25 16:36:10.589  3845  3845 D BluetoothA2dp: Proxy object connected
,08-25 16:36:10.592  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:36:10.595  3845  3845 D BluetoothInputDevice: Proxy object connected
,08-25 16:36:10.595  3845  3845 D HidProfile: Bluetooth service connected
,08-25 16:36:10.600  3845  3845 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 16:36:10.600  3845  3845 D PanProfile: Bluetooth service connected
,08-25 16:36:10.600  3845  3845 D BluetoothMap: Proxy object connected
08-25 16:36:10.600  3845  3845 D MapProfile: Bluetooth service connected
08-25 16:36:10.600  3845  3845 D BluetoothMap: getConnectedDevices()
,08-25 16:36:10.606  3845  3845 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 16:36:10.611  3845  3845 D DockEventReceiver: finishStartingService: stopping service
08-25 16:36:10.612  4160  4160 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 16:36:10.612  4160  4160 D ObexServerSockets0: prepareForNewConnect()
08-25 16:36:10.613  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 16:36:10.624  1362  1362 D BluetoothPbap: Proxy object connected
,08-25 16:36:10.625  1362  1362 D PbapServerProfile: Bluetooth service connected
08-25 16:36:10.625  3845  3845 D BluetoothPbap: Proxy object connected
08-25 16:36:10.625  3845  3845 D PbapServerProfile: Bluetooth service connected
,08-25 16:36:10.638  4160  4208 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 16:36:10.660  4160  4212 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 16:36:10.660  1926  2195 D BluetoothHeadset: Proxy object connected
,08-25 16:36:10.661  3845  3855 D BluetoothHeadset: Proxy object connected
08-25 16:36:10.661   872   872 D BluetoothHeadset: Proxy object connected
08-25 16:36:10.661   872   872 D BluetoothHeadset: Proxy object connected
08-25 16:36:10.661   872   872 D BluetoothHeadset: Proxy object connected
,08-25 16:36:10.661  4160  4212 I BtOppRfcommListener: Accept thread started.
08-25 16:36:10.662  3845  3845 D HeadsetProfile: Bluetooth service connected
08-25 16:36:10.662  1362  1373 D BluetoothHeadset: Proxy object connected
08-25 16:36:10.662  1362  1362 D HeadsetProfile: Bluetooth service connected
,08-25 16:36:10.673   872   889 D BluetoothHeadset: Proxy object connected
,08-25 16:36:10.673  3845  4157 D BluetoothHeadset: Proxy object connected
,08-25 16:36:10.674   872   889 D BluetoothHeadset: Proxy object connected
,08-25 16:36:10.674  3845  3845 D HeadsetProfile: Bluetooth service connected,
,08-25 16:36:10.678  1926  1938 D BluetoothHeadset: Proxy object connected,
,08-25 16:36:10.689  1362  2026 D BluetoothHeadset: Proxy object connected
08-25 16:36:10.689  1362  1362 D HeadsetProfile: Bluetooth service connected
,08-25 16:36:10.899  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:36:10.899  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:36:10.899  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:36:10.899  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 16:36:10.899  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:36:10.899  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:36:10.899  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:36:10.899  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 16:36:10.907  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 16:36:10.911  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 16:36:10.912  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d535ad added. We now have 8 listener(s)
,08-25 16:36:10.912  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 16:36:10.918   872  1979 D WifiService: setWifiEnabled: false pid=3777, uid=10000
08-25 16:36:10.918   872  1979 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 16:36:10.930  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:36:10.931   872  1983 D WifiService: setWifiEnabled: true pid=3777, uid=10000
08-25 16:36:10.931   872  1983 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 16:36:10.948   872  1303 D WifiConfigStore: Loading config and enabling all networks 
,08-25 16:36:10.959  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:36:10.959  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:36:10.959  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:36:10.959  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:36:10.959  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:36:10.959  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 16:36:10.959  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 16:36:10.959  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 16:36:10.964  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 16:36:10.976   872  1303 D WifiConfigStore: loaded 0 passpoint configs
,08-25 16:36:10.977   872  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-25 16:36:10.978   872  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-25 16:36:10.979   872  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 16:36:10.979   872  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-25 16:36:10.979   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-25 16:36:10.979   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 16:36:10.994   872  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.05 rxSuccessRate=0.06 delta 1000 -> 1000
,08-25 16:36:10.994   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-25 16:36:10.995   872  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-25 16:36:10.997   371   870 D CommandListener: Setting iface cfg
,08-25 16:36:11.003   872  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
,08-25 16:36:11.003   872  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 16:36:11.004   872  1303 E native  : do suspend true
,08-25 16:36:11.017   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-25 16:36:11.017   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 16:36:11.027   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 16:36:11.059   872  1302 D WifiNative-HAL: p2pGetDeviceAddress
,08-25 16:36:11.060   872  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 16:36:11.080   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 16:36:11.106  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 16:36:11.534  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 16:36:11.612  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 16:36:11.616  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 16:36:11.622   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 16:36:11.634   872  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 16:36:11.634   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 16:36:11.635   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 16:36:11.651   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 16:36:11.664   371   870 D CommandListener: Setting iface cfg
,08-25 16:36:11.667   872  1303 D WifiStateMachine: Start Dhcp Watchdog 3
,08-25 16:36:11.674   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 16:36:11.690   872  4220 D DhcpClient: Receive thread started
,08-25 16:36:11.772   872  1303 E native  : do suspend false
,08-25 16:36:11.783   872  1874 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 16:36:11.796   872  4220 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null,
08-25 16:36:11.797   872  1874 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-25 16:36:11.799   872  1874 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 16:36:11.812   872  4220 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 16:36:11.813   872  1874 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 16:36:11.817   371   870 D CommandListener: Setting iface cfg
,08-25 16:36:11.825   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-25 16:36:11.827   872  1303 E native  : do suspend true
08-25 16:36:11.827   872  1874 D DhcpClient: Scheduling renewal in 86399s
,08-25 16:36:11.845   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 16:36:11.847   872  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 16:36:11.848   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 16:36:11.853   872  1305 D ConnectivityService: Adding iface wlan0 to network 102
,08-25 16:36:11.859   872  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 16:36:11.921   872  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-25 16:36:11.921   872  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-25 16:36:11.922   872  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-25 16:36:11.923   872  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-25 16:36:11.924   872  1305 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-25 16:36:11.934   872  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-25 16:36:11.941   872  1305 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-25 16:36:11.941   872  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-25 16:36:11.941   872  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-25 16:36:11.941   872  1305 D ConnectivityService:    accepting network in place of null
08-25 16:36:11.943   872  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 16:36:11.944   872  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-25 16:36:11.945   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 16:36:11.953  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:36:11.953  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:36:11.953  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:36:11.953  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:36:11.953  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:36:11.953  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:36:11.953  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:36:11.953  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 16:36:11.956  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 16:36:11.959  3777  3827 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-25 16:36:11.959  3777  3827 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-25 16:36:11.961  3777  3827 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@189f61f Bundle[{}]
,08-25 16:36:11.961  3777  3827 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 16:36:11.961  3777  3827 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-25 16:36:11.962  3777  3827 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-25 16:36:11.962  3777  3827 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-25 16:36:11.963  3777  3827 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-25 16:36:11.963  3777  3827 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 16:36:11.969  3777  3827 I System.out: Running OutgoingSocketThread
,08-25 16:36:11.970  3777  4226 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 423)
,08-25 16:36:11.971  3777  4226 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46850
,08-25 16:36:11.971  3777  4226 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 16:36:11.979   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 16:36:12.011   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 16:36:12.019   872  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-25 16:36:12.020   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:36:12.021   872  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-25 16:36:12.024   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-25 16:36:12.048  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 16:36:12.048  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:36:12.048  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:36:12.048  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:36:12.048  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:36:12.048  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:36:12.048  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:36:12.048  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 16:36:12.052  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 16:36:12.054  1726  1726 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 16:36:12.061  1726  1726 D SystemUpdateService: onCreate
,08-25 16:36:12.065  1726  1726 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 16:36:12.084  1726  4230 I SystemUpdateService: active receiver: enabled
,08-25 16:36:12.087  1726  1726 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 16:36:12.089  1726  2411 I iu.UploadsManager: num queued entries: 0
,08-25 16:36:12.100  1726  1726 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 16:36:12.102  1726  1726 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 16:36:12.104  3966  3966 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 16:36:12.109  1726  4233 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-25 16:36:12.110  1726  4233 W BaseAppContext: Using Auth Proxy for data requests.
,08-25 16:36:12.111  3966  3966 D SprintDMHelper: simOperator: 
,08-25 16:36:12.111  3966  3966 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 16:36:12.127  1726  4233 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,08-25 16:36:12.129  1726  4230 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 16:36:12.147  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 16:36:12.130  1726  2411 I iu.UploadsManager: num updated entries: 0
08-25 16:36:12.151  1726  4230 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-25 16:36:12.152  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 16:36:12.152  1726  4230 I SystemUpdateService: now status is 0 (complete)
,08-25 16:36:12.152  1726  4230 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-25 16:36:12.152  1726  4230 I SystemUpdateService: file has been verified
,08-25 16:36:12.152  1726  4230 I SystemUpdateService: OTA package size = 12249756
08-25 16:36:12.152  1726  2411 I iu.SyncManager: NEXT; no task
,08-25 16:36:12.170  1726  4230 I SystemUpdateService: showing system update notification
,08-25 16:36:12.187  1519  2883 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-25 16:36:12.187  1519  2883 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-25 16:36:12.187  1519  2883 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 16:36:12.188  1519  2883 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 16:36:12.192  1726  1726 D SystemUpdateService: onDestroy
,08-25 16:36:12.202  1726  4233 E MDM     : [180] SitrepService.a: Error sending sitrep.
,08-25 16:36:12.777   872  4218 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155187, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 16:36:12.972  3777  3827 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 424)
,08-25 16:36:12.972  3777  3827 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 424)
,08-25 16:36:12.982  3777  3827 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 429)
,08-25 16:36:12.985  3777  3827 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-25 16:36:12.985  3777  3827 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-25 16:36:12.989  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 16:36:12.989  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f0c0e2 added. We now have 2 listener(s)
08-25 16:36:12.991  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 16:36:12.991  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:36:12.991  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:36:12.992  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:36:12.992  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f132c73 added. We now have 9 listener(s)
08-25 16:36:12.992  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 16:36:12.993  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 16:36:13.001  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 16:36:13.008  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:36:13.008  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:36:13.008  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:36:13.008  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:36:13.008  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:36:13.008  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:36:13.008  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:36:13.008  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 16:36:13.013  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 16:36:13.013  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 16:36:13.014  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 16:36:13.014  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23c7fa9 added. We now have 3 listener(s)
08-25 16:36:13.016  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 16:36:13.016  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:36:13.016  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:36:13.016  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 16:36:13.016  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85e092e added. We now have 10 listener(s)
08-25 16:36:13.017  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 16:36:13.017  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:36:13.017  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:36:13.017  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:36:13.017  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:36:13.017  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:36:13.017  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:36:13.017  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:36:13.017  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f0c0e2 removed from the list
08-25 16:36:13.017  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:36:13.018  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f132c73 removed from the list
08-25 16:36:13.019  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:36:13.019  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:36:13.019  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:36:13.020  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:36:13.020  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:36:13.020   872  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
08-25 16:36:13.022  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:36:13.022  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:36:13.022  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:36:13.022  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f132c73 not in the list
08-25 16:36:13.022  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:36:13.022  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:36:13.025  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:36:13.025  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:36:13.025  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:36:13.026  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85e092e removed from the list
08-25 16:36:13.026  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:36:13.026  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:36:13.026  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does ,not exist in the list - probably already removed
08-25 16:36:13.026  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:36:13.027  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:36:13.027  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23c7fa9 removed from the list
08-25 16:36:13.029  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 16:36:13.029  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6a1ccf added. We now have 2 listener(s)
08-25 16:36:13.035  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 16:36:13.035  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:36:13.036  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:36:13.036  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:36:13.037  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0f865c added. We now have 9 listener(s)
,08-25 16:36:13.037  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 16:36:13.038  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 16:36:13.043  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 16:36:13.050  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:36:13.050  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:36:13.050  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:36:13.050  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:36:13.050  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:36:13.050  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:36:13.050  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:36:13.050  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 16:36:13.055  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 16:36:13.055  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 16:36:13.056  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 16:36:13.056  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6458a3a added. We now have 3 listener(s)
,08-25 16:36:13.058  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 16:36:13.058  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:36:13.058  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:36:13.058  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:36:13.059  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e95b6eb added. We now have 10 listener(s)
08-25 16:36:13.059  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:36:13.059  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 16:36:13.059  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 16:36:13.059  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 16:36:13.059  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 16:36:13.060  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 16:36:13.061  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:36:13.066  3777  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 16:36:13.066  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 16:36:13.068  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:36:13.076  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 16:36:13.078  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 16:36:13.078  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 16:36:13.087  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 16:36:13.087  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 16:36:13.088  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 16:36:13.090  3777  3827 D BluetoothAdapter: STATE_ON
,08-25 16:36:13.097  4160  4204 D BtGatt.GattService: registerClient() - UUID=fbffe334-4257-4d8d-af3c-f2243c1fe500
,08-25 16:36:13.099  4160  4179 D BtGatt.GattService: onClientRegistered() - UUID=fbffe334-4257-4d8d-af3c-f2243c1fe500, clientIf=5
,08-25 16:36:13.099  3777  3788 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 16:36:13.102  4160  4180 D BtGatt.GattService: start scan with filters
,08-25 16:36:13.109  4160  4185 D BtGatt.ScanManager: handling starting scan
,08-25 16:36:13.109  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 16:36:13.110  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 16:36:13.110  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 16:36:13.110  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 16:36:13.114  4160  4185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23110c3
,08-25 16:36:13.119  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 16:36:13.120  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 16:36:13.120  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 16:36:13.120  4160  4179 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 16:36:13.120  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:36:13.121  4160  4185 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 16:36:13.125  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 16:36:13.134  3777  3827 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 16:36:13.134  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 16:36:13.134  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 16:36:13.134  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:36:13.135  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 16:36:13.135  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 16:36:13.135  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 16:36:13.135  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 16:36:13.135  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 16:36:13.135  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 16:36:13.135  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 16:36:13.136  3777  3827 D BluetoothAdapter: STATE_ON
08-25 16:36:13.137  4160  4204 D BtGatt.GattService: stopScan() - queue size =1
08-25 16:36:13.138  4160  4179 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 16:36:13.138  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:36:13.139  4160  4185 D BtGatt.ScanManager: Starting BLE batch scan
08-25 16:36:13.139  4160  4185 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 16:36:13.139  4160  4180 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 16:36:13.140  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:36:13.140  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 16:36:13.140  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 16:36:13.140  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
,08-25 16:36:13.140  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 16:36:13.141  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 16:36:13.141  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 16:36:13.141  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 16:36:13.142  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 16:36:13.142  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 16:36:13.143  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 16:36:13.143  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 16:36:13.143  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 16:36:13.147  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 16:36:13.147  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-25 16:36:13.147  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:36:13.148  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:36:13.148  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:36:13.148  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:36:13.148  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:36:13.148  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6a1ccf removed from the list
,08-25 16:36:13.148  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:36:13.148  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0f865c removed from the list
08-25 16:36:13.148  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:36:13.148  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:36:13.149  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:36:13.149  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:36:13.150  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-25 16:36:13.150  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:36:13.150  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 16:36:13.150  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0f865c not in the list
,08-25 16:36:13.150  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:36:13.150  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:36:13.151  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 16:36:13.151  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:36:13.151  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:36:13.152  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e95b6eb removed from the list
,08-25 16:36:13.152  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:36:13.152  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:36:13.152  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:36:13.152  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:36:13.152  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6458a3a removed from the list
08-25 16:36:13.152  4160  4179 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 16:36:13.152  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:36:13.153  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 16:36:13.153  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@796d6c7 added. We now have 2 listener(s)
08-25 16:36:13.157  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 16:36:13.157  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:36:13.157  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:36:13.157  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 16:36:13.157  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@59444f4 added. We now have 9 listener(s)
08-25 16:36:13.157  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 16:36:13.158  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 16:36:13.161  4160  4179 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 16:36:13.161  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:36:13.162  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 16:36:13.166  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:36:13.166  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:36:13.166  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:36:13.166  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:36:13.166  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:36:13.166  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:36:13.166  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:36:13.166  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 16:36:13.169  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 16:36:13.169  4160  4179 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 16:36:13.169  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:36:13.169  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 16:36:13.169  4160  4185 D BtGatt.ScanManager: stopping BLe Batch
,08-25 16:36:13.170  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 16:36:13.171  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98f2692 added. We now have 3 listener(s)
,08-25 16:36:13.172  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 16:36:13.172  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:36:13.172  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 16:36:13.173  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 16:36:13.173  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 16:36:13.174  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a01863 added. We now have 10 listener(s)
,08-25 16:36:13.174  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 16:36:13.174  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 16:36:13.175  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 16:36:13.175  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 16:36:13.175  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 16:36:13.175  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 16:36:13.175  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 16:36:13.175  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:36:13.177  4160  4179 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 16:36:13.177  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:36:13.177  4160  4185 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 16:36:13.178  3777  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 16:36:13.178  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
08-25 16:36:13.181  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 16:36:13.182  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 16:36:13.182  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
08-25 16:36:13.182  4160  4179 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 16:36:13.182  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:36:13.185  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 16:36:13.185  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 16:36:13.185  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 16:36:13.185  3777  3827 D BluetoothAdapter: STATE_ON
08-25 16:36:13.187  4160  4204 D BtGatt.GattService: registerClient() - UUID=a29f884f-0597-4b40-bddf-5f88fb1e65e8
08-25 16:36:13.187  4160  4179 D BtGatt.GattService: onClientRegistered() - UUID=a29f884f-0597-4b40-bddf-5f88fb1e65e8, clientIf=5
,08-25 16:36:13.187  3777  3788 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 16:36:13.188  4160  4201 D BtGatt.GattService: start scan with filters
08-25 16:36:13.190  4160  4185 D BtGatt.ScanManager: handling starting scan
08-25 16:36:13.190  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 16:36:13.190  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 16:36:13.190  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 16:36:13.190  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-25 16:36:13.195  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 16:36:13.195  4160  4179 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
08-25 16:36:13.195  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 16:36:13.195  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:36:13.195  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 16:36:13.195  4160  4185 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 16:36:13.196  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 16:36:13.198  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 16:36:13.198  3777  3827 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-25 16:36:13.198  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:36:13.198  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 16:36:13.198  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:36:13.198  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:36:13.199  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 16:36:13.199  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 16:36:13.199  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:36:13.199  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@796d6c7 removed from the list
08-25 16:36:13.199  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:36:13.199  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@59444f4 removed from the list
08-25 16:36:13.199  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 16:36:13.199  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:36:13.199  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 16:36:13.199  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 16:36:13.199  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:36:13.199  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 16:36:13.200  4160  4179 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 16:36:13.200  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:36:13.200  4160  4185 D BtGatt.ScanManager: Starting BLE batch scan
08-25 16:36:13.200  4160  4185 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 16:36:13.201  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:36:13.201  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:36:13.201  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-25 16:36:13.201  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@59444f4 not in the list
08-25 16:36:13.201  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 16:36:13.201  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 16:36:13.201  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 16:36:13.201  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 16:36:13.201  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 16:36:13.201  3777  3827 D BluetoothAdapter: STATE_ON
08-25 16:36:13.202  4160  4171 D BtGatt.GattService: stopScan() - queue size =1
,08-25 16:36:13.202  4160  4170 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 16:36:13.202  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:36:13.202  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 16:36:13.203  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 16:36:13.203  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 16:36:13.203  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 16:36:13.203  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 16:36:13.203  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 16:36:13.203  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 16:36:13.204  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 16:36:13.204  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:36:13.205  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:36:13.205  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:36:13.205  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:36:13.205  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a01863 removed from the list
08-25 16:36:13.205  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 16:36:13.205  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:36:13.205  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 16:36:13.205  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:36:13.205  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:36:13.205  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:36:13.205  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98f2692 removed from the list
08-25 16:36:13.205  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 16:36:13.206  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 16:36:13.206  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f71d7bf added. We now have 2 listener(s)
08-25 16:36:13.207  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 16:36:13.207  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:36:13.207  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:36:13.208  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 16:36:13.208  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fef3e8c added. We now have 9 listener(s),
08-25 16:36:13.208  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:36:13.209  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 16:36:13.209  4160  4179 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 16:36:13.210  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:36:13.211  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 16:36:13.214  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-25 16:36:13.214  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:36:13.214  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:36:13.214  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:36:13.214  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:36:13.214  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:36:13.214  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:36:13.214  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
08-25 16:36:13.215  4160  4179 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 16:36:13.215  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:36:13.215  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 16:36:13.215  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 16:36:13.215  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 16:36:13.216  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@534f5ea added. We now have 3 listener(s)
08-25 16:36:13.217  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 16:36:13.217  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:36:13.217  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:36:13.217  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 16:36:13.217  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77630db added. We now have 10 listener(s)
08-25 16:36:13.217  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:36:13.217  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 16:36:13.217  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 16:36:13.217  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:36:13.217  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 16:36:13.217  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 16:36:13.217  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 16:36:13.219  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 16:36:13.220  3777  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 16:36:13.220  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 16:36:13.221  4160  4179 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 16:36:13.221  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:36:13.221  4160  4185 D BtGatt.ScanManager: stopping BLe Batch
08-25 16:36:13.223  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 16:36:13.223  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 16:36:13.223  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 16:36:13.226  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 16:36:13.226  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
08-25 16:36:13.226  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 16:36:13.226  4160  4179 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 16:36:13.226  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:36:13.227  4160  4185 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 16:36:13.227  3777  3827 D BluetoothAdapter: STATE_ON
,08-25 16:36:13.229  4160  4204 D BtGatt.GattService: registerClient() - UUID=10ac3e50-ff63-4422-9880-2972356762ae
,08-25 16:36:13.229  4160  4179 D BtGatt.GattService: onClientRegistered() - UUID=10ac3e50-ff63-4422-9880-2972356762ae, clientIf=5
08-25 16:36:13.229  3777  3789 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 16:36:13.229  4160  4180 D BtGatt.GattService: start scan with filters
,08-25 16:36:13.231  4160  4179 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 16:36:13.231  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:36:13.233  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 16:36:13.233  4160  4185 D BtGatt.ScanManager: handling starting scan
,08-25 16:36:13.233  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 16:36:13.233  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 16:36:13.233  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 16:36:13.235  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 16:36:13.235  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 16:36:13.235  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 16:36:13.236  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 16:36:13.238  4160  4179 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 16:36:13.238  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:36:13.238  4160  4185 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 16:36:13.239  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 16:36:13.239  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 16:36:13.239  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 16:36:13.239  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:36:13.240  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:36:13.240  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 16:36:13.240  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 16:36:13.240  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f71d7bf removed from the list
08-25 16:36:13.240  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:36:13.240  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fef3e8c removed from the list
08-25 16:36:13.240  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:36:13.240  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 16:36:13.240  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 16:36:13.240  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-25 16:36:13.240  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 16:36:13.240  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 16:36:13.241  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 16:36:13.241  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:36:13.241  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:36:13.241  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fef3e8c not in the list
,08-25 16:36:13.241  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 16:36:13.241  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 16:36:13.241  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 16:36:13.241  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 16:36:13.241  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 16:36:13.242  3777  3827 D BluetoothAdapter: STATE_ON
,08-25 16:36:13.242  4160  4171 D BtGatt.GattService: stopScan() - queue size =1
08-25 16:36:13.243  4160  4204 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 16:36:13.243  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 16:36:13.243  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 16:36:13.243  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 16:36:13.243  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 16:36:13.243  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 16:36:13.243  4160  4179 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 16:36:13.243  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:36:13.243  4160  4185 D BtGatt.ScanManager: Starting BLE batch scan
08-25 16:36:13.243  4160  4185 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 16:36:13.244  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 16:36:13.244  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 16:36:13.244  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 16:36:13.244  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 16:36:13.244  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:36:13.245  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 16:36:13.245  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:36:13.245  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:36:13.245  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 16:36:13.245  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77630db removed from the list
08-25 16:36:13.245  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:36:13.245  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:36:13.245  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 16:36:13.245  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:36:13.245  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:36:13.245  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 16:36:13.245  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@534f5ea removed from the list
08-25 16:36:13.246  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 16:36:13.246  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69cffb7 added. We now have 2 listener(s)
,08-25 16:36:13.247  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 16:36:13.247  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 16:36:13.247  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 16:36:13.247  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 16:36:13.247  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54cd324 added. We now have 9 listener(s)
08-25 16:36:13.247  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 16:36:13.247  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 16:36:13.250  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 16:36:13.253  4160  4179 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 16:36:13.253  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:36:13.259  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 16:36:13.259  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 16:36:13.259  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 16:36:13.259  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 16:36:13.259  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 16:36:13.259  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 16:36:13.259  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 16:36:13.259  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 16:36:13.260  4160  4179 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 16:36:13.260  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:36:13.260  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 16:36:13.261  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 16:36:13.261  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 16:36:13.261  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2a5842 added. We now have 3 listener(s)
,08-25 16:36:13.263  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:36:13.263  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 16:36:13.263  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 16:36:13.264  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 16:36:13.264  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 16:36:13.264  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f7e053 added. We now have 10 listener(s)
,08-25 16:36:13.264  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 16:36:13.265  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-25 16:36:13.265  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 16:36:13.265  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 16:36:13.265  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 16:36:13.265  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 16:36:13.265  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 16:36:13.265  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 16:36:13.265  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69cffb7 removed from the list
,08-25 16:36:13.266  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 16:36:13.265  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:36:13.266  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54cd324 removed from the list
08-25 16:36:13.266  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
08-25 16:36:13.266  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 16:36:13.267  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 16:36:13.267  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:36:13.267  4160  4179 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 16:36:13.267  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 16:36:13.267  4160  4185 D BtGatt.ScanManager: stopping BLe Batch
08-25 16:36:13.268  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:36:13.268  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 16:36:13.268  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:36:13.268  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54cd324 not in the list
08-25 16:36:13.268  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 16:36:13.268  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:36:13.269  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 16:36:13.269  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 16:36:13.269  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 16:36:13.269  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f7e053 removed from the list
08-25 16:36:13.269  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 16:36:13.269  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 16:36:13.269  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 16:36:13.269  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 16:36:13.269  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2a5842 removed from the list
08-25 16:36:13.270  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 16:36:13.270  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-25 16:36:13.271  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 16:36:13.271  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 16:36:13.271  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 16:36:13.271  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 16:36:13.273  4160  4179 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 16:36:13.273  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:36:13.273  4160  4185 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 16:36:13.276  3777  4240 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: My test thread name)
08-25 16:36:13.277  3777  4240 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 437, thread name: My test thread name)
,08-25 16:36:13.277  3777  4240 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 437, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 16:36:13.278  4160  4179 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 16:36:13.278  4160  4179 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 16:36:13.279  3777  4241 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: My test thread name)
08-25 16:36:13.279  3777  4241 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: My test thread name)
,08-25 16:36:13.279  3777  4241 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 16:36:13.281  3777  3827 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-25 16:36:13.281  3777  3827 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-25 16:36:13.281  3777  3827 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-25 16:36:13.281  3777  3827 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-25 16:36:13.281  3777  3827 D com.test.thalitest.ThaliTestRunner: Total duration: 22913 ms
08-25 16:36:13.282  3777  3827 I jxcore-log: Total number of executed tests:  80
08-25 16:36:13.282  3777  3827 I jxcore-log: 
,08-25 16:36:13.283  3777  3827 I jxcore-log: Number of passed tests:  80
08-25 16:36:13.283  3777  3827 I jxcore-log: 
08-25 16:36:13.283  3777  3827 I jxcore-log: Number of failed tests:  0
08-25 16:36:13.283  3777  3827 I jxcore-log: 
,08-25 16:36:13.283  3777  3827 I jxcore-log: Number of ignored tests:  0
08-25 16:36:13.283  3777  3827 I jxcore-log: 
08-25 16:36:13.283  3777  3827 I jxcore-log: Total duration:  22913
08-25 16:36:13.283  3777  3827 I jxcore-log: 
,08-25 16:36:13.284  3777  3827 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 16:36:13.284  3777  3827 I jxcore-log: 
,08-25 16:36:13.290  3777  3777 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-25 16:36:13.291  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:36:13.291  3777  3827 I jxcore-log: 
08-25 16:36:13.293  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:36:13.293  3777  3827 I jxcore-log: 
08-25 16:36:13.294  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:36:13.294  3777  3827 I jxcore-log: 
08-25 16:36:13.295  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:36:13.295  3777  3827 I jxcore-log: 
08-25 16:36:13.296  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:36:13.296  3777  3827 I jxcore-log: 
08-25 16:36:13.297  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:36:13.297  3777  3827 I jxcore-log: 
08-25 16:36:13.299  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:36:13.299  3777  3827 I jxcore-log: 
08-25 16:36:13.301  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 16:36:13.301  3777  3827 I jxcore-log: 
08-25 16:36:13.301  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 16:36:13.301  3777  3827 I jxcore-log: 
08-25 16:36:13.302  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 16:36:13.302  3777  3827 I jxcore-log: 
08-25 16:36:13.303  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 16:36:13.303  3777  3827 I jxcore-log: 
,08-25 16:36:13.303  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 16:36:13.303  3777  3827 I jxcore-log: 
,08-25 16:36:13.304  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:36:13.304  3777  3827 I jxcore-log: 
08-25 16:36:13.304  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:36:13.304  3777  3827 I jxcore-log: 
,08-25 16:36:13.305  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 16:36:13.305  3777  3827 I jxcore-log: 
08-25 16:36:13.305  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 16:36:13.305  3777  3827 I jxcore-log: 
,08-25 16:36:13.306  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 16:36:13.306  3777  3827 I jxcore-log: 
,08-25 16:36:13.307  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 16:36:13.307  3777  3827 I jxcore-log: 
08-25 16:36:13.307  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 16:36:13.307  3777  3827 I jxcore-log: 
,08-25 16:36:13.308  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 16:36:13.308  3777  3827 I jxcore-log: 
,08-25 16:36:13.308  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 16:36:13.308  3777  3827 I jxcore-log: 
08-25 16:36:13.309  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 16:36:13.309  3777  3827 I jxcore-log: 
,08-25 16:36:13.309  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 16:36:13.309  3777  3827 I jxcore-log: 
08-25 16:36:13.310  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:36:13.310  3777  3827 I jxcore-log: 
,08-25 16:36:13.310  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:36:13.310  3777  3827 I jxcore-log: 
,08-25 16:36:13.311  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:36:13.311  3777  3827 I jxcore-log: 
,08-25 16:36:13.311  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:36:13.311  3777  3827 I jxcore-log: 
08-25 16:36:13.312  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:36:13.312  3777  3827 I jxcore-log: 
,08-25 16:36:13.312  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:36:13.312  3777  3827 I jxcore-log: 
08-25 16:36:13.313  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 16:36:13.313  3777  3827 I jxcore-log: 
,08-25 16:36:13.644  3777  3777 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 16:36:13.645  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 16:36:13.645  3777  3827 I jxcore-log: 
,08-25 16:36:13.706  3777  3777 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 16:36:13.707  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 16:36:13.707  3777  3827 I jxcore-log: 
,08-25 16:36:13.745  3777  3777 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 16:36:13.747  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 16:36:13.747  3777  3827 I jxcore-log: 
,08-25 16:36:13.942  4242  4242 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-25 16:36:13.944   872  4217 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-25 16:36:13.947  4242  4242 D AndroidRuntime: CheckJNI is OFF
,08-25 16:36:13.989  4242  4242 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-25 16:36:14.037  4242  4242 I Radio-JNI: register_android_hardware_Radio DONE
,08-25 16:36:14.061  4242  4242 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-25 16:36:14.072   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-25 16:36:14.072   872   885 I ActivityManager: Killing 3777:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-25 16:36:14.188   872   895 W PackageSettings: Skipping PackageSetting{23ee624 com.example.hello/10273} due to missing metadata
,08-25 16:36:14.192   872  3093 D GraphicsStats: Buffer count: 2
08-25 16:36:14.192   872  1691 I WindowState: WIN DEATH: Window{cbeddf3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-25 16:36:14.193   872  1304 D WifiService: Client connection lost with reason: 4
,08-25 16:36:14.228   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-25 16:36:14.228   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-25 16:36:14.229   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-25 16:36:14.229   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-25 16:36:14.229   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-25 16:36:14.229   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-25 16:36:14.229   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-25 16:36:14.229   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-25 16:36:14.229   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-25 16:36:14.229   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-25 16:36:14.229   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-25 16:36:14.229   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-25 16:36:14.229   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-25 16:36:14.229   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-25 16:36:14.229   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-25 16:36:14.229   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-25 16:36:14.229   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-25 16:36:14.229   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-25 16:36:14.229   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:36:14.229   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:36:14.229   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 16:36:14.229   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-25 16:36:14.230   872   885 I ActivityManager:   Force finishing activity ActivityRecord{c6b7638 u0 com.test.thalitest/.MainActivity t2}
,08-25 16:36:14.230   872   895 I art     : Starting a blocking GC Explicit
,08-25 16:36:14.233  2113  2633 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-25 16:36:14.245   872  3093 W ActivityManager: Spurious death for ProcessRecord{be30e8d 0:com.test.thalitest/u0a0}, curProc for 3777: null
,08-25 16:36:14.272   872   895 I art     : Explicit concurrent mark sweep GC freed 13660(955KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 788us total 40.333ms
,08-25 16:36:14.293  3924  4235 I Babel   : connection state changed from DISCONNECTED to CONNECTED
08-25 16:36:14.298   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-25 16:36:14.302  4242  4242 I art     : System.exit called, status: 0
08-25 16:36:14.302  4242  4242 I AndroidRuntime: VM exiting with result code 0.
,08-25 16:36:14.309   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-25 16:36:14.328   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-25 16:36:14.342   872  1295 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-25 16:36:14.346  1854  1854 I Keyboard.Facilitator: resetDictionaries() : en_US
08-25 16:36:14.349  4160  4160 D BluetoothMapAppObserver: onReceive
,08-25 16:36:14.349  4160  4160 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-25 16:36:14.350  1854  4256 I Keyboard.Facilitator.DecoderInitializer: run()
,08-25 16:36:14.352  1854  4256 I Decoder : createOrResetDecoder
08-25 16:36:14.360  2113  2274 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-25 16:36:14.370  3614  3614 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-25 16:36:14.386   872  1945 I ActivityManager: Start proc 4258:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-25 16:36:14.411  1926  1926 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-25 16:36:14.420  1519  1519 I ConfigService: onCreate
,08-25 16:36:14.423  1519  4270 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-25 16:36:14.423  1519  4270 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 16:36:14.423  1519  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 16:36:14.423  1519  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 16:36:14.423  1519  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 16:36:14.423  1519  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 16:36:14.423  1519  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 16:36:14.423  1519  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 16:36:14.423  1519  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 16:36:14.423  1519  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 16:36:14.423  1519  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 16:36:14.423  1519  4270 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 16:36:14.423  1519  4270 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 16:36:14.423  1519  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 16:36:14.423  1519  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 16:36:14.423  1519  4270 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-25 16:36:14.423  1519  4270 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-25 16:36:14.423  1519  4270 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):,
08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-25 16:36:14.424  1519  4270 E SQLiteOpenHelper: 	,at java.lang.Thread.run(Thread.java:818)
,08-25 16:36:14.426  1519  4270 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-25 16:36:14.426   872  1301 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-25 16:36:14.440  1854  4256 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-25 16:36:14.443   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-25 16:36:14.446  4258  4258 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-25 16:36:14.464   872  1691 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3777 uid 10000
,08-25 16:36:14.465  1854  1854 I Keyboard.Facilitator: onFinishInput()
,08-25 16:36:14.477  1854  4256 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-25 16:36:14.479  1854  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-25 16:36:14.479  1854  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-25 16:36:14.482  1854  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-25 16:36:14.482  1854  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-25 16:36:14.482  1854  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-25 16:36:14.482  1854  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-25 16:36:14.483  1854  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-25 16:36:14.483  1854  4256 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-25 16:36:14.483  1854  4256 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-25 16:36:14.483  1854  4256 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-25 16:36:14.483  1854  4256 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-25 16:36:14.483  1854  4256 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-25 16:36:14.492   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-25 16:36:14.492   872   884 E PackageManager: Failed to write settings, restoring backup
08-25 16:36:14.492   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-25 16:36:14.492   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-25 16:36:14.492   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-25 16:36:14.492   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-25 16:36:14.492   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-25 16:36:14.492   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:36:14.492   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:36:14.492   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 16:36:14.498   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-25 16:36:14.498   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-25 16:36:14.498   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 16:36:14.498   872   885 E DropBoxManagerService: 	... 13 more
,08-25 16:36:14.502  1940  2020 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-25 16:36:14.514   872   882 I ActivityManager: Start proc 4275:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-25 16:36:14.515  1940  2020 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-25 16:36:14.515  1940  2020 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1940
08-25 16:36:14.515  1940  2020 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 16:36:14.515  1940  2020 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 16:36:14.515  1940  2020 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-25 16:36:14.515  1940  2020 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-25 16:36:14.515  1940  2020 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 16:36:14.515  1940  2020 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-25 16:36:14.515  1940  2020 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-25 16:36:14.515  1940  2020 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-25 16:36:14.515  1940  2020 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 16:36:14.515  1940  2020 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 16:36:14.515  1940  2020 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:36:14.515  1940  2020 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 16:36:14.517  4258  4258 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-25 16:36:14.520   872  1979 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 16:36:14.523   872  4280 E DropBoxManagerService: Can't write: system_app_crash
08-25 16:36:14.523   872  4280 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-25 16:36:14.523   872  4280 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 16:36:14.523   872  4280 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 16:36:14.523   872  4280 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 16:36:14.523   872  4280 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 16:36:14.523   872  4280 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 16:36:14.523   872  4280 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 16:36:14.523   872  4280 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 16:36:14.523   872  4280 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 16:36:14.523   872  4280 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 16:36:14.523   872  4280 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 16:36:14.523   872  4280 E DropBoxManagerService: 	... 5 more
,08-25 16:36:14.529  1940  2020 I Process : Sending signal. PID: 1940 SIG: 9
,08-25 16:36:14.544   872  1988 I ActivityManager: Start proc 4288:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-25 16:36:14.550  4258  4272 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:36:14.550  4258  4272 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:36:14.550  4258  4272 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 16:36:14.567  4258  4290 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-25 16:36:14.596  4288  4288 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-25 16:36:14.618  1519  1519 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-25 16:36:14.618  1519  1519 D AndroidRuntime: Shutting down VM
,08-25 16:36:14.619  1519  1519 E AndroidRuntime: FATAL EXCEPTION: main
08-25 16:36:14.619  1519  1519 E AndroidRuntime: Process: com.google.process.gapps, PID: 1519
08-25 16:36:14.619  1519  1519 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-25 16:36:14.619  1519  1519 E AndroidRuntime: 	... 8 more
,08-25 16:36:14.626  1519  1519 I Process : Sending signal. PID: 1519 SIG: 9
,08-25 16:36:14.628   872  4304 E DropBoxManagerService: Can't write: system_app_crash
08-25 16:36:14.628   872  4304 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-25 16:36:14.628   872  4304 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 16:36:14.628   872  4304 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 16:36:14.628   872  4304 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 16:36:14.628   872  4304 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 16:36:14.628   872  4304 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 16:36:14.628   872  4304 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 16:36:14.628   872  4304 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 16:36:14.628   872  4304 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 16:36:14.628   872  4304 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 16:36:14.628   872  4304 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 16:36:14.628   872  4304 E DropBoxManagerService: 	... 5 more
,08-25 16:36:14.644   872  1984 I WindowState: WIN DEATH: Window{cfb6cb1 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-25 16:36:14.644   872  3093 D GraphicsStats: Buffer count: 1
,08-25 16:36:14.655   872  1945 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1940) has died
,08-25 16:36:14.656   872  1945 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-25 16:36:14.657   872  1945 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-25 16:36:14.669   872  1304 D WifiService: Client connection lost with reason: 4
,08-25 16:36:14.681   872   885 I ActivityManager: Start proc 4308:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 16:36:14.681   872  1979 I ActivityManager: Process com.google.process.gapps (pid 1519) has died
,08-25 16:36:14.682   872  1979 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
08-25 16:36:14.682   872  1979 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 10999ms
,08-25 16:36:14.682   872  1979 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
,08-25 16:36:14.682   872  1979 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 30999ms
,08-25 16:36:14.685   872  4217 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 14:36:14 GMT], X-Android-Received-Millis=[1472135774685], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472135774292]}
,08-25 16:36:14.686   872  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-25 16:36:14.686   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-25 16:36:14.686   872  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 16:36:14.687   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 16:36:14.700  1726  1726 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-25 16:36:14.707   872  1982 I ActivityManager: Start proc 4321:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-25 16:36:14.724  4258  4272 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-25 16:36:14.731  4258  4290 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:36:14.731  4258  4290 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 16:36:14.732  4258  4290 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-25 16:36:14.732  4258  4290 E AndroidRuntime: Process: android.process.acore, PID: 4258
08-25 16:36:14.732  4258  4290 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:36:14.732  4258  4290 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 16:36:14.734   872  4335 E DropBoxManagerService: Can't write: system_app_crash
08-25 16:36:14.734   872  4335 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-25 16:36:14.734   872  4335 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 16:36:14.734   872  4335 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 16:36:14.734   872  4335 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 16:36:14.734   872  4335 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 16:36:14.734   872  4335 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 16:36:14.734   872  4335 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 16:36:14.734   872  4335 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 16:36:14.734   872  4335 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 16:36:14.734   872  4335 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 16:36:14.734   872  4335 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 16:36:14.734   872  4335 E DropBoxManagerService: 	... 5 more
,08-25 16:36:14.734  4258  4290 I Process : Sending signal. PID: 4258 SIG: 9
,08-25 16:36:14.737  1726  1726 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-25 16:36:14.737  1726  1726 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-25 16:36:14.743  1726  1726 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-25 16:36:14.743  4321  4321 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-25 16:36:14.743  1726  1726 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-25 16:36:14.745  4308  4308 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 16:36:14.745  4308  4308 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 16:36:14.745  4308  4308 D AndroidRuntime: Shutting down VM
08-25 16:36:14.747  4321  4321 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-25 16:36:14.750  4321  4321 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 16:36:14.750  4321  4321 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 16:36:14.751  4321  4321 D AndroidRuntime: Shutting down VM
08-25 16:36:14.751  4308  4308 E AndroidRuntime: FATAL EXCEPTION: main
08-25 16:36:14.751  4308  4308 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4308
08-25 16:36:14.751  4308  4308 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 16:36:14.751  4308  4308 E Andr,oidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 16:36:14.751  4308  4308 E AndroidRuntime: 	... 10 more
08-25 16:36:14.753   872  1988 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-25 16:36:14.753  1726  4337 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-25 16:36:14.753  4308  4308 I Process : Sending signal. PID: 4308 SIG: 9
08-25 16:36:14.754  4321  4321 E AndroidRuntime: FATAL EXCEPTION: main
08-25 16:36:14.754  4321  4321 E AndroidRuntime: Process: com.google.process.gapps, PID: 4321
08-25 16:36:14.754  4321  4321 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 16:36:14.754  4321  4321 E A,ndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 16:36:14.754  4321  4321 E AndroidRuntime: 	... 10 more
08-25 16:36:14.758   872  4338 E DropBoxManagerService: Can't write: system_app_crash
08-25 16:36:14.758   872  4338 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-25 16:36:14.758   872  4338 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 16:36:14.758   872  4338 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 16:36:14.758   872  4338 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 16:36:14.758   872  4338 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 16:36:14.758   872  4338 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 16:36:14.758   872  4338 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 16:36:14.758   872  4338 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 16:36:14.758   872  4338 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 16:36:14.758   872  4338 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 16:36:14.758   872  4338 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 16:36:14.758   872  4338 E DropBoxManagerService: 	... 5 more
08-25 16:36:14.761  4321  4321 I Process : Sending signal. PID: 4321 SIG: 9
08-25 16:36:14.764   872  4340 E DropBoxManagerService: Can't write: system_app_crash
08-25 16:36:14.764   872  4340 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-25 16:36:14.764   872  4340 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 16:36:14.764   872  4340 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 16:36:14.764   872  4340 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 16:36:14.764   872  4340 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 16:36:14.764   872  4340 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 16:36:14.764   872  4340 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 16:36:14.764   872  4340 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 16:36:14.764   872  4340 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 16:36:14.764   872  4340 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 16:36:14.764   872  4340 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 16:36:14.764   872  4340 E DropBoxManagerService: 	... 5 more
08-25 16:36:14.766   278   278 E lowmemorykiller: Error writing /proc/4258/oom_score_adj; errno=22
08-25 16:36:14.767   278   278 E lowmemorykiller: Error writing /proc/4258/oom_score_adj; errno=22
08-25 16:36:14.768  1726  4337 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-25 16:36:14.768  1726  4337 E AndroidRuntime: Process: com.google.android.gms, PID: 1726
08-25 16:36:14.768  1726  4337 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 16:36:14.768  1726  4337 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-25 16:36:14.768  2002  4336 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-25 16:36:14.770  1726  4337 I Process : Sending signal. PID: 1726 SIG: 9
08-25 16:36:14.770   872  4341 E DropBoxManagerService: Can't write: system_app_crash
08-25 16:36:14.770   872  4341 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-25 16:36:14.770   872  4341 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 16:36:14.770   872  4341 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 16:36:14.770   872  4341 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 16:36:14.770   872  4341 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 16:36:14.770   872  4341 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 16:36:14.770   872  4341 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 16:36:14.770   872  4341 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 16:36:14.770   872  4341 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 16:36:14.770   872  4341 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 16:36:14.770   872  4341 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 16:36:14.770   872  4341 E DropBoxManagerService: 	... 5 more

```
