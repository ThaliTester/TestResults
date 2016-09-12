#### Test 84265062d118465_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
09-12 18:13:35.207   873  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
09-12 18:13:35.907  3824  3824 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 18:13:35.913  3824  3824 D AndroidRuntime: CheckJNI is OFF
09-12 18:13:35.956  3824  3824 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 18:13:36.035  3824  3824 I Radio-JNI: register_android_hardware_Radio DONE
09-12 18:13:36.060  3824  3824 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-12 18:13:36.062   873  1996 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-12 18:13:36.077  2032  2393 W SearchService: Abort, client detached.
09-12 18:13:36.081  2032  2340 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d91696f
09-12 18:13:36.080  2032  2032 I HotwordDetector: Closing mic
09-12 18:13:36.082  2032  2351 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-12 18:13:36.085  3824  3824 D AndroidRuntime: Shutting down VM
09-12 18:13:36.112   873   883 I ActivityManager: Start proc 3833:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-12 18:13:36.130   375  2353 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-12 18:13:36.131   375  2353 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-12 18:13:36.134   375  1281 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-12 18:13:36.136  2032  2350 I MicroRecognitionRnrImpl: Detection finished
09-12 18:13:36.136  2032  2344 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-12 18:13:36.142  1559  1559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 18:13:36.156  1559  1559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 18:13:36.157  1559  1559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 18:13:36.178  1559  3350 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 18:13:36.179  1559  3350 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 18:13:36.179  1559  3350 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:13:36.179  1559  3350 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 18:13:36.192  3566  3566 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 18:13:36.192  3566  3566 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 18:13:36.192  3566  3566 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-12 18:13:36.205  3833  3833 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-12 18:13:36.229  3833  3833 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-12 18:13:36.235  3833  3833 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9068-9070)
09-12 18:13:36.235  3833  3833 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 18:13:36.246  3833  3833 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9b44ad9}
09-12 18:13:36.247  3833  3833 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 18:13:36.247  3833  3833 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 18:13:36.252  3833  3833 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-12 18:13:36.253  3833  3833 E SysUtils: ApplicationContext is null in ApplicationStatus
09-12 18:13:36.263  3833  3833 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-12 18:13:36.273  3833  3833 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 18:13:36.273  3833  3833 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 18:13:36.273  3833  3833 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 18:13:36.273  3833  3833 I Adreno  : Build Date                       : 10/20/15
09-12 18:13:36.273  3833  3833 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 18:13:36.273  3833  3833 I Adreno  : Local Branch                     : M14
09-12 18:13:36.273  3833  3833 I Adreno  : Remote Branch                    : 
09-12 18:13:36.273  3833  3833 I Adreno  : Remote Branch                    : 
09-12 18:13:36.273  3833  3833 I Adreno  : Reconstruct Branch               : 
09-12 18:13:36.335   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@652b81c:true
,09-12 18:13:36.359  3833  3833 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 18:13:36.373  3833  3833 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-12 18:13:36.417  3833  3873 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-12 18:13:36.429  3833  3859 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-12 18:13:36.467  3833  3873 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 18:13:36.538   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +442ms
,09-12 18:13:36.543  1881  1881 I Keyboard.Facilitator: onFinishInput()
,09-12 18:13:36.596  3833  3833 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3833
,09-12 18:13:36.809  3833  3833 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 18:13:36.914   873  3125 I ActivityManager: Killing 2993:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-12 18:13:36.940  3833  3877 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1704261328
,09-12 18:13:36.944  3833  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 18:13:36.944  3833  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 18:13:36.944  3833  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 18:13:36.944  3833  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 18:13:36.944  3833  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 18:13:36.944  3833  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd00a0d added. We now have 1 listener(s)
,09-12 18:13:36.947  3833  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-12 18:13:36.948  3833  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 18:13:36.948  3833  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 18:13:36.949  3833  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 18:13:36.951  3833  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 18:13:36.951  3833  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 18:13:36.951  3833  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000,
09-12 18:13:36.951  3833  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-12 18:13:36.951  3833  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 18:13:36.951  3833  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 18:13:36.951  3833  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 18:13:36.951  3833  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 18:13:36.951  3833  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 18:13:36.951  3833  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 18:13:36.951  3833  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 18:13:36.951  3833  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 18:13:36.951  3833  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 18:13:36.951  3833  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-12 18:13:36.951  3833  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d5cf10 added. We now have 1 listener(s)
,09-12 18:13:36.951  3833  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:13:36.954   873  1310 D WifiService: New client listening to asynchronous messages
,09-12 18:13:36.956  3833  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 18:13:36.956  3833  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-12 18:13:36.956  3833  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-12 18:13:36.956  3833  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-12 18:13:36.956  3833  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-12 18:13:36.962   873  3125 I ActivityManager: Killing 3243:com.google.android.gm/u0a78 (adj 15): empty #18
,09-12 18:13:37.006  3833  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:13:37.006  3833  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-12 18:13:37.012  3833  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-12 18:13:37.012  3833  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:37.012  3833  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:37.012  3833  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:37.012  3833  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:37.012  3833  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:37.012  3833  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:37.012  3833  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:37.012  3833  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:37.012  3833  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-12 18:13:37.012  3833  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:13:37.013  3833  3877 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 18:13:37.093  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:37.098  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:37.101  3833  3833 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 18:13:37.840  3833  3885 W jxcore-log: Initializing JXcore engine
,09-12 18:13:37.841  3833  3885 W jxcore-log: JXcore engine is ready
,09-12 18:13:37.902  3885  3885 W Thread-337: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8957 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-12 18:13:37.902  3885  3885 W Thread-337: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12092]" dev="sockfs" ino=12092 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-12 18:13:37.902  3885  3885 W Thread-337: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-12 18:13:37.902  3885  3885 W Thread-337: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26131]" dev="sockfs" ino=26131 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-12 18:13:37.921  3833  3885 W jxcore-log: Starting JXcore engine
,09-12 18:13:38.029  3833  3885 W jxcore-log: Platform android
09-12 18:13:38.029  3833  3885 W jxcore-log: 
,09-12 18:13:38.029  3833  3885 W jxcore-log: Process ARCH arm
09-12 18:13:38.029  3833  3885 W jxcore-log: 
,09-12 18:13:38.229   873  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 18:13:38.331  3833  3885 I jxcore-log: JXcore Cordova bridge is ready!
09-12 18:13:38.331  3833  3885 I jxcore-log: 
,09-12 18:13:38.332  3833  3885 W jxcore-log: JXcore engine is started
,09-12 18:13:38.340  3833  3877 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 18:13:38.344  3833  3833 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 18:13:38.602   873  2254 D NetlinkSocketObserver: NeighborEvent{elapsedMs=121437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:13:41.535   873  1309 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-12 18:13:44.116  3053  3892 V KeepSync: Connecting to GoogleApiClient
,09-12 18:13:44.117   873  1998 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 18:13:44.168  1559  1559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:13:44.170  1559  1559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:13:44.187  1559  2392 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 18:13:44.187  1559  2392 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-12 18:13:44.187  1559  2392 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:13:44.187  1559  2392 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:13:44.198  1728  3893 V BaseAuthAsyncOperation: access token request failed
,09-12 18:13:44.198  3053  3892 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 18:13:44.241  1559  1571 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 18:13:44.241  1559  1571 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 18:13:44.241  1559  1571 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:13:44.241  1559  1571 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:13:44.257  3053  3892 E KeepSync: IOException
09-12 18:13:44.257  3053  3892 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 18:13:44.257  3053  3892 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 18:13:44.257  3053  3892 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 18:13:44.257  3053  3892 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 18:13:44.257  3053  3892 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 18:13:44.257  3053  3892 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 18:13:44.257  3053  3892 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 18:13:44.257  3053  3892 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 18:13:44.257  3053  3892 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 18:13:44.257  3053  3892 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 18:13:44.257  3053  3892 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 18:13:44.257  3053  3892 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 18:13:44.257  3053  3892 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 18:13:44.257  3053  3892 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 18:13:44.257  3053  3892 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 18:13:44.257  3053  3892 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 18:13:44.257  3053  3892 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 18:13:44.257  3053  3892 E KeepSync: 	... 10 more
,09-12 18:13:44.257  3053  3892 W KeepSync: Sync result 2
,09-12 18:13:44.265   873  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 18:13:44.270   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 126872, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:13:46.029   873  2254 D NetlinkSocketObserver: NeighborEvent{elapsedMs=128864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 18:13:47.298   873  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 18:13:48.104  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 18:13:48.104  3833  3885 I jxcore-log: 
,09-12 18:13:48.106  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 18:13:48.106  3833  3885 I jxcore-log: 
,09-12 18:13:48.115  3833  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:48.115  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:48.115  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:48.115  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:48.115  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:48.115  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:48.115  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:48.115  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:48.119  3833  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:13:48.126  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 18:13:48.126  3833  3885 I jxcore-log: 
,09-12 18:13:48.133  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 18:13:48.133  3833  3885 I jxcore-log: 
,09-12 18:13:48.656  3833  3885 D executeNativeTests: Running unit tests
,09-12 18:13:48.715  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 18:13:48.715  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d added. We now have 2 listener(s)
,09-12 18:13:48.716  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 18:13:48.716  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:13:48.716  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:13:48.716  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:13:48.716  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 added. We now have 2 listener(s)
09-12 18:13:48.716  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:13:48.717  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:13:48.721  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:13:48.727  3833  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:48.727  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:48.727  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:48.727  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:48.727  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:48.727  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:48.727  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:48.727  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:48.731  3833  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:48.731  3833  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:13:48.733  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 18:13:48.733  3833  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 18:13:48.733  3833  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 18:13:48.734  3833  3885 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-12 18:13:48.735  3833  3885 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 18:13:48.735  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 18:13:48.735  3833  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:13:48.735  3833  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:13:48.735  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:48.736  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:48.736  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:48.736  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:48.736  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:13:48.736  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:13:48.736  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:13:48.736  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d removed from the list
09-12 18:13:48.736  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:48.737  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 removed from the list
09-12 18:13:48.739  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:48.746  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:48.747  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:48.747  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:48.748  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:13:48.749  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:48.751  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:13:48.751  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:48.751  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:48.752  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
,09-12 18:13:48.756  3833  3885 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-12 18:13:48.759  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:13:48.760  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:48.760  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:48.760  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:13:48.761  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:48.761  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:48.761  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
,09-12 18:13:48.761  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:48.762  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:48.762  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:48.762  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:13:48.762  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:48.763  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:48.763  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:48.765  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:13:48.765  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:48.766  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:48.766  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
,09-12 18:13:48.780  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 18:13:48.780  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 18:13:48.780  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 18:13:48.780  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-12 18:13:48.780  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 18:13:48.780  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 18:13:48.780  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 18:13:48.780  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 18:13:48.780  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 18:13:48.781  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 18:13:48.781  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 18:13:48.781  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 18:13:48.781  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 18:13:48.781  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 18:13:48.781  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-12 18:13:48.781  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 18:13:48.781  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 18:13:48.781  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 18:13:48.781  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 18:13:48.781  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 18:13:48.781  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 18:13:48.781  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 18:13:48.781  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 18:13:48.782  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 18:13:48.782  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 18:13:48.782  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-12 18:13:48.782  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 18:13:48.782  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 18:13:48.782  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 18:13:48.782  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 18:13:48.782  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 18:13:48.782  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:48.782  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:48.782  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:48.782  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:13:48.782  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:48.782  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:48.783  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:48.783  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:48.783  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:48.783  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:48.783  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:48.783  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:48.783  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:48.783  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:48.784  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:48.785  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:48.785  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:48.785  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:48.785  3833  3885 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 18:13:48.789  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:13:48.803  3833  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:48.803  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:48.803  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:48.803  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:48.803  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:48.803  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:48.803  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:48.803  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:48.804  3833  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:13:48.805  3833  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:13:48.805  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:13:48.805  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:13:48.805  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:13:48.805  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:13:48.805  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 18:13:48.809  3833  3885 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 18:13:48.809  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 18:13:48.811  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:48.814  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:48.815  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:13:48.817  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 18:13:48.817  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:13:48.820  3833  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-12 18:13:48.823  3833  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-12 18:13:48.823  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 18:13:48.824  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 18:13:48.824  3833  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 18:13:48.825  3833  3885 D BluetoothAdapter: STATE_ON
,09-12 18:13:48.831  2655  2667 D BtGatt.GattService: registerClient() - UUID=d98da46c-a4f1-42b8-b993-f4de9ca64ff9
,09-12 18:13:48.832  2655  2677 D BtGatt.GattService: onClientRegistered() - UUID=d98da46c-a4f1-42b8-b993-f4de9ca64ff9, clientIf=5
,09-12 18:13:48.835  3833  3845 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 18:13:48.837  2655  2722 D BtGatt.GattService: start scan with filters
,09-12 18:13:48.845  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 18:13:48.845  2655  2680 D BtGatt.ScanManager: handling starting scan
09-12 18:13:48.845  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:13:48.845  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 18:13:48.845  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 18:13:48.848  2655  2680 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b
09-12 18:13:48.848  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:13:48.849  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 18:13:48.849  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:13:48.851  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:13:48.856  2655  2677 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 18:13:48.857  3833  3885 I io.jxcore.node.ConnectionHelper: start: OK
09-12 18:13:48.857  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:13:48.859  2655  2680 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 18:13:48.860  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:13:48.860  3833  3885 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 18:13:48.861  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:13:48.861  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 18:13:48.861  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:48.862  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 18:13:48.862  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:13:48.862  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:13:48.862  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 18:13:48.862  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:13:48.862  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 18:13:48.863  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 18:13:48.863  3833  3885 D BluetoothAdapter: STATE_ON
09-12 18:13:48.864  2655  2667 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:13:48.864  2655  2722 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 18:13:48.865  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 18:13:48.865  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 18:13:48.865  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 18:13:48.865  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 18:13:48.865  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 18:13:48.867  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:13:48.867  2655  2677 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
09-12 18:13:48.867  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:13:48.867  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
09-12 18:13:48.867  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 18:13:48.868  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 18:13:48.868  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:13:48.868  2655  2680 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:13:48.869  2655  2680 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 18:13:48.870  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 18:13:48.870  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:13:48.870  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:13:48.871  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:13:48.871  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:48.871  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-12 18:13:48.871  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:48.871  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-12 18:13:48.871  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:48.871  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:48.871  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:48.871  3833  3885 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 18:13:48.873  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:13:48.879  3833  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:48.879  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:48.879  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:48.879  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:48.879  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:48.879  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:48.879  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:48.879  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:48.880  2655  2677 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 18:13:48.881  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:13:48.882  3833  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:48.882  3833  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:13:48.884  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:48.886  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:48.886  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:13:48.886  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:13:48.887  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 18:13:48.887  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:13:48.887  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 18:13:48.889  2655  2677 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 18:13:48.889  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:13:48.892  3833  3885 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 18:13:48.892  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 18:13:48.895  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 18:13:48.896  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 18:13:48.896  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 18:13:48.898  2655  2677 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 18:13:48.898  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:13:48.898  2655  2680 D BtGatt.ScanManager: stopping BLe Batch
,09-12 18:13:48.902  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 18:13:48.902  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 18:13:48.902  3833  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:13:48.904  2655  2677 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 18:13:48.904  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:13:48.904  2655  2680 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 18:13:48.904  3833  3885 D BluetoothAdapter: STATE_ON
,09-12 18:13:48.910  2655  2667 D BtGatt.GattService: registerClient() - UUID=5c21eb7b-1d24-481a-bc8b-d1600091bb5c
09-12 18:13:48.910  2655  2677 D BtGatt.GattService: onClientRegistered() - UUID=5c21eb7b-1d24-481a-bc8b-d1600091bb5c, clientIf=5
,09-12 18:13:48.911  3833  3844 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 18:13:48.911  2655  2677 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 18:13:48.911  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:13:48.913  2655  2722 D BtGatt.GattService: start scan with filters
,09-12 18:13:48.918  2655  2680 D BtGatt.ScanManager: handling starting scan
,09-12 18:13:48.918  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 18:13:48.919  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:13:48.919  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 18:13:48.919  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 18:13:48.923  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:13:48.924  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:13:48.924  2655  2677 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 18:13:48.924  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:13:48.924  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 18:13:48.924  2655  2680 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 18:13:48.926  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:13:48.929  2655  2677 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 18:13:48.929  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:13:48.929  2655  2680 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:13:48.929  2655  2680 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 18:13:48.930  3833  3885 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 18:13:48.932  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:13:48.932  3833  3885 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 18:13:48.933  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:48.933  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 18:13:48.933  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:48.933  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:13:48.933  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:13:48.933  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:13:48.934  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 18:13:48.934  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:13:48.934  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 18:13:48.934  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 18:13:48.935  3833  3885 D BluetoothAdapter: STATE_ON
,09-12 18:13:48.936  2655  2666 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:13:48.937  2655  2723 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 18:13:48.937  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:13:48.937  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 18:13:48.937  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:13:48.938  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 18:13:48.938  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 18:13:48.938  2655  2677 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 18:13:48.938  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:13:48.939  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:13:48.939  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 18:13:48.939  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 18:13:48.939  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 18:13:48.940  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:13:48.941  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 18:13:48.941  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:48.941  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:13:48.941  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:13:48.941  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 18:13:48.942  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
,09-12 18:13:48.942  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:13:48.942  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:13:48.942  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list,
09-12 18:13:48.942  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop,
09-12 18:13:48.942  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:48.943  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:48.943  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-12 18:13:48.943  2655  2677 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 18:13:48.943  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:13:48.944  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:48.944  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-12 18:13:48.944  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:13:48.944  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
,09-12 18:13:48.945  3833  3885 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 18:13:48.947  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:13:48.950  2655  2677 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 18:13:48.950  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:13:48.950  2655  2680 D BtGatt.ScanManager: stopping BLe Batch
,09-12 18:13:48.952  3833  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:48.952  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:48.952  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:48.952  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:48.952  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:48.952  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:48.952  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:48.952  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:48.954  3833  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:13:48.954  3833  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:13:48.954  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:13:48.955  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:13:48.955  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 18:13:48.955  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:13:48.955  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 18:13:48.956  2655  2677 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 18:13:48.956  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:13:48.957  2655  2680 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 18:13:48.957  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:48.959  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:48.960  3833  3885 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 18:13:48.960  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 18:13:48.962  2655  2677 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 18:13:48.962  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,09-12 18:13:48.965  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:13:48.965  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 18:13:48.965  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:13:48.968  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 18:13:48.968  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 18:13:48.968  3833  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:13:48.969  3833  3885 D BluetoothAdapter: STATE_ON
,09-12 18:13:48.971  2655  2722 D BtGatt.GattService: registerClient() - UUID=81f925b1-bc90-42b9-a4bc-3dfcc82f6258
,09-12 18:13:48.971  2655  2677 D BtGatt.GattService: onClientRegistered() - UUID=81f925b1-bc90-42b9-a4bc-3dfcc82f6258, clientIf=5
09-12 18:13:48.971  3833  3844 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 18:13:48.971  2655  2667 D BtGatt.GattService: start scan with filters
,09-12 18:13:48.974  2655  2680 D BtGatt.ScanManager: handling starting scan
,09-12 18:13:48.974  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 18:13:48.974  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:13:48.974  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 18:13:48.974  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 18:13:48.977  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:13:48.977  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 18:13:48.978  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 18:13:48.979  2655  2677 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 18:13:48.979  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:13:48.979  2655  2680 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 18:13:48.980  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:13:48.982  3833  3885 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 18:13:48.982  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:48.982  3833  3885 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 18:13:48.982  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:48.982  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 18:13:48.982  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:48.982  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:13:48.982  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:13:48.982  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:13:48.982  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 18:13:48.983  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:13:48.983  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 18:13:48.983  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 18:13:48.983  3833  3885 D BluetoothAdapter: STATE_ON
09-12 18:13:48.984  2655  2666 D BtGatt.GattService: stopScan() - queue size =1
09-12 18:13:48.984  2655  2677 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 18:13:48.984  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:13:48.985  2655  2723 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 18:13:48.985  2655  2680 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:13:48.985  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:13:48.985  2655  2680 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 18:13:48.985  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 18:13:48.985  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:13:48.985  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 18:13:48.986  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 18:13:48.987  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:13:48.987  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 18:13:48.987  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:13:48.987  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 18:13:48.988  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:13:48.989  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 18:13:48.989  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:13:48.989  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:13:48.990  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:48.990  3833  3885 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 18:13:48.990  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:48.990  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 18:13:48.990  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:48.991  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:48.991  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:13:48.991  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
,09-12 18:13:48.991  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:48.991  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:48.991  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:48.991  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:48.992  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:48.992  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:48.993  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:13:48.993  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:48.993  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:48.993  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
,09-12 18:13:48.994  2655  2677 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 18:13:48.994  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:13:48.994  3833  3885 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-12 18:13:48.995  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:13:48.995  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:48.995  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:48.996  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:48.996  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:13:48.996  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:48.996  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:48.996  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:48.996  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
,09-12 18:13:48.996  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:48.996  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:48.996  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:48.996  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:48.997  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:48.998  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:13:48.998  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:48.998  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:48.998  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
,09-12 18:13:48.999  2655  2677 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 18:13:48.999  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:13:49.000  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-12 18:13:49.000  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:49.001  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:49.001  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 18:13:49.001  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:49.001  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.001  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:49.001  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:49.001  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.002  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.002  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:13:49.002  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.002  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.002  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.002  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:49.003  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:49.003  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:49.003  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.003  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
,09-12 18:13:49.004  3833  3885 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-12 18:13:49.004  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:49.004  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:13:49.004  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:49.005  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:13:49.008  2655  2677 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 18:13:49.005  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.008  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:13:49.008  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.008  2655  2680 D BtGatt.ScanManager: stopping BLe Batch
,09-12 18:13:49.008  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:49.008  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.008  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.008  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:49.009  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.009  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.009  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:13:49.009  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:49.010  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:49.010  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:49.010  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.010  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
,09-12 18:13:49.011  3833  3885 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-12 18:13:49.011  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:49.011  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:49.011  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:49.012  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:13:49.012  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.012  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.012  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:49.012  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:13:49.012  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.012  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:49.012  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.012  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.013  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:13:49.013  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:49.013  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:49.014  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:49.014  2655  2677 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 18:13:49.014  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:13:49.014  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:13:49.014  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.014  2655  2680 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 18:13:49.014  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 18:13:49.016  3833  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 18:13:49.016  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-12 18:13:49.016  3833  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:13:49.016  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 18:13:49.017  3833  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 18:13:49.017  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:49.017  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:49.017  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 18:13:49.017  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:49.017  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.017  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.018  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:49.018  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.018  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.018  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:13:49.018  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.019  2655  2677 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 18:13:49.020  2655  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:13:49.020  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.020  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:13:49.020  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.020  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:49.020  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:49.021  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:13:49.021  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.021  3833  3885 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 18:13:49.021  3833  3885 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-12 18:13:49.022  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-12 18:13:49.026  3833  3885 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 18:13:49.026  3833  3885 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 18:13:49.026  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-12 18:13:49.027  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 18:13:49.027  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-12 18:13:49.027  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 18:13:49.027  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 18:13:49.027  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 18:13:49.027  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-12 18:13:49.027  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 18:13:49.027  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 18:13:49.027  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 18:13:49.027  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-12 18:13:49.027  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-12 18:13:49.029  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 18:13:49.030  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 18:13:49.030  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 18:13:49.030  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 18:13:49.030  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-12 18:13:49.030  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 18:13:49.030  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 18:13:49.030  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 18:13:49.030  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-12 18:13:49.030  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 18:13:49.030  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 18:13:49.030  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 18:13:49.030  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 18:13:49.030  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-12 18:13:49.030  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 18:13:49.031  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 18:13:49.031  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 18:13:49.031  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 18:13:49.031  3833  3885 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-12 18:13:49.031  3833  3885 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 18:13:49.031  3833  3885 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 18:13:49.031  3833  3885 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:13:49.031  3833  3885 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 18:13:49.031  3833  3885 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,09-12 18:13:49.032  3833  3885 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:13:49.032  3833  3885 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 18:13:49.032  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-12 18:13:49.035  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-12 18:13:49.035  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-12 18:13:49.035  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-12 18:13:49.036  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-12 18:13:49.036  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 18:13:49.036  3833  3885 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 18:13:49.036  3833  3885 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:13:49.036  3833  3885 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 18:13:49.036  3833  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 401)
,09-12 18:13:49.037  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:13:49.037  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:13:49.037  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 18:13:49.037  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:13:49.037  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:13:49.037  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:49.038  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 18:13:49.038  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:49.038  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.038  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.038  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:13:49.038  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.038  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.039  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.039  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-12 18:13:49.039  3833  3898 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:13:49.039  3833  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 401
09-12 18:13:49.039  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:49.040  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:49.040  3833  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 401)
09-12 18:13:49.040  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.040  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.040  3833  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 401)
,09-12 18:13:49.040  3833  3885 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 18:13:49.040  3833  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 401)
09-12 18:13:49.041  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:49.041  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:49.041  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:49.041  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:49.041  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.041  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:49.042  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:49.042  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.042  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.042  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:49.042  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.042  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.042  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.043  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.043  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:49.043  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:49.043  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.043  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.044  3833  3885 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 18:13:49.044  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:49.044  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:49.045  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:49.045  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:49.045  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.045  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.045  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:49.045  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.045  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.045  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:49.045  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.045  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.045  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.046  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.046  3833  3885 I org.thalipro,ject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:49.046  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:49.046  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.046  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.047  3833  3885 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 18:13:49.047  3833  3885 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 18:13:49.047  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 18:13:49.047  3833  3885 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 18:13:49.047  3833  3885 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 18:13:49.047  3833  3885 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 18:13:49.047  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 18:13:49.048  3833  3885 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 18:13:49.048  3833  3885 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 18:13:49.048  3833  3885 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 18:13:49.048  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 18:13:49.048  3833  3885 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 18:13:49.048  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:49.048  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:49.048  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:49.048  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:49.048  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.048  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.049  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:49.049  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.049  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.049  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:49.049  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.049  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.049  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.049  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.050  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:49.050  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:49.050  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.050  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.050  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:49.050  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.050  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.050  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:49.051  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.051  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.051  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:49.051  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.051  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.051  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.051  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.051  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:49.051  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.051  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.051  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:49.051  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:49.052  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:49.052  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:49.052  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:49.052  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.052  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.052  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:49.052  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.052  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.052  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:49.052  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.052  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.052  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.053  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.053  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:49.053  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:49.053  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.053  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.055  3833  3885 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 18:13:49.055  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:13:49.055  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 18:13:49.056  3833  3885 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 18:13:49.056  3833  3885 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 18:13:49.056  3833  3833 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 18:13:49.057  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 18:13:49.057  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:13:49.057  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:49.057  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 18:13:49.057  3833  3900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:13:49.057  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 18:13:49.057  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 18:13:49.057  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.057  3833  3885 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 18:13:49.057  3833  3833 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 18:13:49.058  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:49.058  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.058  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:13:49.058  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:13:49.058  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:13:49.058  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.058  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.059  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:13:49.059  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:13:49.059  3833  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 18:13:49.059  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:13:49.059  3833  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 18:13:49.059  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:13:49.059  3833  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 18:13:49.060  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.060  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:49.060  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:49.060  3833  3833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 18:13:49.060  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:49.060  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:49.060  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.060  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.060  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:49.060  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.060  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.060  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:49.061  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.061  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.061  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.061  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.061  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:49.062  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:49.062  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.062  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.063  3833  3885 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 18:13:49.063  3833  3885 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 18:13:49.063  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 18:13:49.065  3833  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:13:49.065  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:49.065  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:49.065  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:49.065  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:49.066  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.066  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.066  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:49.066  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.066  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.066  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:49.066  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.066  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.066  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.066  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.067  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:49.068  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:49.068  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.068  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.071  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:49.071  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:49.071  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:49.071  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:49.072  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.072  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.072  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:49.072  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.072  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.072  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:49.072  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.072  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.072  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.072  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.073  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:49.073  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:49.073  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.074  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.074  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:49.075  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:49.075  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:49.075  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:49.075  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.075  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.075  3833  3885 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c39d not in the list
09-12 18:13:49.075  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.075  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.076  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:49.076  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.076  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.076  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:49.076  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:49.077  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:49.077  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:49.077  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:49.077  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b5012 not in the list
09-12 18:13:49.078  3833  3885 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 18:13:49.078  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 18:13:49.078  3833  3885 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 18:13:49.078  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 18:13:49.078  3833  3885 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 18:13:49.078  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 18:13:49.080  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 18:13:49.080  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-12 18:13:49.080  3833  3885 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 18:13:49.081  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 18:13:49.081  3833  3885 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 18:13:49.081  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 18:13:49.081  3833  3885 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 18:13:49.081  3833  3885 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 18:13:49.081  3833  3885 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 18:13:49.081  3833  3885 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-12 18:13:49.082  3833  3885 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 18:13:49.082  3833  3885 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 18:13:49.082  3833  3885 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 18:13:49.082  3833  3885 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-12 18:13:49.083  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:13:49.083  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f9e0a4 added. We now have 2 listener(s)
09-12 18:13:49.083  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:13:49.084  3833  3885 D BluetoothAdapter: enable(): BT is already enabled..!
09-12 18:13:49.085   873  1698 D WifiService: setWifiEnabled: true pid=3833, uid=10000
09-12 18:13:49.085   873  1698 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 18:13:49.085  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:13:49.086  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6aece0d added. We now have 3 listener(s)
09-12 18:13:49.086  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:13:49.090  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:13:49.090  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@643e1c2 added. We now have 4 listener(s)
09-12 18:13:49.090  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:13:49.091  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:13:49.091  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7bc6bd3 added. We now have 5 listener(s)
09-12 18:13:49.091  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:13:49.093   873  2059 D WifiService: setWifiEnabled: false pid=3833, uid=10000
09-12 18:13:49.093   873  2059 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 18:13:49.098  2655  2673 D BluetoothAdapterState: Current state: ON, message: 23
09-12 18:13:49.098  2655  2673 D BluetoothAdapterProperties: Setting state to 13
09-12 18:13:49.098  2655  2673 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 18:13:49.097  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:13:49.098  2655  2673 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 18:13:49.100  2655  2673 I BluetoothAdapterState: Entering PendingCommandState
09-12 18:13:49.102  2655  2655 D BluetoothMapService: onReceive
09-12 18:13:49.102  2655  2655 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:49.102  2655  2655 D BluetoothMapService: STATE_TURNING_OFF
09-12 18:13:49.102  2655  2655 D BluetoothMapService: MAP Service closeService in
09-12 18:13:49.102  2655  2655 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 18:13:49.102  2655  2655 D ObexServerSockets0: shutdown(block = true)
09-12 18:13:49.103  2655  2655 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 18:13:49.103  2655  2655 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 18:13:49.103  2655  2734 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 18:13:49.103  2655  2733 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-12 18:13:49.104  2655  2655 I BtOppRfcommListener: stopping Accept Thread
09-12 18:13:49.104  2655  3446 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 18:13:49.104  2655  3446 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 18:13:49.104  2655  2718 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-12 18:13:49.106  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:49.106  3833  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:49.106  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:49.106  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:49.106  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:49.106  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:49.106  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:49.106  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:49.106  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:13:49.107  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:49.107  3833  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:49.108  3833  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:13:49.108  1477  1477 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 18:13:49.109   873  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 18:13:49.109   873  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 18:13:49.109   873  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 18:13:49.109   873  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 18:13:49.112  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:49.116  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:49.119   371   871 D CommandListener: Clearing all IP addresses on wlan0
09-12 18:13:49.119   873  2258 D DhcpClient: Clearing IP address
09-12 18:13:49.122   371   871 D CommandListener: Setting iface cfg
09-12 18:13:49.122  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:49.122  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:49.122  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:49.122  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:49.122  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:49.122  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:49.122  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:49.122  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:49.122  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:13:49.123  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:49.123  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:49.124  1559  2963 V NativeCrypto: Read error: ssl=0xaec04a00: I/O error during system call, Connection timed out
09-12 18:13:49.125  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:49.127  1559  2963 V NativeCrypto: SSL shutdown failed: ssl=0xaec04a00: I/O error during system call, Broken pipe
09-12 18:13:49.130   873   884 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-12 18:13:49.130   873  2252 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,09-12 18:13:49.132   873  2252 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-12 18:13:49.133   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,09-12 18:13:49.133   873  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-12 18:13:49.133   873   886 I ActivityManager: Start proc 3904:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-12 18:13:49.133  2655  2677 D BluetoothAdapterProperties: Scan Mode:20
09-12 18:13:49.134  2655  2673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-12 18:13:49.134   873  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 18:13:49.134   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 18:13:49.134   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-12 18:13:49.137   873  1309 D WifiStateMachine: Start Disconnecting Watchdog 1
09-12 18:13:49.137   873  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 18:13:49.138  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:49.138  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:49.138  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:49.138  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:49.138  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:49.138  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:49.138  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:49.138  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:49.138  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:13:49.138  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:49.138  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:13:49.139   394   394 E Parcel  : Reading a NULL string not supported here.
09-12 18:13:49.139  2655  2655 D HeadsetService: Received stop request...Stopping profile...
09-12 18:13:49.141  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:49.141  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:49.141  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:49.141  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:49.141  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:49.141  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:49.141  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:49.141  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:49.141  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:13:49.142  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:49.142  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:13:49.142   371   871 D CommandListener: Clearing all IP addresses on wlan0
09-12 18:13:49.145   873   873 D BluetoothHeadset: Proxy object disconnected
,09-12 18:13:49.145  1957  2163 D BluetoothHeadset: Proxy object disconnected
09-12 18:13:49.146   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 18:13:49.146  2655  2655 D A2dpService: Received stop request...Stopping profile...
09-12 18:13:49.146  1352  1370 D BluetoothHeadset: Proxy object disconnected
09-12 18:13:49.146   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 18:13:49.146  2655  2726 D A2dpStateMachine: Exit Disconnected: -1
09-12 18:13:49.147   873   873 D BluetoothA2dp: Proxy object disconnected
09-12 18:13:49.148  2655  2655 D HidService: Received stop request...Stopping profile...
09-12 18:13:49.148  2655  2655 D HidService: Stopping Bluetooth HidService
09-12 18:13:49.150   873  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-12 18:13:49.151   873  2274 D DhcpClient: Receive thread stopped
09-12 18:13:49.156  1352  1352 D HeadsetProfile: Bluetooth service disconnected
09-12 18:13:49.157  1352  1352 D BluetoothA2dp: Proxy object disconnected
,09-12 18:13:49.162  2655  2655 D HealthService: Received stop request...Stopping profile...
,09-12 18:13:49.162   873  1309 D WifiConfigStore: Retrieve network priorities after PNO.
09-12 18:13:49.165  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:49.165  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:49.165  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:49.165  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:49.165  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:49.165  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:49.165  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:49.165  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:49.165  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:13:49.165  2655  2655 D PanService: Received stop request...Stopping profile...
09-12 18:13:49.166  2655  2655 V BluetoothAdapterState: isTurningOff()=true
09-12 18:13:49.166  2655  2655 V BluetoothAdapterState: isTurningOn()=false
,09-12 18:13:49.166  2655  2655 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:13:49.166  2655  2655 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:13:49.167  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:49.167  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:13:49.167   873  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 18:13:49.168  2655  2655 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 18:13:49.168  2655  2655 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 18:13:49.168  2655  2713 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 18:13:49.168  2655  2713 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 18:13:49.168  2655  2713 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 18:13:49.168  2655  2677 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-12 18:13:49.169  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:49.169  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:49.169  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:49.169  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:49.169  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:49.169  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:49.169  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:49.169  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:49.169  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:13:49.169  2655  2677 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-12 18:13:49.169  2655  2655 D BluetoothMapService: Received stop request...Stopping profile...
,09-12 18:13:49.169  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:49.169  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:13:49.169  2655  2655 D BluetoothMapService: stop()
09-12 18:13:49.172  1896  2303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:13:49.174  2655  2655 D BluetoothMapAppObserver: deinitObservers(),
09-12 18:13:49.174  2655  2655 D BluetoothMapAppObserver: removeReceiver()
09-12 18:13:49.174  1352  1352 D BluetoothInputDevice: Proxy object disconnected
,09-12 18:13:49.174  1352  1352 D HidProfile: Bluetooth service disconnected
,09-12 18:13:49.174  1352  1352 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 18:13:49.174  1352  1352 D PanProfile: Bluetooth service disconnected
09-12 18:13:49.175  1352  1352 D BluetoothMap: Proxy object disconnected
09-12 18:13:49.175  1352  1352 D MapProfile: Bluetooth service disconnected
09-12 18:13:49.175  2655  2655 V BluetoothAdapterState: isTurningOff()=true
,09-12 18:13:49.175  2655  2655 V BluetoothAdapterState: isTurningOn()=false
,09-12 18:13:49.175  2655  2655 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:13:49.175  2655  2655 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:13:49.177  2655  2677 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-12 18:13:49.177  2655  2713 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 18:13:49.177  2655  2713 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
09-12 18:13:49.177  2655  2655 V BluetoothAdapterState: isTurningOff()=true
09-12 18:13:49.177  2655  2655 V BluetoothAdapterState: isTurningOn()=false
09-12 18:13:49.177  2655  2713 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:13:49.177  2655  2713 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:13:49.177  2655  2655 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:13:49.177  2655  2713 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:13:49.178  2655  2713 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:13:49.178  2655  2655 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:13:49.178  2655  2655 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-12 18:13:49.178  2655  2655 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 18:13:49.178  2655  2677 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 18:13:49.178  2655  2655 V BluetoothAdapterState: isTurningOff()=true
,09-12 18:13:49.178  2655  2655 V BluetoothAdapterState: isTurningOn()=false
,09-12 18:13:49.178  2655  2655 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:13:49.178  2655  2655 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:13:49.179  2655  2655 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 18:13:49.179  2655  2677 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 18:13:49.179  2655  2655 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 18:13:49.180  2655  2655 V BluetoothAdapterState: isTurningOff()=true
09-12 18:13:49.180  2655  2655 V BluetoothAdapterState: isTurningOn()=false
09-12 18:13:49.180  2655  2655 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:13:49.180  2655  2655 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:13:49.180  2655  2655 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 18:13:49.181  2655  2655 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-12 18:13:49.182  2655  2655 D BluetoothMapService: MAP Service closeService in
09-12 18:13:49.182  2655  2655 V BluetoothAdapterState: isTurningOff()=true
09-12 18:13:49.182  2655  2655 V BluetoothAdapterState: isTurningOn()=false
09-12 18:13:49.182  2655  2655 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:13:49.182  2655  2655 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:13:49.183  2655  2673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 18:13:49.183  2655  2673 D BluetoothAdapterProperties: Setting state to 15
09-12 18:13:49.183  2655  2673 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 18:13:49.183   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 18:13:49.183  1352  2073 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:13:49.184  1352  1370 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 18:13:49.184  2655  2673 I BluetoothAdapterState: Entering BleOnState
,09-12 18:13:49.184  2655  2655 D BluetoothMapService: cleanup()
09-12 18:13:49.184  2655  2655 D BluetoothMapService: MAP Service closeService in
09-12 18:13:49.185  1352  1373 D BluetoothMap: onBluetoothStateChange: up=false
09-12 18:13:49.185  1352  2073 D BluetoothPan: onBluetoothStateChange on: false
09-12 18:13:49.185   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 18:13:49.186  1352  1370 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 18:13:49.187   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:13:49.187  1352  1373 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 18:13:49.187   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 18:13:49.187  1957  2163 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 18:13:49.188  2655  2673 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-12 18:13:49.188  2655  2673 D BluetoothAdapterProperties: Setting state to 16
,09-12 18:13:49.188  2655  2673 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 18:13:49.189  2655  2673 D BluetoothAdapterProperties: onBleDisable
09-12 18:13:49.189  2655  2673 I BluetoothAdapterState: Entering PendingCommandState
09-12 18:13:49.189  2655  2674 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 18:13:49.190  2655  2713 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms,
09-12 18:13:49.190  2655  2713 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 18:13:49.192  2655  2677 D BluetoothAdapterProperties: Scan Mode:20
09-12 18:13:49.193  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:49.194  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:49.195  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:49.196  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:49.202   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 18:13:49.212  3904  3904 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-12 18:13:49.221  3904  3904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:13:49.225   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d14f010:true
,09-12 18:13:49.227  1559  1559 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:13:49.228   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 18:13:49.229   873  1311 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-12 18:13:49.230   873  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:13:49.240   873  1392 I ActivityManager: Start proc 3921:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-12 18:13:49.245   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-12 18:13:49.248  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:49.249  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:49.249  3453  3453 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@fd00a0d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-12 18:13:49.280  3904  3904 D LocalBluetoothProfileManager: Adding local MAP profile
,09-12 18:13:49.282  3904  3904 D BluetoothMap: Create BluetoothMap proxy object
,09-12 18:13:49.289  3904  3904 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-12 18:13:49.293  3921  3921 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-12 18:13:49.309   371   871 E Netd    : netlink response contains error (No such file or directory)
,09-12 18:13:49.309  3904  3904 D DockEventReceiver: finishStartingService: stopping service
09-12 18:13:49.310   873  1311 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-12 18:13:49.310   873  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 18:13:49.312   873  1392 I ActivityManager: Killing 3095:com.google.android.talk/u0a61 (adj 15): empty #17
,09-12 18:13:49.390  2655  2677 I bt_hci  : shut_down
,09-12 18:13:49.391  2655  2681 D bt_hwcfg: hw_epilog_process
,09-12 18:13:49.392  2655  2681 I bt_vendor: low_power_mode_cb
,09-12 18:13:49.412  2655  2681 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 18:13:49.413  2655  2681 I bt_vendor: epilog_cb
,09-12 18:13:49.413  2655  2681 I bt_hci  : epilog_finished_callback
,09-12 18:13:49.420  2655  2677 I bt_hci_h4: hal_close
,09-12 18:13:49.421  2655  2677 I bt_userial_vendor: device fd = 51 close
,09-12 18:13:49.471  3921  3921 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 18:13:49.471  3921  3921 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 18:13:49.471  3921  3921 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:13:49.471  3921  3921 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 18:13:49.472  3921  3921 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 18:13:49.472  3921  3921 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.r.k.d(PG:583)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 18:13:49.472  3921  3921 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 18:13:49.472  3921  3921 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 18:13:49.472  3921  3921 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:13:49.472  3921  3921 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 18:13:49.525   873  1698 I ActivityManager: Start proc 3955:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
09-12 18:13:49.528   873  1698 I ActivityManager: Killing 3453:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-12 18:13:49.560  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 18:13:49.685  2655  2674 D bt_stack_manager: event_shut_down_stack finished.
,09-12 18:13:49.685  2655  2673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 18:13:49.688  2655  2673 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-12 18:13:49.688  2655  2655 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 18:13:49.689  2655  2655 D BtGatt.GattService: Received stop request...Stopping profile...
,09-12 18:13:49.689  2655  2655 D BtGatt.GattService: stop()
,09-12 18:13:49.689  2655  2655 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 18:13:49.691  2655  2655 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:13:49.691  2655  2655 V BluetoothAdapterState: isTurningOn()=false
,09-12 18:13:49.691  2655  2655 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:13:49.691  2655  2655 V BluetoothAdapterState: isBleTurningOff()=true
,09-12 18:13:49.692  2655  2673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-12 18:13:49.692  2655  2673 D BluetoothAdapterProperties: Setting state to 10
09-12 18:13:49.692  2655  2673 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-12 18:13:49.692  2655  2673 I BluetoothAdapterState: Entering OffState
09-12 18:13:49.693   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-12 18:13:49.706  2655  2655 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-12 18:13:49.706  2655  2655 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-12 18:13:49.706  2655  2674 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 18:13:49.709  2655  2655 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 18:13:49.710  2655  2674 D bt_stack_manager: event_clean_up_stack finished.
,09-12 18:13:49.712  3955  3955 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-12 18:13:49.719  2655  2655 I art     : System.exit called, status: 0
,09-12 18:13:49.719  2655  2655 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 18:13:49.753  3921  3945 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 18:13:49.774   873  2153 I ActivityManager: Process com.android.bluetooth (pid 2655) has died
,09-12 18:13:49.901   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@368fde9:true
,09-12 18:13:49.901  3955  3975 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-12 18:13:49.901  3955  3975 I Babel_SMS: MmsConfig.loadMmsSettings
09-12 18:13:49.902  3955  3975 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
09-12 18:13:49.903  3955  3975 I Babel_SMS: MmsConfig.loadFromDatabase
,09-12 18:13:49.948  3955  3975 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-12 18:13:49.948  3955  3975 I Babel_SMS: MmsConfig.loadFromResources
,09-12 18:13:49.950  3955  3975 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-12 18:13:49.950  3955  3975 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-12 18:13:49.983  3955  3955 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 18:13:49.986  3955  3955 I Babel_Crash: startup - clean
,09-12 18:13:50.013  3955  3955 I Babel_telephony: TeleModule.launchCompleted
,09-12 18:13:50.024   873  1705 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-12 18:13:50.036  3955  3955 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-12 18:13:50.043  3955  3955 W Babel   : BAM#gBA: invalid account id: -1
,09-12 18:13:50.043  3955  3955 W Babel   : BAM#gBA: invalid account id: -1
,09-12 18:13:50.043  3955  3955 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-12 18:13:50.053  3955  3980 I Babel   : deleted: false for 0
,09-12 18:13:50.053   873  2238 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-12 18:13:50.094   873  2059 I ActivityManager: Start proc 3982:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-12 18:13:50.111  3955  3955 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 18:13:50.175  3955  3955 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-12 18:13:50.178  3982  3982 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-12 18:13:50.191  3955  3955 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 18:13:50.193  3955  3955 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 18:13:50.209  3955  3955 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 18:13:50.224  3955  3955 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 18:13:50.232  3955  3955 I vclib   : onServiceConnected
,09-12 18:13:50.282  3982  3982 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-12 18:13:50.320  3904  3904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:13:50.368   873  1987 I ActivityManager: Start proc 4007:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-12 18:13:50.370  3904  3904 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:13:50.372   873  1996 I ActivityManager: Killing 3608:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-12 18:13:50.476  4007  4007 D AdapterServiceConfig: Adding HeadsetService
,09-12 18:13:50.476  4007  4007 D AdapterServiceConfig: Adding A2dpService
,09-12 18:13:50.476  4007  4007 D AdapterServiceConfig: Adding HidService
,09-12 18:13:50.476  4007  4007 D AdapterServiceConfig: Adding HealthService
,09-12 18:13:50.476  4007  4007 D AdapterServiceConfig: Adding PanService
,09-12 18:13:50.477  4007  4007 D AdapterServiceConfig: Adding GattService
,09-12 18:13:50.477  4007  4007 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 18:13:50.481   873  2153 I ActivityManager: Killing 3641:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-12 18:13:50.520  1559  1559 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:13:50.543  1728  1728 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 18:13:50.549  1728  1728 D SystemUpdateService: onCreate
,09-12 18:13:50.554  1728  1728 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 18:13:50.562  1728  4019 I SystemUpdateService: active receiver: enabled
,09-12 18:13:50.565  1728  4019 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 18:13:50.566  1728  1728 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-12 18:13:50.566  1728  4019 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-12 18:13:50.566  1728  4019 I SystemUpdateService: now status is 0 (complete)
09-12 18:13:50.566  1728  4019 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 18:13:50.566  1728  4019 I SystemUpdateService: file has been verified
09-12 18:13:50.567  1728  4019 I SystemUpdateService: OTA package size = 12249756
,09-12 18:13:50.570  1728  2547 I iu.UploadsManager: num queued entries: 0
,09-12 18:13:50.571  1728  2547 I iu.UploadsManager: num updated entries: 0
09-12 18:13:50.571  1728  4019 I SystemUpdateService: showing system update notification
09-12 18:13:50.572  1728  2547 I iu.SyncManager: NEXT; no task,
,09-12 18:13:50.582  1728  1728 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 18:13:50.583  1728  1728 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 18:13:50.598   873  1705 I ActivityManager: Start proc 4021:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-12 18:13:50.601  1728  1728 D SystemUpdateService: onDestroy
,09-12 18:13:50.659  4021  4021 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-12 18:13:50.662  4021  4021 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:13:50.668  4021  4021 D SprintDMHelper: simOperator: 
,09-12 18:13:50.668  4021  4021 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 18:13:50.687   873  2059 I ActivityManager: Start proc 4033:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-12 18:13:50.688   873  2059 I ActivityManager: Killing 3509:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-12 18:13:50.848   873  1987 I ActivityManager: Start proc 4048:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-12 18:13:50.853  3955  4047 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-12 18:13:50.868   873  1697 I ActivityManager: Killing 3549:android.process.acore/u0a5 (adj 15): empty #17
,09-12 18:13:50.933  4048  4048 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-12 18:13:50.994  4048  4048 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-12 18:13:50.994  4048  4048 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 18:13:50.994  4048  4048 I GAv4    :   adb logcat -s GAv4
,09-12 18:13:51.011  4048  4048 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 18:13:51.018  4048  4048 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 18:13:51.052  4048  4065 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 18:13:51.159  4048  4048 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-12 18:13:51.196  4048  4048 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-12 18:13:51.207  4048  4048 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 4036-4042)
,09-12 18:13:51.207  4048  4048 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 18:13:51.216  4048  4048 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ee4907d}
,09-12 18:13:51.216  4048  4048 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 18:13:51.217  4048  4048 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 18:13:51.224  4048  4048 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 18:13:51.226  4048  4048 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 18:13:51.243  4048  4048 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 18:13:51.255  4048  4048 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 18:13:51.255  4048  4048 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 18:13:51.255  4048  4048 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 18:13:51.255  4048  4048 I Adreno  : Build Date                       : 10/20/15
09-12 18:13:51.255  4048  4048 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 18:13:51.255  4048  4048 I Adreno  : Local Branch                     : M14
09-12 18:13:51.255  4048  4048 I Adreno  : Remote Branch                    : 
09-12 18:13:51.255  4048  4048 I Adreno  : Remote Branch                    : 
09-12 18:13:51.255  4048  4048 I Adreno  : Reconstruct Branch               : 
,09-12 18:13:51.304  4048  4095 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-12 18:13:51.321  4048  4048 I NSApplication: Starting up...
,09-12 18:13:51.366   873  2059 I ActivityManager: Start proc 4100:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-12 18:13:51.368   873  2059 I ActivityManager: Killing 3717:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-12 18:13:51.436  4100  4100 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-12 18:13:51.626   873  2059 I ActivityManager: Killing 3733:com.android.musicfx/u0a18 (adj 15): empty #17
,09-12 18:13:52.110   873  2153 D WifiService: setWifiEnabled: true pid=3833, uid=10000
09-12 18:13:52.110   873  2153 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 18:13:52.124   873  1309 D WifiConfigStore: Loading config and enabling all networks 
,09-12 18:13:52.134  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:52.134  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:52.134  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:52.134  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:52.134  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:52.134  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:52.134  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:52.134  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:52.134  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:13:52.135  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:52.135  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:13:52.137  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:52.138  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:52.138  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:52.138  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:52.138  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:52.138  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:52.138  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:52.138  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:52.138  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:13:52.138  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:52.139  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:52.143   873  1309 D WifiConfigStore: loaded 0 passpoint configs
,09-12 18:13:52.144   873  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 18:13:52.145   873  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-12 18:13:52.146   873  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-12 18:13:52.146   873  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 18:13:52.146   873  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-12 18:13:52.146   873  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 18:13:52.161   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 18:13:52.162   873  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.12 rxSuccessRate=12.00 delta 1000 -> 994
,09-12 18:13:52.163   371   871 D CommandListener: Setting iface cfg
,09-12 18:13:52.165   873  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-12 18:13:52.165   873  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 18:13:52.170   873  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 18:13:52.170   873  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:13:52.175   873  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 18:13:52.254   873  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 18:13:52.257  1477  1477 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 18:13:52.273   873  1308 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 18:13:52.275   873  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 18:13:52.690  1477  1477 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 18:13:52.739  1477  1477 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 18:13:52.740  1477  1477 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 18:13:52.748   873  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 18:13:52.766   873  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 18:13:52.767   873  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 18:13:52.768   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 18:13:52.793   873  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:13:52.808   371   871 D CommandListener: Setting iface cfg
,09-12 18:13:52.810   873  1309 D WifiStateMachine: Start Dhcp Watchdog 2
,09-12 18:13:52.826   873  1311 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-12 18:13:52.831   873  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 18:13:52.860   873  4123 D DhcpClient: Receive thread started
,09-12 18:13:52.943   873  1309 E native  : do suspend false
,09-12 18:13:52.962   873  2258 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 18:13:52.978   873  4123 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172689, domain null
,09-12 18:13:52.979   873  2258 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172689 seconds
,09-12 18:13:52.983   873  2258 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 18:13:52.997   873  4123 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 18:13:52.999   873  2258 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 18:13:53.007   371   871 D CommandListener: Setting iface cfg
,09-12 18:13:53.017   873  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 18:13:53.019   873  2258 D DhcpClient: Scheduling renewal in 86399s
,09-12 18:13:53.024   873  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 18:13:53.025   873  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 18:13:53.026   873  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 18:13:53.026   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 18:13:53.029   873  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 18:13:53.032   873  1311 D ConnectivityService: Adding iface wlan0 to network 101
,09-12 18:13:53.080   873  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 18:13:53.081   873  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-12 18:13:53.082   873  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-12 18:13:53.084   873  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-12 18:13:53.085   873  1311 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-12 18:13:53.093   873  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 18:13:53.098   873  1311 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-12 18:13:53.098   873  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-12 18:13:53.099   873  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-12 18:13:53.099   873  1311 D ConnectivityService:    accepting network in place of null
,09-12 18:13:53.099   873  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-12 18:13:53.100   873  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 18:13:53.100   873  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 18:13:53.120   873  4122 D NetlinkSocketObserver: NeighborEvent{elapsedMs=135955, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:13:53.148   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 18:13:53.189   873  4121 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-12 18:13:53.221   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 18:13:53.231   873  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-12 18:13:53.232   873  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:13:53.242   873  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-12 18:13:53.243   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-12 18:13:53.254   873  4121 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 16:13:53 GMT], X-Android-Received-Millis=[1473696833252], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473696833229]}
,09-12 18:13:53.259  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:53.259  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:53.259  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:53.259  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:53.259  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:53.259  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:53.259  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:53.259  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:53.259  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:13:53.259  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:53.259  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:53.265  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:53.265  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:53.265  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:53.265  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:53.265  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:53.265  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:53.265  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:53.265  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:53.265  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:13:53.265  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:53.265  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:53.269   873  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 18:13:53.269   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-12 18:13:53.269   873  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 18:13:53.273   873  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 18:13:53.277  1728  1728 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 18:13:53.280  1728  1728 D SystemUpdateService: onCreate
,09-12 18:13:53.283  1728  1728 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 18:13:53.291  1728  4134 I SystemUpdateService: active receiver: enabled
,09-12 18:13:53.298  1728  4134 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 18:13:53.300  1728  4134 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-12 18:13:53.300  1728  4134 I SystemUpdateService: now status is 0 (complete)
,09-12 18:13:53.300  1728  4134 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 18:13:53.300  1728  4134 I SystemUpdateService: file has been verified
09-12 18:13:53.300  1728  4134 I SystemUpdateService: OTA package size = 12249756
,09-12 18:13:53.305  1728  1728 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 18:13:53.307  1728  4134 I SystemUpdateService: showing system update notification
,09-12 18:13:53.309  1728  2547 I iu.UploadsManager: num queued entries: 0
,09-12 18:13:53.311  1728  2547 I iu.UploadsManager: num updated entries: 0
,09-12 18:13:53.314  1728  4137 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-12 18:13:53.314  1728  4137 W BaseAppContext: Using Auth Proxy for data requests.
09-12 18:13:53.314  1728  2547 I iu.SyncManager: NEXT; no task
09-12 18:13:53.315  1728  1728 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-12 18:13:53.315  1728  4137 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 18:13:53.316  1728  1728 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 18:13:53.318  4021  4021 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:13:53.321  1559  1559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:13:53.322  4021  4021 D SprintDMHelper: simOperator: 
09-12 18:13:53.322  4021  4021 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 18:13:53.323  1559  1559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:13:53.332   873   885 I ActivityManager: Start proc 4140:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-12 18:13:53.334  1728  1728 D SystemUpdateService: onDestroy
,09-12 18:13:53.365  1559  1571 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 18:13:53.365  1559  1571 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-12 18:13:53.365  1559  1571 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:13:53.365  1559  1571 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:13:53.373  4140  4140 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-12 18:13:53.382  1728  4137 E MDM     : [178] SitrepService.a: Error sending sitrep.
,09-12 18:13:53.453  4140  4140 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-12 18:13:53.460  3955  4152 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 18:13:53.461  4140  4140 I BooksApp: Created application version: 3.6.9 (30609)
,09-12 18:13:53.481  1559  1571 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 18:13:53.481  1559  1571 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 18:13:53.481  1559  1571 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:13:53.481  1559  1571 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:13:53.496  3010  4154 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 18:13:53.496  3010  4154 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at jdm.a(PG:82)
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at jcs.o(PG:406)
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at jcn.a(PG:1379)
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at jcs.i(PG:143)
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at blb.a(PG:3937)
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at czp.a(PG:18188)
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at czp.a(PG:9081)
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at czq.run(PG:1686)
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:13:53.496  3010  4154 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at jdj.a(PG:4091)
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at jdj.a(PG:1125)
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at jdm.a(PG:77)
09-12 18:13:53.496  3010  4154 E HttpOperation: 	... 12 more
09-12 18:13:53.496  3010  4154 E HttpOperation: Caused by: faj: BadAuthentication
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at fal.a(PG:38)
09-12 18:13:53.496  3010  4154 E HttpOperation: 	at jdj.a(PG:4089)
09-12 18:13:53.496  3010  4154 E HttpOperation: 	... 14 more
,09-12 18:13:53.522  1559  3350 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 18:13:53.523  1559  3350 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 18:13:53.523  1559  3350 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:13:53.523  1559  3350 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:13:53.538  3010  4154 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 18:13:53.538  3010  4154 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at jdm.a(PG:82)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at jcs.o(PG:406)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at jcn.a(PG:1379)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at jcs.i(PG:143)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at hec.a(PG:42)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at hee.a(PG:102)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at czr.a(PG:65)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at kka.a(PG:108)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at czp.a(PG:19176)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at czp.a(PG:9081)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at czq.run(PG:1686)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:13:53.538  3010  4154 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at jdj.a(PG:4091)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at jdj.a(PG:1125)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at jdm.a(PG:77)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	... 15 more
09-12 18:13:53.538  3010  4154 E HttpOperation: Caused by: faj: BadAuthentication
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at fal.a(PG:38)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	at jdj.a(PG:4089)
09-12 18:13:53.538  3010  4154 E HttpOperation: 	... 17 more
,09-12 18:13:53.539  3010  4154 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 18:13:53.539  3010  4154 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at hec.a(PG:42)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at hee.a(PG:102)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at czr.a(PG:65)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at kka.a(PG:108)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	... 15 more
09-12 18:13:53.539  3010  4154 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at fal.a(PG:38)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 18:13:53.539  3010  4154 E ExperimentLoader: 	... 17 more
,09-12 18:13:53.561  4140  4166 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 18:13:53.622   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 132417, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:13:53.734  4140  4173 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 18:13:53.803  1559  2061 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 18:13:53.803  1559  2061 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 18:13:53.803  1559  2061 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 18:13:53.803  1559  2061 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:13:53.852  1559  2024 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 18:13:53.853  1559  2024 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 18:13:53.853  1559  2024 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 18:13:53.853  1559  2024 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:13:53.873  4140  4173 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 18:13:53.875  4140  4166 E BooksSync: Soft error
09-12 18:13:53.875  4140  4166 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 18:13:53.875  4140  4166 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 18:13:53.875  4140  4166 E BooksSync: Sync error
09-12 18:13:53.875  4140  4166 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 18:13:53.875  4140  4166 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 18:13:53.875  4140  4166 I BooksSync: Finished books sync
,09-12 18:13:53.887   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127467, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:13:53.889   873  1996 I ActivityManager: Killing 3477:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-12 18:13:54.230   873  1311 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-12 18:13:54.809   873  1698 I ActivityManager: Killing 3760:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-12 18:13:55.117   873  3125 D WifiService: setWifiEnabled: false pid=3833, uid=10000
,09-12 18:13:55.117   873  3125 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 18:13:55.154  1477  1477 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 18:13:55.162   873  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 18:13:55.163   873  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 18:13:55.163   873  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 18:13:55.163   873  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:13:55.179   873  2258 D DhcpClient: Clearing IP address
,09-12 18:13:55.180   371   871 D CommandListener: Setting iface cfg
,09-12 18:13:55.186   873  4123 D DhcpClient: Receive thread stopped
,09-12 18:13:55.186   371   871 D CommandListener: Clearing all IP addresses on wlan0
,09-12 18:13:55.188  1559  4162 V NativeCrypto: Read error: ssl=0x9af46e00: I/O error during system call, Connection timed out
,09-12 18:13:55.189  1559  4162 V NativeCrypto: SSL shutdown failed: ssl=0x9af46e00: I/O error during system call, Broken pipe
,09-12 18:13:55.196   873  1998 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-12 18:13:55.196   873  4121 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,09-12 18:13:55.201   873  4121 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-12 18:13:55.202   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-12 18:13:55.203   873  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 18:13:55.207   873  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 18:13:55.219   394   394 E Parcel  : Reading a NULL string not supported here.
,09-12 18:13:55.221   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-12 18:13:55.221   873  1309 D WifiStateMachine: Start Disconnecting Watchdog 2
09-12 18:13:55.221   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-12 18:13:55.222   873  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 18:13:55.223   371   871 D CommandListener: Clearing all IP addresses on wlan0
,09-12 18:13:55.228   873  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-12 18:13:55.231   873  1309 D WifiConfigStore: Retrieve network priorities after PNO.
09-12 18:13:55.235  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:55.236  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:55.236  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:55.236  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:55.236  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:55.236  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:55.236  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:55.236  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:55.236  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:13:55.236  1896  2303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:13:55.236  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:55.236  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:13:55.237  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:55.237  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:55.237  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:55.237  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:55.237  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:55.237  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:55.237  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:55.237  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:55.237  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:13:55.237  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:55.237  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:13:55.238   873  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 18:13:55.260   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 18:13:55.285   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 18:13:55.286   873  1311 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-12 18:13:55.286   873  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:13:55.290   873   890 D Tethering: MasterInitialState.processMessage what=3
09-12 18:13:55.290  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:55.292  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:55.298  1728  1728 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 18:13:55.301  1728  1728 D SystemUpdateService: onCreate
,09-12 18:13:55.303  1728  1728 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 18:13:55.311  1728  1728 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 18:13:55.313  1728  2547 I iu.UploadsManager: num queued entries: 0
09-12 18:13:55.313  1728  2547 I iu.UploadsManager: num updated entries: 0
09-12 18:13:55.313  1728  2547 I iu.SyncManager: NEXT; no task
,09-12 18:13:55.317  1728  4184 I SystemUpdateService: active receiver: enabled
,09-12 18:13:55.319  1728  1728 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 18:13:55.320  1728  1728 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 18:13:55.322  4021  4021 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:13:55.326  4021  4021 D SprintDMHelper: simOperator: 
,09-12 18:13:55.326  4021  4021 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 18:13:55.338  1728  4184 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 18:13:55.353  3955  4187 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-12 18:13:55.355   371   871 E Netd    : netlink response contains error (No such file or directory)
,09-12 18:13:55.356   873  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 18:13:55.356  1728  4184 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-12 18:13:55.356  1728  4184 I SystemUpdateService: now status is 0 (complete)
09-12 18:13:55.357  1728  4184 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 18:13:55.357  1728  4184 I SystemUpdateService: file has been verified
09-12 18:13:55.357  1728  4184 I SystemUpdateService: OTA package size = 12249756
,09-12 18:13:55.365  1728  4184 I SystemUpdateService: showing system update notification
,09-12 18:13:55.372  1728  1728 D SystemUpdateService: onDestroy
,09-12 18:13:58.173   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e6af413:true
,09-12 18:13:58.173  4007  4007 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 18:13:58.178  4007  4007 I bt_bluedroid: init
,09-12 18:13:58.179  4007  4191 I BluetoothAdapterState: Entering OffState
,09-12 18:13:58.185  4007  4192 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 18:13:58.185  4007  4192 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-12 18:13:58.185  4007  4192 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-12 18:13:58.186  4007  4192 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 18:13:58.188  4007  4007 I bt_bluedroid: get_profile_interface socket
,09-12 18:13:58.191  4007  4007 I bt_bluedroid: get_profile_interface sdp
,09-12 18:13:58.195  4007  4195 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 18:13:58.196  4007  4017 I bt_bluedroid: config_hci_snoop_log
,09-12 18:13:58.197  4007  4195 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 18:13:58.200   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 18:13:58.210  4007  4191 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 18:13:58.210  4007  4191 D BluetoothAdapterProperties: Setting state to 14
09-12 18:13:58.210  4007  4191 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 18:13:58.214  4007  4191 D BluetoothBondStateMachine: make
,09-12 18:13:58.219  4007  4196 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 18:13:58.223  4007  4191 I BluetoothAdapterState: Entering PendingCommandState
,09-12 18:13:58.225  4007  4007 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 18:13:58.230  4007  4007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b,
,09-12 18:13:58.231  4007  4007 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 18:13:58.232  4007  4007 D BtGatt.GattService: Received start request. Starting profile...
,09-12 18:13:58.233  4007  4007 D BtGatt.GattService: start()
,09-12 18:13:58.233  4007  4007 I bt_bluedroid: get_profile_interface gatt
09-12 18:13:58.235  4007  4007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b
09-12 18:13:58.235  4007  4007 D BtGatt.AdvertiseManager: advertise manager created
,09-12 18:13:58.246  4007  4007 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:13:58.246  4007  4007 V BluetoothAdapterState: isTurningOn()=false
,09-12 18:13:58.246  4007  4007 V BluetoothAdapterState: isBleTurningOn()=true
09-12 18:13:58.246  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:13:58.247  4007  4191 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 18:13:58.248  4007  4191 I bt_bluedroid: enable
09-12 18:13:58.248  4007  4192 D bt_stack_manager: event_start_up_stack is bringing up the stack.,
09-12 18:13:58.249  4007  4192 I bt_hci  : start_up
,09-12 18:13:58.269  4007  4192 I bt_vendor: alloc value 0xb3939189
,09-12 18:13:58.269  4007  4192 I bt_vendor: init
09-12 18:13:58.269  4007  4192 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 18:13:58.270  4007  4192 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 18:13:58.379  4007  4192 D bt_hci  : start_up starting async portion
,09-12 18:13:58.380  4007  4199 I bt_hci  : event_finish_startup
,09-12 18:13:58.380  4007  4199 I bt_hci_h4: hal_open
,09-12 18:13:58.380  4007  4199 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 18:13:58.389  4007  4199 I bt_userial_vendor: device fd = 51 open
,09-12 18:13:58.418  4007  4199 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 18:13:58.450  4007  4199 D bt_hwcfg: Chipset BCM4354A2
,09-12 18:13:58.450  4007  4199 D bt_hwcfg: Target name = [BCM4354A2]
,09-12 18:13:58.451  4140  4161 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
09-12 18:13:58.451  4007  4199 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 18:13:59.141  4007  4199 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 18:13:59.143  4007  4199 D bt_hwcfg: Settlement delay -- 100 ms
,09-12 18:13:59.143  4007  4199 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 18:13:59.259  4007  4199 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 18:13:59.261  4007  4199 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 18:13:59.290  4007  4199 I bt_hwcfg: vendor lib fwcfg completed
,09-12 18:13:59.291  4007  4199 I bt_vendor: firmware callback
09-12 18:13:59.291  4007  4199 I bt_hci  : firmware_config_callback
,09-12 18:13:59.302  4007  4203 I bt_btu  : btu_task pending for preload complete event
,09-12 18:13:59.302  4007  4203 I bt_btu_task: Bluetooth chip preload is complete
,09-12 18:13:59.303  4007  4203 I bt_btu  : btu_task received preload complete event
,09-12 18:13:59.314  4007  4203 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 18:13:59.315  4007  4203 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-12 18:13:59.315  4007  4203 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-12 18:13:59.316  4007  4203 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 18:13:59.316  4007  4203 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 18:13:59.316  4007  4203 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 18:13:59.316  4007  4203 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 18:13:59.317  4007  4203 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 18:13:59.317  4007  4203 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 18:13:59.317  4007  4203 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 18:13:59.317  4007  4203 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 18:13:59.318  4007  4203 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 18:13:59.318  4007  4203 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 18:13:59.318  4007  4203 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 18:13:59.318  4007  4203 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 18:13:59.453  4007  4203 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38b6d9d
,09-12 18:13:59.453  4007  4203 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38b6d9d 
,09-12 18:13:59.465  4007  4195 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 18:13:59.466  4007  4195 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 18:13:59.467  4007  4195 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 18:13:59.472  4007  4195 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 18:13:59.476  4007  4195 D BluetoothAdapterProperties: Scan Mode:20
,09-12 18:13:59.476  4007  4195 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 18:13:59.477  4007  4195 D bt_hci  : do_postload posting postload work item
09-12 18:13:59.477  4007  4199 I bt_hci  : event_postload
,09-12 18:13:59.477  4007  4199 I bt_vendor: sco_config_cb
,09-12 18:13:59.477  4007  4199 I bt_hci  : sco_config_callback postload finished.
,09-12 18:13:59.480  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:59.480  4007  4195 D bt_bte_conf: Device ID record 1 : primary
,09-12 18:13:59.481  4007  4195 D bt_bte_conf:   vendorId            = 000f
,09-12 18:13:59.481  4007  4195 D bt_bte_conf:   vendorIdSource      = 0001
,09-12 18:13:59.481  4007  4195 D bt_bte_conf:   product             = 1200
,09-12 18:13:59.481  4007  4195 D bt_bte_conf:   version             = 1436
09-12 18:13:59.481  4007  4195 D bt_bte_conf:   clientExecutableURL = 
09-12 18:13:59.482  4007  4195 D bt_bte_conf:   serviceDescription  = 
09-12 18:13:59.482  4007  4195 D bt_bte_conf:   documentationURL    = 
09-12 18:13:59.482  4007  4195 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 18:13:59.482  4007  4192 D bt_stack_manager: event_start_up_stack finished
09-12 18:13:59.483  4007  4199 I bt_vendor: low_power_mode_cb
,09-12 18:13:59.483  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:59.484  4007  4191 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-12 18:13:59.485  4007  4191 D BluetoothAdapterProperties: Setting state to 15
09-12 18:13:59.485  4007  4191 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-12 18:13:59.487  4007  4191 I BluetoothAdapterState: Entering BleOnState
09-12 18:13:59.490  4007  4191 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-12 18:13:59.490  4007  4191 D BluetoothAdapterProperties: Setting state to 11
,09-12 18:13:59.490  4007  4191 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 18:13:59.499  4007  4007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b,
,09-12 18:13:59.501  4007  4007 D HeadsetService: Received start request. Starting profile...
09-12 18:13:59.502  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:59.511  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:59.513  4007  4007 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 18:13:59.514  4007  4007 D HeadsetStateMachine: make
09-12 18:13:59.518  4007  4191 I BluetoothAdapterState: Entering PendingCommandState
,09-12 18:13:59.543  4007  4007 D HeadsetStateMachine: max_hf_connections = 1
,09-12 18:13:59.543  4007  4007 I bt_bluedroid: get_profile_interface handsfree
09-12 18:13:59.544  4007  4195 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-12 18:13:59.544  4007  4195 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 18:13:59.547  4007  4007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b
,09-12 18:13:59.547  4007  4007 D A2dpService: Received start request. Starting profile...
09-12 18:13:59.548  4007  4007 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-12 18:13:59.548  4007  4007 I bt_bluedroid: get_profile_interface avrcp
,09-12 18:13:59.553  4007  4007 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 18:13:59.554  4007  4007 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 18:13:59.554  4007  4007 D A2dpStateMachine: make
,09-12 18:13:59.555  4007  4007 I bt_bluedroid: get_profile_interface a2dp
,09-12 18:13:59.555  4007  4195 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 18:13:59.557  4007  4212 D A2dpStateMachine: Enter Disconnected: -2
,09-12 18:13:59.558  4007  4007 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 18:13:59.559  4007  4007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b
09-12 18:13:59.560  4007  4007 D HidService: Received start request. Starting profile...
09-12 18:13:59.560  4007  4007 I bt_bluedroid: get_profile_interface hidhost
09-12 18:13:59.560  4007  4007 D HidService: setHidService(): set to: null
09-12 18:13:59.560  4007  4195 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38983e5
09-12 18:13:59.560  4007  4195 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-12 18:13:59.561  4007  4007 I BluetoothHealthServiceJni: classInitNative: succeeds
09-12 18:13:59.561  3904  3904 D BluetoothInputDevice: Proxy object connected
09-12 18:13:59.562  4007  4007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b
,09-12 18:13:59.563  4007  4007 D HealthService: Received start request. Starting profile...
,09-12 18:13:59.563  3904  3904 D HidProfile: Bluetooth service connected
,09-12 18:13:59.564  4007  4007 I bt_bluedroid: get_profile_interface health
,09-12 18:13:59.566  1559  1559 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 18:13:59.566  4007  4007 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 18:13:59.567  4007  4007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b
,09-12 18:13:59.569  4007  4007 D PanService: Received start request. Starting profile...
,09-12 18:13:59.569  4007  4007 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 18:13:59.569  4007  4007 I bt_bluedroid: get_profile_interface pan
09-12 18:13:59.569  3904  3904 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 18:13:59.570  4007  4195 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 18:13:59.571  4007  4007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b
09-12 18:13:59.572  3904  3904 D PanProfile: Bluetooth service connected
09-12 18:13:59.573  3904  3904 D BluetoothMap: Proxy object connected
09-12 18:13:59.573  4007  4007 D BluetoothMapService: Received start request. Starting profile...
09-12 18:13:59.573  4007  4007 D BluetoothMapService: start()
09-12 18:13:59.573  3904  3904 D MapProfile: Bluetooth service connected
09-12 18:13:59.573  3904  3904 D BluetoothMap: getConnectedDevices()
09-12 18:13:59.574  3904  3904 D BluetoothMap: Bluetooth is Not enabled
09-12 18:13:59.575  4007  4007 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-12 18:13:59.575  4007  4007 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 18:13:59.576  4007  4007 D BluetoothMapAppObserver: createReceiver()
09-12 18:13:59.577  4007  4007 D BluetoothMapAppObserver: initObservers()
09-12 18:13:59.577  4007  4007 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 18:13:59.584  4007  4007 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:13:59.584  4007  4007 V BluetoothAdapterState: isTurningOn()=true
09-12 18:13:59.584  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:13:59.584  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:13:59.586  4007  4007 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:13:59.586  4007  4007 V BluetoothAdapterState: isTurningOn()=true
09-12 18:13:59.586  4007  4210 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 18:13:59.586  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 18:13:59.586  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:13:59.586  4007  4007 V BluetoothAdapterState: isTurningOff()=false
09-12 18:13:59.586  4007  4007 V BluetoothAdapterState: isTurningOn()=true
09-12 18:13:59.586  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:13:59.586  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:13:59.586  4007  4007 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:13:59.586  4007  4007 V BluetoothAdapterState: isTurningOn()=true
,09-12 18:13:59.586  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:13:59.586  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:13:59.588  4007  4007 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:13:59.588  4007  4007 V BluetoothAdapterState: isTurningOn()=true
09-12 18:13:59.588  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:13:59.588  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:13:59.589  4007  4007 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:13:59.589  4007  4007 V BluetoothAdapterState: isTurningOn()=true
09-12 18:13:59.589  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:13:59.589  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:13:59.589  4007  4191 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 18:13:59.589  4007  4191 D BluetoothAdapterProperties: ScanMode =  20
09-12 18:13:59.589  4007  4191 D BluetoothAdapterProperties: State =  11
,09-12 18:13:59.593  4007  4195 D BluetoothAdapterProperties: Scan Mode:21
09-12 18:13:59.594  4007  4195 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 18:13:59.594  4007  4191 D BluetoothAdapterProperties: Setting state to 12
,09-12 18:13:59.594  4007  4191 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 18:13:59.594   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:13:59.594  4007  4191 I BluetoothAdapterState: Entering OnState
09-12 18:13:59.594  1352  1370 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:13:59.595  1352  2073 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 18:13:59.596  3904  3916 D BluetoothPan: onBluetoothStateChange on: true
09-12 18:13:59.597  1352  1373 D BluetoothMap: onBluetoothStateChange: up=true
09-12 18:13:59.597  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:59.597  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:59.597  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:59.597  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:59.597  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:59.597  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:59.597  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:59.597  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:13:59.598  1352  1352 D BluetoothMap: Proxy object connected
09-12 18:13:59.598  1352  1352 D MapProfile: Bluetooth service connected
09-12 18:13:59.598  1352  1352 D BluetoothMap: getConnectedDevices()
09-12 18:13:59.599  3904  3917 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 18:13:59.599  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:13:59.599  1352  2073 D BluetoothPan: onBluetoothStateChange on: true
09-12 18:13:59.600   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 18:13:59.601  1352  2073 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 18:13:59.601  1352  1352 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 18:13:59.601  1352  1352 D PanProfile: Bluetooth service connected
09-12 18:13:59.602  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:59.602  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:59.602  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:59.602  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:59.602  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:59.602  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:59.602  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:59.602  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:13:59.603   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:13:59.603  4007  4007 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 18:13:59.603  3904  3916 D BluetoothMap: onBluetoothStateChange: up=true
09-12 18:13:59.603  1352  1373 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 18:13:59.603  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:13:59.603  4007  4007 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 18:13:59.605  1352  1352 D BluetoothInputDevice: Proxy object connected
09-12 18:13:59.605  1352  1352 D HidProfile: Bluetooth service connected
09-12 18:13:59.605   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 18:13:59.605  3904  3917 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 18:13:59.607  1957  2302 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:13:59.607  4007  4007 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:13:59.608   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-12 18:13:59.610  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:59.611  4007  4007 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:13:59.612  4007  4007 D ObexServerSockets: Succeed to create listening sockets 
,09-12 18:13:59.612  4007  4007 D ObexServerSockets0: startAccept()
09-12 18:13:59.612  4007  4007 D ObexServerSockets0: prepareForNewConnect()
09-12 18:13:59.612  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:59.613  3904  3904 D LocalBluetoothProfileManager: Adding local A2DP profile
09-12 18:13:59.614  4007  4218 D ObexServerSockets0: Accepting socket connection...
09-12 18:13:59.614  4007  4007 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-12 18:13:59.614  4007  4007 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 18:13:59.615  1352  1352 D BluetoothA2dp: Proxy object connected
09-12 18:13:59.615   873   873 D BluetoothA2dp: Proxy object connected
09-12 18:13:59.615  4007  4219 D ObexServerSockets0: Accepting socket connection...
09-12 18:13:59.616  4007  4007 D BluetoothMapService: onReceive
,09-12 18:13:59.616  4007  4007 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:59.616  4007  4007 D BluetoothMapService: STATE_ON
09-12 18:13:59.620  3904  3904 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-12 18:13:59.624  3904  3904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:13:59.628  3904  3904 D BluetoothA2dp: Proxy object connected
,09-12 18:13:59.630  1559  1559 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:13:59.634  3904  3904 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:13:59.637  1352  1352 D BluetoothPbap: Proxy object connected
,09-12 18:13:59.637  3904  3904 D BluetoothPbap: Proxy object connected
09-12 18:13:59.637  1352  1352 D PbapServerProfile: Bluetooth service connected
09-12 18:13:59.637  3904  3904 D PbapServerProfile: Bluetooth service connected
,09-12 18:13:59.641  4007  4007 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 18:13:59.642  4007  4007 D ObexServerSockets0: prepareForNewConnect()
,09-12 18:13:59.644  4007  4223 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:13:59.653  4007  4227 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:13:59.654  4007  4227 I BtOppRfcommListener: Accept thread started.
,09-12 18:13:59.695   873   873 D BluetoothHeadset: Proxy object connected
,09-12 18:13:59.696  1957  1981 D BluetoothHeadset: Proxy object connected
,09-12 18:13:59.696   873   873 D BluetoothHeadset: Proxy object connected
09-12 18:13:59.697  1352  1373 D BluetoothHeadset: Proxy object connected
,09-12 18:13:59.697  1352  1352 D HeadsetProfile: Bluetooth service connected
09-12 18:13:59.697   873   873 D BluetoothHeadset: Proxy object connected
,09-12 18:13:59.701   873   890 D BluetoothHeadset: Proxy object connected
,09-12 18:13:59.703   873   890 D BluetoothHeadset: Proxy object connected
,09-12 18:13:59.707  1957  1989 D BluetoothHeadset: Proxy object connected
,09-12 18:13:59.722  3904  3916 D BluetoothHeadset: Proxy object connected
,09-12 18:13:59.722  3904  3904 D HeadsetProfile: Bluetooth service connected
,09-12 18:14:01.104   873  1311 D ConnectivityService: handlePromptUnvalidated 101
,09-12 18:14:01.136  4007  4191 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 18:14:01.136  4007  4191 D BluetoothAdapterProperties: Setting state to 13
,09-12 18:14:01.136  4007  4191 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-12 18:14:01.138  4007  4191 D BluetoothAdapterProperties: onBluetoothDisable()
,09-12 18:14:01.147  4007  4191 I BluetoothAdapterState: Entering PendingCommandState
,09-12 18:14:01.151  4007  4007 D BluetoothMapService: onReceive
09-12 18:14:01.151  4007  4007 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:14:01.154  4007  4007 D BluetoothMapService: STATE_TURNING_OFF
09-12 18:14:01.155  4007  4007 D BluetoothMapService: MAP Service closeService in
09-12 18:14:01.155  4007  4007 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 18:14:01.156  4007  4007 D ObexServerSockets0: shutdown(block = true)
09-12 18:14:01.156  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:14:01.156  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:14:01.156  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:01.156  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:01.156  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:14:01.156  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:14:01.156  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:01.156  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:01.156  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:14:01.157  4007  4218 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-12 18:14:01.160  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:14:01.160  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:01.162  4007  4007 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-12 18:14:01.163  4007  4007 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 18:14:01.163  4007  4219 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 18:14:01.164  4007  4007 I BtOppRfcommListener: stopping Accept Thread
09-12 18:14:01.165  4007  4206 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-12 18:14:01.165  4007  4227 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-12 18:14:01.166  4007  4195 D BluetoothAdapterProperties: Scan Mode:20
,09-12 18:14:01.166  4007  4227 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 18:14:01.166  4007  4191 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-12 18:14:01.168  3904  3904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 18:14:01.169  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:14:01.169  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:14:01.169  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:01.169  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:01.169  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:14:01.169  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:14:01.169  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:01.169  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:01.169  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:14:01.171  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:14:01.171  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:01.174  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:14:01.176  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:01.178  4007  4007 D HeadsetService: Received stop request...Stopping profile...
,09-12 18:14:01.181  3904  3904 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:14:01.181   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 18:14:01.181  3904  3916 D BluetoothHeadset: Proxy object disconnected
,09-12 18:14:01.182  4007  4007 D A2dpService: Received stop request...Stopping profile...
09-12 18:14:01.182  1957  2163 D BluetoothHeadset: Proxy object disconnected
09-12 18:14:01.182  4007  4212 D A2dpStateMachine: Exit Disconnected: -1
09-12 18:14:01.183   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 18:14:01.183  1352  1370 D BluetoothHeadset: Proxy object disconnected
09-12 18:14:01.183   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 18:14:01.184  1352  1352 D HeadsetProfile: Bluetooth service disconnected
09-12 18:14:01.185  3904  3904 D HeadsetProfile: Bluetooth service disconnected
09-12 18:14:01.185   873   873 D BluetoothA2dp: Proxy object disconnected
09-12 18:14:01.185  1352  1352 D BluetoothA2dp: Proxy object disconnected
09-12 18:14:01.185  3904  3904 D BluetoothA2dp: Proxy object disconnected
,09-12 18:14:01.188  1559  1559 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 18:14:01.188  4007  4007 D HidService: Received stop request...Stopping profile...
09-12 18:14:01.188  4007  4007 D HidService: Stopping Bluetooth HidService
,09-12 18:14:01.190  1352  1352 D BluetoothInputDevice: Proxy object disconnected
09-12 18:14:01.190  1352  1352 D HidProfile: Bluetooth service disconnected
,09-12 18:14:01.191  4007  4007 D HealthService: Received stop request...Stopping profile...
09-12 18:14:01.192  4007  4007 D PanService: Received stop request...Stopping profile...
09-12 18:14:01.192  3904  3904 D BluetoothInputDevice: Proxy object disconnected
09-12 18:14:01.193  3904  3904 D HidProfile: Bluetooth service disconnected
09-12 18:14:01.193  3904  3904 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 18:14:01.193  1352  1352 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 18:14:01.193  3904  3904 D PanProfile: Bluetooth service disconnected
09-12 18:14:01.193  1352  1352 D PanProfile: Bluetooth service disconnected
09-12 18:14:01.193  4007  4007 D BluetoothMapService: Received stop request...Stopping profile...
09-12 18:14:01.193  4007  4007 D BluetoothMapService: stop()
,09-12 18:14:01.194  4007  4007 D BluetoothMapAppObserver: deinitObservers()
,09-12 18:14:01.194  4007  4007 D BluetoothMapAppObserver: removeReceiver()
09-12 18:14:01.196  1352  1352 D BluetoothMap: Proxy object disconnected
09-12 18:14:01.196  1352  1352 D MapProfile: Bluetooth service disconnected
,09-12 18:14:01.196  4007  4007 V BluetoothAdapterState: isTurningOff()=true
09-12 18:14:01.196  4007  4007 V BluetoothAdapterState: isTurningOn()=false
09-12 18:14:01.196  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:14:01.196  3904  3904 D BluetoothMap: Proxy object disconnected
09-12 18:14:01.196  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:14:01.196  3904  3904 D MapProfile: Bluetooth service disconnected
,09-12 18:14:01.198  4007  4007 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 18:14:01.198  4007  4007 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-12 18:14:01.198  4007  4195 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-12 18:14:01.198  4007  4203 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 18:14:01.198  4007  4203 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 18:14:01.198  4007  4203 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 18:14:01.198  4007  4195 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
09-12 18:14:01.201  4007  4007 V BluetoothAdapterState: isTurningOff()=true
09-12 18:14:01.201  4007  4007 V BluetoothAdapterState: isTurningOn()=false
,09-12 18:14:01.201  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:14:01.201  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:14:01.203  4007  4195 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-12 18:14:01.203  4007  4203 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 18:14:01.203  4007  4203 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 18:14:01.203  4007  4203 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 18:14:01.204  4007  4203 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:14:01.204  4007  4203 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:14:01.204  4007  4203 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:14:01.204  1352  1352 D BluetoothPbap: Proxy object disconnected
,09-12 18:14:01.204  1352  1352 D PbapServerProfile: Bluetooth service disconnected
09-12 18:14:01.205  4007  4007 V BluetoothAdapterState: isTurningOff()=true
09-12 18:14:01.205  4007  4007 V BluetoothAdapterState: isTurningOn()=false
09-12 18:14:01.205  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:14:01.205  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:14:01.206  3904  3904 D BluetoothPbap: Proxy object disconnected
09-12 18:14:01.206  3904  3904 D PbapServerProfile: Bluetooth service disconnected
,09-12 18:14:01.208  4007  4007 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-12 18:14:01.208  4007  4195 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 18:14:01.208  4007  4007 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-12 18:14:01.208  4007  4007 V BluetoothAdapterState: isTurningOff()=true
,09-12 18:14:01.208  4007  4007 V BluetoothAdapterState: isTurningOn()=false
09-12 18:14:01.208  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:14:01.209  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:14:01.209  4007  4007 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 18:14:01.209  4007  4195 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 18:14:01.209  4007  4007 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 18:14:01.210  4007  4007 V BluetoothAdapterState: isTurningOff()=true
,09-12 18:14:01.210  4007  4007 V BluetoothAdapterState: isTurningOn()=false
09-12 18:14:01.210  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:14:01.210  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:14:01.210  4007  4007 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 18:14:01.210  4007  4007 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 18:14:01.211  4007  4007 D BluetoothMapService: MAP Service closeService in
09-12 18:14:01.211  4007  4007 V BluetoothAdapterState: isTurningOff()=true
09-12 18:14:01.211  4007  4007 V BluetoothAdapterState: isTurningOn()=false
09-12 18:14:01.211  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:14:01.211  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:14:01.212  4007  4191 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 18:14:01.212  4007  4191 D BluetoothAdapterProperties: Setting state to 15
,09-12 18:14:01.212  4007  4191 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-12 18:14:01.212  4007  4007 D BluetoothMapService: cleanup()
09-12 18:14:01.212   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:14:01.212  4007  4007 D BluetoothMapService: MAP Service closeService in
09-12 18:14:01.213  4007  4191 I BluetoothAdapterState: Entering BleOnState
09-12 18:14:01.213  1352  1370 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:14:01.213  3904  3916 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:14:01.213  1352  1373 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 18:14:01.214  3904  3917 D BluetoothPan: onBluetoothStateChange on: false
09-12 18:14:01.214  1352  2073 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 18:14:01.215  3904  3916 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 18:14:01.215  3904  3917 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 18:14:01.215  1352  1370 D BluetoothPan: onBluetoothStateChange on: false
09-12 18:14:01.216   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:14:01.216  1352  1373 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 18:14:01.216   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:14:01.216  3904  3916 D BluetoothMap: onBluetoothStateChange: up=false
09-12 18:14:01.217  1352  2073 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 18:14:01.217   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 18:14:01.217  3904  3917 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 18:14:01.218  1957  2302 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:14:01.218  4007  4191 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 18:14:01.218  4007  4191 D BluetoothAdapterProperties: Setting state to 16
09-12 18:14:01.218  4007  4191 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 18:14:01.220  4007  4191 D BluetoothAdapterProperties: onBleDisable
09-12 18:14:01.220  4007  4191 I BluetoothAdapterState: Entering PendingCommandState
,09-12 18:14:01.220  4007  4192 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 18:14:01.221  4007  4203 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-12 18:14:01.222  4007  4203 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 18:14:01.222  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:14:01.223  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:14:01.224  4007  4195 D BluetoothAdapterProperties: Scan Mode:20
09-12 18:14:01.225  3904  3904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:14:01.226  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:14:01.227  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:14:01.230  1559  1559 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:14:01.235  3904  3904 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:14:01.422  4007  4195 I bt_hci  : shut_down
,09-12 18:14:01.440  4007  4199 I bt_vendor: low_power_mode_cb
,09-12 18:14:01.440  4007  4199 D bt_hwcfg: hw_epilog_process
,09-12 18:14:01.460  4007  4199 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 18:14:01.460  4007  4199 I bt_vendor: epilog_cb
09-12 18:14:01.460  4007  4199 I bt_hci  : epilog_finished_callback
,09-12 18:14:01.469  4007  4195 I bt_hci_h4: hal_close
,09-12 18:14:01.470  4007  4195 I bt_userial_vendor: device fd = 51 close
,09-12 18:14:01.584  4007  4192 D bt_stack_manager: event_shut_down_stack finished.
,09-12 18:14:01.585  4007  4191 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 18:14:01.590  4007  4191 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-12 18:14:01.590  4007  4007 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 18:14:01.592  4007  4007 D BtGatt.GattService: Received stop request...Stopping profile...
,09-12 18:14:01.593  4007  4007 D BtGatt.GattService: stop()
09-12 18:14:01.594  4007  4007 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 18:14:01.601  4007  4007 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:14:01.602  4007  4007 V BluetoothAdapterState: isTurningOn()=false
09-12 18:14:01.602  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 18:14:01.602  4007  4007 V BluetoothAdapterState: isBleTurningOff()=true
09-12 18:14:01.603  4007  4191 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-12 18:14:01.604  4007  4191 D BluetoothAdapterProperties: Setting state to 10
09-12 18:14:01.604  4007  4191 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 18:14:01.606  4007  4191 I BluetoothAdapterState: Entering OffState
,09-12 18:14:01.607   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-12 18:14:01.636  4007  4007 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-12 18:14:01.637  4007  4007 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-12 18:14:01.640  4007  4192 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 18:14:01.649  4007  4007 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 18:14:01.651  4007  4192 D bt_stack_manager: event_clean_up_stack finished.
,09-12 18:14:01.652  4007  4007 I art     : System.exit called, status: 0
,09-12 18:14:01.653  4007  4007 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 18:14:01.706   873  1697 I ActivityManager: Process com.android.bluetooth (pid 4007) has died
,09-12 18:14:03.542  3566  3630 D Finsky  : [306] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-12 18:14:03.562  1559  1559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:14:03.571  1559  1559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:14:03.574  1559  1559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:14:03.617  1559  1571 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 18:14:03.617  1559  1571 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-12 18:14:03.617  1559  1571 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 18:14:03.617  1559  1571 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:14:03.646  3566  3630 D Finsky  : [306] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-12 18:14:04.132  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:14:04.133  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:04.646  1559  1559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:14:04.703  1559  2024 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 18:14:04.704  1559  2024 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 18:14:04.704  1559  2024 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 18:14:04.705  1559  2024 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:14:04.731  3566  3566 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 18:14:04.732  3566  3566 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 18:14:04.732  3566  3566 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-12 18:14:07.140  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:14:07.141  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a873e09 added. We now have 6 listener(s)
,09-12 18:14:07.141  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:14:07.146  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:14:07.147   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-12 18:14:07.147  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@472580e added. We now have 7 listener(s)
,09-12 18:14:07.147  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:14:07.149  3833  3885 I System.out: IsBluetoothEnabled
,09-12 18:14:07.158  1881  1881 I Keyboard.Facilitator: onFinishInput()
,09-12 18:14:07.165  3833  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:07.169   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 18:14:07.169   873   893 I Adreno  : Build Date                       : 10/20/15
09-12 18:14:07.169   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 18:14:07.169   873   893 I Adreno  : Local Branch                     : M14
09-12 18:14:07.169   873   893 I Adreno  : Remote Branch                    : 
09-12 18:14:07.169   873   893 I Adreno  : Remote Branch                    : 
09-12 18:14:07.169   873   893 I Adreno  : Reconstruct Branch               : 
,09-12 18:14:07.197   281   305 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (174 us)
,09-12 18:14:07.210   873   890 I ActivityManager: Start proc 4239:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 18:14:07.318  4239  4239 D AdapterServiceConfig: Adding HeadsetService
,09-12 18:14:07.319  4239  4239 D AdapterServiceConfig: Adding A2dpService
,09-12 18:14:07.320  4239  4239 D AdapterServiceConfig: Adding HidService
,09-12 18:14:07.320  4239  4239 D AdapterServiceConfig: Adding HealthService
,09-12 18:14:07.322  4239  4239 D AdapterServiceConfig: Adding PanService
,09-12 18:14:07.322  4239  4239 D AdapterServiceConfig: Adding GattService
,09-12 18:14:07.323  4239  4239 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 18:14:07.349   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@40a970:true
,09-12 18:14:07.349  4239  4239 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 18:14:07.353  4239  4239 I bt_bluedroid: init
,09-12 18:14:07.354  4239  4252 I BluetoothAdapterState: Entering OffState
,09-12 18:14:07.358  4239  4253 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 18:14:07.358  4239  4253 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 18:14:07.358  4239  4253 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-12 18:14:07.359  4239  4253 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 18:14:07.361  4239  4239 I bt_bluedroid: get_profile_interface socket
,09-12 18:14:07.363  4239  4239 I bt_bluedroid: get_profile_interface sdp
09-12 18:14:07.363  4239  4256 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 18:14:07.364  4239  4256 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 18:14:07.367  4239  4251 I bt_bluedroid: config_hci_snoop_log
,09-12 18:14:07.369   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 18:14:07.383  4239  4252 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 18:14:07.384  4239  4252 D BluetoothAdapterProperties: Setting state to 14
09-12 18:14:07.384  4239  4252 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 18:14:07.385  4239  4252 D BluetoothBondStateMachine: make
,09-12 18:14:07.388  4239  4257 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 18:14:07.390  4239  4252 I BluetoothAdapterState: Entering PendingCommandState
,09-12 18:14:07.391  4239  4239 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 18:14:07.393  4239  4239 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b
,09-12 18:14:07.394  4239  4239 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 18:14:07.395  4239  4239 D BtGatt.GattService: Received start request. Starting profile...
,09-12 18:14:07.395  4239  4239 D BtGatt.GattService: start()
09-12 18:14:07.395  4239  4239 I bt_bluedroid: get_profile_interface gatt
09-12 18:14:07.395  4239  4239 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b
,09-12 18:14:07.395  4239  4239 D BtGatt.AdvertiseManager: advertise manager created
,09-12 18:14:07.403  4239  4239 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:14:07.403  4239  4239 V BluetoothAdapterState: isTurningOn()=false
09-12 18:14:07.403  4239  4239 V BluetoothAdapterState: isBleTurningOn()=true
09-12 18:14:07.403  4239  4239 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:14:07.404  4239  4252 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-12 18:14:07.404  4239  4252 I bt_bluedroid: enable
09-12 18:14:07.404  4239  4253 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-12 18:14:07.405  4239  4253 I bt_hci  : start_up
,09-12 18:14:07.414  4239  4253 I bt_vendor: alloc value 0xb399f189
,09-12 18:14:07.414  4239  4253 I bt_vendor: init
09-12 18:14:07.414  4239  4253 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 18:14:07.414  4239  4253 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 18:14:07.523  4239  4253 D bt_hci  : start_up starting async portion
,09-12 18:14:07.524  4239  4260 I bt_hci  : event_finish_startup
,09-12 18:14:07.524  4239  4260 I bt_hci_h4: hal_open
,09-12 18:14:07.524  4239  4260 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 18:14:07.534  4239  4260 I bt_userial_vendor: device fd = 51 open
,09-12 18:14:07.565  4239  4260 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 18:14:07.597  4239  4260 D bt_hwcfg: Chipset BCM4354A2
09-12 18:14:07.598  4239  4260 D bt_hwcfg: Target name = [BCM4354A2]
,09-12 18:14:07.598  4239  4260 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 18:14:07.808  3833  3833 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 18:14:07.808  3833  3833 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 18:14:07.848   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-12 18:14:07.851  3833  3833 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c8e3377 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@457f22f, 16908290=android.view.AbsSavedState$1@457f22f}, android:focusedViewId=100}]}]
09-12 18:14:07.852  3833  3833 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-12 18:14:07.852  3833  3833 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 18:14:07.853   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
09-12 18:14:07.853  3833  3833 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-12 18:14:07.857   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-12 18:14:07.859   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
09-12 18:14:07.859   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-12 18:14:08.092   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-12 18:14:08.095   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0,
09-12 18:14:08.096   873  1336 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,09-12 18:14:08.101   873   893 I DreamManagerService: Entering dreamland.,
,09-12 18:14:08.103   873   893 I PowerManagerService: Dozing...,
,09-12 18:14:08.105   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0,
,09-12 18:14:08.153   375  1317 D audio_hw_primary: adev_set_parameters: enter: screen_state=on,
09-12 18:14:08.153   375  1317 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-12 18:14:08.158   873  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 18:14:08.162   873  1309 E native  : do suspend false
,09-12 18:14:08.163  1942  4263 D NfcService: Discovery configuration equal, not updating.
,09-12 18:14:08.181   873  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 18:14:08.185   873  1309 E native  : do suspend true
,09-12 18:14:08.189  4239  4260 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 18:14:08.189  4239  4260 D bt_hwcfg: Settlement delay -- 100 ms
,09-12 18:14:08.189  4239  4260 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 18:14:08.296   375  1282 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-12 18:14:08.297   375  1282 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-12 18:14:08.309  4239  4260 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 18:14:08.310  4239  4260 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 18:14:08.339  4239  4260 I bt_hwcfg: vendor lib fwcfg completed
,09-12 18:14:08.339  4239  4260 I bt_vendor: firmware callback
09-12 18:14:08.340  4239  4260 I bt_hci  : firmware_config_callback
,09-12 18:14:08.363  4239  4267 I bt_btu  : btu_task pending for preload complete event
,09-12 18:14:08.363  4239  4267 I bt_btu_task: Bluetooth chip preload is complete
,09-12 18:14:08.363  4239  4267 I bt_btu  : btu_task received preload complete event
,09-12 18:14:08.374  4239  4267 I         : BTE_InitTraceLevels -- TRC_HCI
09-12 18:14:08.374  4239  4267 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 18:14:08.374  4239  4267 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-12 18:14:08.375  4239  4267 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 18:14:08.375  4239  4267 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-12 18:14:08.376  4239  4267 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 18:14:08.376  4239  4267 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 18:14:08.377  4239  4267 I         : BTE_InitTraceLevels -- TRC_BTM
,09-12 18:14:08.377  4239  4267 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 18:14:08.377  4239  4267 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 18:14:08.377  4239  4267 I         : BTE_InitTraceLevels -- TRC_SDP
,09-12 18:14:08.379  4239  4267 I         : BTE_InitTraceLevels -- TRC_GATT
,09-12 18:14:08.379  4239  4267 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 18:14:08.379  4239  4267 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 18:14:08.379  4239  4267 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 18:14:08.514  4239  4267 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb391cd9d
,09-12 18:14:08.514  4239  4267 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb391cd9d 
,09-12 18:14:08.524  4239  4256 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-12 18:14:08.526  4239  4256 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 18:14:08.527  4239  4256 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 18:14:08.532  4239  4256 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 18:14:08.535  4239  4256 D BluetoothAdapterProperties: Scan Mode:20
,09-12 18:14:08.536  4239  4256 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 18:14:08.537  4239  4256 D bt_hci  : do_postload posting postload work item
,09-12 18:14:08.538  4239  4260 I bt_hci  : event_postload
,09-12 18:14:08.538  4239  4260 I bt_vendor: sco_config_cb
,09-12 18:14:08.538  4239  4260 I bt_hci  : sco_config_callback postload finished.
,09-12 18:14:08.539  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:08.543  4239  4260 I bt_vendor: low_power_mode_cb
,09-12 18:14:08.544  4239  4256 D bt_bte_conf: Device ID record 1 : primary
,09-12 18:14:08.544  4239  4256 D bt_bte_conf:   vendorId            = 000f
,09-12 18:14:08.544  4239  4256 D bt_bte_conf:   vendorIdSource      = 0001
09-12 18:14:08.545  4239  4256 D bt_bte_conf:   product             = 1200
09-12 18:14:08.545  4239  4256 D bt_bte_conf:   version             = 1436
09-12 18:14:08.545  4239  4256 D bt_bte_conf:   clientExecutableURL = 
,09-12 18:14:08.546  4239  4256 D bt_bte_conf:   serviceDescription  = 
09-12 18:14:08.546  4239  4256 D bt_bte_conf:   documentationURL    = 
09-12 18:14:08.547  4239  4256 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 18:14:08.547  4239  4253 D bt_stack_manager: event_start_up_stack finished
09-12 18:14:08.548  4239  4252 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-12 18:14:08.549  4239  4252 D BluetoothAdapterProperties: Setting state to 15
,09-12 18:14:08.549  4239  4252 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 18:14:08.552  4239  4252 I BluetoothAdapterState: Entering BleOnState
,09-12 18:14:08.557  4239  4252 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-12 18:14:08.557  4239  4252 D BluetoothAdapterProperties: Setting state to 11
,09-12 18:14:08.557  4239  4252 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 18:14:08.564  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:08.570  4239  4239 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b
,09-12 18:14:08.570  4239  4239 D HeadsetService: Received start request. Starting profile...
,09-12 18:14:08.574  4239  4239 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-12 18:14:08.574  4239  4239 D HeadsetStateMachine: make
,09-12 18:14:08.584  4239  4239 D HeadsetStateMachine: max_hf_connections = 1
09-12 18:14:08.584  4239  4239 I bt_bluedroid: get_profile_interface handsfree
09-12 18:14:08.585  4239  4256 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 18:14:08.585  4239  4256 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 18:14:08.590  4239  4252 I BluetoothAdapterState: Entering PendingCommandState
,09-12 18:14:08.592  4239  4239 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b
,09-12 18:14:08.593  1559  1559 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 18:14:08.593  4239  4239 D A2dpService: Received start request. Starting profile...
09-12 18:14:08.594  4239  4239 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 18:14:08.594  4239  4239 I bt_bluedroid: get_profile_interface avrcp
,09-12 18:14:08.603  4239  4239 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 18:14:08.603  4239  4239 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 18:14:08.603  4239  4239 D A2dpStateMachine: make
,09-12 18:14:08.606  4239  4239 I bt_bluedroid: get_profile_interface a2dp
,09-12 18:14:08.607  4239  4256 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 18:14:08.609  4239  4276 D A2dpStateMachine: Enter Disconnected: -2
,09-12 18:14:08.610  4239  4239 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 18:14:08.612  4239  4239 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b
,09-12 18:14:08.613  4239  4239 D HidService: Received start request. Starting profile...
,09-12 18:14:08.613  4239  4239 I bt_bluedroid: get_profile_interface hidhost
,09-12 18:14:08.613  4239  4256 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fe3e5
,09-12 18:14:08.613  4239  4256 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-12 18:14:08.614  4239  4239 D HidService: setHidService(): set to: null
09-12 18:14:08.616  4239  4239 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 18:14:08.617  4239  4239 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b
,09-12 18:14:08.619  4239  4239 D HealthService: Received start request. Starting profile...
,09-12 18:14:08.621  4239  4239 I bt_bluedroid: get_profile_interface health
,09-12 18:14:08.623  4239  4239 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-12 18:14:08.624  4239  4239 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b
09-12 18:14:08.625  4239  4239 D PanService: Received start request. Starting profile...
,09-12 18:14:08.625  4239  4239 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-12 18:14:08.625  4239  4239 I bt_bluedroid: get_profile_interface pan
09-12 18:14:08.626  4239  4256 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 18:14:08.631  4239  4239 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b
,09-12 18:14:08.632  4239  4239 D BluetoothMapService: Received start request. Starting profile...
09-12 18:14:08.632  4239  4239 D BluetoothMapService: start()
,09-12 18:14:08.635  4239  4239 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-12 18:14:08.637  4239  4239 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-12 18:14:08.637  4239  4239 D BluetoothMapAppObserver: createReceiver()
,09-12 18:14:08.639  4239  4239 D BluetoothMapAppObserver: initObservers()
09-12 18:14:08.639  4239  4239 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 18:14:08.657  4239  4239 V BluetoothAdapterState: isTurningOff()=false
09-12 18:14:08.657  4239  4239 V BluetoothAdapterState: isTurningOn()=true
09-12 18:14:08.657  4239  4239 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:14:08.657  4239  4239 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:14:08.660  4239  4274 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-12 18:14:08.660  4239  4239 V BluetoothAdapterState: isTurningOff()=false
09-12 18:14:08.660  4239  4239 V BluetoothAdapterState: isTurningOn()=true
,09-12 18:14:08.660  4239  4239 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 18:14:08.660  4239  4239 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:14:08.660  4239  4239 V BluetoothAdapterState: isTurningOff()=false
09-12 18:14:08.660  4239  4239 V BluetoothAdapterState: isTurningOn()=true
,09-12 18:14:08.660  4239  4239 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 18:14:08.660  4239  4239 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:14:08.661  4239  4239 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:14:08.661  4239  4239 V BluetoothAdapterState: isTurningOn()=true
09-12 18:14:08.661  4239  4239 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 18:14:08.661  4239  4239 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:14:08.661  4239  4239 V BluetoothAdapterState: isTurningOff()=false,
09-12 18:14:08.661  4239  4239 V BluetoothAdapterState: isTurningOn()=true
,09-12 18:14:08.661  4239  4239 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:14:08.661  4239  4239 V BluetoothAdapterState: isBleTurningOff()=false,
09-12 18:14:08.662  4239  4239 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:14:08.662  4239  4239 V BluetoothAdapterState: isTurningOn()=true
09-12 18:14:08.662  4239  4239 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:14:08.662  4239  4239 V BluetoothAdapterState: isBleTurningOff()=false,
09-12 18:14:08.662  4239  4252 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-12 18:14:08.662  4239  4252 D BluetoothAdapterProperties: ScanMode =  20
09-12 18:14:08.663  4239  4252 D BluetoothAdapterProperties: State =  11
,09-12 18:14:08.663  4239  4252 D BluetoothAdapterProperties: Setting state to 12
09-12 18:14:08.663  4239  4252 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 18:14:08.663   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:14:08.664  1352  2073 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 18:14:08.664  4239  4252 I BluetoothAdapterState: Entering OnState
09-12 18:14:08.665  3904  3916 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 18:14:08.666  1352  1373 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 18:14:08.667  4239  4256 D BluetoothAdapterProperties: Scan Mode:21
,09-12 18:14:08.667  4239  4256 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 18:14:08.669  3904  3917 D BluetoothPan: onBluetoothStateChange on: true
,09-12 18:14:08.673  1352  1370 D BluetoothMap: onBluetoothStateChange: up=true
09-12 18:14:08.674  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:14:08.674  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:08.674  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
09-12 18:14:08.674  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:14:08.674  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:08.674  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:08.674  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:08.674  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:14:08.675  3904  3904 D BluetoothPan: BluetoothPAN Proxy object connected,
09-12 18:14:08.675  3904  3904 D PanProfile: Bluetooth service connected
,09-12 18:14:08.676  3904  3917 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 18:14:08.677  1352  1352 D BluetoothMap: Proxy object connected
09-12 18:14:08.678  1352  1352 D MapProfile: Bluetooth service connected,
09-12 18:14:08.678  1352  1352 D BluetoothMap: getConnectedDevices()
09-12 18:14:08.679  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:08.679  3904  3916 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 18:14:08.679  4239  4239 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 18:14:08.680  4239  4239 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 18:14:08.682  1352  1373 D BluetoothPan: onBluetoothStateChange on: true
,09-12 18:14:08.683  4239  4239 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:14:08.684  1352  1352 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 18:14:08.684  1352  1352 D PanProfile: Bluetooth service connected
,09-12 18:14:08.684   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:14:08.684  1352  2073 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 18:14:08.686   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:14:08.686  3904  3917 D BluetoothMap: onBluetoothStateChange: up=true
09-12 18:14:08.687  4239  4239 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:14:08.690  1352  1370 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 18:14:08.690  4239  4239 D ObexServerSockets: Succeed to create listening sockets 
09-12 18:14:08.690  4239  4239 D ObexServerSockets0: startAccept()
,09-12 18:14:08.691  4239  4239 D ObexServerSockets0: prepareForNewConnect()
09-12 18:14:08.691  3904  3904 D BluetoothMap: Proxy object connected
09-12 18:14:08.691   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 18:14:08.691  3904  3904 D MapProfile: Bluetooth service connected
09-12 18:14:08.691  3904  3904 D BluetoothMap: getConnectedDevices()
09-12 18:14:08.692  3904  3916 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 18:14:08.695  1957  2163 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 18:14:08.696  4239  4239 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-12 18:14:08.696  4239  4239 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-12 18:14:08.697   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 18:14:08.700  1352  1352 D BluetoothInputDevice: Proxy object connected
,09-12 18:14:08.700  1352  1352 D HidProfile: Bluetooth service connected
,09-12 18:14:08.701   873   873 D BluetoothA2dp: Proxy object connected
,09-12 18:14:08.701  4239  4283 D ObexServerSockets0: Accepting socket connection...
09-12 18:14:08.701  4239  4239 D BluetoothMapService: onReceive
,09-12 18:14:08.701  4239  4239 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:14:08.701  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:08.701  4239  4239 D BluetoothMapService: STATE_ON
09-12 18:14:08.702  4239  4284 D ObexServerSockets0: Accepting socket connection...
,09-12 18:14:08.707  1352  1352 D BluetoothA2dp: Proxy object connected
,09-12 18:14:08.709  3904  3904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:14:08.713  3904  3904 D BluetoothInputDevice: Proxy object connected
,09-12 18:14:08.713  3904  3904 D HidProfile: Bluetooth service connected
,09-12 18:14:08.716  3904  3904 D BluetoothA2dp: Proxy object connected
09-12 18:14:08.716  1559  1559 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:14:08.722  3904  3904 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:14:08.726  3904  3904 D BluetoothPbap: Proxy object connected
09-12 18:14:08.726  3904  3904 D PbapServerProfile: Bluetooth service connected
,09-12 18:14:08.731  1352  1352 D BluetoothPbap: Proxy object connected
,09-12 18:14:08.732  1352  1352 D PbapServerProfile: Bluetooth service connected
,09-12 18:14:08.734  4239  4239 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 18:14:08.734  4239  4239 D ObexServerSockets0: prepareForNewConnect()
,09-12 18:14:08.740  4239  4289 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:14:08.751  4239  4293 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:14:08.752  4239  4293 I BtOppRfcommListener: Accept thread started.
,09-12 18:14:08.765   873   873 D BluetoothHeadset: Proxy object connected
,09-12 18:14:08.766  3904  3917 D BluetoothHeadset: Proxy object connected
,09-12 18:14:08.766  3904  3904 D HeadsetProfile: Bluetooth service connected
09-12 18:14:08.766  1957  2302 D BluetoothHeadset: Proxy object connected
09-12 18:14:08.766   873   873 D BluetoothHeadset: Proxy object connected
09-12 18:14:08.767  1352  1373 D BluetoothHeadset: Proxy object connected
,09-12 18:14:08.767   873   873 D BluetoothHeadset: Proxy object connected
09-12 18:14:08.767  1352  1352 D HeadsetProfile: Bluetooth service connected
,09-12 18:14:08.784   873   890 D BluetoothHeadset: Proxy object connected
,09-12 18:14:08.786   873   890 D BluetoothHeadset: Proxy object connected
,09-12 18:14:08.796  1957  1981 D BluetoothHeadset: Proxy object connected
,09-12 18:14:09.186  3833  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:14:09.186  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:09.186  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:09.186  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:14:09.186  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:09.186  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:09.186  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:09.186  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:09.193  3833  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:09.197  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:14:09.198  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@496a03c added. We now have 8 listener(s)
,09-12 18:14:09.198  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:14:09.204   873  3125 D WifiService: setWifiEnabled: false pid=3833, uid=10000
,09-12 18:14:09.205   873  3125 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 18:14:09.218  3833  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:14:09.219   873  1998 D WifiService: setWifiEnabled: true pid=3833, uid=10000
,09-12 18:14:09.220   873  1998 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 18:14:09.243   873  1309 D WifiConfigStore: Loading config and enabling all networks 
,09-12 18:14:09.254  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:14:09.254  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:09.254  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:09.254  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:09.254  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:09.254  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:09.254  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:09.254  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:09.261  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:09.271   873  1309 D WifiConfigStore: loaded 0 passpoint configs
,09-12 18:14:09.272   873  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-12 18:14:09.273   873  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-12 18:14:09.274   873  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-12 18:14:09.274   873  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-12 18:14:09.274   873  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-12 18:14:09.274   873  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 18:14:09.295   873  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.06 delta 1000 -> 1000
09-12 18:14:09.295   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-12 18:14:09.295   873  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 18:14:09.297   371   871 D CommandListener: Setting iface cfg
,09-12 18:14:09.304   873  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-12 18:14:09.304   873  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 18:14:09.307   873  1308 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 18:14:09.307   873  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
09-12 18:14:09.308   873  1309 E native  : do suspend true
,09-12 18:14:09.332   873  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-12 18:14:09.332   873  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:14:09.339   873  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 18:14:09.409   873  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 18:14:09.411  1477  1477 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 18:14:09.846  1477  1477 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 18:14:09.894  1477  1477 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 18:14:09.895  1477  1477 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 18:14:09.900   873  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 18:14:09.914   873  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 18:14:09.914   873  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 18:14:09.914   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 18:14:09.943   873  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:14:09.957   371   871 D CommandListener: Setting iface cfg
,09-12 18:14:09.961   873  1309 D WifiStateMachine: Start Dhcp Watchdog 3
,09-12 18:14:09.972   873  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 18:14:09.993   873  4301 D DhcpClient: Receive thread started
,09-12 18:14:10.080   873  1309 E native  : do suspend false
,09-12 18:14:10.100   873  2258 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 18:14:10.113   873  4301 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-12 18:14:10.114   873  2258 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-12 18:14:10.118   873  2258 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 18:14:10.130   873  4301 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 18:14:10.131   873  2258 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 18:14:10.136   371   871 D CommandListener: Setting iface cfg
,09-12 18:14:10.149   873  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-12 18:14:10.151   873  2258 D DhcpClient: Scheduling renewal in 86399s
,09-12 18:14:10.154   873  1309 E native  : do suspend true
,09-12 18:14:10.175   873  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 18:14:10.178   873  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 18:14:10.180   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 18:14:10.182   873  1311 D ConnectivityService: Adding iface wlan0 to network 102
,09-12 18:14:10.196   873  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 18:14:10.240  3833  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:14:10.240  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:10.240  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:10.240  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:10.240  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:10.240  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:10.240  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:10.240  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:10.243  3833  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:10.246  3833  3885 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}],
,09-12 18:14:10.247  3833  3885 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 18:14:10.249  3833  3885 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c8e3377 Bundle[{}]
,09-12 18:14:10.249  3833  3885 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 18:14:10.249  3833  3885 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-12 18:14:10.251  3833  3885 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-12 18:14:10.252  3833  3885 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 18:14:10.252  3833  3885 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-12 18:14:10.253  3833  3885 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-12 18:14:10.254   873  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 18:14:10.255   873  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-12 18:14:10.258   873  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-12 18:14:10.259  3833  3885 I System.out: Running OutgoingSocketThread
09-12 18:14:10.261   873  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-12 18:14:10.263  3833  4304 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 432)
,09-12 18:14:10.266   873  1311 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-12 18:14:10.269  3833  4304 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38020
,09-12 18:14:10.269  3833  4304 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 18:14:10.279   873  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 18:14:10.283   873  1311 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-12 18:14:10.284   873  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-12 18:14:10.284   873  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-12 18:14:10.284   873  1311 D ConnectivityService:    accepting network in place of null
,09-12 18:14:10.284   873  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-12 18:14:10.286   873  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 18:14:10.286   873  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 18:14:10.297   873  4300 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153132, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:14:10.314   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 18:14:10.372   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 18:14:10.377   873  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-12 18:14:10.377   873  4299 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-12 18:14:10.377   873  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 18:14:10.382   873   890 D Tethering: MasterInitialState.processMessage what=3
09-12 18:14:10.393   873  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-12 18:14:10.393  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:14:10.393  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:10.393  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:10.393  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:10.393  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:10.393  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:14:10.393  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:14:10.393  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:14:10.396  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:14:10.411  1728  1728 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 18:14:10.416  1728  1728 D SystemUpdateService: onCreate
,09-12 18:14:10.420  1728  1728 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 18:14:10.432  1728  4311 I SystemUpdateService: active receiver: enabled
,09-12 18:14:10.440  1728  4311 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 18:14:10.441  1728  1728 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 18:14:10.446   873  4299 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 16:14:10 GMT], X-Android-Received-Millis=[1473696850445], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473696850416]}
09-12 18:14:10.446   873  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-12 18:14:10.447   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-12 18:14:10.447   873  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 18:14:10.450   873  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 18:14:10.455  1728  1728 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-12 18:14:10.456  1728  1728 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 18:14:10.458  4021  4021 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:14:10.466  1728  4314 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-12 18:14:10.466  1728  4314 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 18:14:10.467  4021  4021 D SprintDMHelper: simOperator: 
,09-12 18:14:10.467  4021  4021 D SprintDMReceiver: Not Sprint UICC, don't do anything.,
,09-12 18:14:10.471  1728  4314 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 18:14:10.476  1728  4311 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 18:14:10.476  1728  4311 I SystemUpdateService: now status is 0 (complete)
,09-12 18:14:10.476  1728  4311 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 18:14:10.476  1728  4311 I SystemUpdateService: file has been verified
,09-12 18:14:10.477  1728  4311 I SystemUpdateService: OTA package size = 12249756
,09-12 18:14:10.478  1728  2547 I iu.UploadsManager: num queued entries: 0
,09-12 18:14:10.479  1728  2547 I iu.UploadsManager: num updated entries: 0
,09-12 18:14:10.484  1559  1559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:14:10.489  1559  1559 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:14:10.498  1728  4311 I SystemUpdateService: showing system update notification
,09-12 18:14:10.498  1728  2547 I iu.SyncManager: NEXT; no task
,09-12 18:14:10.534  1728  1728 D SystemUpdateService: onDestroy
,09-12 18:14:10.538  1559  2061 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 18:14:10.538  1559  2061 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-12 18:14:10.539  1559  2061 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 18:14:10.540  1559  2061 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:14:10.555  1728  4314 E MDM     : [183] SitrepService.a: Error sending sitrep.
,09-12 18:14:10.584  3955  4317 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 18:14:11.262  3833  3885 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 433)
,09-12 18:14:11.263  3833  3885 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 433)
,09-12 18:14:11.273  3833  3885 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 438)
,09-12 18:14:11.276  3833  3885 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-12 18:14:11.277  3833  3885 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 439)
,09-12 18:14:11.289  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 18:14:11.289  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cb1c5 added. We now have 2 listener(s)
,09-12 18:14:11.298  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 18:14:11.298  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:11.298  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:11.299  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:11.299  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fffe71a added. We now have 9 listener(s)
,09-12 18:14:11.300  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:11.301  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:14:11.306  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:11.313  3833  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:14:11.313  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:11.313  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:11.313  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:11.313  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:11.313  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:14:11.313  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:14:11.313  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:14:11.316  3833  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:14:11.316  3833  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:14:11.316  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:11.316  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74b8428 added. We now have 3 listener(s)
,09-12 18:14:11.318  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 18:14:11.318  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:11.318  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:11.319  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:11.319  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5ba541 added. We now have 10 listener(s)
09-12 18:14:11.319  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:14:11.319  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:14:11.319  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:14:11.319  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:14:11.319  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:11.319  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:11.319  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:14:11.320  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:11.320  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cb1c5 removed from the list
09-12 18:14:11.320  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:11.320  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fffe71a removed from the list
,09-12 18:14:11.322  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:14:11.322  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:14:11.322  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:11.324  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:14:11.324  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:11.326  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:11.326  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 18:14:11.326  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:11.326  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fffe71a not in the list
09-12 18:14:11.326  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:11.326  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:11.330  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:11.330  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:14:11.330  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:11.330  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5ba541 removed from the list
09-12 18:14:11.330  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:11.330  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:14:11.330  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:11.330  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:11.330  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74b8428 removed from the list
09-12 18:14:11.331  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:11.331  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a55ae6 added. We now have 2 listener(s)
09-12 18:14:11.332  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:11.333  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 18:14:11.333  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:11.333  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:11.333  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:14:11.333  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bfdf827 added. We now have 9 listener(s)
09-12 18:14:11.334  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:11.334  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:14:11.338  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:11.344  3833  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:14:11.344  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:11.344  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:11.344  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:11.344  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:11.344  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:14:11.344  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:14:11.344  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:14:11.346  3833  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:14:11.347  3833  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:14:11.347  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:11.347  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc547d added. We now have 3 listener(s)
,09-12 18:14:11.349  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 18:14:11.349  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:11.349  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:11.349  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:11.349  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edc3f72 added. We now have 10 listener(s)
09-12 18:14:11.349  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:11.350  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:14:11.350  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:14:11.350  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 18:14:11.350  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:14:11.350  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 18:14:11.350  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:14:11.354  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:11.355  3833  3885 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 18:14:11.355  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 18:14:11.360  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:14:11.361  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 18:14:11.361  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:14:11.365  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 18:14:11.365  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 18:14:11.365  3833  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:14:11.366  3833  3885 D BluetoothAdapter: STATE_ON
,09-12 18:14:11.370  4239  4272 D BtGatt.GattService: registerClient() - UUID=295e44e3-ea6d-40a8-9972-e07860fd42a6
,09-12 18:14:11.371  4239  4256 D BtGatt.GattService: onClientRegistered() - UUID=295e44e3-ea6d-40a8-9972-e07860fd42a6, clientIf=5
,09-12 18:14:11.372  3833  3844 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 18:14:11.373  4239  4281 D BtGatt.GattService: start scan with filters
,09-12 18:14:11.377  4239  4259 D BtGatt.ScanManager: handling starting scan
,09-12 18:14:11.378   873  1311 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-12 18:14:11.378  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 18:14:11.378  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:14:11.378  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 18:14:11.378  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 18:14:11.381  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:14:11.382  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 18:14:11.382  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 18:14:11.382  4239  4259 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@567a89b
,09-12 18:14:11.384  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:14:11.387  4239  4256 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 18:14:11.387  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:14:11.387  3833  3885 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 18:14:11.388  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 18:14:11.388  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 18:14:11.388  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:14:11.388  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:14:11.388  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:14:11.388  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 18:14:11.389  4239  4259 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 18:14:11.389  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:14:11.389  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 18:14:11.390  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 18:14:11.390  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 18:14:11.392  3833  3885 D BluetoothAdapter: STATE_ON
,09-12 18:14:11.393  4239  4281 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:14:11.394  4239  4285 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 18:14:11.394  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:14:11.395  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 18:14:11.395  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:14:11.395  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 18:14:11.395  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 18:14:11.397  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:14:11.397  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 18:14:11.397  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:14:11.398  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 18:14:11.398  4239  4256 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 18:14:11.398  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:14:11.399  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:14:11.399  4239  4259 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:14:11.399  4239  4259 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 18:14:11.400  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:14:11.400  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:14:11.400  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:14:11.402  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:14:11.403  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:14:11.403  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:14:11.403  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:11.403  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:14:11.403  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:14:11.403  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:11.404  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a55ae6 removed from the list
09-12 18:14:11.404  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:11.404  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bfdf827 removed from the list
09-12 18:14:11.404  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:14:11.404  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:11.405  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:11.405  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:11.406  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:14:11.406  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:11.407  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:11.407  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bfdf827 not in the list
09-12 18:14:11.407  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:11.407  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:11.408  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:11.408  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:11.408  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:14:11.408  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edc3f72 removed from the list
09-12 18:14:11.409  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:11.409  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:11.409  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:11.409  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:11.409  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc547d removed from the list
09-12 18:14:11.410  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:11.410  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2ae0be added. We now have 2 listener(s)
,09-12 18:14:11.412  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 18:14:11.413  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:11.413  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:11.413  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:11.413  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6afc51f added. We now have 9 listener(s)
,09-12 18:14:11.413  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:11.414  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:14:11.418  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:11.420  4239  4256 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 18:14:11.420  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:14:11.424  3833  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:14:11.424  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:11.424  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:11.424  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:11.424  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:11.424  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:14:11.424  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:14:11.424  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:14:11.427  4239  4256 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 18:14:11.427  3833  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:14:11.427  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:14:11.427  3833  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:14:11.428  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:11.428  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a269635 added. We now have 3 listener(s)
,09-12 18:14:11.430  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:11.433  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:11.434  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 18:14:11.434  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:11.434  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 18:14:11.435  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:14:11.435  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6304aca added. We now have 10 listener(s)
,09-12 18:14:11.436  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:14:11.436  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:14:11.436  4239  4256 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 18:14:11.436  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:14:11.437  4239  4259 D BtGatt.ScanManager: stopping BLe Batch
,09-12 18:14:11.437  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:14:11.438  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:14:11.439  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 18:14:11.439  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:14:11.439  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 18:14:11.445  4239  4256 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 18:14:11.445  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:14:11.445  3833  3885 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 18:14:11.445  4239  4259 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 18:14:11.445  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 18:14:11.452  4239  4256 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 18:14:11.452  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:14:11.453  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:14:11.454  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 18:14:11.454  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:14:11.459  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 18:14:11.460  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 18:14:11.460  3833  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:14:11.460  3833  3885 D BluetoothAdapter: STATE_ON
,09-12 18:14:11.463  4239  4251 D BtGatt.GattService: registerClient() - UUID=40ec285e-dedd-4030-aa96-ff9d46054242
,09-12 18:14:11.464  4239  4256 D BtGatt.GattService: onClientRegistered() - UUID=40ec285e-dedd-4030-aa96-ff9d46054242, clientIf=5
,09-12 18:14:11.464  3833  3845 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 18:14:11.465  4239  4250 D BtGatt.GattService: start scan with filters
,09-12 18:14:11.468  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 18:14:11.468  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:14:11.468  4239  4259 D BtGatt.ScanManager: handling starting scan
,09-12 18:14:11.468  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 18:14:11.468  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 18:14:11.472  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:14:11.473  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 18:14:11.473  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 18:14:11.476  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:14:11.477  4239  4256 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 18:14:11.477  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:14:11.478  4239  4259 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 18:14:11.480  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 18:14:11.480  3833  3885 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 18:14:11.481  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:14:11.481  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:14:11.481  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 18:14:11.482  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:14:11.482  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:14:11.482  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:14:11.482  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:11.483  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2ae0be removed from the list
,09-12 18:14:11.483  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:11.483  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6afc51f removed from the list
09-12 18:14:11.483  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:14:11.483  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:14:11.484  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:14:11.484  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-12 18:14:11.484  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:11.484  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:14:11.487  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:14:11.487  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 18:14:11.487  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:14:11.487  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6afc51f not in the list
,09-12 18:14:11.487  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 18:14:11.487  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:14:11.487  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:14:11.488  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 18:14:11.489  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 18:14:11.490  3833  3885 D BluetoothAdapter: STATE_ON
,09-12 18:14:11.490  4239  4256 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 18:14:11.490  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:14:11.491  4239  4259 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:14:11.491  4239  4250 D BtGatt.GattService: stopScan() - queue size =1
09-12 18:14:11.491  4239  4259 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 18:14:11.492  4239  4281 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 18:14:11.492  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 18:14:11.493  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 18:14:11.493  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:14:11.493  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 18:14:11.493  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 18:14:11.495  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:14:11.496  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 18:14:11.496  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 18:14:11.496  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 18:14:11.497  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:11.501  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:11.502  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:11.502  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:11.502  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 18:14:11.502  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6304aca removed from the list
09-12 18:14:11.502  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:14:11.502  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:11.502  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:14:11.502  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:11.502  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:11.503  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:11.503  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a269635 removed from the list
09-12 18:14:11.504  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:11.505  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1704996 added. We now have 2 listener(s)
09-12 18:14:11.508  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 18:14:11.508  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:11.508  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:11.508  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:14:11.509  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33f3917 added. We now have 9 listener(s)
09-12 18:14:11.509  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:11.509  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 18:14:11.510  4239  4256 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 18:14:11.511  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:14:11.514  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:11.517  4239  4256 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 18:14:11.517  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:14:11.520  3833  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:14:11.520  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:11.520  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:11.520  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:11.520  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:11.520  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:14:11.520  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:14:11.520  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:14:11.523  3833  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:14:11.523  3833  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:14:11.524  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 18:14:11.524  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb056ed added. We now have 3 listener(s)
09-12 18:14:11.524  4239  4256 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 18:14:11.524  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:14:11.525  4239  4259 D BtGatt.ScanManager: stopping BLe Batch
,09-12 18:14:11.526  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 18:14:11.526  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:11.526  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:11.526  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:14:11.526  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:14:11.526  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df6922 added. We now have 10 listener(s)
09-12 18:14:11.526  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:11.527  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:14:11.527  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:14:11.527  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:14:11.527  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:11.527  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 18:14:11.530  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:14:11.531  3833  3885 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 18:14:11.531  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 18:14:11.532  4239  4256 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 18:14:11.533  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:14:11.533  4239  4259 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 18:14:11.537  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:14:11.538  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 18:14:11.538  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:14:11.539  4239  4256 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 18:14:11.539  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:14:11.542  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 18:14:11.542  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 18:14:11.543  3833  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:14:11.543  3833  3885 D BluetoothAdapter: STATE_ON
,09-12 18:14:11.546  4239  4281 D BtGatt.GattService: registerClient() - UUID=1accc8a2-ddba-4021-afee-cf9de71acaca
,09-12 18:14:11.546  4239  4256 D BtGatt.GattService: onClientRegistered() - UUID=1accc8a2-ddba-4021-afee-cf9de71acaca, clientIf=5
09-12 18:14:11.547  3833  3844 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 18:14:11.547  4239  4272 D BtGatt.GattService: start scan with filters
,09-12 18:14:11.550  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 18:14:11.550  4239  4259 D BtGatt.ScanManager: handling starting scan
09-12 18:14:11.550  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:14:11.550  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 18:14:11.550  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 18:14:11.555  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:14:11.555  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 18:14:11.556  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 18:14:11.557  4239  4256 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 18:14:11.557  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:14:11.557  4239  4259 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 18:14:11.558  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:14:11.563  4239  4256 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 18:14:11.563  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:14:11.563  4239  4259 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:14:11.563  4239  4259 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 18:14:11.565  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:14:11.565  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:14:11.565  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 18:14:11.566  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:11.566  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:11.566  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:14:11.566  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:11.566  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1704996 removed from the list
09-12 18:14:11.566  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:14:11.566  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33f3917 removed from the list
09-12 18:14:11.566  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:14:11.566  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:14:11.567  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:11.567  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-12 18:14:11.567  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:14:11.567  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:14:11.569  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:14:11.569  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:11.569  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:14:11.569  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33f3917 not in the list
09-12 18:14:11.569  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 18:14:11.569  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 18:14:11.569  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:14:11.570  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 18:14:11.570  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 18:14:11.571  3833  3885 D BluetoothAdapter: STATE_ON
,09-12 18:14:11.571  4239  4251 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:14:11.572  4239  4281 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 18:14:11.572  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 18:14:11.573  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 18:14:11.573  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 18:14:11.573  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 18:14:11.573  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 18:14:11.574  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:14:11.575  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 18:14:11.575  3833  3885 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:14:11.575  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 18:14:11.575  4239  4256 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 18:14:11.575  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:14:11.576  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:11.577  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:11.577  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:14:11.577  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:11.577  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df6922 removed from the list
09-12 18:14:11.577  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 18:14:11.577  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:11.578  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:14:11.578  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:14:11.578  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:11.578  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:14:11.578  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:11.578  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb056ed removed from the list
09-12 18:14:11.579  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 18:14:11.579  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2ef56e added. We now have 2 listener(s)
09-12 18:14:11.582  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 18:14:11.582  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:11.582  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:11.582  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:14:11.582  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cda340f added. We now have 9 listener(s)
09-12 18:14:11.582  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:11.583  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 18:14:11.583  4239  4256 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 18:14:11.583  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:14:11.587  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:11.591  4239  4256 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 18:14:11.591  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:14:11.591  4239  4259 D BtGatt.ScanManager: stopping BLe Batch
09-12 18:14:11.592  3833  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:14:11.592  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:11.592  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:11.592  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:11.592  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:11.592  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:14:11.592  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:14:11.592  3833  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:14:11.594  3833  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:14:11.594  3833  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:14:11.595  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:11.595  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2a76a5 added. We now have 3 listener(s)
,09-12 18:14:11.597  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:11.598  4239  4256 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 18:14:11.598  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:14:11.598  4239  4259 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 18:14:11.599  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:11.600  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 18:14:11.600  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 18:14:11.601  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 18:14:11.601  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:11.601  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d8fa7a added. We now have 10 listener(s)
09-12 18:14:11.601  3833  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:14:11.601  3833  3885 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:14:11.602  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:14:11.602  3833  3885 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 18:14:11.603  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:14:11.603  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:11.603  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:14:11.603  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:11.604  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2ef56e removed from the list
,09-12 18:14:11.604  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:11.604  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cda340f removed from the list
,09-12 18:14:11.604  4239  4256 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 18:14:11.604  3833  3885 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:14:11.604  4239  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:14:11.604  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:11.605  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:11.605  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:11.606  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:11.606  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:11.606  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:11.606  3833  3885 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cda340f not in the list
09-12 18:14:11.606  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:11.606  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:11.607  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:11.607  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:11.607  3833  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:11.607  3833  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d8fa7a removed from the list
09-12 18:14:11.608  3833  3885 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:11.608  3833  3885 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:11.608  3833  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:11.608  3833  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:11.608  3833  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2a76a5 removed from the list
09-12 18:14:11.609  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 18:14:11.609  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 18:14:11.609  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 18:14:11.609  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:14:11.609  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 18:14:11.610  3833  3885 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 18:14:11.616  3833  4323 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 446, name: My test thread name)
09-12 18:14:11.616  3833  4323 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 446, thread name: My test thread name)
09-12 18:14:11.616  3833  4323 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 446, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-12 18:14:11.618  3833  4324 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 448, name: My test thread name)
09-12 18:14:11.618  3833  4324 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 448, thread name: My test thread name)
09-12 18:14:11.618  3833  4324 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 448, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-12 18:14:11.620  3833  3885 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-12 18:14:11.620  3833  3885 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-12 18:14:11.620  3833  3885 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-12 18:14:11.620  3833  3885 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-12 18:14:11.620  3833  3885 D com.test.thalitest.ThaliTestRunner: Total duration: 22907 ms
09-12 18:14:11.622  3833  3885 I jxcore-log: *Native tests were executed*
09-12 18:14:11.622  3833  3885 I jxcore-log: 
09-12 18:14:11.623  3833  3885 I jxcore-log: Total number of executed tests:  80
09-12 18:14:11.623  3833  3885 I jxcore-log: 
09-12 18:14:11.623  3833  3885 I jxcore-log: Number of passed tests:  80
09-12 18:14:11.623  3833  3885 I jxcore-log: 
09-12 18:14:11.623  3833  3885 I jxcore-log: Number of failed tests:  0
09-12 18:14:11.623  3833  3885 I jxcore-log: 
09-12 18:14:11.623  3833  3885 I jxcore-log: Number of ignored tests:  0
09-12 18:14:11.623  3833  3885 I jxcore-log: 
09-12 18:14:11.624  3833  3885 I jxcore-log: Total duration:  22907
09-12 18:14:11.624  3833  3885 I jxcore-log: 
09-12 18:14:11.624  3833  3885 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-12 18:14:11.624  3833  3885 I jxcore-log: 
09-12 18:14:11.631  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:11.631  3833  3885 I jxcore-log: 
09-12 18:14:11.635  3833  3833 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-12 18:14:11.639  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:11.639  3833  3885 I jxcore-log: 
09-12 18:14:11.641  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:11.641  3833  3885 I jxcore-log: 
09-12 18:14:11.643  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:11.643  3833  3885 I jxcore-log: 
09-12 18:14:11.644  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:11.644  3833  3885 I jxcore-log: 
09-12 18:14:11.647  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:11.647  3833  3885 I jxcore-log: 
09-12 18:14:11.651  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:11.651  3833  3885 I jxcore-log: 
09-12 18:14:11.654  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 18:14:11.654  3833  3885 I jxcore-log: 
09-12 18:14:11.656  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 18:14:11.656  3833  3885 I jxcore-log: 
09-12 18:14:11.657  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:14:11.657  3833  3885 I jxcore-log: 
09-12 18:14:11.659  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:14:11.659  3833  3885 I jxcore-log: 
09-12 18:14:11.660  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:14:11.660  3833  3885 I jxcore-log: 
,09-12 18:14:11.662  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 18:14:11.662  3833  3885 I jxcore-log: 
09-12 18:14:11.662  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 18:14:11.662  3833  3885 I jxcore-log: 
09-12 18:14:11.663  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:11.663  3833  3885 I jxcore-log: 
09-12 18:14:11.664  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:11.664  3833  3885 I jxcore-log: 
09-12 18:14:11.665  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:14:11.665  3833  3885 I jxcore-log: 
09-12 18:14:11.666  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:14:11.666  3833  3885 I jxcore-log: 
09-12 18:14:11.666  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:14:11.666  3833  3885 I jxcore-log: 
09-12 18:14:11.667  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:14:11.667  3833  3885 I jxcore-log: 
09-12 18:14:11.668  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:14:11.668  3833  3885 I jxcore-log: 
09-12 18:14:11.669  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:14:11.669  3833  3885 I jxcore-log: 
09-12 18:14:11.670  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:14:11.670  3833  3885 I jxcore-log: 
09-12 18:14:11.671  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:14:11.671  3833  3885 I jxcore-log: 
09-12 18:14:11.671  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 18:14:11.671  3833  3885 I jxcore-log: 
09-12 18:14:11.672  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 18:14:11.672  3833  3885 I jxcore-log: 
09-12 18:14:11.673  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:11.673  3833  3885 I jxcore-log: 
09-12 18:14:11.674  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:11.674  3833  3885 I jxcore-log: 
09-12 18:14:11.675  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:11.675  3833  3885 I jxcore-log: 
09-12 18:14:11.676  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:11.676  3833  3885 I jxcore-log: 
09-12 18:14:11.677  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:11.677  3833  3885 I jxcore-log: 
09-12 18:14:11.678  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:11.678  3833  3885 I jxcore-log: 
,09-12 18:14:11.901  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 18:14:11.905  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:14:11.905  3833  3885 I jxcore-log: 
,09-12 18:14:12.002  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 18:14:12.005  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:14:12.005  3833  3885 I jxcore-log: 
,09-12 18:14:12.078  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 18:14:12.082  3833  3885 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:14:12.082  3833  3885 I jxcore-log: 
,09-12 18:14:12.314  4325  4325 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-12 18:14:12.319  4325  4325 D AndroidRuntime: CheckJNI is OFF
,09-12 18:14:12.362  4325  4325 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-12 18:14:12.411  4325  4325 I Radio-JNI: register_android_hardware_Radio DONE
,09-12 18:14:12.433  4325  4325 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-12 18:14:12.443   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-12 18:14:12.444   873   886 I ActivityManager: Killing 3833:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-12 18:14:12.538   873  2238 D GraphicsStats: Buffer count: 2
,09-12 18:14:12.539   873  1310 D WifiService: Client connection lost with reason: 4
09-12 18:14:12.540   873  3125 I WindowState: WIN DEATH: Window{242604c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-12 18:14:12.589   873   896 W PackageSettings: Skipping PackageSetting{65bdf9c com.example.hello/10273} due to missing metadata
,09-12 18:14:12.616   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-12 18:14:12.616   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-12 18:14:12.618   873   886 E ActivityManager: Failure starting process com.test.thalitest
09-12 18:14:12.618   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-12 18:14:12.618   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-12 18:14:12.618   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-12 18:14:12.618   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-12 18:14:12.618   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-12 18:14:12.618   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-12 18:14:12.618   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-12 18:14:12.618   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-12 18:14:12.618   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-12 18:14:12.618   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-12 18:14:12.618   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-12 18:14:12.618   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-12 18:14:12.618   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-12 18:14:12.618   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-12 18:14:12.618   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-12 18:14:12.618   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:14:12.618   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:14:12.618   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 18:14:12.618   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-12 18:14:12.620   873   886 I ActivityManager:   Force finishing activity ActivityRecord{97cb690 u0 com.test.thalitest/.MainActivity t4}
,09-12 18:14:12.624   873   896 I art     : Starting a blocking GC Explicit
,09-12 18:14:12.636   873  1698 W ActivityManager: Spurious death for ProcessRecord{e01da6d 0:com.test.thalitest/u0a0}, curProc for 3833: null
,09-12 18:14:12.711   873   896 I art     : Explicit concurrent mark sweep GC freed 55972(3MB) AllocSpace objects, 10(300KB) LOS objects, 33% free, 29MB/43MB, paused 1.225ms total 85.735ms
,09-12 18:14:12.744   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-12 18:14:12.748  4325  4325 I art     : System.exit called, status: 0
,09-12 18:14:12.749  4325  4325 I AndroidRuntime: VM exiting with result code 0.
,09-12 18:14:12.759   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-12 18:14:12.781   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-12 18:14:12.787  1896  2260 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-12 18:14:12.788  4239  4239 D BluetoothMapAppObserver: onReceive
09-12 18:14:12.788  4239  4239 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-12 18:14:12.790  1881  1881 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-12 18:14:12.793   873  1301 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-12 18:14:12.798  3703  3703 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-12 18:14:12.812  1881  4338 I Keyboard.Facilitator.DecoderInitializer: run()
,09-12 18:14:12.818  1881  4338 I Decoder : createOrResetDecoder
,09-12 18:14:12.832  1957  1957 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-12 18:14:12.836   873  2153 I ActivityManager: Start proc 4340:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-12 18:14:12.840  1559  1559 I ConfigService: onCreate
,09-12 18:14:12.881  4340  4340 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-12 18:14:12.881  1881  4338 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-12 18:14:12.899   873  1698 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3833 uid 10000
,09-12 18:14:12.900  1881  1881 I Keyboard.Facilitator: onFinishInput()
,09-12 18:14:12.905   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-12 18:14:12.913  1881  4338 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-12 18:14:12.914  1881  4338 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-12 18:14:12.914  1881  4338 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-12 18:14:12.916  1881  4338 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-12 18:14:12.916  1881  4338 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-12 18:14:12.917  1881  4338 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-12 18:14:12.917  1881  4338 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-12 18:14:12.918  1881  4338 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-12 18:14:12.918  1881  4338 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-12 18:14:12.918  1881  4338 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-12 18:14:12.919  1881  4338 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,09-12 18:14:12.919  1881  4338 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-12 18:14:12.919  1881  4338 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-12 18:14:12.919   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-12 18:14:12.920   873   885 E PackageManager: Failed to write settings, restoring backup
09-12 18:14:12.920   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-12 18:14:12.920   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-12 18:14:12.920   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-12 18:14:12.920   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-12 18:14:12.920   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-12 18:14:12.920   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:14:12.920   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:14:12.920   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 18:14:12.924   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-12 18:14:12.924   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 18:14:12.924   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 18:14:12.924   873   886 E DropBoxManagerService: 	... 13 more
,09-12 18:14:12.931  4340  4340 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-12 18:14:12.934  1964  2079 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-12 18:14:12.948   873  2059 I ActivityManager: Start proc 4357:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-12 18:14:12.948  1964  2079 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-12 18:14:12.948  1964  2079 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1964
09-12 18:14:12.948  1964  2079 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 18:14:12.948  1964  2079 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 18:14:12.948  1964  2079 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 18:14:12.948  1964  2079 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 18:14:12.948  1964  2079 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 18:14:12.948  1964  2079 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 18:14:12.948  1964  2079 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-12 18:14:12.948  1964  2079 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-12 18:14:12.948  1964  2079 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 18:14:12.948  1964  2079 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 18:14:12.948  1964  2079 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:14:12.948  1964  2079 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 18:14:12.950   873  1996 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 18:14:12.951   873  4362 E DropBoxManagerService: Can't write: system_app_crash
09-12 18:14:12.951   873  4362 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-12 18:14:12.951   873  4362 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 18:14:12.951   873  4362 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 18:14:12.951   873  4362 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 18:14:12.951   873  4362 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 18:14:12.951   873  4362 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 18:14:12.951   873  4362 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 18:14:12.951   873  4362 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 18:14:12.951   873  4362 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 18:14:12.951   873  4362 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 18:14:12.951   873  4362 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 18:14:12.951   873  4362 E DropBoxManagerService: 	... 5 more
,09-12 18:14:12.956  1964  2079 I Process : Sending signal. PID: 1964 SIG: 9
,09-12 18:14:12.970   873  1698 I ActivityManager: Start proc 4370:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-12 18:14:12.974  4340  4376 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-12 18:14:12.990  4340  4376 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:14:12.990  4340  4376 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 18:14:12.991  4340  4376 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-12 18:14:12.991  4340  4376 E AndroidRuntime: Process: android.process.acore, PID: 4340
09-12 18:14:12.991  4340  4376 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:14:12.991  4340  4376 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 18:14:12.994  4340  4376 I Process : Sending signal. PID: 4340 SIG: 9
,09-12 18:14:12.994   873  4384 E DropBoxManagerService: Can't write: system_app_crash
09-12 18:14:12.994   873  4384 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-12 18:14:12.994   873  4384 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 18:14:12.994   873  4384 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 18:14:12.994   873  4384 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 18:14:12.994   873  4384 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 18:14:12.994   873  4384 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 18:14:12.994   873  4384 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 18:14:12.994   873  4384 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 18:14:12.994   873  4384 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 18:14:12.994   873  4384 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 18:14:12.994   873  4384 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 18:14:12.994   873  4384 E DropBoxManagerService: 	... 5 more
,09-12 18:14:13.011  4370  4370 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-12 18:14:13.025   279   279 E lowmemorykiller: Error writing /proc/4340/oom_score_adj; errno=22
,09-12 18:14:13.034  1559  1559 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-12 18:14:13.034   873  1309 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,09-12 18:14:13.034  1559  1559 D AndroidRuntime: Shutting down VM
,09-12 18:14:13.035  1559  1559 E AndroidRuntime: FATAL EXCEPTION: main
09-12 18:14:13.035  1559  1559 E AndroidRuntime: Process: com.google.process.gapps, PID: 1559
09-12 18:14:13.035  1559  1559 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850),
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-12 18:14:13.035  1559  1559 E AndroidRuntime: ,	... 8 more
,09-12 18:14:13.038   873  4389 E DropBoxManagerService: Can't write: system_app_crash
09-12 18:14:13.038   873  4389 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-12 18:14:13.038   873  4389 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 18:14:13.038   873  4389 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 18:14:13.038   873  4389 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 18:14:13.038   873  4389 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 18:14:13.038   873  4389 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 18:14:13.038   873  4389 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 18:14:13.038   873  4389 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 18:14:13.038   873  4389 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 18:14:13.038   873  4389 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 18:14:13.038   873  4389 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 18:14:13.038   873  4389 E DropBoxManagerService: 	... 5 more
,09-12 18:14:13.039  1559  1559 I Process : Sending signal. PID: 1559 SIG: 9
09-12 18:14:13.040   873  1697 D GraphicsStats: Buffer count: 1
09-12 18:14:13.040   873  1987 I WindowState: WIN DEATH: Window{d71a26d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-12 18:14:13.046   873  1998 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1964) has died
09-12 18:14:13.047   873  1998 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-12 18:14:13.048   873  1998 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-12 18:14:13.064   873   886 I ActivityManager: Start proc 4391:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 18:14:13.074   279   279 E lowmemorykiller: Error writing /proc/4340/oom_score_adj; errno=22
,09-12 18:14:13.081   873   891 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 116)
,09-12 18:14:13.082   873   891 W DisplayManagerService: Failed to notify process 1559 that displays changed, assuming it died.
09-12 18:14:13.082   873   891 W DisplayManagerService: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-12 18:14:13.082   873   891 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 18:14:13.082   873   891 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:503)
09-12 18:14:13.082   873   891 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
09-12 18:14:13.082   873   891 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1166)
09-12 18:14:13.082   873   891 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1004)
09-12 18:14:13.082   873   891 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.-wrap6(DisplayManagerService.java)
09-12 18:14:13.082   873   891 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1099)
09-12 18:14:13.082   873   891 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:14:13.082   873   891 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:14:13.082   873   891 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 18:14:13.082   873   891 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-12 18:14:13.091   873  1310 D WifiService: Client connection lost with reason: 4
,09-12 18:14:13.095   873  1697 I ActivityManager: Process com.google.process.gapps (pid 1559) has died
,09-12 18:14:13.095   873  1697 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
,09-12 18:14:13.096   873  1697 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 10999ms
09-12 18:14:13.096   873  1697 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
,09-12 18:14:13.096   873  1697 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
,09-12 18:14:13.105  1728  1728 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-12 18:14:13.114  4391  4391 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:14:13.114  4391  4391 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 18:14:13.114  4391  4391 D AndroidRuntime: Shutting down VM
,09-12 18:14:13.124   873  1392 I ActivityManager: Start proc 4405:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,09-12 18:14:13.127   873  3125 I ActivityManager: Process android.process.acore (pid 4340) has died
,09-12 18:14:13.127   873  3125 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30968ms
,09-12 18:14:13.136  4391  4391 E AndroidRuntime: FATAL EXCEPTION: main
09-12 18:14:13.136  4391  4391 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4391
09-12 18:14:13.136  4391  4391 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 18:14:13.136  4391  4391 E AndroidRuntime: 	... 10 more
09-12 18:14:13.138   873  1392 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 18:14:13.139  4391  4391 I Process : Sending signal. PID: 4391 SIG: 9
09-12 18:14:13.146   873  4418 E DropBoxManagerService: Can't write: system_app_crash
09-12 18:14:13.146   873  4418 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-12 18:14:13.146   873  4418 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 18:14:13.146   873  4418 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 18:14:13.146   873  4418 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 18:14:13.146   873  4418 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 18:14:13.146   873  4418 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 18:14:13.146   873  4418 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 18:14:13.146   873  4418 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 18:14:13.146   873  4418 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 18:14:13.146   873  4418 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 18:14:13.146   873  4418 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 18:14:13.146   873  4418 E DropBoxManagerService: 	... 5 more
,09-12 18:14:13.154  1728  1728 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-12 18:14:13.154  1728  1728 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-12 18:14:13.159   873  1987 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4391) has died
,09-12 18:14:13.159  1728  1728 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-12 18:14:13.160  1728  1728 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-12 18:14:13.160   873  1987 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-12 18:14:13.162  4405  4405 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-12 18:14:13.164  1728  4420 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-12 18:14:13.172  4405  4405 I MultiDex: VM with version 2.1.0 has multidex support
,09-12 18:14:13.172  4405  4405 I MultiDex: install
09-12 18:14:13.172  4405  4405 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-12 18:14:13.177   873   886 I ActivityManager: Start proc 4422:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 18:14:13.180  4405  4405 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,09-12 18:14:13.183  1728  4420 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
09-12 18:14:13.183  1728  4420 E AndroidRuntime: Process: com.google.android.gms, PID: 1728
09-12 18:14:13.183  1728  4420 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:14:13.183  1728  4420 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,09-12 18:14:13.184  4405  4405 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,09-12 18:14:13.186   873  4429 E DropBoxManagerService: Can't write: system_app_crash
09-12 18:14:13.186   873  4429 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-12 18:14:13.186   873  4429 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 18:14:13.186   873  4429 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 18:14:13.186   873  4429 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 18:14:13.186   873  4429 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 18:14:13.186   873  4429 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 18:14:13.186   873  4429 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 18:14:13.186   873  4429 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 18:14:13.186   873  4429 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 18:14:13.186   873  4429 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 18:14:13.186   873  4429 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 18:14:13.186   873  4429 E DropBoxManagerService: 	... 5 more
,09-12 18:14:13.186  4405  4405 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	,at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:14:13.186  4405  4405 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 18:14:13.186  4405  4405 D AndroidRuntime: Shutting down VM
,09-12 18:14:13.186  1728  4420 I Process : Sending signal. PID: 1728 SIG: 9
,09-12 18:14:13.187  4405  4405 E AndroidRuntime: FATAL EXCEPTION: main
09-12 18:14:13.187  4405  4405 E AndroidRuntime: Process: com.google.process.gapps, PID: 4405
09-12 18:14:13.187  4405  4405 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	at android.app.ActivityTh,read.installProvider(ActivityThread.java:5153)
09-12 18:14:13.187  4405  4405 E AndroidRuntime: 	... 10 more
09-12 18:14:13.189   873  3125 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
09-12 18:14:13.189   873  3125 I ActivityManager: Killing 4405:com.google.process.gapps/u0a11 (adj 0): crash
,09-12 18:14:13.199   873  4434 E DropBoxManagerService: Can't write: system_app_crash
09-12 18:14:13.199   873  4434 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-12 18:14:13.199   873  4434 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 18:14:13.199   873  4434 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 18:14:13.199   873  4434 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 18:14:13.199   873  4434 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 18:14:13.199   873  4434 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 18:14:13.199   873  4434 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 18:14:13.199   873  4434 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 18:14:13.199   873  4434 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 18:14:13.199   873  4434 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 18:14:13.199   873  4434 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 18:14:13.199   873  4434 E DropBoxManagerService: 	... 5 more
,09-12 18:14:13.231   873  3125 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 224)
,09-12 18:14:13.232   873  3125 W ActivityManager: Failure disconnecting service ComponentInfo{com.google.android.gms/com.google.android.gms.auth.GetToken} to connection android.os.BinderProxy@e68ddb6 (in com.google.android.gms)
09-12 18:14:13.232   873  3125 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-12 18:14:13.232   873  3125 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1704)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2336)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15543)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4567)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:12031)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:11933)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:12622)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12129)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 18:14:13.232   873  3125 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 272)
,09-12 18:14:13.232   873  3125 W ActivityManager: Failure disconnecting service ComponentInfo{com.google.android.gms/com.google.android.gms.clearcut.service.ClearcutLoggerService} to connection android.os.BinderProxy@21f4b3 (in com.google.android.gms)
09-12 18:14:13.232   873  3125 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-12 18:14:13.232   873  3125 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1704)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2336)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15543)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4567)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:12031)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:11933)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:12622)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12129)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-12 18:14:13.232   873  3125 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 18:14:13.233   873  3125 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 272)
09-12 18:14:13.233   873  3125 W ActivityManager: Failure disconnecting service ComponentInfo{com.google.android.gms/com.google.android.gms.clearcut.service.ClearcutLoggerService} to connection android.os.BinderProxy@21f4b3 (in com.google.android.gms)
09-12 18:14:13.233   873  3125 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-12 18:14:13.233   873  3125 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 18:14:13.233   873  3125 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
09-12 18:14:13.233   873  3125 W ActivityManager: 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
09-12 18:14:13.233   873  3125 W ActivityManager: 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1704)
09-12 18:14:13.233   873  3125 W ActivityManager: 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2336)
09-12 18:14:13.233   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15543)
09-12 18:14:13.233   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4567)
09-12 18:14:13.233   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-12 18:14:13.233   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:12031)
09-12 18:14:13.233   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:11933)
09-12 18:14:13.233   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:12622)
09-12 18:14:13.233   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12129)
09-12 18:14:13.233   873  3125 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
09-12 18:14:13.233   873  3125 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
09-12 18:14:13.233   873  3125 W ActivityManager: ,	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-12 18:14:13.233   873  3125 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
09-12 18:14:13.234   873  2153 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
,09-12 18:14:13.244   873  1697 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@79f2727)
,09-12 18:14:13.244   873  1311 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-12 18:14:13.245   873  1311 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]

```
