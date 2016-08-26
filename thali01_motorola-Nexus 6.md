#### Test 79763830d186b13_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-26 21:10:36.722  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 21:10:36.738  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 21:10:36.748  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 21:10:36.779  1508  3103 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-26 21:10:36.779  1508  3103 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 21:10:36.779  1508  3103 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 21:10:36.779  1508  3103 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-26 21:10:36.801  3625  3625 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-26 21:10:36.802  3625  3625 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-26 21:10:36.802  3625  3625 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-26 21:10:37.378  3915  3915 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-26 21:10:37.383  3915  3915 D AndroidRuntime: CheckJNI is OFF
08-26 21:10:37.419  3915  3915 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-26 21:10:37.461  3915  3915 I Radio-JNI: register_android_hardware_Radio DONE
08-26 21:10:37.481  3915  3915 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-26 21:10:37.485   871  1606 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 21:10:37.529  1995  3872 W SearchService: Abort, client detached.
08-26 21:10:37.536  1995  2315 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@e1c1811
08-26 21:10:37.537  1995  2333 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-26 21:10:37.537  1995  1995 I HotwordDetector: Closing mic
08-26 21:10:37.540  3915  3915 D AndroidRuntime: Shutting down VM
08-26 21:10:37.565   871  1956 I ActivityManager: Start proc 3924:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-26 21:10:37.596   376  2335 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-26 21:10:37.597   376  2335 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-26 21:10:37.601   376  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-26 21:10:37.607  1995  2332 I MicroRecognitionRnrImpl: Detection finished
08-26 21:10:37.607  1995  2321 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-26 21:10:37.667  3924  3924 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-26 21:10:37.695  3924  3924 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-26 21:10:37.704  3924  3924 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 646-649)
08-26 21:10:37.705  3924  3924 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 21:10:37.734  3924  3924 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ef3b425}
08-26 21:10:37.735  3924  3924 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 21:10:37.736  3924  3924 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 21:10:37.755  3924  3924 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 21:10:37.759  3924  3924 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 21:10:37.788  3924  3924 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-26 21:10:37.804  3924  3924 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 21:10:37.804  3924  3924 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 21:10:37.804  3924  3924 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 21:10:37.804  3924  3924 I Adreno  : Build Date                       : 10/20/15
08-26 21:10:37.804  3924  3924 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 21:10:37.804  3924  3924 I Adreno  : Local Branch                     : M14
08-26 21:10:37.804  3924  3924 I Adreno  : Remote Branch                    : 
08-26 21:10:37.804  3924  3924 I Adreno  : Remote Branch                    : 
08-26 21:10:37.804  3924  3924 I Adreno  : Reconstruct Branch               : 
,08-26 21:10:37.897   871   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a1b494c:true
,08-26 21:10:37.960  3924  3924 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 21:10:37.979  3924  3924 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-26 21:10:38.046  3924  3963 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-26 21:10:38.057  3924  3950 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-26 21:10:38.092  3924  3963 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 21:10:38.178   871   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +639ms
,08-26 21:10:38.183  1870  1870 I Keyboard.Facilitator: onFinishInput()
,08-26 21:10:38.239  3924  3924 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3924
,08-26 21:10:38.404   871  1958 I ActivityManager: Killing 3341:com.google.android.gm/u0a78 (adj 15): empty #17
,08-26 21:10:38.455   871  1958 I ActivityManager: Killing 2761:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,08-26 21:10:38.472  3924  3924 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 21:10:38.575  3924  3966 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1680144080
,08-26 21:10:38.581  3924  3966 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 21:10:38.581  3924  3966 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 21:10:38.581  3924  3966 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 21:10:38.581  3924  3966 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 21:10:38.581  3924  3966 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 21:10:38.581  3924  3966 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4ddd99 added. We now have 1 listener(s)
08-26 21:10:38.589  3924  3966 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-26 21:10:38.591  3924  3966 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 21:10:38.592  3924  3966 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 21:10:38.592  3924  3966 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 21:10:38.595  3924  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 21:10:38.595  3924  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 21:10:38.595  3924  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 21:10:38.595  3924  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-26 21:10:38.595  3924  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 21:10:38.595  3924  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 21:10:38.595  3924  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 21:10:38.595  3924  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 21:10:38.595  3924  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 21:10:38.595  3924  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 21:10:38.595  3924  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 21:10:38.595  3924  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 21:10:38.595  3924  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 21:10:38.595  3924  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 21:10:38.595  3924  3966 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@683310c added. We now have 1 listener(s)
08-26 21:10:38.595  3924  3966 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:10:38.598   871  1314 D WifiService: New client listening to asynchronous messages
08-26 21:10:38.600  3924  3966 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 21:10:38.600  3924  3966 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 21:10:38.600  3924  3966 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-26 21:10:38.600  3924  3966 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 21:10:38.600  3924  3966 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 21:10:38.602  3924  3966 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:10:38.602  3924  3966 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-26 21:10:38.606  3924  3966 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-26 21:10:38.607  3924  3966 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:10:38.607  3924  3966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:38.607  3924  3966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:38.607  3924  3966 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:38.607  3924  3966 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:10:38.607  3924  3966 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:38.607  3924  3966 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:38.607  3924  3966 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:10:38.607  3924  3966 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 21:10:38.607  3924  3966 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 21:10:38.607  3924  3966 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 21:10:38.737  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:38.739  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:38.742  3924  3924 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 21:10:39.380  3924  3974 W jxcore-log: Initializing JXcore engine
08-26 21:10:39.380  3924  3974 W jxcore-log: JXcore engine is ready
,08-26 21:10:39.415  3974  3974 W Thread-353: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8942 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-26 21:10:39.415  3974  3974 W Thread-353: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11658]" dev="sockfs" ino=11658 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-26 21:10:39.415  3974  3974 W Thread-353: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-26 21:10:39.415  3974  3974 W Thread-353: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26239]" dev="sockfs" ino=26239 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-26 21:10:39.432  3924  3974 W jxcore-log: Starting JXcore engine
,08-26 21:10:39.512  3924  3974 W jxcore-log: Platform android
08-26 21:10:39.512  3924  3974 W jxcore-log: 
,08-26 21:10:39.512  3924  3974 W jxcore-log: Process ARCH arm
08-26 21:10:39.512  3924  3974 W jxcore-log: 
,08-26 21:10:39.702  3924  3974 I jxcore-log: JXcore Cordova bridge is ready!
08-26 21:10:39.702  3924  3974 I jxcore-log: 
,08-26 21:10:39.702  3924  3974 W jxcore-log: JXcore engine is started
,08-26 21:10:39.710  3924  3966 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 21:10:39.715  3924  3924 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 21:10:40.729   871  1313 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-26 21:10:49.272  3709  3984 V KeepSync: Connecting to GoogleApiClient
08-26 21:10:49.273   871  1956 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-26 21:10:49.300   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 21:10:49.368  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 21:10:49.370  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 21:10:49.399  1508  3103 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-26 21:10:49.399  1508  3103 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-26 21:10:49.399  1508  3103 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 21:10:49.399  1508  3103 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 21:10:49.420  1717  3985 V BaseAuthAsyncOperation: access token request failed
,08-26 21:10:49.422  3709  3984 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-26 21:10:49.499  1508  2260 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-26 21:10:49.499  1508  2260 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-26 21:10:49.499  1508  2260 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 21:10:49.499  1508  2260 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 21:10:49.541  3709  3984 E KeepSync: IOException
08-26 21:10:49.541  3709  3984 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-26 21:10:49.541  3709  3984 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-26 21:10:49.541  3709  3984 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-26 21:10:49.541  3709  3984 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-26 21:10:49.541  3709  3984 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-26 21:10:49.541  3709  3984 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-26 21:10:49.541  3709  3984 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-26 21:10:49.541  3709  3984 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-26 21:10:49.541  3709  3984 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-26 21:10:49.541  3709  3984 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-26 21:10:49.541  3709  3984 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-26 21:10:49.541  3709  3984 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-26 21:10:49.541  3709  3984 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-26 21:10:49.541  3709  3984 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-26 21:10:49.541  3709  3984 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 21:10:49.541  3709  3984 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 21:10:49.541  3709  3984 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-26 21:10:49.541  3709  3984 E KeepSync: 	... 10 more
,08-26 21:10:49.541  3709  3984 W KeepSync: Sync result 2
,08-26 21:10:49.552   871   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 132132, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-26 21:10:49.789  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 21:10:49.789  3924  3974 I jxcore-log: 
,08-26 21:10:49.791  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 21:10:49.791  3924  3974 I jxcore-log: 
,08-26 21:10:49.797  3924  3974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:10:49.797  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:49.797  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:49.797  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:49.797  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:10:49.797  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:49.797  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:49.797  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:10:49.800  3924  3974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:10:49.803  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 21:10:49.803  3924  3974 I jxcore-log: 
,08-26 21:10:49.806  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 21:10:49.806  3924  3974 I jxcore-log: 
,08-26 21:10:49.876  1508  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 21:10:49.876  1508  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 21:10:49.876  1508  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 21:10:49.876  1508  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 21:10:49.911  3671  3987 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-26 21:10:49.911  3671  3987 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at jdm.a(PG:82)
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at jcs.o(PG:406)
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at jcn.a(PG:1379)
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at jcs.i(PG:143)
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at blb.a(PG:3937)
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at czp.a(PG:18188)
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at czp.a(PG:9081)
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at czq.run(PG:1686)
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 21:10:49.911  3671  3987 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at jdj.a(PG:4091)
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at jdj.a(PG:1125)
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at jdm.a(PG:77)
08-26 21:10:49.911  3671  3987 E HttpOperation: 	... 12 more
08-26 21:10:49.911  3671  3987 E HttpOperation: Caused by: faj: BadAuthentication
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at fal.a(PG:38)
08-26 21:10:49.911  3671  3987 E HttpOperation: 	at jdj.a(PG:4089)
08-26 21:10:49.911  3671  3987 E HttpOperation: 	... 14 more
,08-26 21:10:49.985  1508  3103 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 21:10:49.985  1508  3103 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-26 21:10:49.985  1508  3103 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 21:10:49.986  1508  3103 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 21:10:50.001  3671  3987 E HttpOperation: [getmobileexperiments] Unexpected exception
08-26 21:10:50.001  3671  3987 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at jdm.a(PG:82)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at jcs.o(PG:406)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at jcn.a(PG:1379)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at jcs.i(PG:143)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at hec.a(PG:42)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at hee.a(PG:102)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at czr.a(PG:65)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at kka.a(PG:108)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at czp.a(PG:19176)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at czp.a(PG:9081)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at czq.run(PG:1686)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 21:10:50.001  3671  3987 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at jdj.a(PG:4091)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at jdj.a(PG:1125)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at jdm.a(PG:77)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	... 15 more
08-26 21:10:50.001  3671  3987 E HttpOperation: Caused by: faj: BadAuthentication
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at fal.a(PG:38)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	at jdj.a(PG:4089)
08-26 21:10:50.001  3671  3987 E HttpOperation: 	... 17 more
08-26 21:10:50.001  3671  3987 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-26 21:10:50.001  3671  3987 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at jdm.a(PG:82)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at jcs.o(PG:406)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at jcn.a(PG:1379)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at jcs.i(PG:143)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at hec.a(PG:42)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at hee.a(PG:102)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at czr.a(PG:65)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at kka.a(PG:108)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at czp.a(PG:19176)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at czp.a(PG:9081)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at czq.run(PG:1686)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at jdj.a(PG:4091)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at jdj.a(PG:1125)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at jdm.a(PG:77)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	... 15 more
08-26 21:10:50.001  3671  3987 E ExperimentLoader: Caused by: faj: BadAuthentication
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at fal.a(PG:38)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	at jdj.a(PG:4089)
08-26 21:10:50.001  3671  3987 E ExperimentLoader: 	... 17 more
,08-26 21:10:50.116   871   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 132527, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-26 21:10:50.404  3924  3974 D executeNativeTests: Running unit tests
,08-26 21:10:50.462  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:10:50.462  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 added. We now have 2 listener(s)
,08-26 21:10:50.463  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:10:50.463  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:10:50.463  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:10:50.463  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 21:10:50.463  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae added. We now have 2 listener(s)
08-26 21:10:50.463  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:10:50.464  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 21:10:50.469  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:10:50.477  3924  3974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:10:50.477  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:50.477  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:50.477  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:50.477  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:10:50.477  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:50.477  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:50.477  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:10:50.483  3924  3974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:10:50.483  3924  3974 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 21:10:50.486  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 21:10:50.486  3924  3974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 21:10:50.486  3924  3974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 21:10:50.487  3924  3974 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 21:10:50.487  3924  3974 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-26 21:10:50.487  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 21:10:50.487  3924  3974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 21:10:50.487  3924  3974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 21:10:50.488  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:50.488  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:50.488  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:50.489  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 21:10:50.489  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:50.489  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:10:50.489  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:10:50.489  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 removed from the list
08-26 21:10:50.489  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.489  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae removed from the list
08-26 21:10:50.490  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:50.493  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:50.494  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:50.494  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.497  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.498  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.502  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:50.503  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:50.503  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.503  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
,08-26 21:10:50.508  3924  3974 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 21:10:50.509  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:50.509  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:50.509  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:50.509  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.509  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.509  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.509  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
08-26 21:10:50.509  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.509  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.509  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:50.509  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.510  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.510  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.510  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.511  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:50.511  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:50.511  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.511  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
,08-26 21:10:50.516  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 21:10:50.516  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 21:10:50.516  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 21:10:50.516  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 21:10:50.516  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 21:10:50.516  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 21:10:50.516  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 21:10:50.517  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 21:10:50.517  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 21:10:50.517  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 21:10:50.517  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 21:10:50.517  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 21:10:50.517  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 21:10:50.517  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 21:10:50.517  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 21:10:50.517  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 21:10:50.517  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 21:10:50.517  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 21:10:50.517  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 21:10:50.517  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 21:10:50.517  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 21:10:50.517  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 21:10:50.517  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 21:10:50.518  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 21:10:50.518  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 21:10:50.518  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 21:10:50.518  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 21:10:50.518  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 21:10:50.518  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 21:10:50.518  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 21:10:50.518  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 21:10:50.518  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:50.518  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:50.518  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:50.519  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.519  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.519  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.519  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
08-26 21:10:50.519  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.519  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.519  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:50.519  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.519  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.519  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.519  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.523  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:50.523  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:50.523  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.524  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.524  3924  3974 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 21:10:50.527  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:10:50.535  3924  3974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:10:50.535  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:50.535  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:50.535  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:50.535  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:10:50.535  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:50.535  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:50.535  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:10:50.538  3924  3974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:50.538  3924  3974 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:10:50.538  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:10:50.538  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:10:50.539  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 21:10:50.539  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:10:50.539  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 21:10:50.543  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:50.545  3924  3974 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 21:10:50.545  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 21:10:50.549  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:50.553  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 21:10:50.555  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 21:10:50.555  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 21:10:50.558  3924  3974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-26 21:10:50.561  3924  3974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-26 21:10:50.561  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 21:10:50.561  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 21:10:50.562  3924  3974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 21:10:50.563  3924  3974 D BluetoothAdapter: STATE_ON
08-26 21:10:50.568  2687  2808 D BtGatt.GattService: registerClient() - UUID=8afce381-b138-4d7f-8790-5134cfa981d6
08-26 21:10:50.569  2687  2712 D BtGatt.GattService: onClientRegistered() - UUID=8afce381-b138-4d7f-8790-5134cfa981d6, clientIf=5
08-26 21:10:50.573  3924  3970 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 21:10:50.574  2687  2794 D BtGatt.GattService: start scan with filters
08-26 21:10:50.578  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 21:10:50.578  2687  2715 D BtGatt.ScanManager: handling starting scan
08-26 21:10:50.578  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 21:10:50.578  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 21:10:50.578  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 21:10:50.579  2687  2715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
08-26 21:10:50.582  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 21:10:50.582  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 21:10:50.582  3924  3924 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 21:10:50.586  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-26 21:10:50.587  2687  2712 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 21:10:50.587  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:10:50.587  2687  2715 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 21:10:50.593  2687  2712 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 21:10:50.593  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:10:50.593  3924  3974 I io.jxcore.node.ConnectionHelper: start: OK,
,08-26 21:10:50.593  2687  2715 D BtGatt.ScanManager: Starting BLE batch scan
08-26 21:10:50.594  2687  2715 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 21:10:50.596  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:50.596  3924  3974 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 21:10:50.596  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:50.596  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 21:10:50.596  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.596  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 21:10:50.596  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 21:10:50.597  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 21:10:50.597  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 21:10:50.597  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 21:10:50.598  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 21:10:50.599  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 21:10:50.599  3924  3974 D BluetoothAdapter: STATE_ON
,08-26 21:10:50.600  2687  2808 D BtGatt.GattService: stopScan() - queue size =1
,08-26 21:10:50.600  2687  2794 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 21:10:50.601  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 21:10:50.601  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 21:10:50.601  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 21:10:50.601  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 21:10:50.601  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 21:10:50.603  2687  2712 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 21:10:50.603  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:10:50.603  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:10:50.603  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 21:10:50.604  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 21:10:50.604  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 21:10:50.604  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:10:50.606  3924  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:10:50.606  3924  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:10:50.606  3924  3924 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:10:50.607  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.607  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.607  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:10:50.607  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
08-26 21:10:50.607  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.607  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
,08-26 21:10:50.607  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:50.607  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.608  2687  2712 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
08-26 21:10:50.608  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:10:50.608  3924  3974 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 21:10:50.612  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:10:50.622  3924  3974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:10:50.622  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:50.622  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:50.622  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:50.622  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:10:50.622  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:50.622  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:50.622  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:10:50.622  2687  2712 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 21:10:50.622  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:10:50.622  2687  2715 D BtGatt.ScanManager: stopping BLe Batch
,08-26 21:10:50.629  3924  3974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:10:50.629  3924  3974 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-26 21:10:50.629  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 21:10:50.630  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 21:10:50.630  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 21:10:50.630  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:10:50.630  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 21:10:50.631  2687  2712 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 21:10:50.631  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:10:50.632  2687  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 21:10:50.632  3924  3974 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 21:10:50.632  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 21:10:50.635  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:50.639  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:50.642  2687  2712 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 21:10:50.642  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:10:50.647  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 21:10:50.647  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 21:10:50.647  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 21:10:50.654  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 21:10:50.654  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 21:10:50.654  3924  3974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 21:10:50.655  3924  3974 D BluetoothAdapter: STATE_ON
,08-26 21:10:50.657  2687  2808 D BtGatt.GattService: registerClient() - UUID=b1022191-834a-40fe-9a98-ada13e6634f8
,08-26 21:10:50.658  2687  2712 D BtGatt.GattService: onClientRegistered() - UUID=b1022191-834a-40fe-9a98-ada13e6634f8, clientIf=5
08-26 21:10:50.658  3924  3936 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 21:10:50.658  2687  2794 D BtGatt.GattService: start scan with filters
,08-26 21:10:50.661  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 21:10:50.662  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 21:10:50.662  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 21:10:50.662  2687  2715 D BtGatt.ScanManager: handling starting scan
,08-26 21:10:50.662  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 21:10:50.665  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:10:50.665  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 21:10:50.665  3924  3924 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 21:10:50.667  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-26 21:10:50.667  2687  2712 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 21:10:50.667  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:10:50.667  2687  2715 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 21:10:50.669  3924  3974 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 21:10:50.671  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:50.671  3924  3974 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 21:10:50.671  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:10:50.671  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 21:10:50.671  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:50.672  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 21:10:50.672  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 21:10:50.672  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 21:10:50.672  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 21:10:50.672  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 21:10:50.672  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 21:10:50.672  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 21:10:50.673  3924  3974 D BluetoothAdapter: STATE_ON
,08-26 21:10:50.673  2687  2712 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 21:10:50.673  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:10:50.673  2687  2794 D BtGatt.GattService: stopScan() - queue size =1
08-26 21:10:50.673  2687  2715 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 21:10:50.673  2687  2699 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 21:10:50.674  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:10:50.674  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 21:10:50.673  2687  2715 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 21:10:50.674  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 21:10:50.674  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 21:10:50.674  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 21:10:50.675  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:10:50.675  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 21:10:50.675  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 21:10:50.675  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 21:10:50.675  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:10:50.676  3924  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 21:10:50.676  3924  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:10:50.676  3924  3924 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:10:50.676  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.676  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.676  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:10:50.676  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
08-26 21:10:50.676  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.677  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.677  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:50.677  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:50.677  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.677  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.678  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:50.678  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:50.678  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.678  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.678  3924  3974 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 21:10:50.679  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:10:50.683  3924  3974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:10:50.683  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:50.683  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:50.683  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:50.683  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:10:50.683  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:50.683  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:50.683  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:10:50.684  2687  2712 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 21:10:50.685  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:10:50.685  3924  3974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:50.685  3924  3974 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:10:50.686  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:10:50.686  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:10:50.686  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 21:10:50.687  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:10:50.687  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 21:10:50.688  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:50.690  3924  3974 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 21:10:50.690  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:50.690  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 21:10:50.691  2687  2712 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 21:10:50.691  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:10:50.694  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 21:10:50.695  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 21:10:50.695  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 21:10:50.700  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 21:10:50.700  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 21:10:50.700  2687  2712 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 21:10:50.700  3924  3974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 21:10:50.700  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:10:50.701  2687  2715 D BtGatt.ScanManager: stopping BLe Batch
08-26 21:10:50.701  3924  3974 D BluetoothAdapter: STATE_ON
,08-26 21:10:50.703  2687  2794 D BtGatt.GattService: registerClient() - UUID=9308d6ae-b134-46c4-8974-7d51c620a0e0
,08-26 21:10:50.704  2687  2712 D BtGatt.GattService: onClientRegistered() - UUID=9308d6ae-b134-46c4-8974-7d51c620a0e0, clientIf=5
,08-26 21:10:50.704  3924  3936 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 21:10:50.705  2687  2808 D BtGatt.GattService: start scan with filters
,08-26 21:10:50.707  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 21:10:50.708  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
08-26 21:10:50.708  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 21:10:50.708  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 21:10:50.710  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:10:50.710  3924  3924 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:10:50.710  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 21:10:50.711  2687  2712 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 21:10:50.711  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:10:50.711  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-26 21:10:50.711  2687  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 21:10:50.714  3924  3974 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 21:10:50.714  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:50.714  3924  3974 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 21:10:50.714  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:50.714  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 21:10:50.714  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.714  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 21:10:50.714  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 21:10:50.714  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 21:10:50.714  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 21:10:50.714  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 21:10:50.715  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 21:10:50.715  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 21:10:50.717  3924  3974 D BluetoothAdapter: STATE_ON
08-26 21:10:50.717  2687  2808 D BtGatt.GattService: stopScan() - queue size =0
,08-26 21:10:50.718  2687  2699 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 21:10:50.719  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 21:10:50.719  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 21:10:50.719  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 21:10:50.719  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 21:10:50.719  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 21:10:50.726  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:10:50.726  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 21:10:50.726  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 21:10:50.726  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 21:10:50.726  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:10:50.728  3924  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 21:10:50.728  3924  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:10:50.728  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:10:50.728  3924  3924 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:10:50.728  3924  3974 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 21:10:50.728  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:10:50.728  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 21:10:50.728  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.728  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.728  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-26 21:10:50.728  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
,08-26 21:10:50.729  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.729  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
,08-26 21:10:50.729  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 21:10:50.729  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:50.729  2687  2712 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 21:10:50.729  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:10:50.729  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:50.730  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.730  2687  2715 D BtGatt.ScanManager: handling starting scan
08-26 21:10:50.730  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 21:10:50.731  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:50.731  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:10:50.731  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.731  3924  3974 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 21:10:50.732  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:50.732  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:10:50.732  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:50.732  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-26 21:10:50.732  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:50.732  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.732  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
,08-26 21:10:50.732  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.732  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.733  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 21:10:50.733  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.733  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.733  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:50.733  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.734  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:10:50.734  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:50.734  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.734  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
,08-26 21:10:50.735  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 21:10:50.735  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:10:50.735  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:50.736  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:50.736  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-26 21:10:50.736  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-26 21:10:50.736  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:50.736  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
08-26 21:10:50.736  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.736  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.736  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop,
08-26 21:10:50.736  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.736  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 21:10:50.736  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.736  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:50.736  2687  2712 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 21:10:50.737  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:10:50.737  2687  2715 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 21:10:50.739  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:10:50.739  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:50.739  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:10:50.739  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.739  3924  3974 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-26 21:10:50.740  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:50.740  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:50.740  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 21:10:50.740  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.740  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.740  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:50.740  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
08-26 21:10:50.740  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:10:50.740  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.740  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 21:10:50.740  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.740  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.740  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:50.740  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.742  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:10:50.742  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:50.742  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.742  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
,08-26 21:10:50.742  2687  2712 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 21:10:50.742  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:10:50.742  2687  2715 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 21:10:50.742  2687  2715 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 21:10:50.743  3924  3974 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 21:10:50.743  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:10:50.743  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:50.743  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:50.743  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 21:10:50.743  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.743  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.743  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
,08-26 21:10:50.743  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:10:50.743  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
,08-26 21:10:50.744  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:50.744  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:50.744  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:50.744  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:50.744  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:50.745  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:10:50.745  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:10:50.745  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:10:50.745  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
,08-26 21:10:50.745  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 21:10:50.745  3924  3974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 21:10:50.746  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 21:10:50.746  3924  3974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 21:10:50.746  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 21:10:50.746  3924  3974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 21:10:50.746  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:10:50.746  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:50.746  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:50.746  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.746  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:50.746  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.746  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
08-26 21:10:50.746  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.746  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.747  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:50.747  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.747  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:50.747  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.747  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 21:10:50.749  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:10:50.749  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:10:50.749  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:10:50.749  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.750  3924  3974 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:10:50.750  3924  3974 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 21:10:50.750  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 21:10:50.754  2687  2712 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 21:10:50.754  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:10:50.758  3924  3974 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:10:50.758  3924  3974 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 21:10:50.758  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 21:10:50.758  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-26 21:10:50.758  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 21:10:50.758  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 21:10:50.758  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 21:10:50.758  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 21:10:50.758  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 21:10:50.758  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-26 21:10:50.758  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 21:10:50.759  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 21:10:50.759  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 21:10:50.759  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 21:10:50.759  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 21:10:50.759  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 21:10:50.759  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-26 21:10:50.759  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 21:10:50.759  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 21:10:50.759  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 21:10:50.759  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 21:10:50.759  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 21:10:50.759  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 21:10:50.759  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 21:10:50.759  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 21:10:50.759  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 21:10:50.759  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-26 21:10:50.760  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 21:10:50.760  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 21:10:50.760  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 21:10:50.760  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 21:10:50.760  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 21:10:50.760  3924  3974 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 21:10:50.760  2687  2712 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 21:10:50.760  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:10:50.760  3924  3974 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 21:10:50.760  3924  3974 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 21:10:50.760  3924  3974 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:10:50.760  3924  3974 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 21:10:50.761  3924  3974 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 21:10:50.761  3924  3974 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:10:50.761  3924  3974 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 21:10:50.761  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 21:10:50.764  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 21:10:50.764  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 21:10:50.765  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 21:10:50.765  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 21:10:50.765  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 21:10:50.765  3924  3974 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 21:10:50.765  3924  3974 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:10:50.766  3924  3974 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 21:10:50.766  3924  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 417)
08-26 21:10:50.766  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:50.766  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:50.766  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:50.766  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.766  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.766  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.767  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 21:10:50.767  2687  2712 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 21:10:50.767  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:10:50.767  2687  2715 D BtGatt.ScanManager: stopping BLe Batch
,08-26 21:10:50.767  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
,08-26 21:10:50.767  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:10:50.767  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
,08-26 21:10:50.767  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:50.767  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.767  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.767  3924  3989 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:10:50.767  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.768  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.768  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:50.768  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:50.768  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.768  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
,08-26 21:10:50.769  3924  3974 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 21:10:50.770  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:50.770  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:50.770  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:50.770  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.770  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:50.770  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.770  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
08-26 21:10:50.770  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.770  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.770  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:50.771  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.771  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:50.771  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.771  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.771  3924  3990 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 417
08-26 21:10:50.771  3924  3990 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 417)
08-26 21:10:50.771  2687  2792 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-26 21:10:50.772  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:50.772  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:10:50.772  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.772  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.772  3924  3990 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 417)
08-26 21:10:50.772  3924  3989 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 417)
08-26 21:10:50.772  3924  3974 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 21:10:50.773  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:10:50.773  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:50.773  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:50.773  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.773  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.773  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.773  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
,08-26 21:10:50.773  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.773  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.773  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:50.773  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.773  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.773  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.773  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:50.774  2687  2712 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 21:10:50.774  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:10:50.774  2687  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 21:10:50.774  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:50.774  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:50.775  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.775  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
,08-26 21:10:50.775  3924  3974 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 21:10:50.775  3924  3974 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 21:10:50.775  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 21:10:50.775  3924  3974 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 21:10:50.775  3924  3974 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 21:10:50.776  3924  3974 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 21:10:50.776  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 21:10:50.776  3924  3974 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-26 21:10:50.776  3924  3974 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 21:10:50.776  3924  3974 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 21:10:50.776  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 21:10:50.776  3924  3974 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 21:10:50.776  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:10:50.776  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:50.776  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:50.776  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.776  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.776  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.776  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
08-26 21:10:50.777  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:10:50.777  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.777  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:50.777  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.777  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.777  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.777  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.778  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:10:50.778  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:50.778  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.781  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.782  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.782  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:50.782  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.782  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
08-26 21:10:50.782  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.782  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
,08-26 21:10:50.782  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:50.782  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.782  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.782  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:10:50.782  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.782  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.782  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.782  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.782  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
08-26 21:10:50.782  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:10:50.782  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:50.783  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:50.783  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.783  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.783  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.783  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
08-26 21:10:50.783  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:10:50.783  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.783  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:50.783  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.783  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.783  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.783  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.784  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:10:50.784  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:50.784  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.784  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.785  3924  3974 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 21:10:50.786  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:10:50.786  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 21:10:50.787  3924  3974 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 21:10:50.787  3924  3974 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-26 21:10:50.787  3924  3924 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 21:10:50.787  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 21:10:50.787  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 21:10:50.788  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.788  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 21:10:50.788  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 21:10:50.788  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-26 21:10:50.788  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.788  3924  3974 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 21:10:50.788  3924  3924 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 21:10:50.788  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
08-26 21:10:50.788  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:10:50.788  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 21:10:50.788  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 21:10:50.788  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 21:10:50.789  2687  2712 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 21:10:50.789  2687  2712 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:10:50.789  3924  3991 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 21:10:50.789  3924  3991 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 21:10:50.789  3924  3924 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 21:10:50.790  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.790  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.791  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:10:50.791  3924  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:10:50.791  3924  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:10:50.791  3924  3924 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:10:50.791  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.791  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:10:50.791  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:50.791  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:50.791  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.791  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.791  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:50.792  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
08-26 21:10:50.792  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.792  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.792  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:50.792  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:50.792  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.792  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.792  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.793  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:50.793  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:50.793  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.793  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
,08-26 21:10:50.794  3924  3974 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 21:10:50.794  3924  3974 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 21:10:50.794  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 21:10:50.794  3924  3974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 21:10:50.794  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:50.794  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:10:50.794  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:50.794  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.794  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.794  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.795  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
08-26 21:10:50.795  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.795  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
,08-26 21:10:50.795  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:50.795  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.795  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.795  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.795  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.796  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:50.796  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:10:50.796  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.797  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.799  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:10:50.799  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:50.799  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:50.799  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.799  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.799  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:50.799  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
08-26 21:10:50.799  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.799  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.800  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:50.800  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.800  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.800  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:50.800  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.800  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:50.800  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:50.800  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.801  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.801  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:10:50.801  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:10:50.801  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:10:50.802  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:10:50.802  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:10:50.802  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.802  3924  3974 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a609c29 not in the list
08-26 21:10:50.802  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.802  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.802  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:10:50.802  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.802  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:10:50.802  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:10:50.802  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:10:50.803  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:10:50.803  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:10:50.803  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:10:50.803  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d2bae not in the list
08-26 21:10:50.804  3924  3974 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 21:10:50.804  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-26 21:10:50.804  3924  3974 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 21:10:50.804  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 21:10:50.804  3924  3974 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 21:10:50.804  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 21:10:50.805  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 21:10:50.805  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 21:10:50.806  3924  3974 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 21:10:50.806  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-26 21:10:50.806  3924  3974 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 21:10:50.806  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 21:10:50.806  3924  3974 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 21:10:50.806  3924  3974 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 21:10:50.806  3924  3974 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 21:10:50.807  3924  3974 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-26 21:10:50.807  3924  3974 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 21:10:50.807  3924  3974 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 21:10:50.807  3924  3974 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 21:10:50.807  3924  3974 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 21:10:50.808  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:10:50.808  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b001ae0 added. We now have 2 listener(s)
08-26 21:10:50.808  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:10:50.809  3924  3974 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 21:10:50.809   871  1378 D WifiService: setWifiEnabled: true pid=3924, uid=10000
,08-26 21:10:50.810   871  1378 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 21:10:50.810  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:10:50.810  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7be199 added. We now have 3 listener(s)
08-26 21:10:50.810  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:10:50.814  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:10:50.814  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8d1dc5e added. We now have 4 listener(s)
08-26 21:10:50.814  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:10:50.815  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:10:50.815  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@133a83f added. We now have 5 listener(s)
08-26 21:10:50.815  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:10:50.817   871  1712 D WifiService: setWifiEnabled: false pid=3924, uid=10000
08-26 21:10:50.818   871  1712 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 21:10:50.823  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:10:50.823  2687  2707 D BluetoothAdapterState: Current state: ON, message: 23
,08-26 21:10:50.823  2687  2707 D BluetoothAdapterProperties: Setting state to 13
08-26 21:10:50.823  2687  2707 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 21:10:50.824  2687  2707 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 21:10:50.825  2687  2687 D BluetoothMapService: onReceive
08-26 21:10:50.825  2687  2687 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:10:50.825  2687  2687 D BluetoothMapService: STATE_TURNING_OFF
08-26 21:10:50.825  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:50.825  3924  3974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:10:50.825  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:50.825  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:50.825  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:50.825  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:50.825  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:50.825  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:50.825  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:10:50.825  2687  2687 D BluetoothMapService: MAP Service closeService in
,08-26 21:10:50.826  2687  2687 D BluetoothMapMasInstance0: MAP Service shutdown,
08-26 21:10:50.826  2687  2687 D ObexServerSockets0: shutdown(block = true)
,08-26 21:10:50.826  2687  2707 I BluetoothAdapterState: Entering PendingCommandState
,08-26 21:10:50.826  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:50.827  2687  2809 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 21:10:50.827  3924  3974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:10:50.827  3924  3974 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 21:10:50.827  2687  2687 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-26 21:10:50.827  2687  2687 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-26 21:10:50.828  2687  2810 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-26 21:10:50.828  2687  2792 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-26 21:10:50.828  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:50.829  2687  2687 I BtOppRfcommListener: stopping Accept Thread
,08-26 21:10:50.829  2687  3541 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 21:10:50.830  2687  3541 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 21:10:50.831  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:50.834  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:50.834  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:50.834  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:50.834  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:50.834  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:50.834  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:50.834  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:50.834  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:50.834  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:10:50.835  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 21:10:50.836   871  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 21:10:50.836   871  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-26 21:10:50.836   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 21:10:50.836   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 21:10:50.837  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:50.837  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:10:50.837   871   885 I ActivityManager: Start proc 3994:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-26 21:10:50.837  2687  2712 D BluetoothAdapterProperties: Scan Mode:20
,08-26 21:10:50.838  2687  2707 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-26 21:10:50.842  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:50.845  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 21:10:50.847   372   869 D CommandListener: Clearing all IP addresses on wlan0
08-26 21:10:50.847  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:50.848  2687  2687 D HeadsetService: Received stop request...Stopping profile...
,08-26 21:10:50.848   871  2123 D DhcpClient: Clearing IP address
,08-26 21:10:50.849   871   871 D BluetoothHeadset: Proxy object disconnected
08-26 21:10:50.849   871   871 D BluetoothHeadset: Proxy object disconnected
08-26 21:10:50.849   871   871 D BluetoothHeadset: Proxy object disconnected
,08-26 21:10:50.850  1933  2052 D BluetoothHeadset: Proxy object disconnected
08-26 21:10:50.851  1364  1690 D BluetoothHeadset: Proxy object disconnected
,08-26 21:10:50.851  1508  2538 V NativeCrypto: Read error: ssl=0xaec4ea00: I/O error during system call, Connection timed out
,08-26 21:10:50.852   372   869 D CommandListener: Setting iface cfg
,08-26 21:10:50.852  1508  2538 V NativeCrypto: SSL shutdown failed: ssl=0xaec4ea00: I/O error during system call, Broken pipe
,08-26 21:10:50.854   871  1711 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011,
,08-26 21:10:50.854   871  2104 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-26 21:10:50.855   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-26 21:10:50.855   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-26 21:10:50.855  2687  2687 D A2dpService: Received stop request...Stopping profile...
,08-26 21:10:50.856  2687  2797 D A2dpStateMachine: Exit Disconnected: -1
,08-26 21:10:50.856   871   871 D BluetoothA2dp: Proxy object disconnected
,08-26 21:10:50.858   395   395 E Parcel  : Reading a NULL string not supported here.
,08-26 21:10:50.859   871  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-26 21:10:50.860   871  1313 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-26 21:10:50.861   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 21:10:50.861  2687  2687 D HidService: Received stop request...Stopping profile...
,08-26 21:10:50.861  2687  2687 D HidService: Stopping Bluetooth HidService
,08-26 21:10:50.863  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-26 21:10:50.863  2687  2687 V BluetoothAdapterState: isTurningOn()=false
,08-26 21:10:50.863  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:10:50.863  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 21:10:50.864  1364  1364 D HeadsetProfile: Bluetooth service disconnected
,08-26 21:10:50.864  1364  1364 D BluetoothA2dp: Proxy object disconnected
,08-26 21:10:50.864  1364  1364 D BluetoothInputDevice: Proxy object disconnected
,08-26 21:10:50.864  1364  1364 D HidProfile: Bluetooth service disconnected
,08-26 21:10:50.865   871  2104 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-26 21:10:50.867  2687  2687 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 21:10:50.867  2687  2712 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 21:10:50.867  2687  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:10:50.867  2687  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:10:50.867  2687  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 21:10:50.867  2687  2712 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-26 21:10:50.868  2687  2687 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 21:10:50.869  2687  2687 D HealthService: Received stop request...Stopping profile...
08-26 21:10:50.871  2687  2687 D PanService: Received stop request...Stopping profile...
08-26 21:10:50.872  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-26 21:10:50.872  2687  2687 V BluetoothAdapterState: isTurningOn()=false
,08-26 21:10:50.872  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:10:50.872  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:10:50.878   871  2167 D DhcpClient: Receive thread stopped
08-26 21:10:50.878  2687  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:10:50.879  2687  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:10:50.879  2687  2789 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 21:10:50.879  2687  2789 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:10:50.879  2687  2789 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 21:10:50.879  2687  2789 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:10:50.879  2687  2712 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 21:10:50.880  2687  2687 D BluetoothMapService: Received stop request...Stopping profile...
08-26 21:10:50.880  2687  2687 D BluetoothMapService: stop()
08-26 21:10:50.880  2687  2687 D BluetoothMapAppObserver: deinitObservers()
08-26 21:10:50.880  2687  2687 D BluetoothMapAppObserver: removeReceiver()
08-26 21:10:50.881  2687  2687 V BluetoothAdapterState: isTurningOff()=true
,08-26 21:10:50.881  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-26 21:10:50.881  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:10:50.881  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:10:50.882  2687  2687 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 21:10:50.882  2687  2712 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 21:10:50.882  2687  2687 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 21:10:50.882  2687  2687 V BluetoothAdapterState: isTurningOff()=true
,08-26 21:10:50.882  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-26 21:10:50.882  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:10:50.882  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:10:50.883  2687  2687 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 21:10:50.883  2687  2712 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 21:10:50.883  2687  2687 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-26 21:10:50.883  2687  2687 V BluetoothAdapterState: isTurningOff()=true
08-26 21:10:50.883  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-26 21:10:50.884  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:10:50.884  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:10:50.884  2687  2687 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-26 21:10:50.885  2687  2687 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 21:10:50.885  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 21:10:50.885  1364  1364 D PanProfile: Bluetooth service disconnected
08-26 21:10:50.886  1364  1364 D BluetoothMap: Proxy object disconnected
08-26 21:10:50.886  1364  1364 D MapProfile: Bluetooth service disconnected
08-26 21:10:50.887  2687  2687 D BluetoothMapService: MAP Service closeService in
08-26 21:10:50.887  2687  2687 V BluetoothAdapterState: isTurningOff()=true
,08-26 21:10:50.887  2687  2687 V BluetoothAdapterState: isTurningOn()=false
08-26 21:10:50.887  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:10:50.888  2687  2687 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:10:50.888  2687  2707 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 21:10:50.888  2687  2687 D BluetoothMapService: cleanup()
08-26 21:10:50.888  2687  2707 D BluetoothAdapterProperties: Setting state to 15
08-26 21:10:50.888  2687  2687 D BluetoothMapService: MAP Service closeService in
,08-26 21:10:50.888  2687  2707 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 21:10:50.888   871   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:10:50.888   871   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 21:10:50.888   871   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:10:50.889  2687  2707 I BluetoothAdapterState: Entering BleOnState
08-26 21:10:50.889  1364  1690 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:10:50.889  1364  1381 D BluetoothPan: onBluetoothStateChange on: false
08-26 21:10:50.889  1364  1388 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 21:10:50.890  1364  1690 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 21:10:50.891   871   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:10:50.891  1364  1381 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 21:10:50.891  1364  1388 D BluetoothMap: onBluetoothStateChange: up=false
08-26 21:10:50.892  1933  1949 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:10:50.892  2687  2707 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 21:10:50.892  2687  2707 D BluetoothAdapterProperties: Setting state to 16
,08-26 21:10:50.892  2687  2707 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 21:10:50.893  2687  2707 D BluetoothAdapterProperties: onBleDisable
08-26 21:10:50.893  2687  2707 I BluetoothAdapterState: Entering PendingCommandState
08-26 21:10:50.893  2687  2708 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 21:10:50.894  2687  2789 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 21:10:50.894  2687  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:10:50.894  2687  2712 D BluetoothAdapterProperties: Scan Mode:20
,08-26 21:10:50.897  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:50.898  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:50.898  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:50.898  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:50.898  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:50.898  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:50.898  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:50.898  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:50.898  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:10:50.898  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:50.898  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:10:50.900  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:50.900  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:50.900  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:50.900  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:50.900  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:50.900  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:50.900  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:50.900  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:50.900  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:10:50.900  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:50.901  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:10:50.902   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-26 21:10:50.902  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:50.903  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:50.922   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-26 21:10:50.922   372   869 D CommandListener: Clearing all IP addresses on wlan0
08-26 21:10:50.923   871  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 21:10:50.923   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 21:10:50.928   871   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 21:10:50.930  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:50.931  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:50.933   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
08-26 21:10:50.934  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:50.934  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:50.934  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:50.934  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:50.934  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:10:50.934  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:50.934  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:50.934  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:50.934  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:10:50.934  2098  2337 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:10:50.934  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:50.934  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:10:50.936  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:50.936  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:50.936  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:50.936  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:50.936  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:10:50.936  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:50.936  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:50.936  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:50.936  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:10:50.936  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:50.936  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:10:50.936   871  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 21:10:50.940  3544  3544 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@e4ddd99 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-26 21:10:50.945  3994  3994 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-26 21:10:50.956  3994  3994 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 21:10:50.961  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:10:50.964   871   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d3684a5:true
,08-26 21:10:50.975   871  1712 I ActivityManager: Start proc 4015:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-26 21:10:50.976   372   869 E Netd    : netlink response contains error (No such file or directory)
,08-26 21:10:50.977   871  1315 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-26 21:10:50.977   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 21:10:50.983  3994  3994 D LocalBluetoothProfileManager: Adding local MAP profile
,08-26 21:10:50.986  3994  3994 D BluetoothMap: Create BluetoothMap proxy object
,08-26 21:10:50.992  3994  3994 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-26 21:10:51.005  4015  4015 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-26 21:10:51.008  3994  3994 D DockEventReceiver: finishStartingService: stopping service
,08-26 21:10:51.015   871  1712 I ActivityManager: Killing 3109:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-26 21:10:51.101  2687  2712 I bt_hci  : shut_down
,08-26 21:10:51.115  2687  2716 I bt_vendor: low_power_mode_cb
,08-26 21:10:51.120  2687  2716 D bt_hwcfg: hw_epilog_process
,08-26 21:10:51.131  2687  2716 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 21:10:51.131  2687  2716 I bt_vendor: epilog_cb
,08-26 21:10:51.132  2687  2716 I bt_hci  : epilog_finished_callback
,08-26 21:10:51.139  2687  2712 I bt_hci_h4: hal_close
,08-26 21:10:51.140  2687  2712 I bt_userial_vendor: device fd = 51 close
,08-26 21:10:51.188  4015  4015 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 21:10:51.188  4015  4015 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 21:10:51.188  4015  4015 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 21:10:51.188  4015  4015 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:10:51.188  4015  4015 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 21:10:51.189  4015  4015 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.r.k.d(PG:583)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 21:10:51.189  4015  4015 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at andr,oid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 21:10:51.189  4015  4015 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:10:51.189  4015  4015 D StrictMode,: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 21:10:51.189  4015  4015 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:10:51.189  4015  4015 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 21:10:51.209  3994  3994 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 21:10:51.218  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 21:10:51.230  3994  3994 D DockEventReceiver: finishStartingService: stopping service
08-26 21:10:51.242   871   882 I ActivityManager: Killing 3544:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-26 21:10:51.292  3924  3924 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 21:10:51.365  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 21:10:51.377  1717  1717 D SystemUpdateService: onCreate
,08-26 21:10:51.385  2687  2708 D bt_stack_manager: event_shut_down_stack finished.
,08-26 21:10:51.385  2687  2707 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 21:10:51.409  2687  2687 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 21:10:51.409  2687  2707 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-26 21:10:51.409  2687  2687 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 21:10:51.409  2687  2687 D BtGatt.GattService: stop()
08-26 21:10:51.409  2687  2687 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 21:10:51.412  2687  2687 V BluetoothAdapterState: isTurningOff()=false
,08-26 21:10:51.412  2687  2687 V BluetoothAdapterState: isTurningOn()=false
,08-26 21:10:51.412  2687  2687 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:10:51.412  2687  2687 V BluetoothAdapterState: isBleTurningOff()=true
,08-26 21:10:51.412  2687  2707 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-26 21:10:51.412  2687  2707 D BluetoothAdapterProperties: Setting state to 10
,08-26 21:10:51.412  2687  2707 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-26 21:10:51.413  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 21:10:51.415   871   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-26 21:10:51.415  2687  2707 I BluetoothAdapterState: Entering OffState
,08-26 21:10:51.431  2687  2687 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 21:10:51.431  1717  4047 I SystemUpdateService: active receiver: enabled
08-26 21:10:51.431  2687  2687 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-26 21:10:51.431  2687  2687 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 21:10:51.432  2687  2708 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 21:10:51.435  2687  2708 D bt_stack_manager: event_clean_up_stack finished.
,08-26 21:10:51.436  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 21:10:51.437  1717  4047 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 21:10:51.440  2687  2687 I art     : System.exit called, status: 0
,08-26 21:10:51.440  2687  2687 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 21:10:51.443  1717  2516 I iu.UploadsManager: num queued entries: 0
,08-26 21:10:51.443  1717  2516 I iu.UploadsManager: num updated entries: 0
,08-26 21:10:51.445  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 21:10:51.445  1717  4047 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-26 21:10:51.445  1717  4047 I SystemUpdateService: now status is 0 (complete)
,08-26 21:10:51.446  1717  4047 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-26 21:10:51.446  1717  4047 I SystemUpdateService: file has been verified
08-26 21:10:51.446  1717  4047 I SystemUpdateService: OTA package size = 12249756
08-26 21:10:51.446  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-26 21:10:51.447  1717  2516 I iu.SyncManager: NEXT; no task
,08-26 21:10:51.452  1717  4047 I SystemUpdateService: showing system update notification
,08-26 21:10:51.462   871  1606 I ActivityManager: Start proc 4051:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-26 21:10:51.471  4015  4038 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 21:10:51.476  1717  1717 D SystemUpdateService: onDestroy
,08-26 21:10:51.485   871   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@126e901:true
,08-26 21:10:51.494   871  1956 I ActivityManager: Process com.android.bluetooth (pid 2687) has died
,08-26 21:10:51.516  4051  4051 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-26 21:10:51.519  4051  4051 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:10:51.530  4051  4051 D SprintDMHelper: simOperator: 
,08-26 21:10:51.530  4051  4051 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 21:10:51.543   871  1712 I ActivityManager: Start proc 4063:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-26 21:10:51.622  2406  4077 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 21:10:51.634   871  1711 I ActivityManager: Start proc 4078:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-26 21:10:51.639   871  1711 I ActivityManager: Killing 3589:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-26 21:10:51.703  4078  4078 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-26 21:10:51.751  4078  4078 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 21:10:51.751  4078  4078 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 21:10:51.751  4078  4078 I GAv4    :   adb logcat -s GAv4
,08-26 21:10:51.771  4078  4078 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 21:10:51.777  4078  4078 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 21:10:51.785  4078  4095 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 21:10:51.904  4078  4078 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-26 21:10:51.941  4078  4078 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-26 21:10:51.951  4078  4078 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4893-4896)
,08-26 21:10:51.951  4078  4078 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 21:10:51.963  4078  4078 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1b45f09}
,08-26 21:10:51.963  4078  4078 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 21:10:51.964  4078  4078 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 21:10:51.971  4078  4078 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-26 21:10:51.972  4078  4078 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 21:10:51.987  4078  4078 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-26 21:10:51.997  4078  4078 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 21:10:51.997  4078  4078 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 21:10:51.998  4078  4078 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 21:10:51.998  4078  4078 I Adreno  : Build Date                       : 10/20/15
08-26 21:10:51.998  4078  4078 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 21:10:51.998  4078  4078 I Adreno  : Local Branch                     : M14
08-26 21:10:51.998  4078  4078 I Adreno  : Remote Branch                    : 
08-26 21:10:51.998  4078  4078 I Adreno  : Remote Branch                    : 
08-26 21:10:51.998  4078  4078 I Adreno  : Reconstruct Branch               : 
,08-26 21:10:52.058  4078  4124 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-26 21:10:52.060  4078  4078 I NSApplication: Starting up...
,08-26 21:10:52.101   871  1712 I ActivityManager: Start proc 4129:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
08-26 21:10:52.102   871  1712 I ActivityManager: Killing 3189:android.process.acore/u0a5 (adj 15): empty #17
,08-26 21:10:52.220  4129  4129 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-26 21:10:52.389   871  1958 I ActivityManager: Killing 3775:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-26 21:10:52.476   871  2079 I ActivityManager: Start proc 4143:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-26 21:10:52.527  4143  4143 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-26 21:10:52.572  4143  4143 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-26 21:10:52.631   871  1378 I ActivityManager: Killing 3790:com.android.musicfx/u0a18 (adj 15): empty #17
,08-26 21:10:53.831   871  2080 D WifiService: setWifiEnabled: true pid=3924, uid=10000
08-26 21:10:53.831   871  2080 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 21:10:53.843   871  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-26 21:10:53.850  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:53.851  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:53.851  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:53.851  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:53.851  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:53.851  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:53.851  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:53.851  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:53.851  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:10:53.851  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:53.852  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:10:53.855  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:53.855  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:53.855  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:53.855  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:53.855  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:53.855  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false,
08-26 21:10:53.855  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:53.855  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:53.855  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:10:53.855  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:53.856  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:10:53.896   871  1313 D WifiConfigStore: loaded 0 passpoint configs
,08-26 21:10:53.897   871  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 21:10:53.897   871  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 21:10:53.898   871  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 21:10:53.899   871  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 21:10:53.899   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-26 21:10:53.899   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 21:10:53.913   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 21:10:53.913   871  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.38 rxSuccessRate=14.25 delta 1000 -> 994
,08-26 21:10:53.915   372   869 D CommandListener: Setting iface cfg
,08-26 21:10:53.917   871  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
08-26 21:10:53.917   871  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 21:10:53.924   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-26 21:10:53.924   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 21:10:53.924   871  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 21:10:53.936   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 21:10:53.936   871  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 21:10:54.015   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 21:10:54.018  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 21:10:54.442  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 21:10:54.489  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 21:10:54.490  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 21:10:54.498   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 21:10:54.516   871  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 21:10:54.517   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 21:10:54.517   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 21:10:54.535   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 21:10:54.547   372   869 D CommandListener: Setting iface cfg
,08-26 21:10:54.549   871  1313 D WifiStateMachine: Start Dhcp Watchdog 2
,08-26 21:10:54.578   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 21:10:54.578   871  1315 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-26 21:10:54.586   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 21:10:54.590   871  4176 D DhcpClient: Receive thread started
,08-26 21:10:54.681   871  1313 E native  : do suspend false
,08-26 21:10:54.703   871  2123 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 21:10:54.719   871  4176 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172686, domain null
,08-26 21:10:54.721   871  2123 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172686 seconds
,08-26 21:10:54.724   871  2123 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 21:10:54.736   871  4176 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 21:10:54.737   871  2123 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 21:10:54.742   372   869 D CommandListener: Setting iface cfg
,08-26 21:10:54.753   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 21:10:54.756   871  2123 D DhcpClient: Scheduling renewal in 86399s
,08-26 21:10:54.775   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 21:10:54.779   871  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 21:10:54.781   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 21:10:54.784   871  1315 D ConnectivityService: Adding iface wlan0 to network 101
,08-26 21:10:54.799   871  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 21:10:54.870   871  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 21:10:54.870   871  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-26 21:10:54.874   871  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-26 21:10:54.877   871  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-26 21:10:54.880   871  1315 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-26 21:10:54.896   871  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 21:10:54.910   871  1315 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-26 21:10:54.910   871  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-26 21:10:54.910   871  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-26 21:10:54.910   871  1315 D ConnectivityService:    accepting network in place of null
,08-26 21:10:54.910   871  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-26 21:10:54.911   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
08-26 21:10:54.911   871  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 21:10:54.928   871  4175 D NetlinkSocketObserver: NeighborEvent{elapsedMs=137873, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 21:10:54.964   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 21:10:54.998   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 21:10:55.001   871  4174 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:80a::200e
,08-26 21:10:55.008   871  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 21:10:55.010   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:10:55.019   871   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 21:10:55.016   871  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-26 21:10:55.029  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:55.030  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:55.030  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:55.030  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:55.030  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:55.030  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:55.030  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:55.030  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:55.030  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:10:55.030  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:55.030  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:55.033  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:55.033  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:55.033  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:55.033  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:55.033  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:10:55.033  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:55.033  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:55.033  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:10:55.033  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:10:55.034  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:55.034  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:10:55.041  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-26 21:10:55.049  1717  1717 D SystemUpdateService: onCreate
08-26 21:10:55.055  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 21:10:55.067  1717  4187 I SystemUpdateService: active receiver: enabled
,08-26 21:10:55.070  1717  4187 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 21:10:55.077  1717  4187 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 21:10:55.078  1717  4187 I SystemUpdateService: now status is 0 (complete)
,08-26 21:10:55.078  1717  4187 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 21:10:55.078  1717  4187 I SystemUpdateService: file has been verified
,08-26 21:10:55.078  1717  4187 I SystemUpdateService: OTA package size = 12249756
,08-26 21:10:55.085  1717  4187 I SystemUpdateService: showing system update notification
,08-26 21:10:55.085   871  4174 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 19:10:55 GMT], X-Android-Received-Millis=[1472238655084], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472238655051]}
,08-26 21:10:55.086   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 21:10:55.086   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-26 21:10:55.086   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 21:10:55.088   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 21:10:55.093  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 21:10:55.098  1717  2516 I iu.UploadsManager: num queued entries: 0
,08-26 21:10:55.099  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-26 21:10:55.099  1717  4192 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-26 21:10:55.099  1717  4192 W BaseAppContext: Using Auth Proxy for data requests.
08-26 21:10:55.100  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 21:10:55.100  1717  2516 I iu.UploadsManager: num updated entries: 0
08-26 21:10:55.100  1717  4192 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
08-26 21:10:55.101  1717  2516 I iu.SyncManager: NEXT; no task
,08-26 21:10:55.102  4051  4051 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:10:55.105  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 21:10:55.107  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 21:10:55.107  1717  1717 D SystemUpdateService: onDestroy
,08-26 21:10:55.113  4051  4051 D SprintDMHelper: simOperator: 
08-26 21:10:55.113  4051  4051 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 21:10:55.135  1508  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 21:10:55.135  1508  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 21:10:55.135  1508  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 21:10:55.136  1508  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 21:10:55.150  1717  4192 E MDM     : [177] SitrepService.a: Error sending sitrep.
,08-26 21:10:55.240  2406  4194 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 21:10:56.007   871  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-26 21:10:56.540   871  1965 I ActivityManager: Killing 2240:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-26 21:10:56.848   871  2079 D WifiService: setWifiEnabled: false pid=3924, uid=10000
,08-26 21:10:56.848   871  2079 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 21:10:56.870  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1,
,08-26 21:10:56.873   871  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 21:10:56.873   871  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-26 21:10:56.874   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 21:10:56.874   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 21:10:56.897   871  2123 D DhcpClient: Clearing IP address
,08-26 21:10:56.897   372   869 D CommandListener: Clearing all IP addresses on wlan0
,08-26 21:10:56.902   372   869 D CommandListener: Setting iface cfg
,08-26 21:10:56.907  1508  4199 V NativeCrypto: Read error: ssl=0x9a799200: I/O error during system call, Connection timed out
08-26 21:10:56.912  1508  4199 V NativeCrypto: SSL shutdown failed: ssl=0x9a799200: I/O error during system call, Broken pipe
08-26 21:10:56.914   871  4176 D DhcpClient: Receive thread stopped
08-26 21:10:56.917   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 21:10:56.918   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-26 21:10:56.922   395   395 E Parcel  : Reading a NULL string not supported here.
,08-26 21:10:56.928   871  1313 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-26 21:10:56.929   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 21:10:56.931   372   869 D CommandListener: Clearing all IP addresses on wlan0
,08-26 21:10:56.933   871  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-26 21:10:56.940   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 21:10:56.945  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:56.945  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:56.945  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:56.945  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:56.945  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:10:56.945  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:56.945  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:56.945  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:56.945  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:10:56.946  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:56.946  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:10:56.946   871  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 21:10:56.947  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:10:56.947  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:10:56.947  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:10:56.947  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:10:56.947  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:10:56.947  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:10:56.947  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:10:56.947  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:10:56.947  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:10:56.947  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:10:56.947  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:10:56.950  2098  2337 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 21:10:56.975   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 21:10:56.995   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 21:10:56.996   871  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 21:10:56.996   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:10:56.999   871   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 21:10:57.002  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:10:57.003  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:10:57.009  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 21:10:57.013  1717  1717 D SystemUpdateService: onCreate
,08-26 21:10:57.015  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 21:10:57.023  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 21:10:57.028  1717  2516 I iu.UploadsManager: num queued entries: 0
,08-26 21:10:57.028  1717  2516 I iu.UploadsManager: num updated entries: 0
,08-26 21:10:57.031  1717  4210 I SystemUpdateService: active receiver: enabled
,08-26 21:10:57.033  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 21:10:57.034  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 21:10:57.037  4051  4051 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:10:57.041  4051  4051 D SprintDMHelper: simOperator: 
,08-26 21:10:57.041  4051  4051 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 21:10:57.053  1717  2516 I iu.SyncManager: NEXT; no task
,08-26 21:10:57.055  1717  4210 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 21:10:57.072   372   869 E Netd    : netlink response contains error (No such file or directory)
08-26 21:10:57.073   871  1315 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-26 21:10:57.075  2406  4214 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 21:10:57.082  1717  4210 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-26 21:10:57.082  1717  4210 I SystemUpdateService: now status is 0 (complete)
08-26 21:10:57.082  1717  4210 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 21:10:57.083  1717  4210 I SystemUpdateService: file has been verified
08-26 21:10:57.083  1717  4210 I SystemUpdateService: OTA package size = 12249756
,08-26 21:10:57.088  1717  4210 I SystemUpdateService: showing system update notification
,08-26 21:10:57.107  1717  1717 D SystemUpdateService: onDestroy
,08-26 21:10:57.132  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 21:10:57.161  1508  2015 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-26 21:10:57.162  1508  2015 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 21:10:57.162  1508  2015 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 21:10:57.162  1508  2015 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 21:10:57.175  3625  3625 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-26 21:10:57.176  3625  3625 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-26 21:10:57.176  3625  3625 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-26 21:10:59.910   871   889 I ActivityManager: Start proc 4218:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 21:11:00.053  4218  4218 D AdapterServiceConfig: Adding HeadsetService
,08-26 21:11:00.053  4218  4218 D AdapterServiceConfig: Adding A2dpService
08-26 21:11:00.053  4218  4218 D AdapterServiceConfig: Adding HidService
08-26 21:11:00.054  4218  4218 D AdapterServiceConfig: Adding HealthService
,08-26 21:11:00.054  4218  4218 D AdapterServiceConfig: Adding PanService
,08-26 21:11:00.055  4218  4218 D AdapterServiceConfig: Adding GattService
08-26 21:11:00.055  4218  4218 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 21:11:00.068   871   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a0233d9:true
,08-26 21:11:00.068  4218  4218 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 21:11:00.073  4218  4218 I bt_bluedroid: init
,08-26 21:11:00.073  4218  4230 I BluetoothAdapterState: Entering OffState
08-26 21:11:00.074  4218  4231 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 21:11:00.074  4218  4231 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 21:11:00.074  4218  4231 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 21:11:00.075  4218  4231 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 21:11:00.075  4218  4218 I bt_bluedroid: get_profile_interface socket
08-26 21:11:00.076  4218  4218 I bt_bluedroid: get_profile_interface sdp
08-26 21:11:00.077  4218  4234 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 21:11:00.079  4218  4234 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 21:11:00.080  4218  4229 I bt_bluedroid: config_hci_snoop_log
,08-26 21:11:00.083   871   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 21:11:00.088  4218  4230 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 21:11:00.088  4218  4230 D BluetoothAdapterProperties: Setting state to 14
08-26 21:11:00.089  4218  4230 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 21:11:00.093  4218  4230 D BluetoothBondStateMachine: make
,08-26 21:11:00.096  4218  4236 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 21:11:00.102  4218  4230 I BluetoothAdapterState: Entering PendingCommandState
,08-26 21:11:00.104  4218  4218 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 21:11:00.108  4218  4218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
,08-26 21:11:00.108  4218  4218 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 21:11:00.109  4218  4218 D BtGatt.GattService: Received start request. Starting profile...
,08-26 21:11:00.109  4218  4218 D BtGatt.GattService: start()
08-26 21:11:00.109  4218  4218 I bt_bluedroid: get_profile_interface gatt
08-26 21:11:00.110  4218  4218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
,08-26 21:11:00.110  4218  4218 D BtGatt.AdvertiseManager: advertise manager created
,08-26 21:11:00.116  4218  4218 V BluetoothAdapterState: isTurningOff()=false
08-26 21:11:00.116  4218  4218 V BluetoothAdapterState: isTurningOn()=false
08-26 21:11:00.116  4218  4218 V BluetoothAdapterState: isBleTurningOn()=true
,08-26 21:11:00.116  4218  4218 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 21:11:00.117  4218  4230 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-26 21:11:00.117  4218  4230 I bt_bluedroid: enable
08-26 21:11:00.117  4218  4231 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-26 21:11:00.117  4218  4231 I bt_hci  : start_up
,08-26 21:11:00.126  4218  4231 I bt_vendor: alloc value 0xb399c189
08-26 21:11:00.126  4218  4231 I bt_vendor: init
,08-26 21:11:00.126  4218  4231 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 21:11:00.126  4218  4231 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 21:11:00.233  4218  4231 D bt_hci  : start_up starting async portion
,08-26 21:11:00.233  4218  4239 I bt_hci  : event_finish_startup
,08-26 21:11:00.234  4218  4239 I bt_hci_h4: hal_open
08-26 21:11:00.234  4218  4239 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 21:11:00.245  4218  4239 I bt_userial_vendor: device fd = 51 open
,08-26 21:11:00.276  4218  4239 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 21:11:00.308  4218  4239 D bt_hwcfg: Chipset BCM4354A2
,08-26 21:11:00.308  4218  4239 D bt_hwcfg: Target name = [BCM4354A2]
08-26 21:11:00.309  4218  4239 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 21:11:01.012  4218  4239 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 21:11:01.014  4218  4239 D bt_hwcfg: Settlement delay -- 100 ms
08-26 21:11:01.014  4218  4239 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 21:11:01.131  4218  4239 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-26 21:11:01.132  4218  4239 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 21:11:01.161  4218  4239 I bt_hwcfg: vendor lib fwcfg completed
,08-26 21:11:01.162  4218  4239 I bt_vendor: firmware callback
08-26 21:11:01.162  4218  4239 I bt_hci  : firmware_config_callback
,08-26 21:11:01.175  4218  4241 I bt_btu  : btu_task pending for preload complete event
08-26 21:11:01.176  4218  4241 I bt_btu_task: Bluetooth chip preload is complete
,08-26 21:11:01.176  4218  4241 I bt_btu  : btu_task received preload complete event
,08-26 21:11:01.186  4218  4241 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 21:11:01.187  4218  4241 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 21:11:01.187  4218  4241 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 21:11:01.187  4218  4241 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 21:11:01.188  4218  4241 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 21:11:01.188  4218  4241 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 21:11:01.188  4218  4241 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 21:11:01.188  4218  4241 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 21:11:01.189  4218  4241 I         : BTE_InitTraceLevels -- TRC_GAP
,08-26 21:11:01.189  4218  4241 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 21:11:01.189  4218  4241 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 21:11:01.189  4218  4241 I         : BTE_InitTraceLevels -- TRC_GATT
,08-26 21:11:01.190  4218  4241 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 21:11:01.190  4218  4241 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 21:11:01.190  4218  4241 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 21:11:01.325  4218  4241 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3919d9d
,08-26 21:11:01.326  4218  4241 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3919d9d 
,08-26 21:11:01.343  4218  4234 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 21:11:01.345  4218  4234 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 21:11:01.346  4218  4234 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 21:11:01.349  4218  4234 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 21:11:01.352  4218  4234 D BluetoothAdapterProperties: Scan Mode:20
08-26 21:11:01.352  4218  4234 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 21:11:01.352  4218  4234 D bt_hci  : do_postload posting postload work item
,08-26 21:11:01.353  4218  4239 I bt_hci  : event_postload
08-26 21:11:01.353  4218  4239 I bt_vendor: sco_config_cb
08-26 21:11:01.353  4218  4239 I bt_hci  : sco_config_callback postload finished.
,08-26 21:11:01.355  4218  4234 D bt_bte_conf: Device ID record 1 : primary
08-26 21:11:01.356  4218  4234 D bt_bte_conf:   vendorId            = 000f
08-26 21:11:01.356  4218  4234 D bt_bte_conf:   vendorIdSource      = 0001
08-26 21:11:01.356  4218  4234 D bt_bte_conf:   product             = 1200
,08-26 21:11:01.356  4218  4234 D bt_bte_conf:   version             = 1436
08-26 21:11:01.356  4218  4234 D bt_bte_conf:   clientExecutableURL = 
08-26 21:11:01.356  4218  4234 D bt_bte_conf:   serviceDescription  = 
08-26 21:11:01.356  4218  4234 D bt_bte_conf:   documentationURL    = 
08-26 21:11:01.357  4218  4234 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 21:11:01.357  4218  4231 D bt_stack_manager: event_start_up_stack finished
08-26 21:11:01.359  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:01.363  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:01.362  4218  4230 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 21:11:01.363  4218  4230 D BluetoothAdapterProperties: Setting state to 15
08-26 21:11:01.364  4218  4230 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 21:11:01.365  4218  4230 I BluetoothAdapterState: Entering BleOnState
,08-26 21:11:01.369  4218  4239 I bt_vendor: low_power_mode_cb
,08-26 21:11:01.371  4218  4230 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 21:11:01.371  4218  4230 D BluetoothAdapterProperties: Setting state to 11
,08-26 21:11:01.372  4218  4230 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 21:11:01.378  4218  4218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
,08-26 21:11:01.380  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:01.382  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:01.383  4218  4218 D HeadsetService: Received start request. Starting profile...
,08-26 21:11:01.391  4218  4218 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 21:11:01.392  4218  4230 I BluetoothAdapterState: Entering PendingCommandState
,08-26 21:11:01.393  4218  4218 D HeadsetStateMachine: make
,08-26 21:11:01.403  4218  4218 D HeadsetStateMachine: max_hf_connections = 1
,08-26 21:11:01.403  4218  4218 I bt_bluedroid: get_profile_interface handsfree
,08-26 21:11:01.404  4218  4234 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 21:11:01.404  4218  4234 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-26 21:11:01.407  4218  4218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
,08-26 21:11:01.408  4218  4218 D A2dpService: Received start request. Starting profile...
,08-26 21:11:01.409  4218  4218 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 21:11:01.409  4218  4218 I bt_bluedroid: get_profile_interface avrcp
,08-26 21:11:01.415  4218  4218 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 21:11:01.415  4218  4218 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 21:11:01.415  4218  4218 D A2dpStateMachine: make
,08-26 21:11:01.416  4218  4218 I bt_bluedroid: get_profile_interface a2dp
,08-26 21:11:01.417  4218  4234 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 21:11:01.419  4218  4250 D A2dpStateMachine: Enter Disconnected: -2
,08-26 21:11:01.422  4218  4218 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 21:11:01.422  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:11:01.423  4218  4218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
,08-26 21:11:01.425  4218  4218 D HidService: Received start request. Starting profile...
,08-26 21:11:01.425  4218  4218 I bt_bluedroid: get_profile_interface hidhost
08-26 21:11:01.425  4218  4234 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fb3e5
08-26 21:11:01.425  3994  3994 D BluetoothInputDevice: Proxy object connected
,08-26 21:11:01.425  4218  4234 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 21:11:01.425  4218  4218 D HidService: setHidService(): set to: null
,08-26 21:11:01.426  4218  4218 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 21:11:01.427  4218  4218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
08-26 21:11:01.427  3994  3994 D HidProfile: Bluetooth service connected
,08-26 21:11:01.427  4218  4218 D HealthService: Received start request. Starting profile...
,08-26 21:11:01.429  4218  4218 I bt_bluedroid: get_profile_interface health
,08-26 21:11:01.430  4218  4218 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 21:11:01.431  4218  4218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
,08-26 21:11:01.432  4218  4218 D PanService: Received start request. Starting profile...
,08-26 21:11:01.432  4218  4218 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 21:11:01.432  4218  4218 I bt_bluedroid: get_profile_interface pan
,08-26 21:11:01.433  4218  4234 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 21:11:01.432  3994  3994 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 21:11:01.435  4218  4218 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
,08-26 21:11:01.436  4218  4218 D BluetoothMapService: Received start request. Starting profile...
,08-26 21:11:01.436  4218  4218 D BluetoothMapService: start()
,08-26 21:11:01.439  3994  3994 D PanProfile: Bluetooth service connected
,08-26 21:11:01.439  4218  4218 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 21:11:01.439  3994  3994 D BluetoothMap: Proxy object connected
,08-26 21:11:01.439  4218  4218 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-26 21:11:01.439  4218  4218 D BluetoothMapAppObserver: createReceiver()
,08-26 21:11:01.440  4218  4218 D BluetoothMapAppObserver: initObservers()
,08-26 21:11:01.440  4218  4218 D BluetoothMapAppObserver: getEnabledAccountItems()
08-26 21:11:01.441  3994  3994 D MapProfile: Bluetooth service connected
,08-26 21:11:01.441  3994  3994 D BluetoothMap: getConnectedDevices()
08-26 21:11:01.442  3994  3994 D BluetoothMap: Bluetooth is Not enabled
,08-26 21:11:01.448  4218  4218 V BluetoothAdapterState: isTurningOff()=false
,08-26 21:11:01.448  4218  4218 V BluetoothAdapterState: isTurningOn()=true
08-26 21:11:01.448  4218  4218 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:11:01.448  4218  4248 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5,
08-26 21:11:01.448  4218  4218 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 21:11:01.450  4218  4218 V BluetoothAdapterState: isTurningOff()=false
,08-26 21:11:01.450  4218  4218 V BluetoothAdapterState: isTurningOn()=true
08-26 21:11:01.450  4218  4218 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:11:01.450  4218  4218 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 21:11:01.451  4218  4218 V BluetoothAdapterState: isTurningOff()=false
,08-26 21:11:01.451  4218  4218 V BluetoothAdapterState: isTurningOn()=true
,08-26 21:11:01.451  4218  4218 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:11:01.451  4218  4218 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:11:01.451  4218  4218 V BluetoothAdapterState: isTurningOff()=false
08-26 21:11:01.451  4218  4218 V BluetoothAdapterState: isTurningOn()=true
08-26 21:11:01.451  4218  4218 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:11:01.451  4218  4218 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:11:01.452  4218  4218 V BluetoothAdapterState: isTurningOff()=false
08-26 21:11:01.452  4218  4218 V BluetoothAdapterState: isTurningOn()=true
08-26 21:11:01.452  4218  4218 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:11:01.452  4218  4218 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 21:11:01.452  4218  4218 V BluetoothAdapterState: isTurningOff()=false
08-26 21:11:01.452  4218  4218 V BluetoothAdapterState: isTurningOn()=true
08-26 21:11:01.452  4218  4218 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:11:01.452  4218  4218 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:11:01.453  4218  4230 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-26 21:11:01.453  4218  4230 D BluetoothAdapterProperties: ScanMode =  20
08-26 21:11:01.453  4218  4230 D BluetoothAdapterProperties: State =  11
08-26 21:11:01.455  4218  4234 D BluetoothAdapterProperties: Scan Mode:21
08-26 21:11:01.455  4218  4234 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 21:11:01.455  4218  4230 D BluetoothAdapterProperties: Setting state to 12
,08-26 21:11:01.455  4218  4230 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 21:11:01.456   871   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:11:01.456  3994  4006 D BluetoothMap: onBluetoothStateChange: up=true
08-26 21:11:01.457  4218  4230 I BluetoothAdapterState: Entering OnState
,08-26 21:11:01.457  3994  4007 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 21:11:01.458   871   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 21:11:01.459  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:11:01.459  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:01.459  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:01.459  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:11:01.459  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:01.459  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:11:01.459  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:11:01.459  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:11:01.460   871   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:11:01.461  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:11:01.461  1364  1690 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 21:11:01.461   871   871 D BluetoothA2dp: Proxy object connected
,08-26 21:11:01.464  1364  1388 D BluetoothPan: onBluetoothStateChange on: true
,08-26 21:11:01.466  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:11:01.466  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:01.466  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:01.466  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:11:01.466  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:01.466  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:11:01.466  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:11:01.466  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:11:01.466  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 21:11:01.466  1364  1364 D PanProfile: Bluetooth service connected
,08-26 21:11:01.467  1364  1690 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 21:11:01.467  4218  4218 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 21:11:01.467  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:11:01.468  4218  4218 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 21:11:01.469  1364  1364 D BluetoothA2dp: Proxy object connected
08-26 21:11:01.469  3994  4006 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 21:11:01.470  4218  4218 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:11:01.471  1364  1690 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 21:11:01.472  4218  4218 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:11:01.472   871   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:11:01.473  1364  1388 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 21:11:01.473  4218  4218 D ObexServerSockets: Succeed to create listening sockets 
08-26 21:11:01.473  4218  4218 D ObexServerSockets0: startAccept()
,08-26 21:11:01.473  4218  4218 D ObexServerSockets0: prepareForNewConnect()
,08-26 21:11:01.474  1364  1364 D BluetoothInputDevice: Proxy object connected
08-26 21:11:01.474  1364  1364 D HidProfile: Bluetooth service connected
,08-26 21:11:01.475  3994  4007 D BluetoothPan: onBluetoothStateChange on: true
,08-26 21:11:01.475  4218  4218 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 21:11:01.475  4218  4218 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 21:11:01.476  1364  1690 D BluetoothMap: onBluetoothStateChange: up=true
08-26 21:11:01.476  4218  4256 D ObexServerSockets0: Accepting socket connection...
08-26 21:11:01.476  4218  4257 D ObexServerSockets0: Accepting socket connection...
,08-26 21:11:01.477  1364  1364 D BluetoothMap: Proxy object connected
08-26 21:11:01.478  1364  1364 D MapProfile: Bluetooth service connected
08-26 21:11:01.478  1364  1364 D BluetoothMap: getConnectedDevices()
08-26 21:11:01.478  1933  2052 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:11:01.479   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 21:11:01.480  4218  4218 D BluetoothMapService: onReceive
,08-26 21:11:01.481  4218  4218 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:11:01.481  4218  4218 D BluetoothMapService: STATE_ON
08-26 21:11:01.481  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:01.482  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:01.483  3994  3994 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-26 21:11:01.487  3994  3994 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-26 21:11:01.491  3994  3994 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 21:11:01.494  3994  3994 D BluetoothA2dp: Proxy object connected
,08-26 21:11:01.497  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:11:01.501  3994  3994 D DockEventReceiver: finishStartingService: stopping service
,08-26 21:11:01.508  3994  3994 D BluetoothPbap: Proxy object connected
,08-26 21:11:01.508  3994  3994 D PbapServerProfile: Bluetooth service connected
,08-26 21:11:01.510  1364  1364 D BluetoothPbap: Proxy object connected
,08-26 21:11:01.510  1364  1364 D PbapServerProfile: Bluetooth service connected
,08-26 21:11:01.515  4218  4218 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 21:11:01.515  4218  4218 D ObexServerSockets0: prepareForNewConnect()
,08-26 21:11:01.520  4218  4261 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
,08-26 21:11:01.534  4218  4265 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:11:01.536  4218  4265 I BtOppRfcommListener: Accept thread started.
,08-26 21:11:01.558   871   871 D BluetoothHeadset: Proxy object connected
,08-26 21:11:01.558   871   871 D BluetoothHeadset: Proxy object connected
08-26 21:11:01.558   871   871 D BluetoothHeadset: Proxy object connected
08-26 21:11:01.559  1933  2060 D BluetoothHeadset: Proxy object connected
08-26 21:11:01.559  1364  1388 D BluetoothHeadset: Proxy object connected
08-26 21:11:01.560  1364  1364 D HeadsetProfile: Bluetooth service connected
08-26 21:11:01.560   871   889 D BluetoothHeadset: Proxy object connected
,08-26 21:11:01.562  1364  1690 D BluetoothHeadset: Proxy object connected
08-26 21:11:01.562  1364  1364 D HeadsetProfile: Bluetooth service connected
,08-26 21:11:01.572   871   889 D BluetoothHeadset: Proxy object connected
,08-26 21:11:01.579  1933  1951 D BluetoothHeadset: Proxy object connected
,08-26 21:11:01.590  3994  4007 D BluetoothHeadset: Proxy object connected
,08-26 21:11:01.591  3994  3994 D HeadsetProfile: Bluetooth service connected
,08-26 21:11:02.869  4218  4230 D BluetoothAdapterState: Current state: ON, message: 23
,08-26 21:11:02.869  4218  4230 D BluetoothAdapterProperties: Setting state to 13
,08-26 21:11:02.870  4218  4230 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-26 21:11:02.872  4218  4230 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 21:11:02.873  4218  4230 I BluetoothAdapterState: Entering PendingCommandState
,08-26 21:11:02.882  4218  4218 D BluetoothMapService: onReceive
,08-26 21:11:02.882  4218  4218 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:11:02.887  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:11:02.886  4218  4234 D BluetoothAdapterProperties: Scan Mode:20
,08-26 21:11:02.888  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:11:02.888  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:02.888  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:02.888  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false,
08-26 21:11:02.888  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:11:02.888  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:11:02.888  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:11:02.888  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:11:02.888  4218  4218 D BluetoothMapService: STATE_TURNING_OFF
08-26 21:11:02.889  4218  4230 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-26 21:11:02.889  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:11:02.889  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:11:02.886  3994  3994 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 21:11:02.889  4218  4218 D BluetoothMapService: MAP Service closeService in
08-26 21:11:02.891  4218  4218 D BluetoothMapMasInstance0: MAP Service shutdown,
,08-26 21:11:02.891  4218  4218 D ObexServerSockets0: shutdown(block = true)
,08-26 21:11:02.892  4218  4256 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-26 21:11:02.893  4218  4218 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 21:11:02.894  4218  4257 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 21:11:02.895  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:11:02.895  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:11:02.895  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:02.895  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:02.895  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:11:02.895  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:11:02.895  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:11:02.895  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:11:02.895  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:11:02.897  3924  3924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:11:02.897  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:11:02.897  4218  4243 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 21:11:02.898  4218  4218 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-26 21:11:02.899  4218  4218 I BtOppRfcommListener: stopping Accept Thread
,08-26 21:11:02.899  4218  4265 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 21:11:02.900  4218  4265 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 21:11:02.900  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:02.902  4218  4218 D HeadsetService: Received stop request...Stopping profile...
,08-26 21:11:02.904  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:02.904   871   871 D BluetoothHeadset: Proxy object disconnected
,08-26 21:11:02.904   871   871 D BluetoothHeadset: Proxy object disconnected
08-26 21:11:02.904   871   871 D BluetoothHeadset: Proxy object disconnected
,08-26 21:11:02.905  1933  1951 D BluetoothHeadset: Proxy object disconnected
08-26 21:11:02.905  3994  4007 D BluetoothHeadset: Proxy object disconnected
08-26 21:11:02.906  1364  1690 D BluetoothHeadset: Proxy object disconnected
,08-26 21:11:02.910  4218  4218 D A2dpService: Received stop request...Stopping profile...
,08-26 21:11:02.910  4218  4250 D A2dpStateMachine: Exit Disconnected: -1
08-26 21:11:02.911  1364  1364 D HeadsetProfile: Bluetooth service disconnected
,08-26 21:11:02.912   871   871 D BluetoothA2dp: Proxy object disconnected
08-26 21:11:02.913  4218  4218 V BluetoothAdapterState: isTurningOff()=true
08-26 21:11:02.913  4218  4218 V BluetoothAdapterState: isTurningOn()=false
,08-26 21:11:02.913  4218  4218 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:11:02.913  4218  4218 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 21:11:02.914  4218  4218 D HidService: Received stop request...Stopping profile...
08-26 21:11:02.914  4218  4218 D HidService: Stopping Bluetooth HidService
08-26 21:11:02.914  1364  1364 D BluetoothA2dp: Proxy object disconnected
08-26 21:11:02.915   871  1315 D ConnectivityService: handlePromptUnvalidated 101
08-26 21:11:02.915  1364  1364 D BluetoothInputDevice: Proxy object disconnected
08-26 21:11:02.915  1364  1364 D HidProfile: Bluetooth service disconnected
08-26 21:11:02.917  4218  4218 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-26 21:11:02.917  4218  4234 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 21:11:02.917  4218  4241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:11:02.917  4218  4241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:11:02.917  4218  4241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:11:02.917  4218  4234 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-26 21:11:02.917  4218  4218 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 21:11:02.919  3994  3994 D DockEventReceiver: finishStartingService: stopping service
08-26 21:11:02.922  4218  4218 D HealthService: Received stop request...Stopping profile...
08-26 21:11:02.922  3994  3994 D HeadsetProfile: Bluetooth service disconnected
,08-26 21:11:02.922  3994  3994 D BluetoothA2dp: Proxy object disconnected
08-26 21:11:02.922  3994  3994 D BluetoothInputDevice: Proxy object disconnected
08-26 21:11:02.922  3994  3994 D HidProfile: Bluetooth service disconnected
08-26 21:11:02.923  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:11:02.924  4218  4218 D PanService: Received stop request...Stopping profile...
08-26 21:11:02.924  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 21:11:02.925  4218  4218 V BluetoothAdapterState: isTurningOff()=true
,08-26 21:11:02.925  1364  1364 D PanProfile: Bluetooth service disconnected
08-26 21:11:02.925  4218  4218 V BluetoothAdapterState: isTurningOn()=false
08-26 21:11:02.925  3994  3994 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 21:11:02.925  4218  4218 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:11:02.925  3994  3994 D PanProfile: Bluetooth service disconnected
08-26 21:11:02.925  4218  4218 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:11:02.926  4218  4234 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 21:11:02.926  4218  4241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:11:02.926  4218  4241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 21:11:02.926  4218  4241 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 21:11:02.926  4218  4218 D BluetoothMapService: Received stop request...Stopping profile...
08-26 21:11:02.926  4218  4241 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:11:02.926  4218  4241 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 21:11:02.926  4218  4218 D BluetoothMapService: stop()
08-26 21:11:02.926  4218  4241 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:11:02.927  4218  4218 D BluetoothMapAppObserver: deinitObservers()
,08-26 21:11:02.927  4218  4218 D BluetoothMapAppObserver: removeReceiver()
,08-26 21:11:02.928  1364  1364 D BluetoothMap: Proxy object disconnected
,08-26 21:11:02.928  3994  3994 D BluetoothMap: Proxy object disconnected
08-26 21:11:02.928  1364  1364 D MapProfile: Bluetooth service disconnected,
08-26 21:11:02.928  3994  3994 D MapProfile: Bluetooth service disconnected
08-26 21:11:02.928  4218  4218 V BluetoothAdapterState: isTurningOff()=true
08-26 21:11:02.928  4218  4218 V BluetoothAdapterState: isTurningOn()=false
08-26 21:11:02.928  4218  4218 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:11:02.928  4218  4218 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:11:02.929  4218  4218 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 21:11:02.929  4218  4234 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000,
08-26 21:11:02.929  4218  4218 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 21:11:02.931  1364  1364 D BluetoothPbap: Proxy object disconnected
08-26 21:11:02.931  1364  1364 D PbapServerProfile: Bluetooth service disconnected
,08-26 21:11:02.931  4218  4218 V BluetoothAdapterState: isTurningOff()=true
08-26 21:11:02.931  3994  3994 D BluetoothPbap: Proxy object disconnected
08-26 21:11:02.931  4218  4218 V BluetoothAdapterState: isTurningOn()=false
,08-26 21:11:02.931  3994  3994 D PbapServerProfile: Bluetooth service disconnected
08-26 21:11:02.931  4218  4218 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:11:02.931  4218  4218 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:11:02.931  4218  4218 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 21:11:02.932  4218  4234 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 21:11:02.932  4218  4218 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-26 21:11:02.932  4218  4218 V BluetoothAdapterState: isTurningOff()=true
08-26 21:11:02.932  4218  4218 V BluetoothAdapterState: isTurningOn()=false
,08-26 21:11:02.932  4218  4218 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:11:02.932  4218  4218 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 21:11:02.933  4218  4218 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 21:11:02.933  4218  4218 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 21:11:02.934  4218  4218 D BluetoothMapService: MAP Service closeService in
08-26 21:11:02.934  4218  4218 V BluetoothAdapterState: isTurningOff()=true
08-26 21:11:02.934  4218  4218 V BluetoothAdapterState: isTurningOn()=false
,08-26 21:11:02.934  4218  4218 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:11:02.934  4218  4218 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:11:02.934  4218  4230 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-26 21:11:02.934  4218  4230 D BluetoothAdapterProperties: Setting state to 15
08-26 21:11:02.935  4218  4230 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-26 21:11:02.935  4218  4230 I BluetoothAdapterState: Entering BleOnState
08-26 21:11:02.935  4218  4218 D BluetoothMapService: cleanup()
08-26 21:11:02.935  4218  4218 D BluetoothMapService: MAP Service closeService in
,08-26 21:11:02.936  3994  4255 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:11:02.937   871   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:11:02.937  3994  4006 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 21:11:02.938  3994  4007 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 21:11:02.939   871   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 21:11:02.939   871   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:11:02.939  1364  1690 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:11:02.939  1364  1381 D BluetoothPan: onBluetoothStateChange on: false
08-26 21:11:02.940  1364  1388 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 21:11:02.940  3994  4255 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 21:11:02.941  3994  4006 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 21:11:02.941  1364  1690 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 21:11:02.941   871   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:11:02.942  1364  1381 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 21:11:02.942  3994  4007 D BluetoothPan: onBluetoothStateChange on: false
08-26 21:11:02.942  1364  1388 D BluetoothMap: onBluetoothStateChange: up=false
08-26 21:11:02.943  1933  1949 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:11:02.943  4218  4230 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 21:11:02.943  4218  4230 D BluetoothAdapterProperties: Setting state to 16
08-26 21:11:02.943  4218  4230 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 21:11:02.944  4218  4230 D BluetoothAdapterProperties: onBleDisable
08-26 21:11:02.944  4218  4230 I BluetoothAdapterState: Entering PendingCommandState
08-26 21:11:02.945  4218  4231 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 21:11:02.946  4218  4241 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 21:11:02.946  4218  4241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:11:02.947  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:02.948  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:02.949  4218  4234 D BluetoothAdapterProperties: Scan Mode:20
08-26 21:11:02.949  3994  3994 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 21:11:02.950  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:02.951  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:02.954  3994  3994 D DockEventReceiver: finishStartingService: stopping service
08-26 21:11:02.955  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:11:03.147  4218  4234 I bt_hci  : shut_down
08-26 21:11:03.149  4218  4239 D bt_hwcfg: hw_epilog_process
,08-26 21:11:03.149  4218  4239 I bt_vendor: low_power_mode_cb
,08-26 21:11:03.180  4218  4239 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 21:11:03.180  4218  4239 I bt_vendor: epilog_cb
08-26 21:11:03.180  4218  4239 I bt_hci  : epilog_finished_callback
,08-26 21:11:03.191  4218  4234 I bt_hci_h4: hal_close
,08-26 21:11:03.194  4218  4234 I bt_userial_vendor: device fd = 51 close
,08-26 21:11:03.320  4218  4231 D bt_stack_manager: event_shut_down_stack finished.
,08-26 21:11:03.321  4218  4230 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 21:11:03.327  4218  4218 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 21:11:03.328  4218  4230 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 21:11:03.328  4218  4218 D BtGatt.GattService: Received stop request...Stopping profile...
,08-26 21:11:03.328  4218  4218 D BtGatt.GattService: stop()
08-26 21:11:03.329  4218  4218 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 21:11:03.334  4218  4218 V BluetoothAdapterState: isTurningOff()=false
,08-26 21:11:03.335  4218  4218 V BluetoothAdapterState: isTurningOn()=false
,08-26 21:11:03.335  4218  4218 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:11:03.335  4218  4218 V BluetoothAdapterState: isBleTurningOff()=true
,08-26 21:11:03.336  4218  4230 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-26 21:11:03.337  4218  4230 D BluetoothAdapterProperties: Setting state to 10
,08-26 21:11:03.337  4218  4230 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-26 21:11:03.338  4218  4230 I BluetoothAdapterState: Entering OffState
,08-26 21:11:03.341   871   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 21:11:03.369  4218  4218 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-26 21:11:03.369  4218  4218 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 21:11:03.370  4218  4231 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 21:11:03.376  4218  4231 D bt_stack_manager: event_clean_up_stack finished.
,08-26 21:11:03.377  4218  4218 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 21:11:03.382  4218  4218 I art     : System.exit called, status: 0
,08-26 21:11:03.383  4218  4218 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 21:11:03.456   871  2080 I ActivityManager: Process com.android.bluetooth (pid 4218) has died
,08-26 21:11:05.865  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 21:11:05.866  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:11:07.055   871   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-26 21:11:07.070  1870  1870 I Keyboard.Facilitator: onFinishInput()
,08-26 21:11:07.079   871   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 21:11:07.079   871   892 I Adreno  : Build Date                       : 10/20/15
08-26 21:11:07.079   871   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 21:11:07.079   871   892 I Adreno  : Local Branch                     : M14
08-26 21:11:07.079   871   892 I Adreno  : Remote Branch                    : 
08-26 21:11:07.079   871   892 I Adreno  : Remote Branch                    : 
08-26 21:11:07.079   871   892 I Adreno  : Reconstruct Branch               : 
,08-26 21:11:07.124   282   881 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (213 us)
,08-26 21:11:07.738  3924  3924 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 21:11:07.738  3924  3924 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 21:11:07.776   871   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-26 21:11:07.776  3924  3924 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c777523 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@b1ffe55, 16908290=android.view.AbsSavedState$1@b1ffe55}, android:focusedViewId=100}]}]
08-26 21:11:07.776  3924  3924 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-26 21:11:07.777  3924  3924 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 21:11:07.777  3924  3924 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 21:11:07.783   871   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-26 21:11:07.786   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,08-26 21:11:07.787   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-26 21:11:07.787   871   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-26 21:11:08.019   282   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-26 21:11:08.023   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0,
,08-26 21:11:08.025   871  1339 D SurfaceControl: Excessive delay in setPowerMode(): 238ms
,08-26 21:11:08.027   871   892 I DreamManagerService: Entering dreamland.
,08-26 21:11:08.029   871   892 I PowerManagerService: Dozing...
,08-26 21:11:08.030   871   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-26 21:11:08.109   376  1286 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-26 21:11:08.109   376  1286 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-26 21:11:08.117   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 21:11:08.129   871  1313 E native  : do suspend false
,08-26 21:11:08.144  1921  4277 D NfcService: Discovery configuration equal, not updating.
,08-26 21:11:08.172   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 21:11:08.176   871  1313 E native  : do suspend true
,08-26 21:11:08.245   376  1321 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-26 21:11:08.246   376  1321 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-26 21:11:08.873  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:11:08.874  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6db606a added. We now have 6 listener(s)
08-26 21:11:08.874  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:11:08.878  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 21:11:08.878  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ec4895b added. We now have 7 listener(s)
08-26 21:11:08.879  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:11:08.880  3924  3974 I System.out: IsBluetoothEnabled
,08-26 21:11:08.893  3924  3974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:08.947   871   889 I ActivityManager: Start proc 4283:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 21:11:09.076  4283  4283 D AdapterServiceConfig: Adding HeadsetService
08-26 21:11:09.076  4283  4283 D AdapterServiceConfig: Adding A2dpService
,08-26 21:11:09.076  4283  4283 D AdapterServiceConfig: Adding HidService
08-26 21:11:09.077  4283  4283 D AdapterServiceConfig: Adding HealthService
08-26 21:11:09.077  4283  4283 D AdapterServiceConfig: Adding PanService
08-26 21:11:09.077  4283  4283 D AdapterServiceConfig: Adding GattService
08-26 21:11:09.077  4283  4283 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 21:11:09.106   871   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eaf2ad1:true
,08-26 21:11:09.107  4283  4283 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 21:11:09.112  4283  4283 I bt_bluedroid: init
,08-26 21:11:09.112  4283  4295 I BluetoothAdapterState: Entering OffState
,08-26 21:11:09.115  4283  4296 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 21:11:09.115  4283  4296 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 21:11:09.115  4283  4296 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 21:11:09.115  4283  4296 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 21:11:09.116  4283  4283 I bt_bluedroid: get_profile_interface socket
,08-26 21:11:09.119  4283  4283 I bt_bluedroid: get_profile_interface sdp
,08-26 21:11:09.122  4283  4293 I bt_bluedroid: config_hci_snoop_log
,08-26 21:11:09.122  4283  4299 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 21:11:09.124   871   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 21:11:09.125  4283  4299 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 21:11:09.134  4283  4295 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 21:11:09.134  4283  4295 D BluetoothAdapterProperties: Setting state to 14
08-26 21:11:09.135  4283  4295 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 21:11:09.139  4283  4295 D BluetoothBondStateMachine: make
,08-26 21:11:09.145  4283  4300 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 21:11:09.150  4283  4295 I BluetoothAdapterState: Entering PendingCommandState
,08-26 21:11:09.152  4283  4283 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 21:11:09.156  4283  4283 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
,08-26 21:11:09.157  4283  4283 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 21:11:09.159  4283  4283 D BtGatt.GattService: Received start request. Starting profile...
,08-26 21:11:09.159  4283  4283 D BtGatt.GattService: start()
08-26 21:11:09.159  4283  4283 I bt_bluedroid: get_profile_interface gatt
,08-26 21:11:09.161  4283  4283 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
,08-26 21:11:09.162  4283  4283 D BtGatt.AdvertiseManager: advertise manager created
,08-26 21:11:09.175  4283  4283 V BluetoothAdapterState: isTurningOff()=false
08-26 21:11:09.175  4283  4283 V BluetoothAdapterState: isTurningOn()=false
,08-26 21:11:09.176  4283  4283 V BluetoothAdapterState: isBleTurningOn()=true
08-26 21:11:09.176  4283  4283 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 21:11:09.176  4283  4295 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-26 21:11:09.177  4283  4295 I bt_bluedroid: enable
,08-26 21:11:09.178  4283  4296 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-26 21:11:09.179  4283  4296 I bt_hci  : start_up
,08-26 21:11:09.196  4283  4296 I bt_vendor: alloc value 0xb399c189
,08-26 21:11:09.196  4283  4296 I bt_vendor: init
08-26 21:11:09.196  4283  4296 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-26 21:11:09.196  4283  4296 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 21:11:09.303  4283  4296 D bt_hci  : start_up starting async portion
08-26 21:11:09.304  4283  4303 I bt_hci  : event_finish_startup
,08-26 21:11:09.304  4283  4303 I bt_hci_h4: hal_open
,08-26 21:11:09.304  4283  4303 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 21:11:09.314  4283  4303 I bt_userial_vendor: device fd = 51 open
,08-26 21:11:09.345  4283  4303 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 21:11:09.377  4283  4303 D bt_hwcfg: Chipset BCM4354A2
,08-26 21:11:09.377  4283  4303 D bt_hwcfg: Target name = [BCM4354A2]
08-26 21:11:09.378  4283  4303 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 21:11:10.039  4283  4303 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 21:11:10.040  4283  4303 D bt_hwcfg: Settlement delay -- 100 ms
,08-26 21:11:10.041  4283  4303 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 21:11:10.158  4283  4303 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 21:11:10.159  4283  4303 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 21:11:10.188  4283  4303 I bt_hwcfg: vendor lib fwcfg completed
,08-26 21:11:10.188  4283  4303 I bt_vendor: firmware callback
,08-26 21:11:10.189  4283  4303 I bt_hci  : firmware_config_callback
,08-26 21:11:10.203  4283  4307 I bt_btu  : btu_task pending for preload complete event
,08-26 21:11:10.203  4283  4307 I bt_btu_task: Bluetooth chip preload is complete
08-26 21:11:10.204  4283  4307 I bt_btu  : btu_task received preload complete event
,08-26 21:11:10.213  4283  4307 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 21:11:10.214  4283  4307 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 21:11:10.214  4283  4307 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 21:11:10.214  4283  4307 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 21:11:10.215  4283  4307 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 21:11:10.215  4283  4307 I         : BTE_InitTraceLevels -- TRC_A2D
,08-26 21:11:10.215  4283  4307 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 21:11:10.215  4283  4307 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 21:11:10.216  4283  4307 I         : BTE_InitTraceLevels -- TRC_GAP
,08-26 21:11:10.216  4283  4307 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 21:11:10.216  4283  4307 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 21:11:10.216  4283  4307 I         : BTE_InitTraceLevels -- TRC_GATT
,08-26 21:11:10.217  4283  4307 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 21:11:10.217  4283  4307 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 21:11:10.217  4283  4307 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 21:11:10.351  4283  4307 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3919d9d
,08-26 21:11:10.352  4283  4307 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3919d9d 
,08-26 21:11:10.377  4283  4299 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 21:11:10.381  4283  4299 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 21:11:10.382  4283  4299 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-26 21:11:10.385  4283  4299 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 21:11:10.390  4283  4299 D BluetoothAdapterProperties: Scan Mode:20
08-26 21:11:10.390  4283  4299 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 21:11:10.390  4283  4299 D bt_hci  : do_postload posting postload work item
08-26 21:11:10.390  4283  4303 I bt_hci  : event_postload
,08-26 21:11:10.390  4283  4303 I bt_vendor: sco_config_cb
,08-26 21:11:10.390  4283  4303 I bt_hci  : sco_config_callback postload finished.
,08-26 21:11:10.391  4283  4299 D bt_bte_conf: Device ID record 1 : primary
,08-26 21:11:10.391  4283  4299 D bt_bte_conf:   vendorId            = 000f
,08-26 21:11:10.391  4283  4299 D bt_bte_conf:   vendorIdSource      = 0001
,08-26 21:11:10.391  4283  4299 D bt_bte_conf:   product             = 1200
08-26 21:11:10.391  4283  4299 D bt_bte_conf:   version             = 1436
08-26 21:11:10.391  4283  4299 D bt_bte_conf:   clientExecutableURL = 
08-26 21:11:10.391  4283  4299 D bt_bte_conf:   serviceDescription  = 
08-26 21:11:10.391  4283  4299 D bt_bte_conf:   documentationURL    = 
,08-26 21:11:10.391  4283  4299 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 21:11:10.392  4283  4296 D bt_stack_manager: event_start_up_stack finished
08-26 21:11:10.392  4283  4295 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 21:11:10.392  4283  4295 D BluetoothAdapterProperties: Setting state to 15
08-26 21:11:10.393  4283  4295 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 21:11:10.393  4283  4295 I BluetoothAdapterState: Entering BleOnState
,08-26 21:11:10.394  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:10.400  4283  4295 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 21:11:10.400  4283  4295 D BluetoothAdapterProperties: Setting state to 11
08-26 21:11:10.400  4283  4295 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-26 21:11:10.402  4283  4303 I bt_vendor: low_power_mode_cb
08-26 21:11:10.404  4283  4283 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
,08-26 21:11:10.412  4283  4283 D HeadsetService: Received start request. Starting profile...
08-26 21:11:10.414  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:10.415  4283  4283 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 21:11:10.415  4283  4283 D HeadsetStateMachine: make
08-26 21:11:10.421  4283  4295 I BluetoothAdapterState: Entering PendingCommandState
08-26 21:11:10.431  4283  4283 D HeadsetStateMachine: max_hf_connections = 1
08-26 21:11:10.431  4283  4283 I bt_bluedroid: get_profile_interface handsfree
,08-26 21:11:10.434  4283  4283 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
08-26 21:11:10.435  4283  4283 D A2dpService: Received start request. Starting profile...
08-26 21:11:10.432  4283  4299 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 21:11:10.435  4283  4299 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-26 21:11:10.435  4283  4283 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 21:11:10.435  4283  4283 I bt_bluedroid: get_profile_interface avrcp
,08-26 21:11:10.441  4283  4283 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 21:11:10.441  4283  4283 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 21:11:10.442  4283  4283 D A2dpStateMachine: make
,08-26 21:11:10.442  4283  4283 I bt_bluedroid: get_profile_interface a2dp
,08-26 21:11:10.443  4283  4299 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 21:11:10.445  4283  4316 D A2dpStateMachine: Enter Disconnected: -2
,08-26 21:11:10.446  4283  4283 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 21:11:10.447  4283  4283 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
,08-26 21:11:10.447  4283  4283 D HidService: Received start request. Starting profile...
08-26 21:11:10.448  4283  4283 I bt_bluedroid: get_profile_interface hidhost
08-26 21:11:10.448  4283  4299 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fb3e5
08-26 21:11:10.448  4283  4299 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-26 21:11:10.448  4283  4283 D HidService: setHidService(): set to: null
08-26 21:11:10.449  4283  4283 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 21:11:10.449  4283  4283 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
,08-26 21:11:10.450  4283  4283 D HealthService: Received start request. Starting profile...
,08-26 21:11:10.452  4283  4283 I bt_bluedroid: get_profile_interface health
,08-26 21:11:10.452  4283  4283 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 21:11:10.453  4283  4283 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
,08-26 21:11:10.454  4283  4283 D PanService: Received start request. Starting profile...
08-26 21:11:10.454  4283  4283 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 21:11:10.454  4283  4283 I bt_bluedroid: get_profile_interface pan
08-26 21:11:10.455  4283  4299 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 21:11:10.457  4283  4283 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
,08-26 21:11:10.458  4283  4283 D BluetoothMapService: Received start request. Starting profile...
08-26 21:11:10.458  4283  4283 D BluetoothMapService: start()
,08-26 21:11:10.460  4283  4283 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 21:11:10.461  4283  4283 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-26 21:11:10.461  4283  4283 D BluetoothMapAppObserver: createReceiver()
,08-26 21:11:10.462  4283  4283 D BluetoothMapAppObserver: initObservers()
08-26 21:11:10.462  4283  4283 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 21:11:10.470  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 21:11:10.470  4283  4283 V BluetoothAdapterState: isTurningOff()=false
,08-26 21:11:10.470  4283  4283 V BluetoothAdapterState: isTurningOn()=true
,08-26 21:11:10.471  4283  4283 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:11:10.471  4283  4283 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 21:11:10.473  4283  4314 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 21:11:10.473  4283  4283 V BluetoothAdapterState: isTurningOff()=false
08-26 21:11:10.474  4283  4283 V BluetoothAdapterState: isTurningOn()=true
,08-26 21:11:10.474  4283  4283 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:11:10.474  4283  4283 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:11:10.474  4283  4283 V BluetoothAdapterState: isTurningOff()=false
08-26 21:11:10.474  4283  4283 V BluetoothAdapterState: isTurningOn()=true
08-26 21:11:10.474  4283  4283 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:11:10.474  4283  4283 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:11:10.474  4283  4283 V BluetoothAdapterState: isTurningOff()=false
,08-26 21:11:10.474  4283  4283 V BluetoothAdapterState: isTurningOn()=true
08-26 21:11:10.474  4283  4283 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:11:10.474  4283  4283 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:11:10.475  4283  4283 V BluetoothAdapterState: isTurningOff()=false
,08-26 21:11:10.475  4283  4283 V BluetoothAdapterState: isTurningOn()=true
08-26 21:11:10.475  4283  4283 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:11:10.475  4283  4283 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:11:10.475  4283  4283 V BluetoothAdapterState: isTurningOff()=false
08-26 21:11:10.475  4283  4283 V BluetoothAdapterState: isTurningOn()=true
08-26 21:11:10.475  4283  4283 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:11:10.475  4283  4283 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:11:10.475  4283  4295 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-26 21:11:10.475  4283  4295 D BluetoothAdapterProperties: ScanMode =  20
,08-26 21:11:10.475  4283  4295 D BluetoothAdapterProperties: State =  11
,08-26 21:11:10.479  4283  4299 D BluetoothAdapterProperties: Scan Mode:21
08-26 21:11:10.480  4283  4295 D BluetoothAdapterProperties: Setting state to 12
,08-26 21:11:10.480  4283  4295 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 21:11:10.480  4283  4299 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 21:11:10.480  4283  4295 I BluetoothAdapterState: Entering OnState
08-26 21:11:10.480  3994  4007 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 21:11:10.481   871   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 21:11:10.481  3994  4255 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 21:11:10.483  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:11:10.483  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:10.483  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:10.483  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:11:10.483  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:10.483  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:11:10.483  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:11:10.483  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:11:10.484  3994  4006 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 21:11:10.485  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:11:10.486   871   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 21:11:10.486   871   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:11:10.486  1364  1388 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:11:10.487  3994  3994 D BluetoothMap: Proxy object connected
08-26 21:11:10.487  3994  3994 D MapProfile: Bluetooth service connected
08-26 21:11:10.487  3994  3994 D BluetoothMap: getConnectedDevices()
08-26 21:11:10.487  1364  1381 D BluetoothPan: onBluetoothStateChange on: true
,08-26 21:11:10.488   871   871 D BluetoothA2dp: Proxy object connected
08-26 21:11:10.488  4283  4283 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 21:11:10.489  1364  1690 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 21:11:10.489  4283  4283 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 21:11:10.490  1364  1364 D BluetoothA2dp: Proxy object connected
,08-26 21:11:10.491  4283  4283 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:11:10.492  3994  4255 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 21:11:10.493  3994  3994 D BluetoothInputDevice: Proxy object connected
08-26 21:11:10.493  3994  3994 D HidProfile: Bluetooth service connected
08-26 21:11:10.494  3994  4006 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 21:11:10.494  4283  4283 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:11:10.495  4283  4283 D ObexServerSockets: Succeed to create listening sockets 
08-26 21:11:10.495  4283  4283 D ObexServerSockets0: startAccept()
08-26 21:11:10.495  4283  4283 D ObexServerSockets0: prepareForNewConnect()
08-26 21:11:10.495  3994  3994 D BluetoothA2dp: Proxy object connected
08-26 21:11:10.496  1364  1381 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 21:11:10.497   871   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 21:11:10.497  4283  4283 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-26 21:11:10.497  4283  4283 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 21:11:10.497  1364  1690 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 21:11:10.498  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 21:11:10.498  1364  1364 D PanProfile: Bluetooth service connected
08-26 21:11:10.498  4283  4324 D ObexServerSockets0: Accepting socket connection...
08-26 21:11:10.499  1364  1364 D BluetoothInputDevice: Proxy object connected
,08-26 21:11:10.499  1364  1364 D HidProfile: Bluetooth service connected
08-26 21:11:10.499  4283  4323 D ObexServerSockets0: Accepting socket connection...
08-26 21:11:10.499  3994  4255 D BluetoothPan: onBluetoothStateChange on: true
08-26 21:11:10.501  1364  1381 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 21:11:10.501  3994  3994 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 21:11:10.501  3994  3994 D PanProfile: Bluetooth service connected
08-26 21:11:10.502  1364  1364 D BluetoothMap: Proxy object connected
08-26 21:11:10.502  1364  1364 D MapProfile: Bluetooth service connected
,08-26 21:11:10.502  1364  1364 D BluetoothMap: getConnectedDevices()
08-26 21:11:10.502  1933  2060 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 21:11:10.503   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 21:11:10.505  4283  4283 D BluetoothMapService: onReceive
,08-26 21:11:10.505  4283  4283 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:11:10.505  4283  4283 D BluetoothMapService: STATE_ON
08-26 21:11:10.505  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:10.511  3994  3994 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 21:11:10.515  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:11:10.517  3994  3994 D DockEventReceiver: finishStartingService: stopping service
,08-26 21:11:10.523  3994  3994 D BluetoothPbap: Proxy object connected
,08-26 21:11:10.523  3994  3994 D PbapServerProfile: Bluetooth service connected
,08-26 21:11:10.529  1364  1364 D BluetoothPbap: Proxy object connected
,08-26 21:11:10.529  1364  1364 D PbapServerProfile: Bluetooth service connected
,08-26 21:11:10.530  4283  4283 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 21:11:10.530  4283  4283 D ObexServerSockets0: prepareForNewConnect()
,08-26 21:11:10.531  4283  4329 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:11:10.552  4283  4333 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:11:10.556  4283  4333 I BtOppRfcommListener: Accept thread started.
,08-26 21:11:10.584   871   871 D BluetoothHeadset: Proxy object connected
,08-26 21:11:10.584   871   871 D BluetoothHeadset: Proxy object connected
,08-26 21:11:10.584   871   871 D BluetoothHeadset: Proxy object connected
08-26 21:11:10.584  1933  1951 D BluetoothHeadset: Proxy object connected
08-26 21:11:10.586  3994  4255 D BluetoothHeadset: Proxy object connected
08-26 21:11:10.586  3994  3994 D HeadsetProfile: Bluetooth service connected
,08-26 21:11:10.586  1364  1690 D BluetoothHeadset: Proxy object connected
08-26 21:11:10.587  1364  1364 D HeadsetProfile: Bluetooth service connected
08-26 21:11:10.587   871   889 D BluetoothHeadset: Proxy object connected
08-26 21:11:10.588  1364  1388 D BluetoothHeadset: Proxy object connected
,08-26 21:11:10.590  1364  1364 D HeadsetProfile: Bluetooth service connected
,08-26 21:11:10.597   871   889 D BluetoothHeadset: Proxy object connected
,08-26 21:11:10.602  1933  1949 D BluetoothHeadset: Proxy object connected
,08-26 21:11:10.914  3924  3974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:11:10.914  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:10.914  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:10.914  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:11:10.914  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:10.914  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:11:10.914  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:11:10.914  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:11:10.918  3924  3974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:11:10.919  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:11:10.919  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ea65f8 added. We now have 8 listener(s)
,08-26 21:11:10.919  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:11:10.921   871  1711 D WifiService: setWifiEnabled: false pid=3924, uid=10000
08-26 21:11:10.922   871  1711 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 21:11:10.929  3924  3974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:10.930   871   882 D WifiService: setWifiEnabled: true pid=3924, uid=10000
,08-26 21:11:10.931   871   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 21:11:10.941   871  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-26 21:11:10.962  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:11:10.962  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:10.962  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:10.962  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:11:10.962  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:10.962  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:11:10.962  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:11:10.962  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:11:10.968  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:11:10.971   871  1313 D WifiConfigStore: loaded 0 passpoint configs
,08-26 21:11:10.972   871  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 21:11:10.972   871  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 21:11:10.973   871  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 21:11:10.973   871  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 21:11:10.974   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-26 21:11:10.974   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 21:11:10.985   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 21:11:10.986   871  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.07 delta 1000 -> 1000
,08-26 21:11:10.986   871  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-26 21:11:10.986   372   869 D CommandListener: Setting iface cfg,
08-26 21:11:10.986   871  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
,08-26 21:11:10.987   871  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 21:11:10.997   871  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 21:11:10.997   871  1313 E native  : do suspend true
,08-26 21:11:10.997   871  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 21:11:11.021   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-26 21:11:11.021   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 21:11:11.029   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 21:11:11.063   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 21:11:11.065  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 21:11:11.488  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 21:11:11.531  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 21:11:11.531  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 21:11:11.535   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 21:11:11.549   871  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 21:11:11.550   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 21:11:11.550   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 21:11:11.565   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 21:11:11.577   372   869 D CommandListener: Setting iface cfg
,08-26 21:11:11.578   871  1313 D WifiStateMachine: Start Dhcp Watchdog 3
,08-26 21:11:11.590   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 21:11:11.616   871  4341 D DhcpClient: Receive thread started
,08-26 21:11:11.707   871  1313 E native  : do suspend false
,08-26 21:11:11.729   871  2123 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 21:11:11.746   871  4341 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-26 21:11:11.747   871  2123 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-26 21:11:11.751   871  2123 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 21:11:11.765   871  4341 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 21:11:11.766   871  2123 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 21:11:11.771   372   869 D CommandListener: Setting iface cfg
,08-26 21:11:11.783   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 21:11:11.784   871  1313 E native  : do suspend true
08-26 21:11:11.785   871  2123 D DhcpClient: Scheduling renewal in 86399s
,08-26 21:11:11.801   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 21:11:11.802   871  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 21:11:11.803   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 21:11:11.804   871  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 21:11:11.805   871  1315 D ConnectivityService: Adding iface wlan0 to network 102
,08-26 21:11:11.882   871  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 21:11:11.883   871  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-26 21:11:11.886   871  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-26 21:11:11.889   871  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-26 21:11:11.892   871  1315 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-26 21:11:11.905   871  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 21:11:11.911   871  1315 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-26 21:11:11.912   871  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-26 21:11:11.912   871  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-26 21:11:11.913   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 21:11:11.913   871  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-26 21:11:11.913   871  1315 D ConnectivityService:    accepting network in place of null
,08-26 21:11:11.914   871  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 21:11:11.928   871  4340 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154873, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 21:11:11.947  3924  3974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:11:11.947  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:11.947  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:11.947  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:11:11.947  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:11.947  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:11:11.947  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:11:11.947  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:11:11.952  3924  3974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:11:11.959  3924  3974 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 21:11:11.960  3924  3974 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 21:11:11.964  3924  3974 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c777523 Bundle[{}]
,08-26 21:11:11.965  3924  3974 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 21:11:11.966  3924  3974 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 21:11:11.967  3924  3974 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 21:11:11.968  3924  3974 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 21:11:11.969  3924  3974 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-26 21:11:11.970   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 21:11:11.972  3924  3974 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 21:11:11.981  3924  3974 I System.out: Running OutgoingSocketThread
,08-26 21:11:11.983  3924  4348 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 447)
08-26 21:11:11.984  3924  4348 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48634
08-26 21:11:11.984  3924  4348 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 21:11:11.997   871  4338 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:815::200e
,08-26 21:11:12.002   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 21:11:12.006   871  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-26 21:11:12.006   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:11:12.009   871  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-26 21:11:12.012   871   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 21:11:12.021  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:11:12.021  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:12.021  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:12.021  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:11:12.021  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:12.021  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:11:12.021  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:11:12.021  3924  3924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:11:12.025  3924  3924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:11:12.032  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 21:11:12.045  1717  1717 D SystemUpdateService: onCreate
,08-26 21:11:12.049  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 21:11:12.068  1717  4351 I SystemUpdateService: active receiver: enabled
,08-26 21:11:12.072  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 21:11:12.074   871  4338 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 19:11:12 GMT], X-Android-Received-Millis=[1472238672073], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472238672043]}
,08-26 21:11:12.075   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-26 21:11:12.075   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-26 21:11:12.075   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 21:11:12.076   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 21:11:12.086  1717  2516 I iu.UploadsManager: num queued entries: 0
,08-26 21:11:12.086  1717  2516 I iu.UploadsManager: num updated entries: 0
,08-26 21:11:12.088  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 21:11:12.089  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-26 21:11:12.091  4051  4051 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:11:12.100  1717  4354 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-26 21:11:12.100  1717  4354 W BaseAppContext: Using Auth Proxy for data requests.
08-26 21:11:12.100  4051  4051 D SprintDMHelper: simOperator: 
,08-26 21:11:12.100  4051  4051 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 21:11:12.120  1717  4354 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 21:11:12.136  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 21:11:12.136  1717  4351 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-26 21:11:12.139  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 21:11:12.147  1717  4351 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 21:11:12.147  1717  4351 I SystemUpdateService: now status is 0 (complete)
08-26 21:11:12.147  1717  4351 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 21:11:12.147  1717  4351 I SystemUpdateService: file has been verified
08-26 21:11:12.148  1717  4351 I SystemUpdateService: OTA package size = 12249756
,08-26 21:11:12.154  1717  2516 I iu.SyncManager: NEXT; no task
,08-26 21:11:12.166  1717  4351 I SystemUpdateService: showing system update notification
,08-26 21:11:12.178  1508  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-26 21:11:12.178  1508  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 21:11:12.178  1508  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 21:11:12.179  1508  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 21:11:12.181  1717  1717 D SystemUpdateService: onDestroy
,08-26 21:11:12.197  1717  4354 E MDM     : [182] SitrepService.a: Error sending sitrep.
,08-26 21:11:12.239  2406  4357 I Babel   : connection state changed from DISCONNECTED to CONNECTED,
,08-26 21:11:12.985  3924  3974 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 448)
,08-26 21:11:12.985  3924  3974 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 448)
,08-26 21:11:12.995  3924  3974 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 453)
,08-26 21:11:12.998  3924  3974 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 21:11:12.998  3924  3974 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 454)
,08-26 21:11:13.007  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 21:11:13.007   871  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-26 21:11:13.007  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eaf2ad1 added. We now have 2 listener(s)
,08-26 21:11:13.014  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:11:13.015  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 21:11:13.015  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:11:13.016  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:11:13.017  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e471936 added. We now have 9 listener(s)
,08-26 21:11:13.017  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:11:13.017  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 21:11:13.020  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:11:13.027  3924  3974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:11:13.027  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:13.027  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:13.027  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:11:13.027  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:13.027  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:11:13.027  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:11:13.027  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:11:13.030  3924  3974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:11:13.030  3924  3974 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 21:11:13.031  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:11:13.031  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45be9a4 added. We now have 3 listener(s)
08-26 21:11:13.033  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 21:11:13.033  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:11:13.033  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:13.033  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:11:13.033  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 21:11:13.034  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52aa30d added. We now have 10 listener(s)
08-26 21:11:13.034  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:11:13.034  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:11:13.034  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:11:13.034  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:11:13.034  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 21:11:13.034  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:13.034  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:11:13.034  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 21:11:13.035  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eaf2ad1 removed from the list
08-26 21:11:13.035  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:13.035  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e471936 removed from the list
08-26 21:11:13.038  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:13.038  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:11:13.038  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:11:13.039  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:11:13.039  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:11:13.040  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:11:13.040  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:11:13.040  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:13.040  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e471936 not in the list
,08-26 21:11:13.041  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:13.041  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:11:13.042  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:11:13.042  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:11:13.042  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:11:13.042  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52aa30d removed from the list
08-26 21:11:13.042  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:11:13.042  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:13.043  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:11:13.043  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:11:13.043  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45be9a4 removed from the list
,08-26 21:11:13.044  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:11:13.044  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e392c2 added. We now have 2 listener(s)
,08-26 21:11:13.047  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:11:13.047  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 21:11:13.047  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:11:13.047  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:11:13.047  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8c8d3 added. We now have 9 listener(s)
08-26 21:11:13.047  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:11:13.048  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 21:11:13.053  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:11:13.060  3924  3974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:11:13.060  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:13.060  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:13.060  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:11:13.060  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:13.060  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:11:13.060  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:11:13.060  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:11:13.062  3924  3974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:11:13.062  3924  3974 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 21:11:13.063  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 21:11:13.063  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d6b6309 added. We now have 3 listener(s)
,08-26 21:11:13.065  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:11:13.065  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:11:13.065  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 21:11:13.065  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 21:11:13.065  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc190e added. We now have 10 listener(s)
08-26 21:11:13.065  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-26 21:11:13.066  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 21:11:13.066  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:11:13.066  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 21:11:13.066  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:11:13.066  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 21:11:13.067  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:13.070  3924  3974 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 21:11:13.070  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 21:11:13.073  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:13.076  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 21:11:13.077  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 21:11:13.077  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 21:11:13.083  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 21:11:13.083  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 21:11:13.084  3924  3974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 21:11:13.085  3924  3974 D BluetoothAdapter: STATE_ON
,08-26 21:11:13.090  4283  4322 D BtGatt.GattService: registerClient() - UUID=8af0d6fa-44e3-403d-8bb0-5903166731c6
,08-26 21:11:13.091  4283  4299 D BtGatt.GattService: onClientRegistered() - UUID=8af0d6fa-44e3-403d-8bb0-5903166731c6, clientIf=5
,08-26 21:11:13.092  3924  3936 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 21:11:13.093  4283  4293 D BtGatt.GattService: start scan with filters
,08-26 21:11:13.098  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 21:11:13.098  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 21:11:13.098  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 21:11:13.099  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 21:11:13.099  4283  4302 D BtGatt.ScanManager: handling starting scan
,08-26 21:11:13.102  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:11:13.102  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 21:11:13.102  3924  3924 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 21:11:13.103  4283  4302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e2de787
08-26 21:11:13.104  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 21:11:13.107  3924  3974 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 21:11:13.107  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 21:11:13.107  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 21:11:13.108  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:11:13.108  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 21:11:13.108  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 21:11:13.108  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 21:11:13.108  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 21:11:13.108  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 21:11:13.108  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 21:11:13.108  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 21:11:13.110  3924  3974 D BluetoothAdapter: STATE_ON
,08-26 21:11:13.110  4283  4322 D BtGatt.GattService: stopScan() - queue size =1
,08-26 21:11:13.111  4283  4293 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 21:11:13.111  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 21:11:13.111  4283  4299 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 21:11:13.112  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 21:11:13.112  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 21:11:13.112  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:11:13.112  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 21:11:13.112  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 21:11:13.113  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:11:13.113  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 21:11:13.113  4283  4302 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 21:11:13.114  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 21:11:13.114  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 21:11:13.114  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:11:13.116  3924  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 21:11:13.116  3924  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:11:13.117  3924  3924 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:11:13.120  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:11:13.121  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:11:13.121  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:11:13.121  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:11:13.122  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:13.122  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:11:13.122  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:11:13.122  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e392c2 removed from the list
08-26 21:11:13.123  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:13.123  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8c8d3 removed from the list
,08-26 21:11:13.123  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:11:13.123  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:11:13.125  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:13.125  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:11:13.125  4283  4299 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 21:11:13.126  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:11:13.127  4283  4302 D BtGatt.ScanManager: Starting BLE batch scan
08-26 21:11:13.127  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:11:13.128  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:11:13.128  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:13.128  4283  4302 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 21:11:13.128  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8c8d3 not in the list
08-26 21:11:13.128  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:13.128  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:11:13.130  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:11:13.130  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:11:13.130  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:13.130  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc190e removed from the list
08-26 21:11:13.130  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:11:13.130  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:13.130  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:11:13.130  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:11:13.130  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d6b6309 removed from the list
,08-26 21:11:13.131  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:11:13.131  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc4b81a added. We now have 2 listener(s)
,08-26 21:11:13.133  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:11:13.133  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:11:13.133  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:11:13.133  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 21:11:13.133  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f67f4b added. We now have 9 listener(s)
08-26 21:11:13.134  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:11:13.134  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 21:11:13.136  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:11:13.142  3924  3974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:11:13.142  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:13.142  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:13.142  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:11:13.142  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:13.142  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:11:13.142  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:11:13.142  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:11:13.144  4283  4299 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 21:11:13.144  3924  3974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:11:13.145  3924  3974 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:11:13.145  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:11:13.145  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:11:13.145  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ff6a41 added. We now have 3 listener(s)
,08-26 21:11:13.147  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:11:13.147  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:11:13.147  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 21:11:13.148  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 21:11:13.148  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6663be6 added. We now have 10 listener(s)
,08-26 21:11:13.149  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:11:13.149  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 21:11:13.150  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 21:11:13.150  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:11:13.150  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 21:11:13.150  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:11:13.150  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 21:11:13.152  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:13.154  3924  3974 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted,
08-26 21:11:13.155  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 21:11:13.155  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:13.156  4283  4299 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 21:11:13.156  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:11:13.160  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 21:11:13.160  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 21:11:13.161  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 21:11:13.165  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 21:11:13.165  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 21:11:13.165  3924  3974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
08-26 21:11:13.166  3924  3974 D BluetoothAdapter: STATE_ON
,08-26 21:11:13.169  4283  4294 D BtGatt.GattService: registerClient() - UUID=d73353fa-7639-461a-b170-9d01cea2e6ed
08-26 21:11:13.169  4283  4299 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 21:11:13.169  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:11:13.170  4283  4299 D BtGatt.GattService: onClientRegistered() - UUID=d73353fa-7639-461a-b170-9d01cea2e6ed, clientIf=5
,08-26 21:11:13.171  3924  3935 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 21:11:13.171  4283  4313 D BtGatt.GattService: start scan with filters
,08-26 21:11:13.172  4283  4302 D BtGatt.ScanManager: stopping BLe Batch
,08-26 21:11:13.175  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 21:11:13.175  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 21:11:13.175  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 21:11:13.176  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 21:11:13.178  4283  4299 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 21:11:13.178  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:11:13.179  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:11:13.179  3924  3924 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
,08-26 21:11:13.179  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 21:11:13.179  4283  4302 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 21:11:13.181  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 21:11:13.184  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 21:11:13.184  3924  3974 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-26 21:11:13.185  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,08-26 21:11:13.185  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:11:13.185  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:11:13.185  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 21:11:13.185  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:11:13.185  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 21:11:13.185  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 21:11:13.186  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc4b81a removed from the list
08-26 21:11:13.186  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 21:11:13.186  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f67f4b removed from the list
08-26 21:11:13.186  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 21:11:13.186  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:11:13.186  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:11:13.186  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-26 21:11:13.187  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:11:13.187  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:11:13.188  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 21:11:13.188  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:11:13.188  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:13.188  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f67f4b not in the list
08-26 21:11:13.188  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 21:11:13.188  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 21:11:13.188  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 21:11:13.189  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 21:11:13.189  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 21:11:13.189  3924  3974 D BluetoothAdapter: STATE_ON
,08-26 21:11:13.190  4283  4294 D BtGatt.GattService: stopScan() - queue size =0
08-26 21:11:13.190  4283  4313 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 21:11:13.190  4283  4299 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 21:11:13.191  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:11:13.191  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 21:11:13.191  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 21:11:13.191  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 21:11:13.191  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 21:11:13.191  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 21:11:13.193  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:11:13.193  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 21:11:13.193  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 21:11:13.193  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 21:11:13.193  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:11:13.194  4283  4302 D BtGatt.ScanManager: handling starting scan
08-26 21:11:13.195  3924  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:11:13.195  3924  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:11:13.195  3924  3924 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:11:13.195  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:11:13.195  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:11:13.195  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:13.195  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6663be6 removed from the list
08-26 21:11:13.195  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:11:13.195  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:13.196  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:11:13.196  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:11:13.196  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ff6a41 removed from the list
08-26 21:11:13.196  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:11:13.197  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64a3072 added. We now have 2 listener(s)
08-26 21:11:13.198  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:11:13.199  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:11:13.199  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:11:13.199  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:11:13.199  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2858cc3 added. We now have 9 listener(s)
08-26 21:11:13.199  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:11:13.200  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 21:11:13.203  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:11:13.207  3924  3974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:11:13.207  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:13.207  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:11:13.207  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:11:13.207  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:13.207  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:11:13.207  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:11:13.207  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:11:13.207  4283  4299 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 21:11:13.208  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:11:13.208  4283  4302 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 21:11:13.210  3924  3974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:11:13.210  3924  3974 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:11:13.210  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:11:13.210  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb62079 added. We now have 3 listener(s)
,08-26 21:11:13.212  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:13.213  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 21:11:13.214  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:11:13.214  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 21:11:13.214  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:11:13.215  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e06e1be added. We now have 10 listener(s)
08-26 21:11:13.215  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:11:13.215  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:11:13.215  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:11:13.215  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 21:11:13.215  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:11:13.215  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:11:13.215  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 21:11:13.218  4283  4299 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 21:11:13.218  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:11:13.218  4283  4302 D BtGatt.ScanManager: Starting BLE batch scan
08-26 21:11:13.218  4283  4302 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 21:11:13.218  3924  3974 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 21:11:13.218  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 21:11:13.222  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 21:11:13.223  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 21:11:13.223  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 21:11:13.227  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 21:11:13.228  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 21:11:13.228  3924  3974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 21:11:13.229  3924  3974 D BluetoothAdapter: STATE_ON
,08-26 21:11:13.231  4283  4299 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 21:11:13.231  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:11:13.233  4283  4294 D BtGatt.GattService: registerClient() - UUID=7b604b47-28dc-4032-bdf9-f761c03e9a4a
,08-26 21:11:13.233  4283  4299 D BtGatt.GattService: onClientRegistered() - UUID=7b604b47-28dc-4032-bdf9-f761c03e9a4a, clientIf=5
08-26 21:11:13.234  3924  3935 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 21:11:13.234  4283  4313 D BtGatt.GattService: start scan with filters
,08-26 21:11:13.237  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 21:11:13.237  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 21:11:13.237  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 21:11:13.237  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 21:11:13.238  4283  4299 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 21:11:13.238  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:11:13.240  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:11:13.240  3924  3924 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:11:13.241  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 21:11:13.243  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 21:11:13.247  4283  4299 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 21:11:13.247  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:11:13.247  4283  4302 D BtGatt.ScanManager: stopping BLe Batch
,08-26 21:11:13.248  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:11:13.249  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:11:13.249  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:11:13.249  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:11:13.249  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:11:13.249  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 21:11:13.249  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-26 21:11:13.250  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64a3072 removed from the list
08-26 21:11:13.250  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:11:13.250  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2858cc3 removed from the list
08-26 21:11:13.250  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop,
08-26 21:11:13.250  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:11:13.250  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:11:13.250  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 21:11:13.250  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:11:13.251  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:11:13.252  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:11:13.252  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:11:13.252  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:11:13.252  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2858cc3 not in the list
08-26 21:11:13.252  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
08-26 21:11:13.252  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 21:11:13.252  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 21:11:13.252  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 21:11:13.252  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 21:11:13.253  3924  3974 D BluetoothAdapter: STATE_ON
,08-26 21:11:13.254  4283  4322 D BtGatt.GattService: stopScan() - queue size =0
08-26 21:11:13.254  4283  4293 D BtGatt.GattService: unregisterClient() - clientIf=5,
08-26 21:11:13.255  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:11:13.255  4283  4299 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 21:11:13.255  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:11:13.255  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 21:11:13.255  4283  4302 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 21:11:13.256  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 21:11:13.256  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 21:11:13.256  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 21:11:13.257  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:11:13.257  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 21:11:13.257  3924  3974 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 21:11:13.257  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 21:11:13.258  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:11:13.259  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:11:13.259  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:11:13.259  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:13.259  3924  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-26 21:11:13.259  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e06e1be removed from the list
,08-26 21:11:13.259  3924  3924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:11:13.259  3924  3924 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:11:13.259  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:11:13.259  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:13.259  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:11:13.259  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:11:13.260  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb62079 removed from the list
08-26 21:11:13.260  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 21:11:13.260  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4b5bca added. We now have 2 listener(s)
08-26 21:11:13.262  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 21:11:13.262  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 21:11:13.263  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:11:13.263  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-26 21:11:13.263  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@749d13b added. We now have 9 listener(s)
,08-26 21:11:13.263  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:11:13.263  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 21:11:13.264  4283  4299 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 21:11:13.264  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:11:13.266  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:11:13.267  4283  4302 D BtGatt.ScanManager: handling starting scan
,08-26 21:11:13.271  3924  3974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:11:13.271  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:11:13.271  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-26 21:11:13.271  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:11:13.271  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:11:13.271  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:11:13.271  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:11:13.271  3924  3974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:11:13.273  3924  3974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:11:13.273  3924  3974 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:11:13.273  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:11:13.273  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65665b1 added. We now have 3 listener(s)
,08-26 21:11:13.275  4283  4299 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 21:11:13.275  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:11:13.276  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:13.277  4283  4302 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 21:11:13.277  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:11:13.277  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 21:11:13.277  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:11:13.278  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,08-26 21:11:13.278  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dab6a96 added. We now have 10 listener(s)
,08-26 21:11:13.278  3924  3974 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-26 21:11:13.278  3924  3974 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:11:13.278  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:11:13.279  3924  3974 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:11:13.279  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:11:13.279  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:11:13.279  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:11:13.279  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 21:11:13.279  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4b5bca removed from the list
,08-26 21:11:13.279  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:11:13.280  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@749d13b removed from the list
,08-26 21:11:13.281  3924  3924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:11:13.281  3924  3974 D io.jxcore.node.ConnectivityMonitor: stop,
08-26 21:11:13.281  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 21:11:13.282  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:11:13.282  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:11:13.283  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:11:13.283  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:11:13.283  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:11:13.283  3924  3974 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@749d13b not in the list
,08-26 21:11:13.284  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:11:13.284  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:11:13.284  4283  4299 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 21:11:13.284  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:11:13.285  4283  4302 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 21:11:13.285  4283  4302 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 21:11:13.285  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:11:13.286  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:11:13.286  3924  3974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 21:11:13.286  3924  3974 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dab6a96 removed from the list
,08-26 21:11:13.286  3924  3974 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 21:11:13.286  3924  3974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:11:13.286  3924  3974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:11:13.286  3924  3974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:11:13.286  3924  3974 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65665b1 removed from the list
,08-26 21:11:13.287  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-26 21:11:13.287  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-26 21:11:13.287  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 21:11:13.287  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:11:13.287  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 21:11:13.288  3924  3974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:11:13.299  3924  4364 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: My test thread name)
08-26 21:11:13.300  3924  4364 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 461, thread name: My test thread name)
08-26 21:11:13.300  3924  4364 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 21:11:13.303  4283  4299 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 21:11:13.303  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:11:13.304  3924  4365 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 463, name: My test thread name)
08-26 21:11:13.304  3924  4365 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 463, thread name: My test thread name)
08-26 21:11:13.304  3924  4365 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 463, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 21:11:13.307  3924  3974 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 21:11:13.307  3924  3974 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 21:11:13.307  3924  3974 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-26 21:11:13.307  3924  3974 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 21:11:13.308  3924  3974 D com.test.thalitest.ThaliTestRunner: Total duration: 22847 ms
,08-26 21:11:13.310  3924  3974 I jxcore-log: *Native tests were executed*
08-26 21:11:13.310  3924  3974 I jxcore-log: 
,08-26 21:11:13.310  3924  3974 I jxcore-log: Total number of executed tests:  80
08-26 21:11:13.310  3924  3974 I jxcore-log: 
,08-26 21:11:13.310  3924  3974 I jxcore-log: Number of passed tests:  80
08-26 21:11:13.310  3924  3974 I jxcore-log: 
08-26 21:11:13.310  3924  3974 I jxcore-log: Number of failed tests:  0
08-26 21:11:13.310  3924  3974 I jxcore-log: 
,08-26 21:11:13.311  3924  3974 I jxcore-log: Number of ignored tests:  0
08-26 21:11:13.311  3924  3974 I jxcore-log: 
,08-26 21:11:13.312  3924  3974 I jxcore-log: Total duration:  22847
08-26 21:11:13.312  3924  3974 I jxcore-log: 
08-26 21:11:13.312  3924  3974 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 21:11:13.312  3924  3974 I jxcore-log: 
,08-26 21:11:13.312  4283  4299 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 21:11:13.312  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:11:13.317  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:13.317  3924  3974 I jxcore-log: 
,08-26 21:11:13.320  4283  4299 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 21:11:13.320  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-26 21:11:13.320  3924  3924 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-26 21:11:13.320  4283  4302 D BtGatt.ScanManager: stopping BLe Batch
08-26 21:11:13.322  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:13.322  3924  3974 I jxcore-log: 
08-26 21:11:13.324  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:13.324  3924  3974 I jxcore-log: 
,08-26 21:11:13.325  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:13.325  3924  3974 I jxcore-log: 
08-26 21:11:13.326  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:13.326  3924  3974 I jxcore-log: 
08-26 21:11:13.327  4283  4299 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 21:11:13.327  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:11:13.327  4283  4302 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 21:11:13.328  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:13.328  3924  3974 I jxcore-log: 
08-26 21:11:13.330  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:13.330  3924  3974 I jxcore-log: 
08-26 21:11:13.332  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 21:11:13.332  3924  3974 I jxcore-log: 
,08-26 21:11:13.333  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 21:11:13.333  3924  3974 I jxcore-log: 
,08-26 21:11:13.334  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:11:13.334  3924  3974 I jxcore-log: 
08-26 21:11:13.334  4283  4299 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 21:11:13.334  4283  4299 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:11:13.335  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:11:13.335  3924  3974 I jxcore-log: 
08-26 21:11:13.336  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 21:11:13.336  3924  3974 I jxcore-log: 
,08-26 21:11:13.336  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 21:11:13.336  3924  3974 I jxcore-log: 
,08-26 21:11:13.337  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 21:11:13.337  3924  3974 I jxcore-log: 
,08-26 21:11:13.338  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:13.338  3924  3974 I jxcore-log: 
,08-26 21:11:13.339  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:13.339  3924  3974 I jxcore-log: 
,08-26 21:11:13.339  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:11:13.339  3924  3974 I jxcore-log: 
,08-26 21:11:13.340  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:11:13.340  3924  3974 I jxcore-log: 
,08-26 21:11:13.341  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 21:11:13.341  3924  3974 I jxcore-log: 
,08-26 21:11:13.342  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 21:11:13.342  3924  3974 I jxcore-log: 
,08-26 21:11:13.342  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:11:13.342  3924  3974 I jxcore-log: 
,08-26 21:11:13.343  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:11:13.343  3924  3974 I jxcore-log: 
,08-26 21:11:13.344  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 21:11:13.344  3924  3974 I jxcore-log: 
,08-26 21:11:13.345  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 21:11:13.345  3924  3974 I jxcore-log: 
,08-26 21:11:13.346  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 21:11:13.346  3924  3974 I jxcore-log: 
,08-26 21:11:13.346  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:13.346  3924  3974 I jxcore-log: 
,08-26 21:11:13.347  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:13.347  3924  3974 I jxcore-log: 
,08-26 21:11:13.348  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:13.348  3924  3974 I jxcore-log: 
,08-26 21:11:13.349  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:13.349  3924  3974 I jxcore-log: 
,08-26 21:11:13.349  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:13.349  3924  3974 I jxcore-log: 
,08-26 21:11:13.350  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:13.350  3924  3974 I jxcore-log: 
,08-26 21:11:13.350  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:11:13.350  3924  3974 I jxcore-log: 
,08-26 21:11:13.618  3924  3924 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 21:11:13.621  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 21:11:13.621  3924  3974 I jxcore-log: 
,08-26 21:11:13.695  3924  3924 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 21:11:13.698  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 21:11:13.698  3924  3974 I jxcore-log: 
,08-26 21:11:13.759  3924  3924 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 21:11:13.763  3924  3974 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 21:11:13.763  3924  3974 I jxcore-log: 
,08-26 21:11:13.890  4367  4367 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-26 21:11:13.895  4367  4367 D AndroidRuntime: CheckJNI is OFF
,08-26 21:11:13.938  4367  4367 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-26 21:11:13.984  4367  4367 I Radio-JNI: register_android_hardware_Radio DONE
,08-26 21:11:14.008  4367  4367 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 21:11:14.019   871   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-26 21:11:14.020   871   885 I ActivityManager: Killing 3924:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-26 21:11:14.103   871  1304 W InputDispatcher: channel 'ba99d7c com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,08-26 21:11:14.104   871  1304 E InputDispatcher: channel 'ba99d7c com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,08-26 21:11:14.111   871  1711 D GraphicsStats: Buffer count: 2
,08-26 21:11:14.112   871  1314 D WifiService: Client connection lost with reason: 4
08-26 21:11:14.111   871  1378 I WindowState: WIN DEATH: Window{ba99d7c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 21:11:14.113   871  1378 W InputDispatcher: Attempted to unregister already unregistered input channel 'ba99d7c com.test.thalitest/com.test.thalitest.MainActivity (server)'
,08-26 21:11:14.140   871   895 W PackageSettings: Skipping PackageSetting{58ea358 com.example.hello/10273} due to missing metadata
,08-26 21:11:14.167   871   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-26 21:11:14.167   871   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-26 21:11:14.168   871   885 E ActivityManager: Failure starting process com.test.thalitest
08-26 21:11:14.168   871   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-26 21:11:14.168   871   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-26 21:11:14.168   871   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-26 21:11:14.168   871   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-26 21:11:14.168   871   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-26 21:11:14.168   871   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-26 21:11:14.168   871   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-26 21:11:14.168   871   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-26 21:11:14.168   871   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-26 21:11:14.168   871   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-26 21:11:14.168   871   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-26 21:11:14.168   871   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-26 21:11:14.168   871   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-26 21:11:14.168   871   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-26 21:11:14.168   871   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-26 21:11:14.168   871   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:11:14.168   871   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:11:14.168   871   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 21:11:14.168   871   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-26 21:11:14.168   871   885 I ActivityManager:   Force finishing activity ActivityRecord{bd2216d u0 com.test.thalitest/.MainActivity t2}
08-26 21:11:14.170   871   895 I art     : Starting a blocking GC Explicit
,08-26 21:11:14.176   871  3355 W ActivityManager: Spurious death for ProcessRecord{2459e92 0:com.test.thalitest/u0a0}, curProc for 3924: null
,08-26 21:11:14.217   871   895 I art     : Explicit concurrent mark sweep GC freed 13739(958KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 728us total 46.662ms
,08-26 21:11:14.274   871   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-26 21:11:14.280  4367  4367 I art     : System.exit called, status: 0
,08-26 21:11:14.280  4367  4367 I AndroidRuntime: VM exiting with result code 0.
,08-26 21:11:14.286   871   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-26 21:11:14.318   871   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-26 21:11:14.322  4283  4283 D BluetoothMapAppObserver: onReceive
,08-26 21:11:14.322  4283  4283 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-26 21:11:14.325  2098  2302 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 21:11:14.326  3761  3761 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-26 21:11:14.328  1870  1870 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-26 21:11:14.330   871  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 21:11:14.334  1870  4378 I Keyboard.Facilitator.DecoderInitializer: run()
,08-26 21:11:14.337  1870  4378 I Decoder : createOrResetDecoder
,08-26 21:11:14.370   871  2080 I ActivityManager: Start proc 4381:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-26 21:11:14.383  1933  1933 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-26 21:11:14.393  1508  1508 I ConfigService: onCreate
,08-26 21:11:14.425  1870  4378 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-26 21:11:14.447   871  1965 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3924 uid 10000
,08-26 21:11:14.448  1870  1870 I Keyboard.Facilitator: onFinishInput()
,08-26 21:11:14.455   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 21:11:14.458  4381  4381 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-26 21:11:14.466  1870  4378 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-26 21:11:14.467  1870  4378 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-26 21:11:14.467  1870  4378 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-26 21:11:14.471  1870  4378 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-26 21:11:14.471  1870  4378 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-26 21:11:14.472  1870  4378 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-26 21:11:14.472  1870  4378 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-26 21:11:14.475  1870  4378 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-26 21:11:14.475  1870  4378 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-26 21:11:14.475  1870  4378 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-26 21:11:14.476  1870  4378 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-26 21:11:14.476  1870  4378 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-26 21:11:14.476  1870  4378 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-26 21:11:14.477   871   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-26 21:11:14.478   871   884 E PackageManager: Failed to write settings, restoring backup
08-26 21:11:14.478   871   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-26 21:11:14.478   871   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-26 21:11:14.478   871   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-26 21:11:14.478   871   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-26 21:11:14.478   871   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-26 21:11:14.478   871   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:11:14.478   871   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:11:14.478   871   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 21:11:14.482   871   885 E DropBoxManagerService: Can't write: system_server_wtf
08-26 21:11:14.482   871   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-26 21:11:14.482   871   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 21:11:14.482   871   885 E DropBoxManagerService: 	... 13 more
,08-26 21:11:14.486  1950  2018 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-26 21:11:14.498   871  2079 I ActivityManager: Start proc 4395:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-26 21:11:14.498  1950  2018 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-26 21:11:14.498  1950  2018 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1950
08-26 21:11:14.498  1950  2018 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 21:11:14.498  1950  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 21:11:14.498  1950  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 21:11:14.498  1950  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 21:11:14.498  1950  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 21:11:14.498  1950  2018 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 21:11:14.498  1950  2018 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-26 21:11:14.498  1950  2018 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-26 21:11:14.498  1950  2018 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 21:11:14.498  1950  2018 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 21:11:14.498  1950  2018 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:11:14.498  1950  2018 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 21:11:14.501   871   883 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 21:11:14.504   871  4403 E DropBoxManagerService: Can't write: system_app_crash
08-26 21:11:14.504   871  4403 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-26 21:11:14.504   871  4403 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 21:11:14.504   871  4403 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 21:11:14.504   871  4403 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 21:11:14.504   871  4403 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 21:11:14.504   871  4403 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 21:11:14.504   871  4403 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 21:11:14.504   871  4403 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 21:11:14.504   871  4403 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 21:11:14.504   871  4403 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 21:11:14.504   871  4403 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 21:11:14.504   871  4403 E DropBoxManagerService: 	... 5 more
,08-26 21:11:14.509  1950  2018 I Process : Sending signal. PID: 1950 SIG: 9
,08-26 21:11:14.537  4381  4381 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-26 21:11:14.554  4381  4413 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 21:11:14.555   871   882 I ActivityManager: Start proc 4412:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-26 21:11:14.559  4381  4401 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:11:14.559  4381  4401 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:11:14.560  4381  4401 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 21:11:14.563   871  1378 D GraphicsStats: Buffer count: 1
08-26 21:11:14.563   871  1954 I WindowState: WIN DEATH: Window{c61749e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-26 21:11:14.574   871  2079 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1950) has died
,08-26 21:11:14.575   871  2079 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-26 21:11:14.580   871  2079 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 21:11:14.595   871  1956 I ActivityManager: Start proc 4426:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 21:11:14.609  4412  4412 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-26 21:11:14.634  1508  1508 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-26 21:11:14.636  1508  1508 D AndroidRuntime: Shutting down VM
08-26 21:11:14.636  1508  1508 E AndroidRuntime: FATAL EXCEPTION: main
08-26 21:11:14.636  1508  1508 E AndroidRuntime: Process: com.google.process.gapps, PID: 1508
08-26 21:11:14.636  1508  1508 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-26 21:11:14.636  1508  1508 E AndroidRuntime: 	... 8 more
,08-26 21:11:14.639  1508  1508 I Process : Sending signal. PID: 1508 SIG: 9
,08-26 21:11:14.642  4426  4426 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:11:14.642  4426  4426 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 21:11:14.642  4426  4426 D AndroidRuntime: Shutting down VM
08-26 21:11:14.642   871  4442 E DropBoxManagerService: Can't write: system_app_crash
08-26 21:11:14.642   871  4442 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-26 21:11:14.642   871  4442 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 21:11:14.642   871  4442 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 21:11:14.642   871  4442 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 21:11:14.642   871  4442 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 21:11:14.642   871  4442 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 21:11:14.642   871  4442 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 21:11:14.642   871  4442 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 21:11:14.642   871  4442 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 21:11:14.642   871  4442 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 21:11:14.642   871  4442 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 21:11:14.642   871  4442 E DropBoxManagerService: 	... 5 more
,08-26 21:11:14.646  4426  4426 E AndroidRuntime: FATAL EXCEPTION: main
08-26 21:11:14.646  4426  4426 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4426
08-26 21:11:14.646  4426  4426 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 21:11:14.646  4426  4426 E AndroidRuntime: 	... 10 more
08-26 21:11:14.652   871  3278 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 21:11:14.652  4426  4426 I Process : Sending signal. PID: 4426 SIG: 9
08-26 21:11:14.654   871  4444 E DropBoxManagerService: Can't write: system_app_crash
08-26 21:11:14.654   871  4444 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-26 21:11:14.654   871  4444 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 21:11:14.654   871  4444 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 21:11:14.654   871  4444 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 21:11:14.654   871  4444 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 21:11:14.654   871  4444 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 21:11:14.654   871  4444 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 21:11:14.654   871  4444 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 21:11:14.654   871  4444 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 21:11:14.654   871  4444 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 21:11:14.654   871  4444 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 21:11:14.654   871  4444 E DropBoxManagerService: 	... 5 more
08-26 21:11:14.670   871   883 I ActivityManager: Killing 3815:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-26 21:11:14.692   871  1314 D WifiService: Client connection lost with reason: 4
,08-26 21:11:14.693  1717  4443 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@69c66c3
,08-26 21:11:14.701  4381  4401 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-26 21:11:14.706  4381  4413 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:11:14.706  4381  4413 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 21:11:14.706  4381  4413 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-26 21:11:14.706  4381  4413 E AndroidRuntime: Process: android.process.acore, PID: 4381
08-26 21:11:14.706  4381  4413 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:11:14.706  4381  4413 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 21:11:14.707  4381  4401 I Process : Sending signal. PID: 4381 SIG: 9
,08-26 21:11:14.717   871  3278 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4426) has died
,08-26 21:11:14.719   871  3278 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 21:11:14.722   871  1606 I ActivityManager: Process com.google.process.gapps (pid 1508) has died
,08-26 21:11:14.722   871  1606 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-26 21:11:14.722   871  1606 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms,
08-26 21:11:14.722   871  1606 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 21000ms
08-26 21:11:14.722   871  1606 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms,
08-26 21:11:14.736   871   885 I ActivityManager: Start proc 4445:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 21:11:14.750   871  3355 I ActivityManager: Start proc 4456:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
08-26 21:11:14.759   871  2079 I ActivityManager: Process android.process.acore (pid 4381) has died
08-26 21:11:14.759  1717  1717 W RocketImpressions: ClearcutLogger connection suspended: 1
08-26 21:11:14.760   871  2079 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40962ms
08-26 21:11:14.760   871  4462 E DropBoxManagerService: Can't write: system_app_crash
08-26 21:11:14.760   871  4462 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-26 21:11:14.760   871  4462 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 21:11:14.760   871  4462 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 21:11:14.760   871  4462 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 21:11:14.760   871  4462 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 21:11:14.760   871  4462 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 21:11:14.760   871  4462 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 21:11:14.760   871  4462 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 21:11:14.760   871  4462 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 21:11:14.760   871  4462 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 21:11:14.760   871  4462 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 21:11:14.760   871  4462 E DropBoxManagerService: 	... 5 more
,08-26 21:11:14.784   282   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
