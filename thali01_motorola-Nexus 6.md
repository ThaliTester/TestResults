#### Test 832611203a07957_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-30 17:40:23.953  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:40:23.964  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 17:40:23.967  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 17:40:24.012  1521  2994 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-30 17:40:24.012  1521  2994 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 17:40:24.013  1521  2994 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 17:40:24.013  1521  2994 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 17:40:24.049  3523  3523 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 17:40:24.052  3523  3523 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 17:40:24.053  3523  3523 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-30 17:40:24.621  3803  3803 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 17:40:24.626  3803  3803 D AndroidRuntime: CheckJNI is OFF
08-30 17:40:24.668  3803  3803 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 17:40:24.718  3803  3803 I Radio-JNI: register_android_hardware_Radio DONE
08-30 17:40:24.741  3803  3803 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 17:40:24.747   872   882 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 17:40:24.792  2004  3759 W SearchService: Abort, client detached.
08-30 17:40:24.795  3803  3803 D AndroidRuntime: Shutting down VM
08-30 17:40:24.796  2004  2332 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@380b5a7
08-30 17:40:24.796  2004  2004 I HotwordDetector: Closing mic
08-30 17:40:24.796  2004  2342 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-30 17:40:24.839   872  1394 I ActivityManager: Start proc 3812:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 17:40:24.853   378  2348 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 17:40:24.857   378  2348 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-30 17:40:24.863   378  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 17:40:24.866  2004  2334 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-30 17:40:24.867  2004  2341 I MicroRecognitionRnrImpl: Detection finished
08-30 17:40:24.930  3812  3812 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 17:40:24.963  3812  3812 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 17:40:24.978  3812  3812 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 776-786)
08-30 17:40:24.978  3812  3812 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:40:25.002  3812  3812 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7d14d84}
08-30 17:40:25.003  3812  3812 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:40:25.003  3812  3812 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 17:40:25.011  3812  3812 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 17:40:25.014  3812  3812 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 17:40:25.036  3812  3812 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 17:40:25.051  3812  3812 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 17:40:25.051  3812  3812 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 17:40:25.051  3812  3812 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 17:40:25.051  3812  3812 I Adreno  : Build Date                       : 10/20/15
08-30 17:40:25.051  3812  3812 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 17:40:25.051  3812  3812 I Adreno  : Local Branch                     : M14
08-30 17:40:25.051  3812  3812 I Adreno  : Remote Branch                    : 
08-30 17:40:25.051  3812  3812 I Adreno  : Remote Branch                    : 
08-30 17:40:25.051  3812  3812 I Adreno  : Reconstruct Branch               : 
,08-30 17:40:25.138   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35e3145:true
,08-30 17:40:25.189  3812  3812 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 17:40:25.207  3812  3812 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 17:40:25.280  3812  3851 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 17:40:25.293  3812  3837 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 17:40:25.324  3812  3851 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 17:40:25.404   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +582ms
08-30 17:40:25.408  1871  1871 I Keyboard.Facilitator: onFinishInput()
,08-30 17:40:25.502  3812  3812 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3812
,08-30 17:40:25.659   872  1977 I ActivityManager: Killing 2972:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-30 17:40:25.695  3812  3812 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 17:40:25.722   872  1977 I ActivityManager: Killing 3216:com.google.android.gm/u0a78 (adj 15): empty #18
,08-30 17:40:25.842  3812  3853 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1695876816
,08-30 17:40:25.847  3812  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 17:40:25.847  3812  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 17:40:25.847  3812  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 17:40:25.847  3812  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 17:40:25.847  3812  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 17:40:25.847  3812  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fc8 added. We now have 1 listener(s)
,08-30 17:40:25.851  3812  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-30 17:40:25.854  3812  3853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 17:40:25.855  3812  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:40:25.856  3812  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:40:25.863  3812  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 17:40:25.863  3812  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 17:40:25.863  3812  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 17:40:25.863  3812  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 17:40:25.863  3812  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 17:40:25.863  3812  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 17:40:25.863  3812  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 17:40:25.863  3812  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 17:40:25.863  3812  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 17:40:25.863  3812  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 17:40:25.863  3812  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 17:40:25.863  3812  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 17:40:25.863  3812  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 17:40:25.863  3812  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 17:40:25.863  3812  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fc7047 added. We now have 1 listener(s)
,08-30 17:40:25.863  3812  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:40:25.866   872  1306 D WifiService: New client listening to asynchronous messages
,08-30 17:40:25.867  3812  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:40:25.867  3812  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-30 17:40:25.867  3812  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 17:40:25.868  3812  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 17:40:25.868  3812  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 17:40:25.871  3812  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:40:25.871  3812  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-30 17:40:25.879  3812  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 17:40:25.879  3812  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:25.879  3812  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:25.879  3812  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:25.879  3812  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:25.879  3812  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:25.879  3812  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:25.879  3812  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:25.879  3812  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:40:25.879  3812  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 17:40:25.879  3812  3853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:40:25.880  3812  3853 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 17:40:25.994  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-30 17:40:25.998  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:26.000  3812  3812 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 17:40:26.764  3812  3863 W jxcore-log: Initializing JXcore engine
,08-30 17:40:26.765  3812  3863 W jxcore-log: JXcore engine is ready
,08-30 17:40:26.805  3863  3863 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8981 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-30 17:40:26.805  3863  3863 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11616]" dev="sockfs" ino=11616 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-30 17:40:26.805  3863  3863 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 17:40:26.805  3863  3863 W Thread-330: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[26454]" dev="sockfs" ino=26454 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 17:40:26.820  3812  3863 W jxcore-log: Starting JXcore engine
,08-30 17:40:26.896  3812  3863 W jxcore-log: Platform android
08-30 17:40:26.896  3812  3863 W jxcore-log: 
,08-30 17:40:26.896  3812  3863 W jxcore-log: Process ARCH arm
08-30 17:40:26.896  3812  3863 W jxcore-log: 
08-30 17:40:26.896   872  1305 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-30 17:40:27.106  3812  3863 I jxcore-log: JXcore Cordova bridge is ready!
08-30 17:40:27.106  3812  3863 I jxcore-log: 
,08-30 17:40:27.106  3812  3863 W jxcore-log: JXcore engine is started
,08-30 17:40:27.113  3812  3853 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 17:40:27.119  3812  3812 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 17:40:31.124  3025  3869 V KeepSync: Connecting to GoogleApiClient
,08-30 17:40:31.125   872  1954 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 17:40:31.175  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:40:31.177  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:40:31.209  1521  2994 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 17:40:31.209  1521  2994 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-30 17:40:31.210  1521  2994 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 17:40:31.210  1521  2994 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 17:40:31.241  1737  3870 V BaseAuthAsyncOperation: access token request failed
,08-30 17:40:31.243  3025  3869 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 17:40:31.318  1521  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 17:40:31.319  1521  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-30 17:40:31.319  1521  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 17:40:31.319  1521  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 17:40:31.336  3025  3869 E KeepSync: IOException
08-30 17:40:31.336  3025  3869 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 17:40:31.336  3025  3869 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 17:40:31.336  3025  3869 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 17:40:31.336  3025  3869 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 17:40:31.336  3025  3869 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 17:40:31.336  3025  3869 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 17:40:31.336  3025  3869 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 17:40:31.336  3025  3869 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 17:40:31.336  3025  3869 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 17:40:31.336  3025  3869 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 17:40:31.336  3025  3869 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 17:40:31.336  3025  3869 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 17:40:31.336  3025  3869 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 17:40:31.336  3025  3869 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 17:40:31.336  3025  3869 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 17:40:31.336  3025  3869 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 17:40:31.336  3025  3869 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 17:40:31.336  3025  3869 E KeepSync: 	... 10 more
08-30 17:40:31.336  3025  3869 W KeepSync: Sync result 2
,08-30 17:40:31.343   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 126795, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 17:40:37.123  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 17:40:37.123  3812  3863 I jxcore-log: 
,08-30 17:40:37.125  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 17:40:37.125  3812  3863 I jxcore-log: 
,08-30 17:40:37.135  3812  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:37.135  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:37.135  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:37.135  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:37.135  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:37.135  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:37.135  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:37.135  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:40:37.140  3812  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:40:37.142  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 17:40:37.142  3812  3863 I jxcore-log: 
,08-30 17:40:37.144  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 17:40:37.144  3812  3863 I jxcore-log: 
,08-30 17:40:37.638  3812  3863 D executeNativeTests: Running unit tests
,08-30 17:40:37.696  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 17:40:37.697  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 added. We now have 2 listener(s)
08-30 17:40:37.698  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 17:40:37.698  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 17:40:37.698  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:40:37.698  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:40:37.698  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 added. We now have 2 listener(s)
,08-30 17:40:37.698  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:40:37.699  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:40:37.701  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:40:37.714  3812  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:37.714  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:37.714  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:37.714  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:37.714  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:37.714  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:37.714  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:37.714  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:40:37.719  3812  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:40:37.720  3812  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:40:37.722  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:37.723  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-30 17:40:37.730  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 17:40:37.730  3812  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
,08-30 17:40:37.731  3812  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 17:40:37.738  3812  3863 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 17:40:37.739  3812  3863 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-30 17:40:37.740  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 17:40:37.740  3812  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 17:40:37.741  3812  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:40:37.742  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:37.744  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:37.744  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:37.745  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:37.745  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:37.745  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:40:37.745  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:40:37.745  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 removed from the list
08-30 17:40:37.745  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:37.745  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 removed from the list
08-30 17:40:37.745  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:37.745  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:37.746  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:37.746  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:37.747  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:37.747  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:37.747  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:37.747  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:37.749  3812  3863 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 17:40:37.750  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:37.750  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:37.750  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:37.750  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:37.750  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:37.750  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:37.751  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
08-30 17:40:37.751  ,3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:37.751  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:37.751  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:37.751  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:37.751  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:37.751  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:37.751  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:37.752  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:37.752  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:37.752  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:37.752  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:37.759  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 17:40:37.759  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 17:40:37.759  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 17:40:37.759  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 17:40:37.759  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 17:40:37.759  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 17:40:37.759  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 17:40:37.759  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 17:40:37.760  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 17:40:37.761  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 17:40:37.761  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 17:40:37.761  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 17:40:37.761  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 17:40:37.761  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 17:40:37.761  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:37.761  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:37.761  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:37.761  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:37.761  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:37.761  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:37.761  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
08-30 17:40:37.761  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:37.762  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:37.762  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:37.762  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:37.762  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:37.762  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManag,er: release: The given listener does not exist in the list - probably already removed
08-30 17:40:37.762  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:37.763  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:37.763  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:37.763  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:37.764  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:37.764  3812  3863 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 17:40:37.766  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:40:37.769  3812  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:37.769  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:37.769  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:37.769  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:37.769  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:37.769  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:37.769  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:37.769  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:40:37.771  3812  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:37.771  3812  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:40:37.773  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:37.774  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:37.774  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:40:37.775  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:40:37.775  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:40:37.775  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:40:37.775  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:40:37.779  3812  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 17:40:37.779  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:40:37.782  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 17:40:37.783  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 17:40:37.784  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 17:40:37.785  3812  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-30 17:40:37.787  3812  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-30 17:40:37.787  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 17:40:37.787  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:40:37.788  3812  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:40:37.789  3812  3863 D BluetoothAdapter: STATE_ON
08-30 17:40:37.802  2661  2768 D BtGatt.GattService: registerClient() - UUID=178e0a87-84ab-41d2-bc87-e58e0ae74dd7
08-30 17:40:37.804  2661  2682 D BtGatt.GattService: onClientRegistered() - UUID=178e0a87-84ab-41d2-bc87-e58e0ae74dd7, clientIf=5
08-30 17:40:37.805  3812  3824 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 17:40:37.806  2661  2790 D BtGatt.GattService: start scan with filters
08-30 17:40:37.809  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 17:40:37.809  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:40:37.809  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:40:37.809  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 17:40:37.809  2661  2685 D BtGatt.ScanManager: handling starting scan
08-30 17:40:37.825  2661  2685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
08-30 17:40:37.826  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:40:37.826  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 17:40:37.826  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:40:37.830  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:40:37.834  3812  3863 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 17:40:37.836  2661  2682 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 17:40:37.836  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:40:37.837  2661  2685 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 17:40:37.842  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:40:37.842  3812  3863 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 17:40:37.842  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:40:37.843  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 17:40:37.843  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:37.844  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 17:40:37.844  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 17:40:37.844  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:40:37.845  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 17:40:37.845  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 17:40:37.845  2661  2682 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 17:40:37.845  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-30 17:40:37.846  2661  2685 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 17:40:37.846  2661  2685 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 17:40:37.846  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 17:40:37.847  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:40:37.849  3812  3863 D BluetoothAdapter: STATE_ON
,08-30 17:40:37.855  2661  2672 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:40:37.857  2661  2673 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 17:40:37.857  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:40:37.857  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 17:40:37.858  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 17:40:37.858  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 17:40:37.858  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 17:40:37.859  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:40:37.859  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 17:40:37.859  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 17:40:37.860  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 17:40:37.860  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:40:37.861  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 17:40:37.861  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 17:40:37.861  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:40:37.862  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:40:37.862  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:37.862  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:40:37.862  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
,08-30 17:40:37.862  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:37.862  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:37.862  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:37.862  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:37.862  3812  3863 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 17:40:37.866  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:40:37.868  2661  2682 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 17:40:37.868  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:40:37.875  3812  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:37.875  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:37.875  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:37.875  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:37.875  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:37.875  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:37.875  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:37.875  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:40:37.876  2661  2682 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 17:40:37.876  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:40:37.879  3812  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:40:37.879  3812  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:40:37.880  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:40:37.880  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 17:40:37.880  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:40:37.880  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:40:37.880  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:40:37.884  2661  2682 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 17:40:37.884  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:40:37.885  2661  2685 D BtGatt.ScanManager: stopping BLe Batch
,08-30 17:40:37.886  3812  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 17:40:37.886  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:40:37.887  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:37.890  2661  2682 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 17:40:37.890  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:40:37.891  2661  2685 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 17:40:37.894  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:40:37.895  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:37.896  2661  2682 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 17:40:37.896  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 17:40:37.896  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:40:37.896  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:40:37.904  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 17:40:37.905  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 17:40:37.905  3812  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:40:37.907  3812  3863 D BluetoothAdapter: STATE_ON
,08-30 17:40:37.912  2661  2768 D BtGatt.GattService: registerClient() - UUID=a9df5df0-1715-4d55-9cbd-d9416b1146db
,08-30 17:40:37.913  2661  2682 D BtGatt.GattService: onClientRegistered() - UUID=a9df5df0-1715-4d55-9cbd-d9416b1146db, clientIf=5
08-30 17:40:37.913  3812  3859 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 17:40:37.914  2661  2673 D BtGatt.GattService: start scan with filters
,08-30 17:40:37.921  2661  2685 D BtGatt.ScanManager: handling starting scan
08-30 17:40:37.921  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 17:40:37.921  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:40:37.922  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 17:40:37.922  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:40:37.932  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:40:37.932  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:40:37.932  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 17:40:37.933  2661  2682 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 17:40:37.933  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:40:37.933  2661  2685 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 17:40:37.935  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:40:37.938  3812  3863 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 17:40:37.938  2661  2682 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 17:40:37.939  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:40:37.939  2661  2685 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 17:40:37.939  2661  2685 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 17:40:37.944  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:40:37.944  3812  3863 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 17:40:37.944  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:40:37.944  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 17:40:37.944  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:37.944  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:40:37.944  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 17:40:37.944  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:40:37.944  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 17:40:37.944  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:40:37.945  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:40:37.945  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:40:37.948  3812  3863 D BluetoothAdapter: STATE_ON
,08-30 17:40:37.949  2661  2790 D BtGatt.GattService: stopScan() - queue size =1
08-30 17:40:37.949  2661  2673 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 17:40:37.950  2661  2682 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 17:40:37.950  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 17:40:37.950  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-30 17:40:37.950  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 17:40:37.950  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 17:40:37.950  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 17:40:37.950  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:40:37.951  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:40:37.951  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:40:37.951  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:40:37.951  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 17:40:37.952  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:40:37.954  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:40:37.954  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 17:40:37.954  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:40:37.955  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:40:37.955  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:37.955  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:40:37.955  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
08-30 17:40:37.955  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:37.955  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
,08-30 17:40:37.955  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:37.955  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:37.955  2661  2682 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 17:40:37.955  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:40:37.956  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:37.956  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:37.958  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:40:37.958  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:37.958  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:37.958  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:37.960  3812  3863 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 17:40:37.964  2661  2682 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 17:40:37.964  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:40:37.964  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:40:37.964  2661  2685 D BtGatt.ScanManager: stopping BLe Batch
,08-30 17:40:37.972  2661  2682 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 17:40:37.972  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:40:37.973  2661  2685 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 17:40:37.973  3812  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:37.973  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:37.973  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:37.973  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:37.973  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:37.973  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:37.973  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:37.973  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:40:37.975  3812  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:40:37.976  3812  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:40:37.976  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:40:37.976  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 17:40:37.976  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:40:37.976  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:40:37.976  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:40:37.978  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:37.980  3812  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 17:40:37.980  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:40:37.981  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:37.981  2661  2682 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 17:40:37.981  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:40:37.984  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:40:37.984  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 17:40:37.985  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:40:37.988  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 17:40:37.988  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 17:40:37.988  3812  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 17:40:37.989  3812  3863 D BluetoothAdapter: STATE_ON
,08-30 17:40:37.991  2661  2672 D BtGatt.GattService: registerClient() - UUID=73fb7ab2-533c-472f-a40e-487f3af0c4ef
,08-30 17:40:37.991  2661  2682 D BtGatt.GattService: onClientRegistered() - UUID=73fb7ab2-533c-472f-a40e-487f3af0c4ef, clientIf=5
08-30 17:40:37.991  3812  3823 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 17:40:37.992  2661  2673 D BtGatt.GattService: start scan with filters
,08-30 17:40:37.995  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 17:40:37.995  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:40:37.995  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:40:37.995  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:40:37.995  2661  2685 D BtGatt.ScanManager: handling starting scan
,08-30 17:40:37.998  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:40:37.998  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 17:40:37.999  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:40:38.000  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-30 17:40:38.002  3812  3863 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 17:40:38.003  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:40:38.003  3812  3863 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 17:40:38.003  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:40:38.003  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 17:40:38.003  2661  2682 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 17:40:38.003  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:40:38.003  2661  2685 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 17:40:38.003  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:38.004  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 17:40:38.004  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 17:40:38.004  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 17:40:38.004  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 17:40:38.004  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:40:38.004  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 17:40:38.004  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:40:38.006  3812  3863 D BluetoothAdapter: STATE_ON
,08-30 17:40:38.007  2661  2673 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:40:38.008  2661  2768 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 17:40:38.008  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 17:40:38.008  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 17:40:38.008  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 17:40:38.008  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 17:40:38.008  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:40:38.011  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:40:38.011  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:40:38.011  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:40:38.011  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:40:38.011  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:40:38.013  2661  2682 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 17:40:38.013  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:40:38.013  2661  2685 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 17:40:38.013  2661  2685 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 17:40:38.013  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:40:38.014  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:40:38.014  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:40:38.015  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:40:38.015  3812  3863 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 17:40:38.015  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:38.015  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:38.016  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:40:38.016  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.016  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:40:38.016  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
08-30 17:40:38.016  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-30 17:40:38.017  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
,08-30 17:40:38.017  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:38.017  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:38.018  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.018  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.020  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:40:38.020  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:38.020  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 17:40:38.021  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
,08-30 17:40:38.024  3812  3863 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-30 17:40:38.025  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:40:38.025  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:38.025  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 17:40:38.025  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:38.025  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:38.025  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.025  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
08-30 17:40:38.025  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.025  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
,08-30 17:40:38.025  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:38.025  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.025  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-30 17:40:38.025  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.026  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:38.026  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:38.026  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:38.026  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:40:38.026  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.027  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 17:40:38.027  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:38.027  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:38.027  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 17:40:38.028  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:38.028  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.028  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-30 17:40:38.028  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
08-30 17:40:38.028  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:40:38.028  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
,08-30 17:40:38.028  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:40:38.028  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.028  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:38.028  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.028  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:38.029  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:38.029  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:40:38.029  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.029  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.030  3812  3863 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 17:40:38.030  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:40:38.030  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:40:38.030  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:38.030  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:38.030  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.030  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.030  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
,08-30 17:40:38.030  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.030  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
,08-30 17:40:38.030  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:38.030  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.030  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:38.031  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.031  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.031  2661  2682 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 17:40:38.031  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:40:38.032  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:38.032  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:40:38.032  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.032  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.032  3812  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 17:40:38.032  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:40:38.032  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:38.032  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 17:40:38.033  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:38.033  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.033  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.033  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
,08-30 17:40:38.033  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.033  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list,
08-30 17:40:38.033  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:40:38.033  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.033  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:38.033  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.033  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.034  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-30 17:40:38.034  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:38.034  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 17:40:38.034  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
,08-30 17:40:38.035  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 17:40:38.036  3812  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 17:40:38.036  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 17:40:38.036  3812  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:40:38.036  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 17:40:38.036  3812  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 17:40:38.037  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:38.037  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:38.037  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 17:40:38.037  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:38.037  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.037  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:38.037  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
08-30 17:40:38.037  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.037  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
,08-30 17:40:38.037  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:40:38.037  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.037  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.037  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.037  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:38.038  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:38.038  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:38.038  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.038  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list,
08-30 17:40:38.039  3812  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:40:38.039  3812  3863 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 17:40:38.039  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 17:40:38.042  3812  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 17:40:38.042  3812  3863 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 17:40:38.043  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 17:40:38.043  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 17:40:38.043  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 17:40:38.043  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-30 17:40:38.043  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 17:40:38.043  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 17:40:38.043  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 17:40:38.043  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-30 17:40:38.044  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 17:40:38.044  2661  2682 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 17:40:38.044  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:40:38.044  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 17:40:38.046  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-30 17:40:38.046  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 17:40:38.046  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-30 17:40:38.046  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 17:40:38.046  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 17:40:38.048  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-30 17:40:38.048  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-30 17:40:38.048  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-30 17:40:38.048  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-30 17:40:38.048  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-30 17:40:38.048  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-30 17:40:38.048  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-30 17:40:38.049  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 17:40:38.049  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-30 17:40:38.049  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 17:40:38.049  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 17:40:38.049  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 17:40:38.049  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 17:40:38.049  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-30 17:40:38.049  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-30 17:40:38.049  3812  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 17:40:38.050  3812  3863 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:40:38.050  3812  3863 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-30 17:40:38.050  3812  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:40:38.050  3812  3863 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-30 17:40:38.050  3812  3863 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 17:40:38.050  3812  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:40:38.050  3812  3863 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-30 17:40:38.050  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 17:40:38.053  2661  2682 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 17:40:38.053  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:40:38.053  2661  2685 D BtGatt.ScanManager: stopping BLe Batch
08-30 17:40:38.055  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-30 17:40:38.056  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 17:40:38.056  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 17:40:38.056  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-30 17:40:38.057  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 17:40:38.057  3812  3863 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-30 17:40:38.057  3812  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:40:38.057  3812  3863 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 17:40:38.058  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:40:38.058  3812  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
08-30 17:40:38.058  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:40:38.058  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:38.058  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:38.058  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:38.058  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.058  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 17:40:38.059  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list,
08-30 17:40:38.059  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.059  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.059  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:38.059  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:38.059  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.059  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.059  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.059  3812  3875 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:40:38.060  2661  2682 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 17:40:38.060  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:40:38.060  3812  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
,08-30 17:40:38.060  2661  2685 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 17:40:38.060  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:38.060  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:38.060  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:40:38.060  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.061  3812  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 394)
08-30 17:40:38.061  3812  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 394)
08-30 17:40:38.061  3812  3863 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 17:40:38.061  3812  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
08-30 17:40:38.061  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:40:38.061  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:38.062  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:38.062  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:38.062  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.062  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:38.062  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
08-30 17:40:38.062  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.062  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.062  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:38.062  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.062  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:38.062  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.062  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.063  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:40:38.063  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:38.063  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.064  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list,
08-30 17:40:38.064  3812  3863 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 17:40:38.064  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:40:38.064  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:38.064  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:38.065  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:40:38.065  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.065  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.065  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
08-30 17:40:38.065  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.065  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
,08-30 17:40:38.065  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:38.065  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.065  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.065  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:38.065  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.066  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:38.066  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:38.066  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.066  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list,
08-30 17:40:38.066  3812  3863 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 17:40:38.066  3812  3863 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 17:40:38.066  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:40:38.066  3812  3863 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,08-30 17:40:38.067  3812  3863 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 17:40:38.067  3812  3863 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 17:40:38.067  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:40:38.067  3812  3863 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 17:40:38.067  3812  3863 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-30 17:40:38.067  2661  2682 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 17:40:38.067  2661  2682 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:40:38.067  3812  3863 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-30 17:40:38.068  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:40:38.068  3812  3863 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 17:40:38.068  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:40:38.068  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:38.068  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:38.068  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:38.068  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:38.069  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.069  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
,08-30 17:40:38.069  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.069  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.069  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:40:38.069  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.069  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.069  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.069  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.070  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:40:38.070  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:38.070  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.070  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.070  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:38.070  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:38.070  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.070  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
08-30 17:40:38.070  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.070  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.070  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:38.070  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.071  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.071  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.071  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.071  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:40:38.071  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.071  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.071  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
08-30 17:40:38.071  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:38.071  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:38.071  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:38.074  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:40:38.075  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.075  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.075  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
08-30 17:40:38.075  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.075  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.075  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:38.075  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.075  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:38.075  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.075  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.076  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:38.076  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:38.076  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.076  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.077  3812  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 17:40:38.078  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:40:38.078  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-30 17:40:38.079  3812  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 17:40:38.079  3812  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 17:40:38.079  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 17:40:38.079  3812  3812 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 17:40:38.079  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:40:38.080  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:38.080  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-30 17:40:38.080  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 17:40:38.080  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 17:40:38.080  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.080  3812  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-30 17:40:38.080  3812  3812 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 17:40:38.080  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
,08-30 17:40:38.080  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.080  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:40:38.080  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 17:40:38.080  3812  3877 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:40:38.080  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:40:38.081  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.081  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.082  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:40:38.082  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:40:38.082  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.082  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:40:38.082  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:40:38.082  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:40:38.082  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:38.082  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 17:40:38.082  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:38.082  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:38.082  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.082  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
08-30 17:40:38.082  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 17:40:38.083  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.083  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:38.083  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.083  3812  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 17:40:38.083  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-30 17:40:38.083  3812  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 17:40:38.083  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.083  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.083  3812  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-30 17:40:38.083  3812  3812 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 17:40:38.085  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:38.085  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:40:38.085  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.085  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.092  3812  3863 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-30 17:40:38.092  3812  3863 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-30 17:40:38.092  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 17:40:38.094  3812  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 17:40:38.094  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:38.095  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:38.095  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 17:40:38.095  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:40:38.095  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:38.095  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:38.095  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
08-30 17:40:38.095  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:40:38.095  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.095  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:38.095  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.095  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.095  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.095  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:38.097  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:38.097  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:38.097  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.097  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.100  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:38.100  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:38.100  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:38.100  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:38.101  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:38.101  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.101  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
08-30 17:40:38.101  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.101  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
08-30 17:40:38.101  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:40:38.101  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.101  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.101  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.101  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:38.102  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:38.102  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:38.102  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.102  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
,08-30 17:40:38.103  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:40:38.103  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:38.103  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:38.103  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:38.103  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.103  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:38.103  3812  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0a498 not in the list
08-30 17:40:38.103  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:38.104  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
,08-30 17:40:38.104  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:38.104  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:38.104  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.104  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:38.104  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:38.105  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:40:38.106  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:38.106  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:40:38.106  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94f1 not in the list
,08-30 17:40:38.106  3812  3863 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 17:40:38.106  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:40:38.106  3812  3863 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 17:40:38.106  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:40:38.106  3812  3863 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 17:40:38.107  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:40:38.108  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 17:40:38.108  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 17:40:38.108  3812  3863 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 17:40:38.108  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 17:40:38.108  3812  3863 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-30 17:40:38.108  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-30 17:40:38.108  3812  3863 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-30 17:40:38.108  3812  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 17:40:38.109  3812  3863 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 17:40:38.109  3812  3863 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 17:40:38.109  3812  3863 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 17:40:38.109  3812  3863 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-30 17:40:38.109  3812  3863 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 17:40:38.109  3812  3863 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 17:40:38.110  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:40:38.110  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a199c6b added. We now have 2 listener(s)
08-30 17:40:38.110  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:40:38.113  3812  3863 D BluetoothAdapter: enable(): BT is already enabled..!
,08-30 17:40:38.113   872  2069 D WifiService: setWifiEnabled: true pid=3812, uid=10000
08-30 17:40:38.113   872  2069 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 17:40:38.114  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:40:38.114  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5263c8 added. We now have 3 listener(s)
08-30 17:40:38.114  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:40:38.120  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:40:38.120  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22b9c61 added. We now have 4 listener(s)
08-30 17:40:38.120  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:40:38.121  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:40:38.121  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a3d5386 added. We now have 5 listener(s)
08-30 17:40:38.121  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:40:38.123   872  1394 D WifiService: setWifiEnabled: false pid=3812, uid=10000
08-30 17:40:38.123   872  1394 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 17:40:38.126  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:40:38.128  2661  2678 D BluetoothAdapterState: Current state: ON, message: 23
08-30 17:40:38.128  2661  2678 D BluetoothAdapterProperties: Setting state to 13
08-30 17:40:38.128  2661  2678 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 17:40:38.129  3812  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 17:40:38.129  2661  2678 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 17:40:38.129  3812  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:38.129  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:38.129  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:40:38.129  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:38.129  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:38.129  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:38.129  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:38.129  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:40:38.129  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:38.130  3812  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:38.130  3812  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:40:38.130  2661  2678 I BluetoothAdapterState: Entering PendingCommandState
08-30 17:40:38.133  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:40:38.133  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:38.133  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:38.133  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:40:38.133  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:38.133  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:38.133  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:38.133  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:38.133  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:40:38.134  2661  2661 D BluetoothMapService: onReceive
08-30 17:40:38.134  2661  2661 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:38.134  2661  2661 D BluetoothMapService: STATE_TURNING_OFF
08-30 17:40:38.134  2661  2661 D BluetoothMapService: MAP Service closeService in
08-30 17:40:38.134  2661  2661 D BluetoothMapMasInstance0: MAP Service shutdown
,08-30 17:40:38.134  2661  2661 D ObexServerSockets0: shutdown(block = true)
08-30 17:40:38.135  2661  2791 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 17:40:38.135  2661  2661 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 17:40:38.135  2661  2764 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 17:40:38.135  2661  2661 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 17:40:38.135  2661  2792 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 17:40:38.136  2661  2661 I BtOppRfcommListener: stopping Accept Thread
08-30 17:40:38.136  2661  3429 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 17:40:38.136  2661  3429 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 17:40:38.137  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:38.137  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:38.140  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:38.143  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:38.143  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 17:40:38.143  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:38.143  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:38.143  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:40:38.143  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:38.143  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:38.143  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:38.143  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:38.143  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:40:38.144  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:38.144  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:38.144   872  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 17:40:38.144   872  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 17:40:38.144   872  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 17:40:38.144   872  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:40:38.146  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:38.154   872  1849 D DhcpClient: Clearing IP address
,08-30 17:40:38.154   374   870 D CommandListener: Clearing all IP addresses on wlan0
08-30 17:40:38.155   872   885 I ActivityManager: Start proc 3881:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-30 17:40:38.156   374   870 D CommandListener: Setting iface cfg
08-30 17:40:38.159  1521  2134 V NativeCrypto: Read error: ssl=0xaebaae00: I/O error during system call, Connection timed out
08-30 17:40:38.160  2661  2682 D BluetoothAdapterProperties: Scan Mode:20
08-30 17:40:38.160   872  1851 D DhcpClient: Receive thread stopped
08-30 17:40:38.161  2661  2678 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 17:40:38.161  1521  2134 V NativeCrypto: SSL shutdown failed: ssl=0xaebaae00: I/O error during system call, Broken pipe
08-30 17:40:38.164   872   882 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-30 17:40:38.164   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 17:40:38.164   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-30 17:40:38.164   872  1843 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-30 17:40:38.168   872  1305 D WifiStateMachine: Start Disconnecting Watchdog 1
08-30 17:40:38.168   872  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 17:40:38.168  2661  2661 D HeadsetService: Received stop request...Stopping profile...
08-30 17:40:38.168  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:38.169  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:38.169  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:38.169  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:40:38.169  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:38.169  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:38.169  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:38.169  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:38.169  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:40:38.169  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:38.169  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:40:38.170   872   872 D BluetoothHeadset: Proxy object disconnected
08-30 17:40:38.170   872   872 D BluetoothHeadset: Proxy object disconnected
08-30 17:40:38.170   872   872 D BluetoothHeadset: Proxy object disconnected
08-30 17:40:38.170  1362  1383 D BluetoothHeadset: Proxy object disconnected
08-30 17:40:38.171  1362  1362 D HeadsetProfile: Bluetooth service disconnected
08-30 17:40:38.171   397   397 E Parcel  : Reading a NULL string not supported here.
08-30 17:40:38.171  1937  1951 D BluetoothHeadset: Proxy object disconnected
08-30 17:40:38.171  2661  2661 D A2dpService: Received stop request...Stopping profile...
08-30 17:40:38.172  2661  2785 D A2dpStateMachine: Exit Disconnected: -1
08-30 17:40:38.173   374   870 D CommandListener: Clearing all IP addresses on wlan0
08-30 17:40:38.173  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:38.173  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:38.173  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:38.173  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:40:38.173  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:38.173  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:38.173  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:38.173  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:38.173  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:40:38.175  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:38.175  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:40:38.176   872  1843 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-30 17:40:38.178   872   872 D BluetoothA2dp: Proxy object disconnected
08-30 17:40:38.178  1362  1362 D BluetoothA2dp: Proxy object disconnected
08-30 17:40:38.178   872  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 17:40:38.180  2661  2661 D HidService: Received stop request...Stopping profile...
08-30 17:40:38.180  2661  2661 D HidService: Stopping Bluetooth HidService
08-30 17:40:38.181  1362  1362 D BluetoothInputDevice: Proxy object disconnected
08-30 17:40:38.181  1362  1362 D HidProfile: Bluetooth service disconnected
08-30 17:40:38.182  2661  2661 D HealthService: Received stop request...Stopping profile...
08-30 17:40:38.187  2661  2661 D PanService: Received stop request...Stopping profile...
08-30 17:40:38.187   872  1305 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 17:40:38.189  2087  2300 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:40:38.190  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:38.190  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:38.190  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:38.190  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:40:38.190  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:38.190  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:38.190  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:38.190  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:38.190  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:40:38.190  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:38.190  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:40:38.191   872  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 17:40:38.191  2661  2661 D BluetoothMapService: Received stop request...Stopping profile...
08-30 17:40:38.191  2661  2661 D BluetoothMapService: stop()
08-30 17:40:38.192  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:38.192  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:38.192  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:38.192  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:40:38.192  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:38.192  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:38.192  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:38.192  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:38.192  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:40:38.192  2661  2661 D BluetoothMapAppObserver: deinitObservers()
08-30 17:40:38.192  2661  2661 D BluetoothMapAppObserver: removeReceiver()
08-30 17:40:38.192  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:38.193  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:40:38.193  2661  2661 V BluetoothAdapterState: isTurningOff()=true
08-30 17:40:38.193  2661  2661 V BluetoothAdapterState: isTurningOn()=false
08-30 17:40:38.193  2661  2661 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:38.194  2661  2661 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:38.195  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 17:40:38.195  1362  1362 D PanProfile: Bluetooth service disconnected
08-30 17:40:38.196  1362  1362 D BluetoothMap: Proxy object disconnected
08-30 17:40:38.196  1362  1362 D MapProfile: Bluetooth service disconnected
08-30 17:40:38.196  2661  2661 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 17:40:38.196  2661  2682 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 17:40:38.196  2661  2661 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 17:40:38.196  2661  2760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:40:38.196  2661  2760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:40:38.196  2661  2760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:40:38.196  2661  2682 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 17:40:38.196  2661  2661 V BluetoothAdapterState: isTurningOff()=true
08-30 17:40:38.196  2661  2661 V BluetoothAdapterState: isTurningOn()=false
,08-30 17:40:38.196  2661  2661 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:38.196  2661  2661 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:38.198  2661  2682 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 17:40:38.198  2661  2760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:40:38.198  2661  2760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:40:38.198  2661  2760 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:40:38.198  2661  2661 V BluetoothAdapterState: isTurningOff()=true
08-30 17:40:38.198  2661  2760 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:40:38.198  2661  2760 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:40:38.198  2661  2661 V BluetoothAdapterState: isTurningOn()=false
08-30 17:40:38.198  2661  2760 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 17:40:38.198  2661  2661 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:38.198  2661  2661 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:38.198  2661  2661 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 17:40:38.198  2661  2682 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 17:40:38.198  2661  2661 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 17:40:38.199  2661  2661 V BluetoothAdapterState: isTurningOff()=true
,08-30 17:40:38.199  2661  2661 V BluetoothAdapterState: isTurningOn()=false
08-30 17:40:38.199  2661  2661 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:38.199  2661  2661 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:38.199  2661  2661 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 17:40:38.199  2661  2682 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 17:40:38.199  2661  2661 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 17:40:38.199  2661  2661 V BluetoothAdapterState: isTurningOff()=true
08-30 17:40:38.199  2661  2661 V BluetoothAdapterState: isTurningOn()=false
08-30 17:40:38.199  2661  2661 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:38.199  2661  2661 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:38.200  2661  2661 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 17:40:38.200  2661  2661 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 17:40:38.200  2661  2661 D BluetoothMapService: MAP Service closeService in
,08-30 17:40:38.200  2661  2661 V BluetoothAdapterState: isTurningOff()=true
08-30 17:40:38.200  2661  2661 V BluetoothAdapterState: isTurningOn()=false
08-30 17:40:38.201  2661  2661 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 17:40:38.201  2661  2661 V BluetoothAdapterState: isBleTurningOff()=false,
08-30 17:40:38.203  2661  2678 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 17:40:38.203  2661  2678 D BluetoothAdapterProperties: Setting state to 15
08-30 17:40:38.203  2661  2678 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 17:40:38.203   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:40:38.203   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 17:40:38.204  1362  1383 D BluetoothMap: onBluetoothStateChange: up=false
08-30 17:40:38.204  2661  2678 I BluetoothAdapterState: Entering BleOnState
08-30 17:40:38.204  1362  1375 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:40:38.204   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:40:38.204  1362  1374 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 17:40:38.204  2661  2661 D BluetoothMapService: cleanup()
08-30 17:40:38.205  2661  2661 D BluetoothMapService: MAP Service closeService in
08-30 17:40:38.205  1937  1951 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:40:38.205  1362  1383 D BluetoothPan: onBluetoothStateChange on: false
08-30 17:40:38.208   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:40:38.208  1362  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 17:40:38.208  1362  1375 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 17:40:38.209  2661  2678 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 17:40:38.209  2661  2678 D BluetoothAdapterProperties: Setting state to 16
08-30 17:40:38.209  2661  2678 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 17:40:38.210  2661  2678 D BluetoothAdapterProperties: onBleDisable
08-30 17:40:38.210  2661  2678 I BluetoothAdapterState: Entering PendingCommandState
08-30 17:40:38.210  2661  2679 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 17:40:38.210  2661  2682 D BluetoothAdapterProperties: Scan Mode:20,
08-30 17:40:38.211  2661  2760 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 17:40:38.211  2661  2760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:40:38.214  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:38.215  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:38.217  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:38.218  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:38.220  3881  3881 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm,
08-30 17:40:38.233   374   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 17:40:38.250   374   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 17:40:38.252   872  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 17:40:38.252   872  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:40:38.254   872   889 D Tethering: MasterInitialState.processMessage what=3
08-30 17:40:38.256  3881  3881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:40:38.263  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:38.266  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:38.268  3417  3417 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@1d4fc8 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-30 17:40:38.278   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1df7a29:true
,08-30 17:40:38.278  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:40:38.292   872   882 I ActivityManager: Start proc 3901:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-30 17:40:38.301  3881  3881 D LocalBluetoothProfileManager: Adding local MAP profile
,08-30 17:40:38.304  3881  3881 D BluetoothMap: Create BluetoothMap proxy object
,08-30 17:40:38.309  3881  3881 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 17:40:38.316  3881  3881 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:40:38.325   872   882 I ActivityManager: Killing 3081:com.google.android.talk/u0a61 (adj 15): empty #17
,08-30 17:40:38.332  3901  3901 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-30 17:40:38.336   374   870 E Netd    : netlink response contains error (No such file or directory)
,08-30 17:40:38.336   872  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 17:40:38.413  2661  2682 I bt_hci  : shut_down
,08-30 17:40:38.418  2661  2686 I bt_vendor: low_power_mode_cb
,08-30 17:40:38.420  2661  2686 D bt_hwcfg: hw_epilog_process
,08-30 17:40:38.441  2661  2686 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-30 17:40:38.441  2661  2686 I bt_vendor: epilog_cb
,08-30 17:40:38.441  2661  2686 I bt_hci  : epilog_finished_callback
,08-30 17:40:38.450  2661  2682 I bt_hci_h4: hal_close
,08-30 17:40:38.450  2661  2682 I bt_userial_vendor: device fd = 51 close
,08-30 17:40:38.501  3901  3901 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 17:40:38.501  3901  3901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:40:38.501  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:40:38.502  3901  3901 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
,08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:40:38.502  3901  3901 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:40:38.502  3901  3901 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:40:38.502  3901  3901 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:40:38.502  3901  3901 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:40:38.502  3901  3901 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:40:38.502  3901  3901 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:40:38.502  3901  3901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:40:38.533   872  1978 I ActivityManager: Start proc 3931:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-30 17:40:38.536   872  1978 I ActivityManager: Killing 3577:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-30 17:40:38.583  3812  3812 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 17:40:38.600  2661  2679 D bt_stack_manager: event_shut_down_stack finished.
,08-30 17:40:38.600  2661  2678 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24,
,08-30 17:40:38.607  2661  2661 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 17:40:38.607  2661  2678 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-30 17:40:38.608  2661  2661 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 17:40:38.608  2661  2661 D BtGatt.GattService: stop()
08-30 17:40:38.608  2661  2661 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 17:40:38.610  2661  2661 V BluetoothAdapterState: isTurningOff()=false
,08-30 17:40:38.610  2661  2661 V BluetoothAdapterState: isTurningOn()=false
,08-30 17:40:38.610  2661  2661 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 17:40:38.610  2661  2661 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 17:40:38.610  2661  2678 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-30 17:40:38.610  2661  2678 D BluetoothAdapterProperties: Setting state to 10
08-30 17:40:38.610  2661  2678 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-30 17:40:38.611  2661  2678 I BluetoothAdapterState: Entering OffState
08-30 17:40:38.611   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-30 17:40:38.619  2661  2661 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 17:40:38.619  2661  2661 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 17:40:38.619  2661  2679 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 17:40:38.619  2661  2661 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 17:40:38.622  2661  2679 D bt_stack_manager: event_clean_up_stack finished.
,08-30 17:40:38.630  3931  3931 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-30 17:40:38.631  2661  2661 I art     : System.exit called, status: 0
,08-30 17:40:38.631  2661  2661 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 17:40:38.699   872  1978 I ActivityManager: Process com.android.bluetooth (pid 2661) has died
,08-30 17:40:38.869  3931  3952 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-30 17:40:38.869  3931  3952 I Babel_SMS: MmsConfig.loadMmsSettings
,08-30 17:40:38.878  3931  3952 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-30 17:40:38.878  3931  3952 I Babel_SMS: MmsConfig.loadFromDatabase
,08-30 17:40:38.922  3931  3952 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-30 17:40:38.922  3931  3952 I Babel_SMS: MmsConfig.loadFromResources
,08-30 17:40:38.929  3931  3952 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-30 17:40:38.930  3931  3952 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-30 17:40:38.959  3931  3931 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:40:38.963  3931  3931 I Babel_Crash: startup - clean
,08-30 17:40:38.993  3931  3931 I Babel_telephony: TeleModule.launchCompleted
,08-30 17:40:39.005   872  2062 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-30 17:40:39.015  3931  3931 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-30 17:40:39.023  3931  3931 W Babel   : BAM#gBA: invalid account id: -1
,08-30 17:40:39.023  3931  3931 W Babel   : BAM#gBA: invalid account id: -1
08-30 17:40:39.023  3931  3931 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-30 17:40:39.028  3931  3957 I Babel   : deleted: false for 0
,08-30 17:40:39.035   872  1978 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-30 17:40:39.068   872   883 I ActivityManager: Start proc 3959:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-30 17:40:39.112  3931  3931 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 17:40:39.147  3959  3959 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-30 17:40:39.198  3931  3931 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 17:40:39.215  3931  3931 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 17:40:39.216  3931  3931 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 17:40:39.222  3901  3921 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 17:40:39.234  3931  3931 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 17:40:39.251  3931  3931 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 17:40:39.265  3931  3931 I vclib   : onServiceConnected
,08-30 17:40:39.295  3959  3959 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-30 17:40:39.324   872  2062 I ActivityManager: Killing 3417:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-30 17:40:39.388   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9169328:true
,08-30 17:40:39.432  3881  3881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:40:39.461   872  1467 I ActivityManager: Start proc 3984:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-30 17:40:39.464  3881  3881 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:40:39.562  3984  3984 D AdapterServiceConfig: Adding HeadsetService
08-30 17:40:39.562  3984  3984 D AdapterServiceConfig: Adding A2dpService
08-30 17:40:39.562  3984  3984 D AdapterServiceConfig: Adding HidService
08-30 17:40:39.562  3984  3984 D AdapterServiceConfig: Adding HealthService
08-30 17:40:39.562  3984  3984 D AdapterServiceConfig: Adding PanService
08-30 17:40:39.562  3984  3984 D AdapterServiceConfig: Adding GattService
08-30 17:40:39.563  3984  3984 D AdapterServiceConfig: Adding BluetoothMapService
08-30 17:40:39.565   872  1394 I ActivityManager: Killing 3466:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-30 17:40:39.609  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:40:39.622  1737  1737 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 17:40:39.626  1737  1737 D SystemUpdateService: onCreate
,08-30 17:40:39.628  1737  1737 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 17:40:39.638  1737  3996 I SystemUpdateService: active receiver: enabled
,08-30 17:40:39.645  1737  3996 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 17:40:39.646  1737  3996 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 17:40:39.647  1737  3996 I SystemUpdateService: now status is 0 (complete)
,08-30 17:40:39.647  1737  3996 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 17:40:39.647  1737  3996 I SystemUpdateService: file has been verified
08-30 17:40:39.647  1737  3996 I SystemUpdateService: OTA package size = 12249756
,08-30 17:40:39.651  1737  1737 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-30 17:40:39.652  1737  3996 I SystemUpdateService: showing system update notification
,08-30 17:40:39.654  1737  2419 I iu.UploadsManager: num queued entries: 0
,08-30 17:40:39.655  1737  2419 I iu.UploadsManager: num updated entries: 0
,08-30 17:40:39.655  1737  2419 I iu.SyncManager: NEXT; no task
,08-30 17:40:39.664  1737  1737 D SystemUpdateService: onDestroy
,08-30 17:40:39.677  1737  1737 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 17:40:39.681  1737  1737 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 17:40:39.696   872  2068 I ActivityManager: Start proc 3998:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-30 17:40:39.751  3998  3998 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-30 17:40:39.753  3998  3998 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:39.759  3998  3998 D SprintDMHelper: simOperator: 
,08-30 17:40:39.759  3998  3998 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 17:40:39.796   872  2068 I ActivityManager: Start proc 4010:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-30 17:40:39.797   872  2068 I ActivityManager: Killing 3506:android.process.acore/u0a5 (adj 15): empty #17
,08-30 17:40:40.053   872  1977 I ActivityManager: Start proc 4026:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-30 17:40:40.057  3931  4025 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-30 17:40:40.064   872   882 I ActivityManager: Killing 3663:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-30 17:40:40.116  4026  4026 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-30 17:40:40.165  4026  4026 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 17:40:40.165  4026  4026 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 17:40:40.165  4026  4026 I GAv4    :   adb logcat -s GAv4
,08-30 17:40:40.181  4026  4026 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 17:40:40.187  4026  4026 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 17:40:40.197  4026  4043 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 17:40:40.356  4026  4026 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-30 17:40:40.395  4026  4026 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 17:40:40.407  4026  4026 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6213-6216)
,08-30 17:40:40.409  4026  4026 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 17:40:40.425  4026  4026 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {da83af8}
,08-30 17:40:40.425  4026  4026 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 17:40:40.425  4026  4026 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 17:40:40.435  4026  4026 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,08-30 17:40:40.436  4026  4026 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 17:40:40.454  4026  4026 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 17:40:40.466  4026  4026 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 17:40:40.466  4026  4026 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 17:40:40.466  4026  4026 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 17:40:40.466  4026  4026 I Adreno  : Build Date                       : 10/20/15
08-30 17:40:40.466  4026  4026 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 17:40:40.466  4026  4026 I Adreno  : Local Branch                     : M14
08-30 17:40:40.466  4026  4026 I Adreno  : Remote Branch                    : 
08-30 17:40:40.466  4026  4026 I Adreno  : Remote Branch                    : 
08-30 17:40:40.466  4026  4026 I Adreno  : Reconstruct Branch               : 
,08-30 17:40:40.539  4026  4026 I NSApplication: Starting up...
,08-30 17:40:40.550  4026  4072 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 17:40:40.582   872  1978 I ActivityManager: Start proc 4077:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-30 17:40:40.585   872  1978 I ActivityManager: Killing 3677:com.android.musicfx/u0a18 (adj 15): empty #17
,08-30 17:40:40.656  4077  4077 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-30 17:40:40.834   872   883 I ActivityManager: Killing 2215:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-30 17:40:41.132   872  2068 D WifiService: setWifiEnabled: true pid=3812, uid=10000
,08-30 17:40:41.133   872  2068 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 17:40:41.146   872  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-30 17:40:41.155  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:40:41.155  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:41.155  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:41.155  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:40:41.155  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:41.155  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:41.155  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:41.155  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:41.155  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:40:41.155  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:40:41.156  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:40:41.159  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:40:41.160  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:41.160  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:41.160  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:40:41.160  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:41.160  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:41.160  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:41.160  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:41.160  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:40:41.160  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:40:41.160  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:40:41.208   872  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-30 17:40:41.209   872  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 17:40:41.210   872  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-30 17:40:41.211   872  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-30 17:40:41.211   872  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 17:40:41.211   872  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-30 17:40:41.211   872  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 17:40:41.222   374   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 17:40:41.223   872  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.00 rxSuccessRate=14.62 delta 1000 -> 994
08-30 17:40:41.223   374   870 D CommandListener: Setting iface cfg
,08-30 17:40:41.225   872  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '132 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 132 Failed to set address (No such device)'
,08-30 17:40:41.225   872  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 17:40:41.230   872  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 17:40:41.230   872  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:40:41.241   872  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 17:40:41.243   872  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 17:40:41.287   872  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 17:40:41.308   872  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 17:40:41.325  1454  1454 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 17:40:41.751  1454  1454 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 17:40:41.793  1454  1454 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 17:40:41.795  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 17:40:41.800   872  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 17:40:41.813   872  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 17:40:41.813   872  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:40:41.813   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 17:40:41.839   872  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:40:41.857   374   870 D CommandListener: Setting iface cfg
,08-30 17:40:41.859   872  1305 D WifiStateMachine: Start Dhcp Watchdog 2
,08-30 17:40:41.880   872  1307 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-30 17:40:41.885   872  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 17:40:41.913   872  4100 D DhcpClient: Receive thread started
,08-30 17:40:41.997   872  1305 E native  : do suspend false
,08-30 17:40:42.015   872  1849 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 17:40:42.028   872  4100 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,08-30 17:40:42.029   872  1849 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,08-30 17:40:42.034   872  1849 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 17:40:42.048   872  4100 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 17:40:42.049   872  1849 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 17:40:42.054   374   870 D CommandListener: Setting iface cfg
,08-30 17:40:42.065   872  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 17:40:42.065   872  1849 D DhcpClient: Scheduling renewal in 86399s
,08-30 17:40:42.082   872  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 17:40:42.086   872  1305 D WifiConfigStore: No blacklist allowed without epno enabled
08-30 17:40:42.086   872  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 17:40:42.087   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 17:40:42.090   872  1307 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 17:40:42.105   872  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 17:40:42.141   872  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 17:40:42.141   872  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-30 17:40:42.143   872  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-30 17:40:42.144   872  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 17:40:42.145   872  1307 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 17:40:42.151   872  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 17:40:42.155   872  1307 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-30 17:40:42.156   872  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-30 17:40:42.156   872  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-30 17:40:42.156   872  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 17:40:42.156   872  1307 D ConnectivityService:    accepting network in place of null
08-30 17:40:42.156   872  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 17:40:42.159   872  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 17:40:42.169   872  4099 D NetlinkSocketObserver: NeighborEvent{elapsedMs=137977, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 17:40:42.187   374   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 17:40:42.212   374   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 17:40:42.214   872  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 17:40:42.214   872  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:42.218   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-30 17:40:42.219   872  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-30 17:40:42.231  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:40:42.231  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:42.231  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:42.231  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:40:42.231  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:42.231  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:42.231  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:42.231  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:42.231  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:40:42.231  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:42.231  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:42.232  1737  1737 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 17:40:42.232  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:40:42.233  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:42.233  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:42.233  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:40:42.233  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:42.233  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:42.233  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:42.233  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:42.233  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:40:42.233  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:42.233  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:40:42.238   872  4098 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-30 17:40:42.239  1737  1737 D SystemUpdateService: onCreate
,08-30 17:40:42.243  1737  1737 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 17:40:42.245  1737  4111 I SystemUpdateService: active receiver: enabled
,08-30 17:40:42.249  1737  4111 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 17:40:42.251  1737  4111 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 17:40:42.251  1737  4111 I SystemUpdateService: now status is 0 (complete)
08-30 17:40:42.251  1737  4111 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 17:40:42.252  1737  4111 I SystemUpdateService: file has been verified
08-30 17:40:42.252  1737  4111 I SystemUpdateService: OTA package size = 12249756
,08-30 17:40:42.260  1737  4111 I SystemUpdateService: showing system update notification
,08-30 17:40:42.262  1737  1737 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 17:40:42.263  1737  2419 I iu.UploadsManager: num queued entries: 0
08-30 17:40:42.263  1737  2419 I iu.UploadsManager: num updated entries: 0
,08-30 17:40:42.265  1737  2419 I iu.SyncManager: NEXT; no task
,08-30 17:40:42.273  1737  1737 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-30 17:40:42.274  1737  1737 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 17:40:42.276  3998  3998 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:42.278  1737  4115 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 17:40:42.278  1737  4115 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 17:40:42.279  1737  4115 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
08-30 17:40:42.281  3998  3998 D SprintDMHelper: simOperator: 
08-30 17:40:42.281  3998  3998 D SprintDMReceiver: Not Sprint UICC, don't do anything.,
08-30 17:40:42.284  1737  1737 D SystemUpdateService: onDestroy
,08-30 17:40:42.289  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:40:42.291  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:40:42.300   872  4098 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 15:40:42 GMT], X-Android-Received-Millis=[1472571642300], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472571642278]}
,08-30 17:40:42.301   872  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 17:40:42.301   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-30 17:40:42.301   872  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 17:40:42.302   872  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 17:40:42.322  1521  2416 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 17:40:42.323  1521  2416 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-30 17:40:42.323  1521  2416 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 17:40:42.323  1521  2416 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 17:40:42.348  1737  4115 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-30 17:40:42.404  3931  4117 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 17:40:43.215   872  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 17:40:43.984   872  2069 I ActivityManager: Killing 3702:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-30 17:40:44.140   872  2069 D WifiService: setWifiEnabled: false pid=3812, uid=10000
08-30 17:40:44.141   872  2069 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 17:40:44.155  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 17:40:44.157   872  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 17:40:44.157   872  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 17:40:44.157   872  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 17:40:44.157   872  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:40:44.179   872  1849 D DhcpClient: Clearing IP address
,08-30 17:40:44.180   374   870 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:40:44.184   374   870 D CommandListener: Setting iface cfg
,08-30 17:40:44.194  1521  4123 V NativeCrypto: Read error: ssl=0x9a22a600: I/O error during system call, Connection timed out
,08-30 17:40:44.198   872  4100 D DhcpClient: Receive thread stopped
08-30 17:40:44.200  1521  4123 V NativeCrypto: SSL shutdown failed: ssl=0x9a22a600: I/O error during system call, Broken pipe
,08-30 17:40:44.201   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 17:40:44.202   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-30 17:40:44.206   872  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 17:40:44.207   397   397 E Parcel  : Reading a NULL string not supported here.
,08-30 17:40:44.206   872  1305 D WifiStateMachine: Start Disconnecting Watchdog 2
08-30 17:40:44.212   872  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 17:40:44.242   374   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 17:40:44.278  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:40:44.289   374   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 17:40:44.290   872  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 17:40:44.290   872  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:44.291   374   870 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:40:44.295   872   889 D Tethering: MasterInitialState.processMessage what=3
08-30 17:40:44.305  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:44.305  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:44.305  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:44.305  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:40:44.305  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:44.305  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:44.305  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:44.305  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:44.305  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:40:44.305  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:44.305  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:40:44.306  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:44.306  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:44.306  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:44.306  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:40:44.306  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:44.306  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:44.306  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:44.306  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:44.306  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:40:44.306  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:44.306  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:40:44.308  1521  2060 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-30 17:40:44.308  1521  2060 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 17:40:44.308  1521  2060 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 17:40:44.308  1521  2060 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 17:40:44.324  1737  1737 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 17:40:44.327  1737  1737 D SystemUpdateService: onCreate
08-30 17:40:44.329  1737  1737 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 17:40:44.338  1737  1737 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 17:40:44.340  1737  2419 I iu.UploadsManager: num queued entries: 0
,08-30 17:40:44.342  3523  3523 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 17:40:44.342  3523  3523 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 17:40:44.343  3523  3523 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-30 17:40:44.350  1737  1737 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 17:40:44.351  1737  1737 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 17:40:44.353  3998  3998 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:44.362  3998  3998 D SprintDMHelper: simOperator: 
08-30 17:40:44.362  3998  3998 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 17:40:44.375  1737  2419 I iu.UploadsManager: num updated entries: 0
,08-30 17:40:44.388   374   870 E Netd    : netlink response contains error (No such file or directory)
08-30 17:40:44.389   872  1307 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-30 17:40:44.393   872  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 17:40:44.396  3931  4140 I Babel   : connection state changed from CONNECTED to DISCONNECTED
08-30 17:40:44.397  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:44.397  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:44.397  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:44.397  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:40:44.397  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:44.397  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:44.397  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:44.397  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:44.397  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:40:44.397  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:44.397  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:40:44.398  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:44.398  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:44.398  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:44.398  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:40:44.398  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:44.398  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:44.398  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:44.398  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:44.398  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:40:44.398  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:44.398  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:40:44.400  2087  2300 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:40:44.401   872  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-30 17:40:44.407  1737  4136 I SystemUpdateService: active receiver: enabled
,08-30 17:40:44.416  1737  2419 I iu.SyncManager: NEXT; no task
,08-30 17:40:44.417  1737  4136 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 17:40:44.419  1737  4136 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-30 17:40:44.419  1737  4136 I SystemUpdateService: now status is 0 (complete)
,08-30 17:40:44.419  1737  4136 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 17:40:44.420  1737  4136 I SystemUpdateService: file has been verified
08-30 17:40:44.420  1737  4136 I SystemUpdateService: OTA package size = 12249756
,08-30 17:40:44.426  1737  4136 I SystemUpdateService: showing system update notification
,08-30 17:40:44.435  1737  1737 D SystemUpdateService: onDestroy
,08-30 17:40:47.191   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4adb6db:true
,08-30 17:40:47.192  3984  3984 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 17:40:47.197  3984  3984 I bt_bluedroid: init
,08-30 17:40:47.198  3984  4143 I BluetoothAdapterState: Entering OffState
,08-30 17:40:47.203  3984  4144 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 17:40:47.204  3984  4144 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 17:40:47.204  3984  4144 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 17:40:47.204  3984  4144 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 17:40:47.207  3984  3984 I bt_bluedroid: get_profile_interface socket
,08-30 17:40:47.209  3984  3984 I bt_bluedroid: get_profile_interface sdp
,08-30 17:40:47.212  3984  3994 I bt_bluedroid: config_hci_snoop_log
,08-30 17:40:47.212  3984  4147 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-30 17:40:47.214   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 17:40:47.215  3984  4147 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 17:40:47.220  3984  4143 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 17:40:47.221  3984  4143 D BluetoothAdapterProperties: Setting state to 14
,08-30 17:40:47.221  3984  4143 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 17:40:47.226  3984  4143 D BluetoothBondStateMachine: make
,08-30 17:40:47.231  3984  4148 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 17:40:47.237  3984  3984 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-30 17:40:47.237  3984  4143 I BluetoothAdapterState: Entering PendingCommandState
,08-30 17:40:47.240  3984  3984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
,08-30 17:40:47.241  3984  3984 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 17:40:47.241  3984  3984 D BtGatt.GattService: Received start request. Starting profile...
08-30 17:40:47.242  3984  3984 D BtGatt.GattService: start()
,08-30 17:40:47.242  3984  3984 I bt_bluedroid: get_profile_interface gatt
08-30 17:40:47.243  3984  3984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
,08-30 17:40:47.243  3984  3984 D BtGatt.AdvertiseManager: advertise manager created
,08-30 17:40:47.252  3984  3984 V BluetoothAdapterState: isTurningOff()=false
08-30 17:40:47.252  3984  3984 V BluetoothAdapterState: isTurningOn()=false
08-30 17:40:47.253  3984  3984 V BluetoothAdapterState: isBleTurningOn()=true
08-30 17:40:47.253  3984  3984 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:47.253  3984  4143 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 17:40:47.253  3984  4143 I bt_bluedroid: enable
08-30 17:40:47.253  3984  4144 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 17:40:47.254  3984  4144 I bt_hci  : start_up
,08-30 17:40:47.263  3984  4144 I bt_vendor: alloc value 0xb39e9189
08-30 17:40:47.264  3984  4144 I bt_vendor: init
,08-30 17:40:47.264  3984  4144 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 17:40:47.264  3984  4144 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 17:40:47.373  3984  4144 D bt_hci  : start_up starting async portion
08-30 17:40:47.373  3984  4151 I bt_hci  : event_finish_startup
08-30 17:40:47.374  3984  4151 I bt_hci_h4: hal_open
08-30 17:40:47.374  3984  4151 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 17:40:47.380  3984  4151 I bt_userial_vendor: device fd = 51 open
,08-30 17:40:47.415  3984  4151 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 17:40:47.447  3984  4151 D bt_hwcfg: Chipset BCM4354A2
,08-30 17:40:47.447  3984  4151 D bt_hwcfg: Target name = [BCM4354A2]
08-30 17:40:47.447  3984  4151 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 17:40:48.114  3984  4151 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 17:40:48.116  3984  4151 D bt_hwcfg: Settlement delay -- 100 ms
08-30 17:40:48.116  3984  4151 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 17:40:48.233  3984  4151 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 17:40:48.235  3984  4151 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 17:40:48.264  3984  4151 I bt_hwcfg: vendor lib fwcfg completed
,08-30 17:40:48.264  3984  4151 I bt_vendor: firmware callback
08-30 17:40:48.264  3984  4151 I bt_hci  : firmware_config_callback
,08-30 17:40:48.275  3984  4153 I bt_btu  : btu_task pending for preload complete event
,08-30 17:40:48.275  3984  4153 I bt_btu_task: Bluetooth chip preload is complete
,08-30 17:40:48.276  3984  4153 I bt_btu  : btu_task received preload complete event
,08-30 17:40:48.285  3984  4153 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 17:40:48.286  3984  4153 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 17:40:48.286  3984  4153 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 17:40:48.286  3984  4153 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 17:40:48.287  3984  4153 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 17:40:48.287  3984  4153 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 17:40:48.287  3984  4153 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-30 17:40:48.287  3984  4153 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 17:40:48.288  3984  4153 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 17:40:48.288  3984  4153 I         : BTE_InitTraceLevels -- TRC_PAN
,08-30 17:40:48.288  3984  4153 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 17:40:48.288  3984  4153 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 17:40:48.289  3984  4153 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 17:40:48.289  3984  4153 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-30 17:40:48.289  3984  4153 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 17:40:48.425  3984  4153 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3966d9d
,08-30 17:40:48.426  3984  4153 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3966d9d 
,08-30 17:40:48.436  3984  4147 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 17:40:48.438  3984  4147 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 17:40:48.438  3984  4147 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-30 17:40:48.441  3984  4147 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 17:40:48.444  3984  4147 D BluetoothAdapterProperties: Scan Mode:20
,08-30 17:40:48.445  3984  4147 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 17:40:48.447  3984  4147 D bt_hci  : do_postload posting postload work item
08-30 17:40:48.447  3984  4151 I bt_hci  : event_postload
,08-30 17:40:48.447  3984  4151 I bt_vendor: sco_config_cb
08-30 17:40:48.448  3984  4151 I bt_hci  : sco_config_callback postload finished.
,08-30 17:40:48.449  3984  4147 D bt_bte_conf: Device ID record 1 : primary
,08-30 17:40:48.450  3984  4147 D bt_bte_conf:   vendorId            = 000f
08-30 17:40:48.450  3984  4147 D bt_bte_conf:   vendorIdSource      = 0001
,08-30 17:40:48.450  3984  4147 D bt_bte_conf:   product             = 1200
08-30 17:40:48.450  3984  4147 D bt_bte_conf:   version             = 1436
08-30 17:40:48.450  3984  4147 D bt_bte_conf:   clientExecutableURL = 
08-30 17:40:48.451  3984  4147 D bt_bte_conf:   serviceDescription  = 
,08-30 17:40:48.451  3984  4147 D bt_bte_conf:   documentationURL    = 
08-30 17:40:48.451  3984  4147 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 17:40:48.452  3984  4144 D bt_stack_manager: event_start_up_stack finished
08-30 17:40:48.453  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:48.453  3984  4143 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 17:40:48.454  3984  4143 D BluetoothAdapterProperties: Setting state to 15
08-30 17:40:48.454  3984  4143 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 17:40:48.455  3984  4143 I BluetoothAdapterState: Entering BleOnState
,08-30 17:40:48.458  3984  4151 I bt_vendor: low_power_mode_cb
08-30 17:40:48.461  3984  4143 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-30 17:40:48.461  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:48.461  3984  4143 D BluetoothAdapterProperties: Setting state to 11
08-30 17:40:48.461  3984  4143 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-30 17:40:48.471  3984  3984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
08-30 17:40:48.472  3984  3984 D HeadsetService: Received start request. Starting profile...
,08-30 17:40:48.474  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:48.476  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:48.480  3984  3984 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 17:40:48.480  3984  3984 D HeadsetStateMachine: make
08-30 17:40:48.487  3984  4143 I BluetoothAdapterState: Entering PendingCommandState
,08-30 17:40:48.492  3984  3984 D HeadsetStateMachine: max_hf_connections = 1,
08-30 17:40:48.492  3984  3984 I bt_bluedroid: get_profile_interface handsfree
08-30 17:40:48.492  3984  4147 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-30 17:40:48.493  3984  4147 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-30 17:40:48.498  3984  3984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
,08-30 17:40:48.499  3984  3984 D A2dpService: Received start request. Starting profile...
08-30 17:40:48.499  3984  3984 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 17:40:48.500  3984  3984 I bt_bluedroid: get_profile_interface avrcp
,08-30 17:40:48.507  3984  3984 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 17:40:48.507  3984  3984 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 17:40:48.507  3984  3984 D A2dpStateMachine: make
,08-30 17:40:48.509  3984  3984 I bt_bluedroid: get_profile_interface a2dp
,08-30 17:40:48.511  3984  4147 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 17:40:48.514  3984  4162 D A2dpStateMachine: Enter Disconnected: -2
,08-30 17:40:48.516  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:40:48.517  3984  3984 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 17:40:48.519  3984  3984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
,08-30 17:40:48.520  3881  3881 D BluetoothInputDevice: Proxy object connected
,08-30 17:40:48.521  3881  3881 D HidProfile: Bluetooth service connected
08-30 17:40:48.521  3984  3984 D HidService: Received start request. Starting profile...
08-30 17:40:48.521  3984  3984 I bt_bluedroid: get_profile_interface hidhost
,08-30 17:40:48.521  3984  3984 D HidService: setHidService(): set to: null
08-30 17:40:48.521  3984  4147 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39483e5
08-30 17:40:48.521  3984  4147 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 17:40:48.522  3984  3984 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 17:40:48.523  3984  3984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
08-30 17:40:48.524  3984  3984 D HealthService: Received start request. Starting profile...
,08-30 17:40:48.526  3984  3984 I bt_bluedroid: get_profile_interface health
,08-30 17:40:48.526  3984  3984 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 17:40:48.527  3984  3984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
,08-30 17:40:48.528  3984  3984 D PanService: Received start request. Starting profile...
,08-30 17:40:48.529  3881  3881 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:40:48.529  3984  3984 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 17:40:48.529  3984  3984 I bt_bluedroid: get_profile_interface pan
08-30 17:40:48.529  3881  3881 D PanProfile: Bluetooth service connected
,08-30 17:40:48.530  3984  4147 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 17:40:48.532  3984  3984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
,08-30 17:40:48.533  3984  3984 D BluetoothMapService: Received start request. Starting profile...
08-30 17:40:48.533  3984  3984 D BluetoothMapService: start()
,08-30 17:40:48.536  3984  3984 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 17:40:48.536  3984  3984 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 17:40:48.537  3984  3984 D BluetoothMapAppObserver: createReceiver()
,08-30 17:40:48.538  3984  3984 D BluetoothMapAppObserver: initObservers()
,08-30 17:40:48.538  3984  3984 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 17:40:48.541  3881  3881 D BluetoothMap: Proxy object connected
,08-30 17:40:48.542  3881  3881 D MapProfile: Bluetooth service connected
,08-30 17:40:48.542  3881  3881 D BluetoothMap: getConnectedDevices()
,08-30 17:40:48.543  3881  3881 D BluetoothMap: Bluetooth is Not enabled
,08-30 17:40:48.550  3984  3984 V BluetoothAdapterState: isTurningOff()=false
,08-30 17:40:48.550  3984  3984 V BluetoothAdapterState: isTurningOn()=true
08-30 17:40:48.550  3984  3984 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 17:40:48.550  3984  3984 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 17:40:48.553  3984  4160 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 17:40:48.554  3984  3984 V BluetoothAdapterState: isTurningOff()=false
08-30 17:40:48.554  3984  3984 V BluetoothAdapterState: isTurningOn()=true
08-30 17:40:48.554  3984  3984 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:48.554  3984  3984 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:48.555  3984  3984 V BluetoothAdapterState: isTurningOff()=false
,08-30 17:40:48.555  3984  3984 V BluetoothAdapterState: isTurningOn()=true
08-30 17:40:48.555  3984  3984 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 17:40:48.555  3984  3984 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:48.556  3984  3984 V BluetoothAdapterState: isTurningOff()=false
08-30 17:40:48.556  3984  3984 V BluetoothAdapterState: isTurningOn()=true
,08-30 17:40:48.556  3984  3984 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:48.556  3984  3984 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 17:40:48.556  3984  3984 V BluetoothAdapterState: isTurningOff()=false
08-30 17:40:48.556  3984  3984 V BluetoothAdapterState: isTurningOn()=true
08-30 17:40:48.556  3984  3984 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 17:40:48.557  3984  3984 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:48.557  3984  3984 V BluetoothAdapterState: isTurningOff()=false
,08-30 17:40:48.557  3984  3984 V BluetoothAdapterState: isTurningOn()=true
08-30 17:40:48.557  3984  3984 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 17:40:48.557  3984  3984 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:48.557  3984  4143 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 17:40:48.558  3984  4143 D BluetoothAdapterProperties: ScanMode =  20
,08-30 17:40:48.558  3984  4143 D BluetoothAdapterProperties: State =  11
08-30 17:40:48.561  3984  4147 D BluetoothAdapterProperties: Scan Mode:21
,08-30 17:40:48.562  3984  4147 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 17:40:48.562  3984  4143 D BluetoothAdapterProperties: Setting state to 12,
08-30 17:40:48.562  3984  4143 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 17:40:48.563   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 17:40:48.563  3984  4143 I BluetoothAdapterState: Entering OnState
,08-30 17:40:48.563  3881  3892 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 17:40:48.565   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:40:48.566  3881  3893 D BluetoothPan: onBluetoothStateChange on: true
,08-30 17:40:48.566  3812  3812 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 17:40:48.566  1362  1383 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 17:40:48.566   872   872 D BluetoothA2dp: Proxy object connected
08-30 17:40:48.566  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:48.566  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:48.566  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:48.566  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:48.566  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:48.566  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:48.566  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:48.566  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:40:48.568  1362  1362 D BluetoothMap: Proxy object connected
,08-30 17:40:48.568  1362  1362 D MapProfile: Bluetooth service connected
,08-30 17:40:48.568  1362  1362 D BluetoothMap: getConnectedDevices()
08-30 17:40:48.569  1362  1374 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:40:48.570   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 17:40:48.570  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:40:48.570  1362  1375 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 17:40:48.572  1937  2140 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:40:48.573  3881  3892 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 17:40:48.573  3984  3984 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 17:40:48.573  1362  1383 D BluetoothPan: onBluetoothStateChange on: true
,08-30 17:40:48.574  3984  3984 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-30 17:40:48.574  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:48.574  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:48.574  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:48.574  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:48.574  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:48.574  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:48.574  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:48.574  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:40:48.575  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 17:40:48.575  1362  1362 D PanProfile: Bluetooth service connected
08-30 17:40:48.575   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:40:48.575  1362  1375 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:40:48.576  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:40:48.577  3984  3984 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:40:48.577  1362  1362 D BluetoothA2dp: Proxy object connected
,08-30 17:40:48.578  3881  3893 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 17:40:48.578  1362  1383 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 17:40:48.580  1362  1362 D BluetoothInputDevice: Proxy object connected
08-30 17:40:48.580  1362  1362 D HidProfile: Bluetooth service connected
08-30 17:40:48.582   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 17:40:48.583  3984  3984 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:40:48.584  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:48.586  3881  3881 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 17:40:48.586  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:48.587  3984  3984 D ObexServerSockets: Succeed to create listening sockets 
08-30 17:40:48.587  3984  3984 D ObexServerSockets0: startAccept()
08-30 17:40:48.587  3984  3984 D ObexServerSockets0: prepareForNewConnect()
,08-30 17:40:48.591  3984  3984 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-30 17:40:48.591  3984  3984 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 17:40:48.593  3984  3984 D BluetoothMapService: onReceive
08-30 17:40:48.593  3984  3984 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:48.593  3984  3984 D BluetoothMapService: STATE_ON
08-30 17:40:48.593  3881  3881 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-30 17:40:48.593  3984  4170 D ObexServerSockets0: Accepting socket connection...
08-30 17:40:48.594  3984  4171 D ObexServerSockets0: Accepting socket connection...
,08-30 17:40:48.600  3881  3881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:40:48.602  3881  3881 D BluetoothA2dp: Proxy object connected
,08-30 17:40:48.605  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:40:48.609  3881  3881 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:40:48.614  3881  3881 D BluetoothPbap: Proxy object connected
,08-30 17:40:48.614  3881  3881 D PbapServerProfile: Bluetooth service connected
,08-30 17:40:48.619  3984  3984 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 17:40:48.619  1362  1362 D BluetoothPbap: Proxy object connected
08-30 17:40:48.619  3984  3984 D ObexServerSockets0: prepareForNewConnect()
08-30 17:40:48.619  1362  1362 D PbapServerProfile: Bluetooth service connected
,08-30 17:40:48.621  3984  4175 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:40:48.636  3984  4179 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:40:48.636  3984  4179 I BtOppRfcommListener: Accept thread started.
,08-30 17:40:48.664   872   872 D BluetoothHeadset: Proxy object connected
,08-30 17:40:48.664   872   872 D BluetoothHeadset: Proxy object connected
08-30 17:40:48.664   872   872 D BluetoothHeadset: Proxy object connected
08-30 17:40:48.664  1362  1374 D BluetoothHeadset: Proxy object connected
,08-30 17:40:48.665  1362  1362 D HeadsetProfile: Bluetooth service connected
08-30 17:40:48.665  1937  2141 D BluetoothHeadset: Proxy object connected
,08-30 17:40:48.669  1362  1383 D BluetoothHeadset: Proxy object connected
,08-30 17:40:48.669  1362  1362 D HeadsetProfile: Bluetooth service connected
,08-30 17:40:48.671   872   889 D BluetoothHeadset: Proxy object connected
,08-30 17:40:48.672  1937  1951 D BluetoothHeadset: Proxy object connected
,08-30 17:40:48.676   872   889 D BluetoothHeadset: Proxy object connected
,08-30 17:40:48.696  3881  3892 D BluetoothHeadset: Proxy object connected
,08-30 17:40:48.697  3881  3881 D HeadsetProfile: Bluetooth service connected
,08-30 17:40:50.160  3984  4143 D BluetoothAdapterState: Current state: ON, message: 23
08-30 17:40:50.160  3984  4143 D BluetoothAdapterProperties: Setting state to 13
08-30 17:40:50.161  3984  4143 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-30 17:40:50.161   872  1307 D ConnectivityService: handlePromptUnvalidated 101
,08-30 17:40:50.162  3984  4143 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 17:40:50.167  3984  4143 I BluetoothAdapterState: Entering PendingCommandState
,08-30 17:40:50.180  3984  3984 D BluetoothMapService: onReceive
08-30 17:40:50.180  3984  3984 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:40:50.181  3984  3984 D BluetoothMapService: STATE_TURNING_OFF
08-30 17:40:50.181  3984  3984 D BluetoothMapService: MAP Service closeService in
08-30 17:40:50.182  3984  3984 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 17:40:50.182  3984  3984 D ObexServerSockets0: shutdown(block = true)
,08-30 17:40:50.184  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:50.185  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:50.185  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:50.185  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:50.185  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:50.185  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:50.185  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:50.185  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:50.185  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:40:50.185  3984  4170 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-30 17:40:50.186  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:50.186  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:40:50.187  3984  4147 D BluetoothAdapterProperties: Scan Mode:20
08-30 17:40:50.187  3984  4143 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 17:40:50.189  3984  3984 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 17:40:50.189  3984  4171 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 17:40:50.190  3984  3984 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 17:40:50.190  3984  4155 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 17:40:50.191  3984  3984 D HeadsetService: Received stop request...Stopping profile...
,08-30 17:40:50.192  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:50.193  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:50.193  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:50.193  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:50.193  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:50.193  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:50.193  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:50.193  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:50.193  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:40:50.194   872   872 D BluetoothHeadset: Proxy object disconnected
08-30 17:40:50.194   872   872 D BluetoothHeadset: Proxy object disconnected
08-30 17:40:50.194  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:50.194   872   872 D BluetoothHeadset: Proxy object disconnected
,08-30 17:40:50.194  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:40:50.195  3984  3984 D A2dpService: Received stop request...Stopping profile...
08-30 17:40:50.195  3984  4162 D A2dpStateMachine: Exit Disconnected: -1
08-30 17:40:50.196  1362  1375 D BluetoothHeadset: Proxy object disconnected
08-30 17:40:50.196  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:50.197  3881  3893 D BluetoothHeadset: Proxy object disconnected
,08-30 17:40:50.198  1937  1952 D BluetoothHeadset: Proxy object disconnected
08-30 17:40:50.198  3984  3984 I BtOppRfcommListener: stopping Accept Thread
08-30 17:40:50.198  3984  4179 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:40:50.199   872   872 D BluetoothA2dp: Proxy object disconnected
08-30 17:40:50.199  3984  4179 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 17:40:50.199  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:50.200  3984  3984 D HidService: Received stop request...Stopping profile...
08-30 17:40:50.200  3984  3984 D HidService: Stopping Bluetooth HidService
,08-30 17:40:50.202  3984  3984 V BluetoothAdapterState: isTurningOff()=true
08-30 17:40:50.202  3984  3984 V BluetoothAdapterState: isTurningOn()=false
08-30 17:40:50.202  3984  3984 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:50.202  3984  3984 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:50.203  3881  3881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:40:50.204  3984  3984 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 17:40:50.204  3984  4153 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 17:40:50.204  3984  4153 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:40:50.204  3984  4153 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:40:50.204  3984  4147 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 17:40:50.204  3984  4147 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-30 17:40:50.204  3984  3984 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 17:40:50.205  3984  3984 D HealthService: Received stop request...Stopping profile...
08-30 17:40:50.207  1362  1362 D HeadsetProfile: Bluetooth service disconnected
,08-30 17:40:50.208  1362  1362 D BluetoothA2dp: Proxy object disconnected
,08-30 17:40:50.208  3984  3984 V BluetoothAdapterState: isTurningOff()=true
08-30 17:40:50.208  1362  1362 D BluetoothInputDevice: Proxy object disconnected
08-30 17:40:50.208  3984  3984 V BluetoothAdapterState: isTurningOn()=false
08-30 17:40:50.208  1362  1362 D HidProfile: Bluetooth service disconnected
08-30 17:40:50.208  3984  3984 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:50.208  3984  3984 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:50.209  3984  3984 D PanService: Received stop request...Stopping profile...
,08-30 17:40:50.209  3881  3881 D HeadsetProfile: Bluetooth service disconnected
08-30 17:40:50.210  3881  3881 D BluetoothA2dp: Proxy object disconnected
08-30 17:40:50.211  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 17:40:50.211  1362  1362 D PanProfile: Bluetooth service disconnected
08-30 17:40:50.210  3881  3881 D BluetoothInputDevice: Proxy object disconnected
08-30 17:40:50.211  3881  3881 D HidProfile: Bluetooth service disconnected
08-30 17:40:50.213  3984  4153 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:40:50.213  3984  4153 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:40:50.213  3984  4153 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 17:40:50.213  3984  4153 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:40:50.213  3984  4153 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:40:50.213  3984  4153 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:40:50.214  3984  4147 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 17:40:50.214  3984  3984 D BluetoothMapService: Received stop request...Stopping profile...
08-30 17:40:50.215  3984  3984 D BluetoothMapService: stop()
08-30 17:40:50.215  3984  3984 D BluetoothMapAppObserver: deinitObservers()
,08-30 17:40:50.215  3984  3984 D BluetoothMapAppObserver: removeReceiver()
08-30 17:40:50.217  1362  1362 D BluetoothMap: Proxy object disconnected
08-30 17:40:50.217  1362  1362 D MapProfile: Bluetooth service disconnected
08-30 17:40:50.219  3984  3984 V BluetoothAdapterState: isTurningOff()=true
,08-30 17:40:50.219  3984  3984 V BluetoothAdapterState: isTurningOn()=false
08-30 17:40:50.219  3984  3984 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:50.219  3984  3984 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:50.219  3984  3984 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 17:40:50.220  3984  4147 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 17:40:50.220  3984  3984 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 17:40:50.220  3984  3984 V BluetoothAdapterState: isTurningOff()=true
08-30 17:40:50.220  3984  3984 V BluetoothAdapterState: isTurningOn()=false
08-30 17:40:50.220  3984  3984 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:50.220  3984  3984 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:50.221  3984  3984 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 17:40:50.221  3984  4147 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-30 17:40:50.221  3984  3984 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 17:40:50.222  3984  3984 V BluetoothAdapterState: isTurningOff()=true
08-30 17:40:50.222  3984  3984 V BluetoothAdapterState: isTurningOn()=false
08-30 17:40:50.222  3984  3984 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 17:40:50.222  3984  3984 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:50.222  3881  3881 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:40:50.225  3984  3984 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-30 17:40:50.225  3881  3881 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 17:40:50.225  3881  3881 D PanProfile: Bluetooth service disconnected
,08-30 17:40:50.225  3881  3881 D BluetoothMap: Proxy object disconnected
,08-30 17:40:50.225  3881  3881 D MapProfile: Bluetooth service disconnected
08-30 17:40:50.225  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 17:40:50.226  3984  3984 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 17:40:50.226  3984  3984 D BluetoothMapService: MAP Service closeService in
08-30 17:40:50.226  3984  3984 V BluetoothAdapterState: isTurningOff()=true
08-30 17:40:50.226  3984  3984 V BluetoothAdapterState: isTurningOn()=false
,08-30 17:40:50.227  3984  3984 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:50.227  3984  3984 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:50.227  3984  4143 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 17:40:50.227  3984  4143 D BluetoothAdapterProperties: Setting state to 15
08-30 17:40:50.227  3984  4143 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 17:40:50.227  3984  4143 I BluetoothAdapterState: Entering BleOnState
08-30 17:40:50.227   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:40:50.228  3984  3984 D BluetoothMapService: cleanup()
,08-30 17:40:50.228  3984  3984 D BluetoothMapService: MAP Service closeService in
08-30 17:40:50.228  3881  3893 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 17:40:50.229   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 17:40:50.230  3881  4182 D BluetoothPan: onBluetoothStateChange on: false
08-30 17:40:50.230  1362  1374 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 17:40:50.232  1362  1362 D BluetoothPbap: Proxy object disconnected
08-30 17:40:50.232  1362  1362 D PbapServerProfile: Bluetooth service disconnected
,08-30 17:40:50.235  1362  1375 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 17:40:50.236  3881  3892 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 17:40:50.236   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:40:50.236  1362  1383 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 17:40:50.237  1937  2140 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:40:50.238  3881  3893 D BluetoothMap: onBluetoothStateChange: up=false
08-30 17:40:50.238  1362  4184 D BluetoothPan: onBluetoothStateChange on: false
08-30 17:40:50.238   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 17:40:50.239  1362  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 17:40:50.239  3881  4182 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 17:40:50.239  1362  1375 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 17:40:50.240  3881  3892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 17:40:50.240  3984  4143 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 17:40:50.240  3984  4143 D BluetoothAdapterProperties: Setting state to 16
08-30 17:40:50.240  3984  4143 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-30 17:40:50.241  3984  4143 D BluetoothAdapterProperties: onBleDisable
,08-30 17:40:50.241  3984  4143 I BluetoothAdapterState: Entering PendingCommandState
08-30 17:40:50.242  3984  4144 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-30 17:40:50.242  3984  4153 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-30 17:40:50.243  3984  4153 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 17:40:50.243  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:50.244  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:50.245  3984  4147 D BluetoothAdapterProperties: Scan Mode:20
,08-30 17:40:50.246  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:50.246  3881  3881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 ,
08-30 17:40:50.247  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:50.250  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:40:50.254  3881  3881 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:40:50.443  3984  4147 I bt_hci  : shut_down
,08-30 17:40:50.443  3984  4151 D bt_hwcfg: hw_epilog_process
,08-30 17:40:50.454  3984  4151 I bt_vendor: low_power_mode_cb
,08-30 17:40:50.482  3984  4151 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-30 17:40:50.482  3984  4151 I bt_vendor: epilog_cb
08-30 17:40:50.483  3984  4151 I bt_hci  : epilog_finished_callback
,08-30 17:40:50.490  3984  4147 I bt_hci_h4: hal_close
,08-30 17:40:50.492  3984  4147 I bt_userial_vendor: device fd = 51 close
,08-30 17:40:50.617  3984  4144 D bt_stack_manager: event_shut_down_stack finished.
,08-30 17:40:50.618  3984  4143 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 17:40:50.624  3984  3984 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 17:40:50.625  3984  4143 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 17:40:50.626  3984  3984 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 17:40:50.626  3984  3984 D BtGatt.GattService: stop()
,08-30 17:40:50.627  3984  3984 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 17:40:50.632  3984  3984 V BluetoothAdapterState: isTurningOff()=false
,08-30 17:40:50.632  3984  3984 V BluetoothAdapterState: isTurningOn()=false
,08-30 17:40:50.633  3984  3984 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:50.633  3984  3984 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 17:40:50.633  3984  4143 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25,
,08-30 17:40:50.635  3984  4143 D BluetoothAdapterProperties: Setting state to 10
08-30 17:40:50.635  3984  4143 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-30 17:40:50.637  3984  4143 I BluetoothAdapterState: Entering OffState
08-30 17:40:50.639   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 17:40:50.660  3984  3984 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-30 17:40:50.661  3984  3984 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 17:40:50.661  3984  4144 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 17:40:50.664  3984  4144 D bt_stack_manager: event_clean_up_stack finished.
08-30 17:40:50.664  3984  3984 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 17:40:50.667  3984  3984 I art     : System.exit called, status: 0
08-30 17:40:50.667  3984  3984 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 17:40:50.718   872   883 I ActivityManager: Process com.android.bluetooth (pid 3984) has died
,08-30 17:40:53.157  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:40:53.158  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:54.453   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-30 17:40:54.460  1871  1871 I Keyboard.Facilitator: onFinishInput()
,08-30 17:40:54.467   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 17:40:54.467   872   892 I Adreno  : Build Date                       : 10/20/15
08-30 17:40:54.467   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 17:40:54.467   872   892 I Adreno  : Local Branch                     : M14
08-30 17:40:54.467   872   892 I Adreno  : Remote Branch                    : 
08-30 17:40:54.467   872   892 I Adreno  : Remote Branch                    : 
08-30 17:40:54.467   872   892 I Adreno  : Reconstruct Branch               : 
,08-30 17:40:54.505   281   350 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (287 us)
,08-30 17:40:55.122  3812  3812 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 17:40:55.122  3812  3812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 17:40:55.182   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-30 17:40:55.186  3812  3812 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c36afa Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@20df474, 16908290=android.view.AbsSavedState$1@20df474}, android:focusedViewId=100}]}]
,08-30 17:40:55.186  3812  3812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 17:40:55.187  3812  3812 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 17:40:55.187  3812  3812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-30 17:40:55.188   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-30 17:40:55.194   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,08-30 17:40:55.194   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-30 17:40:55.195   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-30 17:40:55.426   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 17:40:55.430   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-30 17:40:55.435   872  1331 D SurfaceControl: Excessive delay in setPowerMode(): 241ms
,08-30 17:40:55.436   872   892 I DreamManagerService: Entering dreamland.
08-30 17:40:55.438   872   892 I PowerManagerService: Dozing...
08-30 17:40:55.439   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-30 17:40:55.491   378  1278 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-30 17:40:55.492   378  1278 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-30 17:40:55.495   872  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 17:40:55.500   872  1305 E native  : do suspend false
,08-30 17:40:55.518  1924  4193 D NfcService: Discovery configuration equal, not updating.
,08-30 17:40:55.548   872  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 17:40:55.554   872  1305 E native  : do suspend true
,08-30 17:40:55.628   378  1313 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-30 17:40:55.628   378  1313 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-30 17:40:56.165  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:40:56.166  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6249d9d added. We now have 6 listener(s)
08-30 17:40:56.166  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:40:56.170  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:40:56.170  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a0b2212 added. We now have 7 listener(s)
,08-30 17:40:56.170  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:40:56.172  3812  3863 I System.out: IsBluetoothEnabled
,08-30 17:40:56.184  3812  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:56.230   872   889 I ActivityManager: Start proc 4199:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 17:40:56.397  4199  4199 D AdapterServiceConfig: Adding HeadsetService
08-30 17:40:56.397  4199  4199 D AdapterServiceConfig: Adding A2dpService
,08-30 17:40:56.397  4199  4199 D AdapterServiceConfig: Adding HidService
08-30 17:40:56.397  4199  4199 D AdapterServiceConfig: Adding HealthService
08-30 17:40:56.398  4199  4199 D AdapterServiceConfig: Adding PanService
08-30 17:40:56.398  4199  4199 D AdapterServiceConfig: Adding GattService
08-30 17:40:56.398  4199  4199 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 17:40:56.414  4199  4199 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 17:40:56.414   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ec7de13:true
,08-30 17:40:56.421  4199  4199 I bt_bluedroid: init
,08-30 17:40:56.421  4199  4211 I BluetoothAdapterState: Entering OffState
,08-30 17:40:56.426  4199  4212 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 17:40:56.426  4199  4212 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-30 17:40:56.426  4199  4212 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 17:40:56.426  4199  4212 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 17:40:56.427  4199  4199 I bt_bluedroid: get_profile_interface socket
,08-30 17:40:56.429  4199  4199 I bt_bluedroid: get_profile_interface sdp
,08-30 17:40:56.433  4199  4215 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 17:40:56.436  4199  4215 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 17:40:56.436  4199  4209 I bt_bluedroid: config_hci_snoop_log
,08-30 17:40:56.439   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 17:40:56.446  4199  4211 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 17:40:56.447  4199  4211 D BluetoothAdapterProperties: Setting state to 14
08-30 17:40:56.447  4199  4211 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 17:40:56.451  4199  4211 D BluetoothBondStateMachine: make
,08-30 17:40:56.455  4199  4217 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 17:40:56.464  4199  4211 I BluetoothAdapterState: Entering PendingCommandState
,08-30 17:40:56.465  4199  4199 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 17:40:56.473  4199  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
,08-30 17:40:56.474  4199  4199 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 17:40:56.476  4199  4199 D BtGatt.GattService: Received start request. Starting profile...
,08-30 17:40:56.476  4199  4199 D BtGatt.GattService: start()
08-30 17:40:56.476  4199  4199 I bt_bluedroid: get_profile_interface gatt
,08-30 17:40:56.477  4199  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
08-30 17:40:56.477  4199  4199 D BtGatt.AdvertiseManager: advertise manager created
,08-30 17:40:56.487  4199  4199 V BluetoothAdapterState: isTurningOff()=false
08-30 17:40:56.487  4199  4199 V BluetoothAdapterState: isTurningOn()=false
,08-30 17:40:56.487  4199  4199 V BluetoothAdapterState: isBleTurningOn()=true
08-30 17:40:56.487  4199  4199 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 17:40:56.488  4199  4211 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-30 17:40:56.488  4199  4211 I bt_bluedroid: enable
08-30 17:40:56.489  4199  4212 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-30 17:40:56.489  4199  4212 I bt_hci  : start_up
,08-30 17:40:56.512  4199  4212 I bt_vendor: alloc value 0xb3a44189
,08-30 17:40:56.512  4199  4212 I bt_vendor: init
08-30 17:40:56.512  4199  4212 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-30 17:40:56.513  4199  4212 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 17:40:56.620  4199  4212 D bt_hci  : start_up starting async portion
,08-30 17:40:56.620  4199  4220 I bt_hci  : event_finish_startup
08-30 17:40:56.621  4199  4220 I bt_hci_h4: hal_open
,08-30 17:40:56.621  4199  4220 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 17:40:56.630  4199  4220 I bt_userial_vendor: device fd = 51 open
,08-30 17:40:56.661  4199  4220 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 17:40:56.693  4199  4220 D bt_hwcfg: Chipset BCM4354A2
08-30 17:40:56.694  4199  4220 D bt_hwcfg: Target name = [BCM4354A2]
,08-30 17:40:56.694  4199  4220 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 17:40:57.361  4199  4220 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 17:40:57.362  4199  4220 D bt_hwcfg: Settlement delay -- 100 ms
08-30 17:40:57.362  4199  4220 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 17:40:57.479  4199  4220 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 17:40:57.480  4199  4220 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 17:40:57.510  4199  4220 I bt_hwcfg: vendor lib fwcfg completed
,08-30 17:40:57.511  4199  4220 I bt_vendor: firmware callback
08-30 17:40:57.511  4199  4220 I bt_hci  : firmware_config_callback
,08-30 17:40:57.522  4199  4222 I bt_btu  : btu_task pending for preload complete event
,08-30 17:40:57.522  4199  4222 I bt_btu_task: Bluetooth chip preload is complete
08-30 17:40:57.523  4199  4222 I bt_btu  : btu_task received preload complete event
,08-30 17:40:57.530  4199  4222 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 17:40:57.530  4199  4222 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 17:40:57.530  4199  4222 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 17:40:57.530  4199  4222 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 17:40:57.530  4199  4222 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 17:40:57.530  4199  4222 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 17:40:57.531  4199  4222 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-30 17:40:57.531  4199  4222 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 17:40:57.531  4199  4222 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 17:40:57.531  4199  4222 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 17:40:57.531  4199  4222 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 17:40:57.531  4199  4222 I         : BTE_InitTraceLevels -- TRC_GATT
,08-30 17:40:57.531  4199  4222 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 17:40:57.531  4199  4222 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 17:40:57.531  4199  4222 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 17:40:57.661  4199  4222 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c1d9d
,08-30 17:40:57.662  4199  4222 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c1d9d 
,08-30 17:40:57.669  4199  4215 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 17:40:57.673  4199  4215 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 17:40:57.674  4199  4215 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 17:40:57.679  4199  4215 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 17:40:57.682  4199  4215 D BluetoothAdapterProperties: Scan Mode:20
,08-30 17:40:57.683  4199  4215 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 17:40:57.684  4199  4215 D bt_hci  : do_postload posting postload work item
,08-30 17:40:57.684  4199  4220 I bt_hci  : event_postload
08-30 17:40:57.684  4199  4220 I bt_vendor: sco_config_cb
08-30 17:40:57.684  4199  4220 I bt_hci  : sco_config_callback postload finished.
,08-30 17:40:57.688  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:57.689  4199  4215 D bt_bte_conf: Device ID record 1 : primary
08-30 17:40:57.689  4199  4215 D bt_bte_conf:   vendorId            = 000f
08-30 17:40:57.689  4199  4215 D bt_bte_conf:   vendorIdSource      = 0001
08-30 17:40:57.690  4199  4215 D bt_bte_conf:   product             = 1200
08-30 17:40:57.690  4199  4215 D bt_bte_conf:   version             = 1436
,08-30 17:40:57.690  4199  4215 D bt_bte_conf:   clientExecutableURL = 
,08-30 17:40:57.690  4199  4215 D bt_bte_conf:   serviceDescription  = 
,08-30 17:40:57.690  4199  4215 D bt_bte_conf:   documentationURL    = 
,08-30 17:40:57.691  4199  4215 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 17:40:57.691  4199  4212 D bt_stack_manager: event_start_up_stack finished
08-30 17:40:57.692  4199  4211 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 17:40:57.693  4199  4211 D BluetoothAdapterProperties: Setting state to 15
08-30 17:40:57.693  4199  4211 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-30 17:40:57.694  4199  4211 I BluetoothAdapterState: Entering BleOnState
08-30 17:40:57.697  4199  4220 I bt_vendor: low_power_mode_cb
08-30 17:40:57.699  4199  4211 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 17:40:57.700  4199  4211 D BluetoothAdapterProperties: Setting state to 11
08-30 17:40:57.700  4199  4211 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-30 17:40:57.712  4199  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
,08-30 17:40:57.719  4199  4199 D HeadsetService: Received start request. Starting profile...
,08-30 17:40:57.720  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:57.722  4199  4199 I BluetoothHeadsetServiceJni: classInitNative: succeeds,
08-30 17:40:57.723  4199  4199 D HeadsetStateMachine: make
,08-30 17:40:57.733  4199  4199 D HeadsetStateMachine: max_hf_connections = 1
,08-30 17:40:57.733  4199  4199 I bt_bluedroid: get_profile_interface handsfree
,08-30 17:40:57.733  4199  4215 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 17:40:57.733  4199  4215 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-30 17:40:57.735  4199  4211 I BluetoothAdapterState: Entering PendingCommandState,
08-30 17:40:57.736  4199  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
08-30 17:40:57.738  4199  4199 D A2dpService: Received start request. Starting profile...
,08-30 17:40:57.739  4199  4199 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 17:40:57.739  4199  4199 I bt_bluedroid: get_profile_interface avrcp
,08-30 17:40:57.749  4199  4199 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 17:40:57.750  4199  4199 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 17:40:57.750  4199  4199 D A2dpStateMachine: make
,08-30 17:40:57.752  4199  4199 I bt_bluedroid: get_profile_interface a2dp
,08-30 17:40:57.753  4199  4215 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 17:40:57.756  4199  4230 D A2dpStateMachine: Enter Disconnected: -2
,08-30 17:40:57.759  4199  4199 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 17:40:57.759  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:40:57.760  4199  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
08-30 17:40:57.762  4199  4199 D HidService: Received start request. Starting profile...
,08-30 17:40:57.762  4199  4199 I bt_bluedroid: get_profile_interface hidhost
,08-30 17:40:57.762  4199  4199 D HidService: setHidService(): set to: null
08-30 17:40:57.762  4199  4215 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a33e5
08-30 17:40:57.762  4199  4215 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-30 17:40:57.763  4199  4199 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 17:40:57.764  4199  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
,08-30 17:40:57.767  4199  4199 D HealthService: Received start request. Starting profile...
,08-30 17:40:57.769  4199  4199 I bt_bluedroid: get_profile_interface health
,08-30 17:40:57.771  4199  4199 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 17:40:57.772  4199  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
,08-30 17:40:57.774  4199  4199 D PanService: Received start request. Starting profile...
,08-30 17:40:57.775  4199  4199 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 17:40:57.775  4199  4199 I bt_bluedroid: get_profile_interface pan
,08-30 17:40:57.776  4199  4215 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 17:40:57.780  4199  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
,08-30 17:40:57.780  4199  4199 D BluetoothMapService: Received start request. Starting profile...
08-30 17:40:57.780  4199  4199 D BluetoothMapService: start()
,08-30 17:40:57.783  4199  4199 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 17:40:57.784  4199  4199 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 17:40:57.784  4199  4199 D BluetoothMapAppObserver: createReceiver()
,08-30 17:40:57.785  4199  4199 D BluetoothMapAppObserver: initObservers()
08-30 17:40:57.785  4199  4199 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 17:40:57.791  4199  4199 V BluetoothAdapterState: isTurningOff()=false
,08-30 17:40:57.791  4199  4199 V BluetoothAdapterState: isTurningOn()=true
08-30 17:40:57.791  4199  4199 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:57.791  4199  4199 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 17:40:57.793  4199  4199 V BluetoothAdapterState: isTurningOff()=false
08-30 17:40:57.793  4199  4199 V BluetoothAdapterState: isTurningOn()=true
08-30 17:40:57.793  4199  4199 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:57.793  4199  4199 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:57.794  4199  4228 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 17:40:57.794  4199  4199 V BluetoothAdapterState: isTurningOff()=false
08-30 17:40:57.794  4199  4199 V BluetoothAdapterState: isTurningOn()=true
08-30 17:40:57.794  4199  4199 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:57.795  4199  4199 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:57.795  4199  4199 V BluetoothAdapterState: isTurningOff()=false
08-30 17:40:57.795  4199  4199 V BluetoothAdapterState: isTurningOn()=true
08-30 17:40:57.795  4199  4199 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:57.795  4199  4199 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 17:40:57.795  4199  4199 V BluetoothAdapterState: isTurningOff()=false
,08-30 17:40:57.795  4199  4199 V BluetoothAdapterState: isTurningOn()=true
08-30 17:40:57.795  4199  4199 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:57.795  4199  4199 V BluetoothAdapterState: isBleTurningOff()=false
08-30 17:40:57.796  4199  4199 V BluetoothAdapterState: isTurningOff()=false
08-30 17:40:57.796  4199  4199 V BluetoothAdapterState: isTurningOn()=true
08-30 17:40:57.796  4199  4199 V BluetoothAdapterState: isBleTurningOn()=false
08-30 17:40:57.796  4199  4199 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 17:40:57.796  4199  4211 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 17:40:57.797  4199  4211 D BluetoothAdapterProperties: ScanMode =  20
08-30 17:40:57.797  4199  4211 D BluetoothAdapterProperties: State =  11
,08-30 17:40:57.797  4199  4211 D BluetoothAdapterProperties: Setting state to 12
08-30 17:40:57.797  4199  4211 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 17:40:57.798  4199  4211 I BluetoothAdapterState: Entering OnState
,08-30 17:40:57.798   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:40:57.799  4199  4215 D BluetoothAdapterProperties: Scan Mode:21
08-30 17:40:57.799  4199  4215 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 17:40:57.802  3881  3892 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 17:40:57.803  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:57.803  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:57.803  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:57.803  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:57.803  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:57.803  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:57.803  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:57.803  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:40:57.805  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:40:57.805   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:40:57.807  3881  3893 D BluetoothPan: onBluetoothStateChange on: true
08-30 17:40:57.808   872   872 D BluetoothA2dp: Proxy object connected
,08-30 17:40:57.810  1362  1374 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 17:40:57.812  4199  4199 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 17:40:57.813  4199  4199 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-30 17:40:57.815  4199  4199 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:40:57.815  1362  1383 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:40:57.816  3881  3892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 17:40:57.817   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 17:40:57.817  4199  4199 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:40:57.818  1362  1375 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 17:40:57.818  3881  3881 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:40:57.818  3881  3881 D PanProfile: Bluetooth service connected
,08-30 17:40:57.819  4199  4199 D ObexServerSockets: Succeed to create listening sockets 
,08-30 17:40:57.819  4199  4199 D ObexServerSockets0: startAccept()
,08-30 17:40:57.819  4199  4199 D ObexServerSockets0: prepareForNewConnect()
08-30 17:40:57.822  4199  4199 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 17:40:57.822  4199  4199 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 17:40:57.823  1937  1952 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 17:40:57.824  3881  3893 D BluetoothMap: onBluetoothStateChange: up=true
08-30 17:40:57.826  1362  1362 D BluetoothMap: Proxy object connected
08-30 17:40:57.826  1362  1362 D MapProfile: Bluetooth service connected
08-30 17:40:57.826  1362  1362 D BluetoothMap: getConnectedDevices()
,08-30 17:40:57.826  4199  4235 D ObexServerSockets0: Accepting socket connection...
08-30 17:40:57.826  4199  4236 D ObexServerSockets0: Accepting socket connection...
08-30 17:40:57.828  1362  1374 D BluetoothPan: onBluetoothStateChange on: true
,08-30 17:40:57.830  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:40:57.830  1362  1362 D PanProfile: Bluetooth service connected
08-30 17:40:57.830   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:40:57.831  1362  1375 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:40:57.831  3881  3881 D BluetoothMap: Proxy object connected
08-30 17:40:57.831  3881  3881 D MapProfile: Bluetooth service connected
08-30 17:40:57.832  3881  3881 D BluetoothMap: getConnectedDevices()
08-30 17:40:57.833  1362  1362 D BluetoothA2dp: Proxy object connected
,08-30 17:40:57.834  3881  3892 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 17:40:57.836  1362  1383 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 17:40:57.837  3881  3881 D BluetoothInputDevice: Proxy object connected
,08-30 17:40:57.837  3881  3881 D HidProfile: Bluetooth service connected
,08-30 17:40:57.839  1362  1362 D BluetoothInputDevice: Proxy object connected
08-30 17:40:57.839  1362  1362 D HidProfile: Bluetooth service connected
08-30 17:40:57.839  3881  3893 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:40:57.842  3881  3881 D BluetoothA2dp: Proxy object connected
,08-30 17:40:57.844   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 17:40:57.846  4199  4199 D BluetoothMapService: onReceive
,08-30 17:40:57.846  4199  4199 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:57.846  4199  4199 D BluetoothMapService: STATE_ON
,08-30 17:40:57.847  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:57.854  3881  3881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:40:57.863  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:40:57.873  4199  4199 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 17:40:57.873  4199  4199 D ObexServerSockets0: prepareForNewConnect()
08-30 17:40:57.874  3881  3881 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:40:57.876  3881  3881 D BluetoothPbap: Proxy object connected
,08-30 17:40:57.876  3881  3881 D PbapServerProfile: Bluetooth service connected
08-30 17:40:57.876  1362  1362 D BluetoothPbap: Proxy object connected
08-30 17:40:57.876  1362  1362 D PbapServerProfile: Bluetooth service connected
,08-30 17:40:57.888  4199  4241 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:40:57.900   872   872 D BluetoothHeadset: Proxy object connected
,08-30 17:40:57.900   872   872 D BluetoothHeadset: Proxy object connected
08-30 17:40:57.900   872   872 D BluetoothHeadset: Proxy object connected
,08-30 17:40:57.900  1362  1374 D BluetoothHeadset: Proxy object connected
,08-30 17:40:57.901  1362  1362 D HeadsetProfile: Bluetooth service connected
,08-30 17:40:57.901  4199  4245 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:40:57.901  3881  3893 D BluetoothHeadset: Proxy object connected
,08-30 17:40:57.901  1937  2140 D BluetoothHeadset: Proxy object connected
08-30 17:40:57.903  4199  4245 I BtOppRfcommListener: Accept thread started.
,08-30 17:40:57.904  3881  3881 D HeadsetProfile: Bluetooth service connected
,08-30 17:40:57.916  1362  1383 D BluetoothHeadset: Proxy object connected
,08-30 17:40:57.916  1362  1362 D HeadsetProfile: Bluetooth service connected
08-30 17:40:57.916  3881  3892 D BluetoothHeadset: Proxy object connected
,08-30 17:40:57.917  3881  3881 D HeadsetProfile: Bluetooth service connected
,08-30 17:40:57.918   872   889 D BluetoothHeadset: Proxy object connected
,08-30 17:40:57.923  1937  2141 D BluetoothHeadset: Proxy object connected
,08-30 17:40:57.930   872   889 D BluetoothHeadset: Proxy object connected
,08-30 17:40:58.205  3812  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:58.205  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:58.205  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:58.205  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:58.205  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:58.205  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:58.205  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:58.205  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:40:58.211  3812  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:40:58.214  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:40:58.214  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@70b2de3 added. We now have 8 listener(s)
,08-30 17:40:58.214  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:40:58.219   872  1969 D WifiService: setWifiEnabled: false pid=3812, uid=10000
,08-30 17:40:58.219   872  1969 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 17:40:58.228  3812  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:58.229   872   882 D WifiService: setWifiEnabled: true pid=3812, uid=10000
,08-30 17:40:58.229   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 17:40:58.240   872  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-30 17:40:58.253  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:58.253  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:58.253  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:58.253  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:58.253  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:58.253  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:58.253  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:58.253  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:40:58.261   872  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-30 17:40:58.262   872  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 17:40:58.263   872  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 17:40:58.263   872  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 17:40:58.264   872  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-30 17:40:58.264   872  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK,
08-30 17:40:58.264   872  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-30 17:40:58.271  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:40:58.284   374   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 17:40:58.284   872  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.07 delta 1000 -> 1000
,08-30 17:40:58.285   872  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 17:40:58.285   374   870 D CommandListener: Setting iface cfg
,08-30 17:40:58.286   872  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
08-30 17:40:58.286   872  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 17:40:58.296   872  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 17:40:58.297   872  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-30 17:40:58.297   872  1305 E native  : do suspend true
,08-30 17:40:58.310   872  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 17:40:58.310   872  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:40:58.325   872  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 17:40:58.382   872  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 17:40:58.384  1454  1454 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 17:40:58.807  1454  1454 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 17:40:58.860  1454  1454 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 17:40:58.864  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 17:40:58.867   872  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 17:40:58.884   872  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 17:40:58.885   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 17:40:58.885   872  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:40:58.911   872  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:40:58.927   374   870 D CommandListener: Setting iface cfg
,08-30 17:40:58.928   872  1305 D WifiStateMachine: Start Dhcp Watchdog 3
,08-30 17:40:58.942   872  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 17:40:58.978   872  4254 D DhcpClient: Receive thread started
,08-30 17:40:59.063   872  1305 E native  : do suspend false
,08-30 17:40:59.084   872  1849 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 17:40:59.097   872  4254 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,08-30 17:40:59.098   872  1849 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,08-30 17:40:59.102   872  1849 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 17:40:59.114   872  4254 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 17:40:59.115   872  1849 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 17:40:59.120   374   870 D CommandListener: Setting iface cfg
,08-30 17:40:59.133   872  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 17:40:59.133   872  1849 D DhcpClient: Scheduling renewal in 86399s
,08-30 17:40:59.138   872  1305 E native  : do suspend true
,08-30 17:40:59.158   872  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 17:40:59.158   872  1305 D WifiConfigStore: No blacklist allowed without epno enabled
08-30 17:40:59.159   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 17:40:59.161   872  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 17:40:59.162   872  1307 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 17:40:59.211   872  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 17:40:59.211   872  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 17:40:59.212   872  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 17:40:59.213   872  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-30 17:40:59.214   872  1307 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 17:40:59.221   872  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 17:40:59.226   872  1307 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-30 17:40:59.226   872  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-30 17:40:59.227   872  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-30 17:40:59.227   872  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 17:40:59.227   872  1307 D ConnectivityService:    accepting network in place of null
08-30 17:40:59.227   872  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 17:40:59.228   872  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 17:40:59.243   872  4253 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155052, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 17:40:59.246  3812  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:59.246  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:59.246  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:59.246  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:59.246  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:59.246  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:59.246  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:59.246  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:40:59.250  3812  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:40:59.254  3812  3863 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 17:40:59.254  3812  3863 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 17:40:59.257  3812  3863 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c36afa Bundle[{}]
,08-30 17:40:59.258  3812  3863 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 17:40:59.258  3812  3863 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 17:40:59.259  3812  3863 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 17:40:59.259  3812  3863 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 17:40:59.260  3812  3863 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-30 17:40:59.260  3812  3863 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 17:40:59.261   374   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 17:40:59.267  3812  3863 I System.out: Running OutgoingSocketThread
,08-30 17:40:59.271  3812  4261 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424)
,08-30 17:40:59.273  3812  4261 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38326
,08-30 17:40:59.273  3812  4261 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 17:40:59.309   374   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 17:40:59.315   872  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 17:40:59.316   872  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:59.318   872  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 17:40:59.322   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-30 17:40:59.327   872  4251 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
08-30 17:40:59.334  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:59.334  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:59.334  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:59.334  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:59.334  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:59.334  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:59.334  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:59.334  3812  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:40:59.337  3812  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:40:59.349  1737  1737 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 17:40:59.358  1737  1737 D SystemUpdateService: onCreate
,08-30 17:40:59.362  1737  1737 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 17:40:59.370  1737  4264 I SystemUpdateService: active receiver: enabled
,08-30 17:40:59.382  1737  4264 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 17:40:59.386  1737  4264 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 17:40:59.387  1737  1737 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 17:40:59.390  1737  2419 I iu.UploadsManager: num queued entries: 0
,08-30 17:40:59.390  1737  2419 I iu.UploadsManager: num updated entries: 0
,08-30 17:40:59.387  1737  4264 I SystemUpdateService: now status is 0 (complete)
,08-30 17:40:59.392  1737  4264 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 17:40:59.392  1737  4264 I SystemUpdateService: file has been verified
08-30 17:40:59.393  1737  4264 I SystemUpdateService: OTA package size = 12249756
,08-30 17:40:59.398   872  4251 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 15:40:59 GMT], X-Android-Received-Millis=[1472571659397], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472571659373]}
,08-30 17:40:59.400   872  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 17:40:59.400   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-30 17:40:59.400   872  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 17:40:59.402   872  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 17:40:59.406  1737  2419 I iu.SyncManager: NEXT; no task
08-30 17:40:59.406  1737  4264 I SystemUpdateService: showing system update notification
,08-30 17:40:59.409  1737  1737 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 17:40:59.410  1737  1737 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 17:40:59.412  3998  3998 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:59.417  1737  4267 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 17:40:59.417  1737  4267 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 17:40:59.418  1737  4267 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 17:40:59.420  3998  3998 D SprintDMHelper: simOperator: 
,08-30 17:40:59.420  3998  3998 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 17:40:59.431  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:40:59.435  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:40:59.467  1737  1737 D SystemUpdateService: onDestroy
,08-30 17:40:59.489  1521  2060 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 17:40:59.489  1521  2060 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-30 17:40:59.490  1521  2060 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 17:40:59.491  1521  2060 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 17:40:59.507  1737  4267 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-30 17:40:59.548  3931  4270 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 17:40:59.568  1521  2154 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 17:41:00.271  3812  3863 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
,08-30 17:41:00.271  3812  3863 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
,08-30 17:41:00.280  3812  3863 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-30 17:41:00.282  3812  3863 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-30 17:41:00.282  3812  3863 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,08-30 17:41:00.288  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 17:41:00.289  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84fe3e0 added. We now have 2 listener(s)
,08-30 17:41:00.291  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 17:41:00.291  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 17:41:00.291  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 17:41:00.292  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:00.292  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b27699 added. We now have 9 listener(s)
08-30 17:41:00.292  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:00.293  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:41:00.297  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:41:00.304  3812  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:41:00.304  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:00.304  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:41:00.304  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:00.304  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:00.304  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:00.304  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:00.304  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:41:00.308  3812  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:41:00.308  3812  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:41:00.308  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:41:00.309  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@738c53f added. We now have 3 listener(s)
08-30 17:41:00.310  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 17:41:00.310  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:00.311  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:41:00.311  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:00.311  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cff5e0c added. We now have 10 listener(s)
08-30 17:41:00.311  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:00.311  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:00.311  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:00.311  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:00.311  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:00.312  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:41:00.312  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:00.312  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:41:00.312  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84fe3e0 removed from the list
08-30 17:41:00.312  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:00.312  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b27699 removed from the list
,08-30 17:41:00.314  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:41:00.314  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:41:00.315  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:41:00.315  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:00.316   872  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-30 17:41:00.316  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:00.318  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:41:00.318  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:41:00.318  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:41:00.318  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b27699 not in the list
,08-30 17:41:00.319  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:41:00.319  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:41:00.322  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:41:00.322  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:00.322  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:00.323  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:00.323  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cff5e0c removed from the list
08-30 17:41:00.323  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:00.323  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:00.323  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:00.324  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:41:00.324  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@738c53f removed from the list
08-30 17:41:00.326  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:41:00.326  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aae355 added. We now have 2 listener(s)
08-30 17:41:00.332  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 17:41:00.332  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:00.333  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 17:41:00.333  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:41:00.333  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c4e16a added. We now have 9 listener(s)
08-30 17:41:00.334  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:41:00.335  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:41:00.342  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:41:00.352  3812  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:41:00.352  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:00.352  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:41:00.352  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:00.352  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:00.352  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:00.352  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:00.352  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:41:00.356  3812  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:41:00.357  3812  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:41:00.357  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:41:00.357  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a4ef8 added. We now have 3 listener(s)
,08-30 17:41:00.363  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:41:00.363  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 17:41:00.363  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 17:41:00.364  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:41:00.364  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:00.365  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2835fd1 added. We now have 10 listener(s)
,08-30 17:41:00.365  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:00.365  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:41:00.365  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 17:41:00.366  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:41:00.366  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:00.366  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:41:00.369  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:41:00.373  3812  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 17:41:00.373  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:41:00.382  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:41:00.383  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 17:41:00.383  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:41:00.390  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 17:41:00.390  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:41:00.391  3812  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:41:00.392  3812  3863 D BluetoothAdapter: STATE_ON
,08-30 17:41:00.399  4199  4237 D BtGatt.GattService: registerClient() - UUID=e333a0a4-9b03-4428-bb98-ff3764a3cef5
,08-30 17:41:00.401  4199  4215 D BtGatt.GattService: onClientRegistered() - UUID=e333a0a4-9b03-4428-bb98-ff3764a3cef5, clientIf=5
,08-30 17:41:00.402  3812  3859 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 17:41:00.405  4199  4216 D BtGatt.GattService: start scan with filters
,08-30 17:41:00.414  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 17:41:00.415  4199  4219 D BtGatt.ScanManager: handling starting scan
08-30 17:41:00.415  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:41:00.415  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:41:00.416  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:41:00.418  4199  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77b5dee
,08-30 17:41:00.426  4199  4215 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 17:41:00.427  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:41:00.429  4199  4219 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 17:41:00.429  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:41:00.430  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 17:41:00.430  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:41:00.436  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:41:00.445  3812  3863 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 17:41:00.446  4199  4215 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 17:41:00.446  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:41:00.446  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:41:00.446  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 17:41:00.446  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:41:00.447  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:41:00.447  4199  4219 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:41:00.447  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:41:00.447  4199  4219 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 17:41:00.447  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:41:00.448  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 17:41:00.448  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 17:41:00.448  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 17:41:00.448  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:41:00.450  3812  3863 D BluetoothAdapter: STATE_ON
08-30 17:41:00.453  4199  4216 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:41:00.455  4199  4237 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 17:41:00.456  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:00.456  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 17:41:00.457  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:41:00.457  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 17:41:00.458  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 17:41:00.461  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:41:00.462  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:41:00.462  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 17:41:00.463  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:41:00.464  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:00.467  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 17:41:00.467  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:41:00.468  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:41:00.475  4199  4215 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 17:41:00.475  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:41:00.475  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:41:00.475  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:00.475  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:00.476  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:00.476  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:41:00.476  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:41:00.477  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 17:41:00.478  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aae355 removed from the list
08-30 17:41:00.478  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:00.479  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c4e16a removed from the list
08-30 17:41:00.479  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:00.479  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:00.480  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:00.480  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:41:00.484  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:00.484  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:41:00.484  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:41:00.484  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c4e16a not in the list
08-30 17:41:00.485  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:00.485  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:41:00.486  4199  4215 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 17:41:00.487  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:41:00.488  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:41:00.488  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:00.488  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:00.488  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2835fd1 removed from the list
08-30 17:41:00.489  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:00.489  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:00.489  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:00.489  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 17:41:00.491  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a4ef8 removed from the list
,08-30 17:41:00.492  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:41:00.492  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8d280d added. We now have 2 listener(s)
,08-30 17:41:00.496  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 17:41:00.496  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:00.496  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:41:00.496  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:41:00.496  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75c33c2 added. We now have 9 listener(s)
08-30 17:41:00.497  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:00.497  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:41:00.500  4199  4215 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 17:41:00.500  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:41:00.500  4199  4219 D BtGatt.ScanManager: stopping BLe Batch
,08-30 17:41:00.502  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:41:00.507  3812  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:41:00.507  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:00.507  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:41:00.507  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:00.507  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:00.507  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:00.507  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:00.507  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:41:00.509  3812  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:41:00.510  4199  4215 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 17:41:00.510  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:41:00.510  3812  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:41:00.510  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:41:00.511  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4940510 added. We now have 3 listener(s)
08-30 17:41:00.511  4199  4219 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 17:41:00.513  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:41:00.513  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 17:41:00.513  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 17:41:00.513  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-30 17:41:00.513  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:41:00.514  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f13809 added. We now have 10 listener(s)
,08-30 17:41:00.514  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:41:00.514  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 17:41:00.515  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:41:00.515  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:41:00.515  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:41:00.516  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:00.516  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:41:00.516  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:00.519  3812  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 17:41:00.519  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:41:00.524  4199  4215 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 17:41:00.524  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:41:00.526  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:41:00.527  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 17:41:00.527  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:41:00.532  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 17:41:00.532  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 17:41:00.532  3812  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 17:41:00.533  3812  3863 D BluetoothAdapter: STATE_ON
,08-30 17:41:00.535  4199  4209 D BtGatt.GattService: registerClient() - UUID=f1149960-0758-42ef-88a2-e1f37fe39a31
,08-30 17:41:00.536  4199  4215 D BtGatt.GattService: onClientRegistered() - UUID=f1149960-0758-42ef-88a2-e1f37fe39a31, clientIf=5
,08-30 17:41:00.536  3812  3824 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 17:41:00.537  4199  4216 D BtGatt.GattService: start scan with filters
,08-30 17:41:00.540  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 17:41:00.541  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:41:00.541  4199  4219 D BtGatt.ScanManager: handling starting scan
,08-30 17:41:00.541  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:41:00.541  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:41:00.543  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:41:00.544  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:41:00.544  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 17:41:00.547  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:41:00.550  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:41:00.551  3812  3863 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 17:41:00.551  4199  4215 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 17:41:00.551  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:00.551  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:41:00.551  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:00.551  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:00.551  4199  4219 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 17:41:00.552  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:00.552  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:00.552  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:41:00.552  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 17:41:00.552  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8d280d removed from the list
08-30 17:41:00.552  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:00.553  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75c33c2 removed from the list
08-30 17:41:00.553  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:00.553  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:41:00.554  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:00.554  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 17:41:00.554  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:00.554  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:41:00.557  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:41:00.557  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:00.557  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:00.557  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75c33c2 not in the list
08-30 17:41:00.557  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:41:00.557  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 17:41:00.558  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:41:00.558  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:41:00.558  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 17:41:00.560  3812  3863 D BluetoothAdapter: STATE_ON
,08-30 17:41:00.561  4199  4237 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:41:00.562  4199  4216 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 17:41:00.562  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:00.562  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:41:00.562  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:41:00.562  4199  4215 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 17:41:00.562  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:41:00.562  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:41:00.563  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 17:41:00.563  4199  4219 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 17:41:00.563  4199  4219 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 17:41:00.564  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:41:00.564  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:41:00.564  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:41:00.564  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 17:41:00.565  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:41:00.566  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:41:00.566  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:41:00.566  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:41:00.566  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:41:00.566  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:41:00.567  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:00.567  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f13809 removed from the list
08-30 17:41:00.567  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:00.567  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:00.567  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:41:00.567  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:41:00.567  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4940510 removed from the list
08-30 17:41:00.568  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 17:41:00.568  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56c4bc5 added. We now have 2 listener(s)
08-30 17:41:00.570  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 17:41:00.571  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:00.571  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:41:00.571  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:00.571  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d90791a added. We now have 9 listener(s)
08-30 17:41:00.571  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:41:00.572  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:41:00.576  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:41:00.580  3812  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:41:00.580  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:00.580  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:41:00.580  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:00.580  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:00.580  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:00.580  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:00.580  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:41:00.583  3812  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:41:00.583  3812  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:41:00.584  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 17:41:00.584  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b6628 added. We now have 3 listener(s)
08-30 17:41:00.586  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:00.586  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 17:41:00.587  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:00.587  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 17:41:00.587  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:00.587  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cadf41 added. We now have 10 listener(s)
08-30 17:41:00.587  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:41:00.587  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:41:00.587  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:41:00.588  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:41:00.588  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:00.588  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:41:00.589  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:00.591  4199  4215 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 17:41:00.591  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:41:00.593  3812  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 17:41:00.593  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:41:00.597  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 17:41:00.597  4199  4215 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 17:41:00.598  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:41:00.598  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 17:41:00.598  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:41:00.602  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 17:41:00.602  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:41:00.602  3812  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:41:00.603  3812  3863 D BluetoothAdapter: STATE_ON
,08-30 17:41:00.604  4199  4215 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 17:41:00.604  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:41:00.604  4199  4219 D BtGatt.ScanManager: stopping BLe Batch
,08-30 17:41:00.606  4199  4210 D BtGatt.GattService: registerClient() - UUID=e64cb6e3-25e9-42dd-878b-dcf31dbbfe3f
,08-30 17:41:00.606  4199  4215 D BtGatt.GattService: onClientRegistered() - UUID=e64cb6e3-25e9-42dd-878b-dcf31dbbfe3f, clientIf=5
08-30 17:41:00.607  3812  3824 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 17:41:00.607  4199  4237 D BtGatt.GattService: start scan with filters
,08-30 17:41:00.610  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 17:41:00.610  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:41:00.610  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:41:00.610  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:41:00.611  4199  4215 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 17:41:00.611  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:41:00.611  4199  4219 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 17:41:00.614  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:41:00.614  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:41:00.614  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 17:41:00.616  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:41:00.617  4199  4215 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 17:41:00.617  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:41:00.618  4199  4219 D BtGatt.ScanManager: handling starting scan
,08-30 17:41:00.622  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:41:00.622  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:00.622  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:00.623  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:00.623  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:41:00.623  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 17:41:00.623  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:41:00.623  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56c4bc5 removed from the list
08-30 17:41:00.623  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:00.624  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d90791a removed from the list
08-30 17:41:00.624  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:41:00.625  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:00.625  4199  4215 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 17:41:00.625  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 17:41:00.625  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:00.625  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-30 17:41:00.625  4199  4219 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 17:41:00.625  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:00.625  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:00.627  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:00.627  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:41:00.627  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:00.627  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d90791a not in the list
08-30 17:41:00.628  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:41:00.628  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:41:00.628  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 17:41:00.628  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:41:00.628  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:41:00.630  3812  3863 D BluetoothAdapter: STATE_ON
08-30 17:41:00.631  4199  4215 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 17:41:00.631  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:41:00.631  4199  4219 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:41:00.631  4199  4219 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 17:41:00.632  4199  4210 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:41:00.632  4199  4209 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 17:41:00.633  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 17:41:00.633  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:41:00.633  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:41:00.633  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:41:00.633  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:41:00.634  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:41:00.634  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:41:00.634  3812  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 17:41:00.634  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:41:00.635  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:41:00.636  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:41:00.636  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:41:00.636  3812  3812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:41:00.636  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:00.636  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:00.636  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:41:00.638  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cadf41 removed from the list
,08-30 17:41:00.638  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:41:00.638  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:41:00.638  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:41:00.638  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-30 17:41:00.639  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b6628 removed from the list,
08-30 17:41:00.640  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 17:41:00.640  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a252e7d added. We now have 2 listener(s)
08-30 17:41:00.642  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
08-30 17:41:00.642  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 17:41:00.643  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:41:00.643  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:41:00.643  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ad1172 added. We now have 9 listener(s)
08-30 17:41:00.643  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:00.643  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:41:00.647  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:00.648  4199  4215 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 17:41:00.648  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:41:00.653  3812  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:41:00.653  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:00.653  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:41:00.653  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:00.653  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:00.653  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:00.653  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:00.653  3812  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:00.655  4199  4215 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 17:41:00.655  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:41:00.657  3812  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:00.657  3812  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:41:00.657  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:41:00.657  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47ad240 added. We now have 3 listener(s)
08-30 17:41:00.659  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:00.660  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 17:41:00.660  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:00.660  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:41:00.660  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:00.660  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1db3579 added. We now have 10 listener(s)
08-30 17:41:00.660  3812  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:00.661  3812  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:00.661  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:00.661  3812  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:00.661  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:00.662  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:00.662  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:00.662  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:00.662  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:41:00.662  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a252e7d removed from the list
08-30 17:41:00.662  4199  4215 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 17:41:00.662  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:00.662  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:41:00.662  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ad1172 removed from the list
08-30 17:41:00.662  3812  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:00.662  4199  4219 D BtGatt.ScanManager: stopping BLe Batch
08-30 17:41:00.662  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:00.663  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:00.663  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:00.664  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:00.664  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:00.664  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:00.664  3812  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ad1172 not in the list
08-30 17:41:00.664  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:00.665  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:00.666  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:00.666  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:00.666  3812  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:00.666  3812  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1db3579 removed from the list
08-30 17:41:00.666  3812  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:00.666  3812  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:00.666  3812  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:00.666  3812  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:41:00.666  3812  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47ad240 removed from the list
08-30 17:41:00.667  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 17:41:00.667  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 17:41:00.667  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 17:41:00.667  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:41:00.668  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 17:41:00.668  3812  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:00.668  4199  4215 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 17:41:00.669  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:41:00.669  4199  4219 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 17:41:00.674  3812  4277 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name)
08-30 17:41:00.674  3812  4277 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name)
08-30 17:41:00.674  3812  4277 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 17:41:00.675  4199  4215 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 17:41:00.675  4199  4215 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 17:41:00.676  3812  4278 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
08-30 17:41:00.676  3812  4278 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
08-30 17:41:00.676  3812  4278 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 17:41:00.678  3812  3863 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 17:41:00.678  3812  3863 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 17:41:00.678  3812  3863 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 17:41:00.678  3812  3863 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 17:41:00.678  3812  3863 D com.test.thalitest.ThaliTestRunner: Total duration: 22983 ms
08-30 17:41:00.680  3812  3863 I jxcore-log: *Native tests were executed*
08-30 17:41:00.680  3812  3863 I jxcore-log: 
08-30 17:41:00.680  3812  3863 I jxcore-log: Total number of executed tests:  80
08-30 17:41:00.680  3812  3863 I jxcore-log: 
08-30 17:41:00.680  3812  3863 I jxcore-log: Number of passed tests:  80
08-30 17:41:00.680  3812  3863 I jxcore-log: 
08-30 17:41:00.680  3812  3863 I jxcore-log: Number of failed tests:  0
08-30 17:41:00.680  3812  3863 I jxcore-log: 
08-30 17:41:00.680  3812  3863 I jxcore-log: Number of ignored tests:  0
08-30 17:41:00.680  3812  3863 I jxcore-log: 
08-30 17:41:00.681  3812  3863 I jxcore-log: Total duration:  22983
08-30 17:41:00.681  3812  3863 I jxcore-log: 
08-30 17:41:00.681  3812  3863 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 17:41:00.681  3812  3863 I jxcore-log: 
08-30 17:41:00.684  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:00.684  3812  3863 I jxcore-log: 
08-30 17:41:00.687  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:00.687  3812  3863 I jxcore-log: 
08-30 17:41:00.688  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:00.688  3812  3863 I jxcore-log: 
08-30 17:41:00.689  3812  3812 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 17:41:00.690  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:00.690  3812  3863 I jxcore-log: 
08-30 17:41:00.691  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:00.691  3812  3863 I jxcore-log: 
08-30 17:41:00.692  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:00.692  3812  3863 I jxcore-log: 
08-30 17:41:00.694  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:00.694  3812  3863 I jxcore-log: 
08-30 17:41:00.696  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:00.696  3812  3863 I jxcore-log: 
08-30 17:41:00.697  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:41:00.697  3812  3863 I jxcore-log: 
08-30 17:41:00.698  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:41:00.698  3812  3863 I jxcore-log: 
08-30 17:41:00.698  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:41:00.698  3812  3863 I jxcore-log: 
08-30 17:41:00.699  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:41:00.699  3812  3863 I jxcore-log: 
08-30 17:41:00.700  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:41:00.700  3812  3863 I jxcore-log: 
08-30 17:41:00.701  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:41:00.701  3812  3863 I jxcore-log: 
08-30 17:41:00.702  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:41:00.702  3812  3863 I jxcore-log: 
08-30 17:41:00.702  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:00.702  3812  3863 I jxcore-log: 
08-30 17:41:00.703  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:00.703  3812  3863 I jxcore-log: 
08-30 17:41:00.703  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:41:00.703  3812  3863 I jxcore-log: 
08-30 17:41:00.704  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:41:00.704  3812  3863 I jxcore-log: 
08-30 17:41:00.705  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:41:00.705  3812  3863 I jxcore-log: 
08-30 17:41:00.705  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:41:00.705  3812  3863 I jxcore-log: 
08-30 17:41:00.706  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:41:00.706  3812  3863 I jxcore-log: 
08-30 17:41:00.707  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:41:00.707  3812  3863 I jxcore-log: 
08-30 17:41:00.707  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:41:00.707  3812  3863 I jxcore-log: 
08-30 17:41:00.708  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:41:00.708  3812  3863 I jxcore-log: 
08-30 17:41:00.709  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:41:00.709  3812  3863 I jxcore-log: 
08-30 17:41:00.709  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:41:00.709  3812  3863 I jxcore-log: 
08-30 17:41:00.710  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:41:00.710  3812  3863 I jxcore-log: 
08-30 17:41:00.711  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:00.711  3812  3863 I jxcore-log: 
08-30 17:41:00.711  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:00.711  3812  3863 I jxcore-log: 
08-30 17:41:00.712  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:00.712  3812  3863 I jxcore-log: 
08-30 17:41:00.712  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:00.712  3812  3863 I jxcore-log: 
08-30 17:41:00.713  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:00.713  3812  3863 I jxcore-log: 
08-30 17:41:00.714  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:00.714  3812  3863 I jxcore-log: 
08-30 17:41:00.714  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:00.714  3812  3863 I jxcore-log: 
,08-30 17:41:00.969  3812  3812 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 17:41:00.970  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:41:00.970  3812  3863 I jxcore-log: 
,08-30 17:41:01.067  3812  3812 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 17:41:01.068  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:41:01.068  3812  3863 I jxcore-log: 
,08-30 17:41:01.137  3812  3812 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 17:41:01.138  3812  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:41:01.138  3812  3863 I jxcore-log: 
,08-30 17:41:01.252  2087  2644 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 17:41:01.388  4279  4279 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 17:41:01.393  4279  4279 D AndroidRuntime: CheckJNI is OFF
,08-30 17:41:01.435  4279  4279 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 17:41:01.483  4279  4279 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 17:41:01.507  4279  4279 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 17:41:01.515   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-30 17:41:01.516   872   885 I ActivityManager: Killing 3812:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-30 17:41:01.624   872   895 W PackageSettings: Skipping PackageSetting{c6888c3 com.example.hello/10273} due to missing metadata
,08-30 17:41:01.644   872  2065 D GraphicsStats: Buffer count: 2
08-30 17:41:01.645   872  1704 I WindowState: WIN DEATH: Window{346f5b5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 17:41:01.645   872  1306 D WifiService: Client connection lost with reason: 4
,08-30 17:41:01.676   872   895 I art     : Starting a blocking GC Explicit
,08-30 17:41:01.684   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-30 17:41:01.685   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-30 17:41:01.687   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-30 17:41:01.687   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 17:41:01.687   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 17:41:01.687   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 17:41:01.687   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 17:41:01.687   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 17:41:01.687   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 17:41:01.687   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 17:41:01.687   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 17:41:01.687   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 17:41:01.687   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 17:41:01.687   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 17:41:01.687   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 17:41:01.687   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 17:41:01.687   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 17:41:01.687   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 17:41:01.687   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:41:01.687   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:41:01.687   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:41:01.687   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-30 17:41:01.691   872   885 I ActivityManager:   Force finishing activity ActivityRecord{cfc8992 u0 com.test.thalitest/.MainActivity t2}
,08-30 17:41:01.698   872  2069 W ActivityManager: Spurious death for ProcessRecord{bc7f6cc 0:com.test.thalitest/u0a0}, curProc for 3812: null
,08-30 17:41:01.730   872   895 I art     : Explicit concurrent mark sweep GC freed 13909(970KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 801us total 53.888ms
,08-30 17:41:01.751   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 17:41:01.754  4279  4279 I art     : System.exit called, status: 0
,08-30 17:41:01.755  4279  4279 I AndroidRuntime: VM exiting with result code 0.
,08-30 17:41:01.768   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-30 17:41:01.789   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-30 17:41:01.792  1871  1871 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-30 17:41:01.793  4199  4199 D BluetoothMapAppObserver: onReceive
08-30 17:41:01.793  4199  4199 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-30 17:41:01.797   872  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 17:41:01.797  2087  2255 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 17:41:01.797  3649  3649 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-30 17:41:01.831  1871  4292 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 17:41:01.837  1937  1937 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 17:41:01.840  1871  4292 I Decoder : createOrResetDecoder
,08-30 17:41:01.848   872   882 I ActivityManager: Start proc 4293:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-30 17:41:01.858  1521  1521 I ConfigService: onCreate
,08-30 17:41:01.880  1871  4292 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-30 17:41:01.896   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 17:41:01.901  4293  4293 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 17:41:01.918   872  1467 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3812 uid 10000
,08-30 17:41:01.919  1871  1871 I Keyboard.Facilitator: onFinishInput()
,08-30 17:41:01.929   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-30 17:41:01.929  1953  2028 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-30 17:41:01.930   872   884 E PackageManager: Failed to write settings, restoring backup
08-30 17:41:01.930   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 17:41:01.930   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 17:41:01.930   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 17:41:01.930   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 17:41:01.930   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 17:41:01.930   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:41:01.930   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:41:01.930   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:41:01.933   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-30 17:41:01.933   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 17:41:01.933   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:41:01.933   872   885 E DropBoxManagerService: 	... 13 more
,08-30 17:41:01.939  1871  4292 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-30 17:41:01.940  1871  4292 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-30 17:41:01.941  1871  4292 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-30 17:41:01.942  1871  4292 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-30 17:41:01.942  1871  4292 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-30 17:41:01.943  1871  4292 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-30 17:41:01.943  1871  4292 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 17:41:01.945  1871  4292 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-30 17:41:01.945  1871  4292 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 17:41:01.945   872   883 I ActivityManager: Start proc 4310:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-30 17:41:01.945  1871  4292 I Keyboard.Facilitator.Delight2FileSweeper: run()
--------- beginning of crash
08-30 17:41:01.945  1953  2028 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 17:41:01.945  1953  2028 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1953
08-30 17:41:01.945  1953  2028 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:41:01.945  1953  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:41:01.945  1953  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 17:41:01.945  1953  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 17:41:01.945  1953  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:41:01.945  1953  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 17:41:01.945  1953  2028 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 17:41:01.945  1953  2028 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 17:41:01.945  1953  2028 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:41:01.945  1953  2028 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:41:01.945  1953  2028 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:41:01.945  1953  2028 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:41:01.948   872  1704 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 17:41:01.949   872  4316 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:41:01.949   872  4316 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-30 17:41:01.949   872  4316 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:41:01.949   872  4316 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:41:01.949   872  4316 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:41:01.949   872  4316 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:41:01.949   872  4316 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:41:01.949   872  4316 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:41:01.949   872  4316 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:41:01.949   872  4316 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:41:01.949   872  4316 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:41:01.949   872  4316 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:41:01.949   872  4316 E DropBoxManagerService: 	... 5 more
08-30 17:41:01.951  1953  2028 I Process : Sending signal. PID: 1953 SIG: 9
,08-30 17:41:01.950  1871  4292 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-30 17:41:01.955  1871  4292 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 17:41:01.955  1871  4292 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-30 17:41:01.998  4293  4293 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 17:41:02.048   872  1969 I ActivityManager: Start proc 4325:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-30 17:41:02.048  4293  4324 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 17:41:02.071  4293  4324 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:41:02.071  4293  4324 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:41:02.073  4293  4324 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 17:41:02.073  4293  4324 E AndroidRuntime: Process: android.process.acore, PID: 4293
08-30 17:41:02.073  4293  4324 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:41:02.073  4293  4324 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:41:02.081   872  4337 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:41:02.081   872  4337 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-30 17:41:02.081   872  4337 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:41:02.081   872  4337 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:41:02.081   872  4337 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:41:02.081   872  4337 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerServ,ice.java:211)
08-30 17:41:02.081   872  4337 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:41:02.081   872  4337 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:41:02.081   872  4337 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:41:02.081   872  4337 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:41:02.081   872  4337 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:41:02.081   872  4337 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:41:02.081   872  4337 E DropBoxManagerService: 	... 5 more
08-30 17:41:02.082   872  1467 D GraphicsStats: Buffer count: 1
08-30 17:41:02.082   872  1954 I WindowState: WIN DEATH: Window{8b54513 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-30 17:41:02.081  4293  4324 I Process : Sending signal. PID: 4293 SIG: 9
08-30 17:41:02.094   872  1467 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1953) has died
08-30 17:41:02.094   872  1467 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-30 17:41:02.096   872  1467 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-30 17:41:02.099   279   279 E lowmemorykiller: Error writing /proc/4293/oom_score_adj; errno=22
,08-30 17:41:02.112   872   885 I ActivityManager: Start proc 4340:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:41:02.132  1737  4339 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 17:41:02.134  1737  4339 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-30 17:41:02.144   872  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
08-30 17:41:02.143  4325  4325 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-30 17:41:02.163  1521  1521 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-30 17:41:02.164  1521  1521 D AndroidRuntime: Shutting down VM
,08-30 17:41:02.164   279   279 E lowmemorykiller: Error writing /proc/4293/oom_score_adj; errno=22
,08-30 17:41:02.164   279   279 E lowmemorykiller: Error writing /proc/4293/oom_score_adj; errno=22
08-30 17:41:02.165  1521  1521 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:41:02.165  1521  1521 E AndroidRuntime: Process: com.google.process.gapps, PID: 1521
08-30 17:41:02.165  1521  1521 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 17:41:02.165  1521  1521 E AndroidRuntime: 	... 8 more
08-30 17:41:02.169  1521  1521 I Process : Sending signal. PID: 1521 SIG: 9
08-30 17:41:02.170   872  4355 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:41:02.170   872  4355 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-30 17:41:02.170   872  4355 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:41:02.170   872  4355 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:41:02.170   872  4355 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:41:02.170   872  4355 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:41:02.170   872  4355 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:41:02.170   872  4355 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:41:02.170   872  4355 E DropBoxManagerService: Caused by: android.system.ErrnoException: op,en failed: EROFS (Read-only file system)
08-30 17:41:02.170   872  4355 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:41:02.170   872  4355 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:41:02.170   872  4355 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:41:02.170   872  4355 E DropBoxManagerService: 	... 5 more
,08-30 17:41:02.177  4340  4340 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:41:02.177  4340  4340 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:41:02.178  4340  4340 D AndroidRuntime: Shutting down VM
,08-30 17:41:02.184  4340  4340 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:41:02.184  4340  4340 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4340
08-30 17:41:02.184  4340  4340 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 17:41:02.184  4340  4340 E AndroidRuntime: 	... 10 more
08-30 17:41:02.186   872  1704 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 17:41:02.186  4340  4340 I Process : Sending signal. PID: 4340 SIG: 9
08-30 17:41:02.187   872  4356 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:41:02.187   872  4356 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-30 17:41:02.187   872  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:41:02.187   872  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:41:02.187   872  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:41:02.187   872  4356 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:41:02.187   872  4356 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:41:02.187   872  4356 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:41:02.187   872  4356 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:41:02.187   872  4356 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:41:02.187   872  4356 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:41:02.187   872  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:41:02.187   872  4356 E DropBoxManagerService: 	... 5 more
,08-30 17:41:02.196  1737  4339 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 17:41:02.196  1737  4339 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-30 17:41:02.202   872  1704 I ActivityManager: Process android.process.acore (pid 4293) has died
,08-30 17:41:02.202   872  1704 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-30 17:41:02.209   872  1306 D WifiService: Client connection lost with reason: 4
,08-30 17:41:02.214   872  1394 I ActivityManager: Process com.google.process.gapps (pid 1521) has died
,08-30 17:41:02.214   872  1394 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,08-30 17:41:02.214   872  1394 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 11000ms
,08-30 17:41:02.214   872  1394 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
08-30 17:41:02.214   872  1394 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 31000ms
08-30 17:41:02.216   872  1969 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4340) has died
,08-30 17:41:02.217   872  1969 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 17:41:02.234   872   885 I ActivityManager: Start proc 4357:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:41:02.246   872  1704 I ActivityManager: Start proc 4369:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-30 17:41:02.251  1737  1737 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-30 17:41:02.266   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
