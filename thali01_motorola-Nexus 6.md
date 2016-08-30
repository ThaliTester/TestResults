#### Test 82865362e858c08_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
08-30 19:17:44.559   871  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
08-30 19:17:45.888  3748  3748 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 19:17:45.893  3748  3748 D AndroidRuntime: CheckJNI is OFF
08-30 19:17:45.930  3748  3748 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 19:17:45.974  3748  3748 I Radio-JNI: register_android_hardware_Radio DONE
08-30 19:17:45.994  3748  3748 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 19:17:46.002   871  2153 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 19:17:46.040  3748  3748 D AndroidRuntime: Shutting down VM
08-30 19:17:46.048  2016  2027 W SearchService: Abort, client detached.
08-30 19:17:46.053  2016  2345 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3600aa0
08-30 19:17:46.053  2016  2016 I HotwordDetector: Closing mic
08-30 19:17:46.054  2016  2351 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-30 19:17:46.078   871  2154 I ActivityManager: Start proc 3757:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 19:17:46.110   376  2353 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 19:17:46.111   376  2353 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-30 19:17:46.116   376  1275 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 19:17:46.117  2016  2349 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-30 19:17:46.119  2016  2350 I MicroRecognitionRnrImpl: Detection finished
08-30 19:17:46.153  3757  3757 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 19:17:46.173  3757  3757 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 19:17:46.180  3757  3757 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5253-5255)
08-30 19:17:46.180  3757  3757 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 19:17:46.195  3757  3757 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {51eca22}
08-30 19:17:46.195  3757  3757 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 19:17:46.195  3757  3757 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 19:17:46.201  3757  3757 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 19:17:46.202  3757  3757 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 19:17:46.215  3757  3757 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 19:17:46.224  3757  3757 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 19:17:46.224  3757  3757 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 19:17:46.224  3757  3757 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 19:17:46.224  3757  3757 I Adreno  : Build Date                       : 10/20/15
08-30 19:17:46.224  3757  3757 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 19:17:46.224  3757  3757 I Adreno  : Local Branch                     : M14
08-30 19:17:46.224  3757  3757 I Adreno  : Remote Branch                    : 
08-30 19:17:46.224  3757  3757 I Adreno  : Remote Branch                    : 
08-30 19:17:46.224  3757  3757 I Adreno  : Reconstruct Branch               : 
,08-30 19:17:46.279   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bf6009:true
,08-30 19:17:46.306  3757  3757 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 19:17:46.320  3757  3757 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 19:17:46.377  3757  3795 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 19:17:46.384  3757  3782 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 19:17:46.413  3757  3795 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 19:17:46.467   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +408ms
,08-30 19:17:46.469  1873  1873 I Keyboard.Facilitator: onFinishInput()
,08-30 19:17:46.518  3757  3757 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3757
,08-30 19:17:46.621  3757  3757 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 19:17:46.832  3757  3797 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1679099600
,08-30 19:17:46.842  3757  3797 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 19:17:46.842  3757  3797 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 19:17:46.842  3757  3797 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 19:17:46.842  3757  3797 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 19:17:46.842  3757  3797 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 19:17:46.842  3757  3797 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d242e1 added. We now have 1 listener(s)
,08-30 19:17:46.847  3757  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-30 19:17:46.850  3757  3797 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 19:17:46.851  3757  3797 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 19:17:46.851  3757  3797 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 19:17:46.862  3757  3797 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 19:17:46.862  3757  3797 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 19:17:46.862  3757  3797 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 19:17:46.862  3757  3797 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 19:17:46.862  3757  3797 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 19:17:46.862  3757  3797 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 19:17:46.862  3757  3797 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 19:17:46.862  3757  3797 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 19:17:46.862  3757  3797 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 19:17:46.862  3757  3797 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 19:17:46.862  3757  3797 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 19:17:46.862  3757  3797 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 19:17:46.862  3757  3797 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 19:17:46.862  3757  3797 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 19:17:46.862  3757  3797 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7acf4 added. We now have 1 listener(s)
,08-30 19:17:46.862  3757  3797 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 19:17:46.872   871  1307 D WifiService: New client listening to asynchronous messages
,08-30 19:17:46.872  3757  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 19:17:46.872  3757  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 19:17:46.873  3757  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-30 19:17:46.873  3757  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-30 19:17:46.873  3757  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 19:17:46.876  3757  3797 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 19:17:46.876  3757  3797 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-30 19:17:46.883  3757  3797 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 19:17:46.883  3757  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 19:17:46.883  3757  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:17:46.883  3757  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:17:46.883  3757  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:17:46.883  3757  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:17:46.883  3757  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:17:46.883  3757  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:17:46.883  3757  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 19:17:46.884  3757  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 19:17:46.884  3757  3797 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 19:17:46.884   871  2128 I ActivityManager: Killing 2988:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-30 19:17:46.885  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:17:46.887  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:17:46.889  3757  3797 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 19:17:46.957   871  2128 I ActivityManager: Killing 3101:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-30 19:17:47.055  3757  3757 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 19:17:47.847  3757  3807 W jxcore-log: Initializing JXcore engine
,08-30 19:17:47.847  3757  3807 W jxcore-log: JXcore engine is ready
,08-30 19:17:47.883  3807  3807 W Thread-317: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-30 19:17:47.883  3807  3807 W Thread-317: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11852]" dev="sockfs" ino=11852 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-30 19:17:47.883  3807  3807 W Thread-317: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-30 19:17:47.898  3757  3807 W jxcore-log: Starting JXcore engine
,08-30 19:17:47.883  3807  3807 W Thread-317: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25998]" dev="sockfs" ino=25998 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 19:17:47.976  3757  3807 W jxcore-log: Platform android
08-30 19:17:47.976  3757  3807 W jxcore-log: 
,08-30 19:17:47.977  3757  3807 W jxcore-log: Process ARCH arm
08-30 19:17:47.977  3757  3807 W jxcore-log: 
,08-30 19:17:48.211  3757  3807 I jxcore-log: JXcore Cordova bridge is ready!
08-30 19:17:48.211  3757  3807 I jxcore-log: 
,08-30 19:17:48.211  3757  3807 W jxcore-log: JXcore engine is started
,08-30 19:17:48.223  3757  3797 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 19:17:48.230  3757  3757 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 19:17:52.001   871  1869 D NetlinkSocketObserver: NeighborEvent{elapsedMs=121076, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:17:53.970   871  1306 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-30 19:17:56.311  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:17:56.317  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:17:56.319  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:17:56.350  1510  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 19:17:56.350  1510  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 19:17:56.350  1510  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:17:56.350  1510  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:17:56.373  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 19:17:56.373  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 19:17:56.374  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-30 19:17:56.673   871  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 19:17:58.915  3047  3819 V KeepSync: Connecting to GoogleApiClient
,08-30 19:17:58.916   871   882 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 19:17:58.992  1510  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 19:17:58.993  1510  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 19:17:58.993  1510  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:17:58.993  1510  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:17:59.015  1705  3820 V BaseAuthAsyncOperation: access token request failed
,08-30 19:17:59.016  3047  3819 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 19:17:59.074  1510  2411 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 19:17:59.074  1510  2411 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-30 19:17:59.075  1510  2411 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-30 19:17:59.075  1510  2411 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:17:59.106  3047  3819 E KeepSync: IOException
08-30 19:17:59.106  3047  3819 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 19:17:59.106  3047  3819 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 19:17:59.106  3047  3819 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 19:17:59.106  3047  3819 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 19:17:59.106  3047  3819 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 19:17:59.106  3047  3819 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 19:17:59.106  3047  3819 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 19:17:59.106  3047  3819 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 19:17:59.106  3047  3819 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 19:17:59.106  3047  3819 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 19:17:59.106  3047  3819 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 19:17:59.106  3047  3819 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 19:17:59.106  3047  3819 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 19:17:59.106  3047  3819 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 19:17:59.106  3047  3819 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 19:17:59.106  3047  3819 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 19:17:59.106  3047  3819 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 19:17:59.106  3047  3819 E KeepSync: 	... 10 more
,08-30 19:17:59.106  3047  3819 W KeepSync: Sync result 2
,08-30 19:17:59.120   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 127808, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 19:17:59.707   871  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100],
,08-30 19:18:02.717  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 19:18:02.717  3757  3807 I jxcore-log: 
,08-30 19:18:02.720  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 19:18:02.720  3757  3807 I jxcore-log: 
,08-30 19:18:02.733  3757  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 19:18:02.733  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:02.733  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:02.733  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:02.733  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:18:02.733  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:18:02.733  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:18:02.733  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 19:18:02.739  3757  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 19:18:02.741  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 19:18:02.741  3757  3807 I jxcore-log: 
,08-30 19:18:02.743  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 19:18:02.743  3757  3807 I jxcore-log: 
,08-30 19:18:03.098  3757  3807 I jxcore-log: Running unit tests
08-30 19:18:03.098  3757  3807 I jxcore-log: 
08-30 19:18:03.099  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 19:18:03.099  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ca9a9d added. We now have 2 listener(s)
08-30 19:18:03.100  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 19:18:03.100  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 19:18:03.100  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 19:18:03.100  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 19:18:03.100  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acddb12 added. We now have 2 listener(s)
,08-30 19:18:03.100  3757  3807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 19:18:03.102  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 19:18:03.105  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 19:18:03.112  3757  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 19:18:03.112  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:03.112  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:03.112  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:03.112  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:18:03.112  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:18:03.112  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:18:03.112  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 19:18:03.116  3757  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 19:18:03.116  3757  3807 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 19:18:03.116  3757  3807 D executeNativeTests: Running unit tests
,08-30 19:18:03.122  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:03.129  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:03.178  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 19:18:03.178  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 added. We now have 3 listener(s)
,08-30 19:18:03.179  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 19:18:03.179  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 19:18:03.179  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 19:18:03.179  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 19:18:03.179  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 added. We now have 3 listener(s)
08-30 19:18:03.179  3757  3807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 19:18:03.181  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 19:18:03.201  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 19:18:03.213  3757  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 19:18:03.213  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:03.213  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:03.213  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:03.213  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:18:03.213  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:18:03.213  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:18:03.213  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 19:18:03.219  3757  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 19:18:03.220  3757  3807 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 19:18:03.226  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:03.227  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 19:18:03.231  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 19:18:03.231  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 19:18:03.231  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 19:18:03.231  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:03.233  3757  3807 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 19:18:03.233  3757  3807 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
08-30 19:18:03.233  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 19:18:03.233  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 19:18:03.233  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 19:18:03.233  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 19:18:03.234  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 19:18:03.234  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 19:18:03.234  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 19:18:03.234  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:18:03.234  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:03.234  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 19:18:03.234  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 19:18:03.235  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 removed from the list
,08-30 19:18:03.235  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 19:18:03.235  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 removed from the list
08-30 19:18:03.235  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 19:18:03.235  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:03.236  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:03.236  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:03.237  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 19:18:03.237  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:18:03.237  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:03.237  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
,08-30 19:18:03.239  3757  3807 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 19:18:03.240  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 19:18:03.240  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 19:18:03.240  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 19:18:03.240  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:18:03.240  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:03.240  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:03.240  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
08-30 19:18:03.240  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 19:18:03.240  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:03.240  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 19:18:03.240  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:03.240  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:03.240  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:03.240  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:03.241  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 19:18:03.241  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:18:03.241  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 19:18:03.242  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:03.246  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-30 19:18:03.247  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-30 19:18:03.247  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 19:18:03.247  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-30 19:18:03.247  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 19:18:03.247  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-30 19:18:03.247  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 19:18:03.247  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-30 19:18:03.247  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 19:18:03.247  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 19:18:03.247  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 19:18:03.247  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-30 19:18:03.247  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 19:18:03.247  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 19:18:03.247  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 19:18:03.248  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-30 19:18:03.248  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 19:18:03.248  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 19:18:03.248  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 19:18:03.248  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 19:18:03.248  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 19:18:03.248  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 19:18:03.248  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 19:18:03.248  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 19:18:03.248  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 19:18:03.248  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 19:18:03.248  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-30 19:18:03.248  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 19:18:03.248  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 19:18:03.248  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 19:18:03.248  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 19:18:03.248  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 19:18:03.249  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 19:18:03.249  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 19:18:03.249  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:18:03.249  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:03.249  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:03.249  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
08-30 19:18:03.249  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:03.249  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
,08-30 19:18:03.249  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:03.249  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:03.249  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:03.249  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:03.249  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:03.250  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:18:03.250  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:18:03.250  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:03.250  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:03.251  3757  3807 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 19:18:03.253  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 19:18:03.256  3757  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 19:18:03.256  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:03.256  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:03.256  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:03.256  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:18:03.256  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:18:03.256  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:18:03.256  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 19:18:03.257  3757  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 19:18:03.258  3757  3807 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 19:18:03.258  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 19:18:03.258  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 19:18:03.258  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 19:18:03.258  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 19:18:03.258  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 19:18:03.263  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:18:03.264  3757  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 19:18:03.264  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 19:18:03.266  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:18:03.270  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 19:18:03.271  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 19:18:03.271  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 19:18:03.273  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-30 19:18:03.275  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-30 19:18:03.275  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 19:18:03.275  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 19:18:03.275  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 19:18:03.276  3757  3807 D BluetoothAdapter: STATE_ON
08-30 19:18:03.279  2715  2727 D BtGatt.GattService: registerClient() - UUID=51e5ad6a-1dba-41f6-8a19-ce160da5fafe
08-30 19:18:03.280  2715  2769 D BtGatt.GattService: onClientRegistered() - UUID=51e5ad6a-1dba-41f6-8a19-ce160da5fafe, clientIf=5
08-30 19:18:03.281  3757  3768 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 19:18:03.282  2715  2729 D BtGatt.GattService: start scan with filters
08-30 19:18:03.285  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 19:18:03.285  2715  2782 D BtGatt.ScanManager: handling starting scan
08-30 19:18:03.285  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 19:18:03.285  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 19:18:03.285  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 19:18:03.286  2715  2782 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
08-30 19:18:03.287  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 19:18:03.287  3757  3757 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 19:18:03.288  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 19:18:03.289  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 19:18:03.291  3757  3807 I io.jxcore.node.ConnectionHelper: start: OK
08-30 19:18:03.293  2715  2769 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 19:18:03.293  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 19:18:03.294  2715  2782 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 19:18:03.299  2715  2769 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 19:18:03.299  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 19:18:03.299  2715  2782 D BtGatt.ScanManager: Starting BLE batch scan
08-30 19:18:03.300  2715  2782 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 19:18:03.311  2715  2769 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 19:18:03.311  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 19:18:03.317  2715  2769 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 19:18:03.317  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:03.788  3757  3757 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 19:18:03.788  3757  3757 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 19:18:03.789  3757  3757 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 19:18:04.824  2715  2715 D BtGatt.ScanManager: awakened up at time 133899
,08-30 19:18:04.828  2715  2782 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 19:18:04.878  2715  2769 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-30 19:18:04.879  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:04.879  2715  2769 D BtGatt.GattService: current time is 133955350176
,08-30 19:18:04.881  2715  2769 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -92, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -87, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -90, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -86, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 19:18:04.886  2715  2769 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-30 19:18:04.889  2715  2769 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-30 19:18:04.890  2715  2769 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 19:18:04.890  2715  2769 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 19:18:04.891  2715  2769 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 19:18:04.892  2715  2769 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 19:18:06.382  2715  2715 D BtGatt.ScanManager: awakened up at time 135457
08-30 19:18:06.384  2715  2782 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 19:18:06.413  2715  2769 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
08-30 19:18:06.414  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:06.415  2715  2769 D BtGatt.GattService: current time is 135490887257
,08-30 19:18:06.416  2715  2769 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -91, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -83, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 19:18:06.417  2715  2769 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-30 19:18:06.418  2715  2769 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 19:18:07.918  2715  2715 D BtGatt.ScanManager: awakened up at time 136993
,08-30 19:18:07.921  2715  2782 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 19:18:07.929  2715  2769 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 19:18:07.930  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:08.300  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 19:18:08.301  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 19:18:08.301  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 19:18:08.302  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:08.302  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 19:18:08.303  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 19:18:08.304  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 19:18:08.304  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 19:18:08.304  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 19:18:08.308  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 19:18:08.309  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 19:18:08.313  3757  3807 D BluetoothAdapter: STATE_ON
,08-30 19:18:08.316  2715  2913 D BtGatt.GattService: stopScan() - queue size =1
,08-30 19:18:08.319  2715  2727 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 19:18:08.321  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 19:18:08.323  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 19:18:08.323  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 19:18:08.323  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 19:18:08.325  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 19:18:08.330  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 19:18:08.332  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 19:18:08.333  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 19:18:08.335  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 19:18:08.337  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 19:18:08.337  2715  2769 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 19:18:08.337  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 19:18:08.338  2715  2782 D BtGatt.ScanManager: stopping BLe Batch
,08-30 19:18:08.340  3757  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 19:18:08.340  3757  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 19:18:08.341  3757  3757 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 19:18:08.341  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:18:08.341  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:08.341  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 19:18:08.342  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
08-30 19:18:08.342  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:08.342  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
,08-30 19:18:08.342  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:08.343  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:08.346  2715  2769 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 19:18:08.346  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 19:18:08.347  2715  2782 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 19:18:08.356  2715  2769 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 19:18:08.357  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:08.841  3757  3757 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 19:18:09.695   871  1869 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:18:13.346  3757  3807 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 19:18:13.352  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 19:18:13.365  3757  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 19:18:13.365  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:13.365  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:13.365  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:13.365  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:18:13.365  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:18:13.365  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:18:13.365  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 19:18:13.372  3757  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 19:18:13.373  3757  3807 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 19:18:13.373  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 19:18:13.374  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 19:18:13.374  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 19:18:13.374  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 19:18:13.375  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 19:18:13.381  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:13.386  3757  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 19:18:13.386  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 19:18:13.389  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:13.400  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 19:18:13.402  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 19:18:13.403  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 19:18:13.414  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 19:18:13.414  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 19:18:13.415  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 19:18:13.417  3757  3807 D BluetoothAdapter: STATE_ON
,08-30 19:18:13.424  2715  2913 D BtGatt.GattService: registerClient() - UUID=ce04bfe6-a6e0-4ac9-9f9c-c6f6193769e5
08-30 19:18:13.425  2715  2769 D BtGatt.GattService: onClientRegistered() - UUID=ce04bfe6-a6e0-4ac9-9f9c-c6f6193769e5, clientIf=5
,08-30 19:18:13.426  3757  3769 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 19:18:13.427  2715  2727 D BtGatt.GattService: start scan with filters
,08-30 19:18:13.436  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 19:18:13.436  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 19:18:13.436  2715  2782 D BtGatt.ScanManager: handling starting scan
,08-30 19:18:13.436  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 19:18:13.437  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 19:18:13.447  2715  2769 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 19:18:13.448  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:13.448  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 19:18:13.448  2715  2782 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 19:18:13.449  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 19:18:13.449  3757  3757 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 19:18:13.456  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 19:18:13.467  3757  3807 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 19:18:13.469  2715  2769 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 19:18:13.469  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:13.470  2715  2782 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 19:18:13.470  2715  2782 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 19:18:13.472  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 19:18:13.472  3757  3807 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 19:18:13.472  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 19:18:13.472  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 19:18:13.472  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:13.472  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 19:18:13.472  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 19:18:13.472  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 19:18:13.472  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 19:18:13.472  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 19:18:13.473  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 19:18:13.473  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 19:18:13.474  3757  3807 D BluetoothAdapter: STATE_ON,
08-30 19:18:13.474  2715  2727 D BtGatt.GattService: stopScan() - queue size =1
,08-30 19:18:13.481  2715  2913 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 19:18:13.481  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 19:18:13.481  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 19:18:13.481  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 19:18:13.481  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 19:18:13.481  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 19:18:13.482  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 19:18:13.482  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 19:18:13.483  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 19:18:13.483  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 19:18:13.483  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 19:18:13.485  3757  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 19:18:13.485  3757  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 19:18:13.485  3757  3757 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 19:18:13.485  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:18:13.485  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:13.485  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 19:18:13.486  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
08-30 19:18:13.486  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:13.486  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:13.486  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop,
08-30 19:18:13.486  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:13.487  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:13.487  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:13.488  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 19:18:13.488  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:18:13.488  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 19:18:13.488  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:13.489  3757  3807 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 19:18:13.491  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 19:18:13.495  2715  2769 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 19:18:13.495  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:13.497  3757  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 19:18:13.497  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:13.497  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:13.497  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:13.497  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:18:13.497  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:18:13.497  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:18:13.497  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 19:18:13.499  3757  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 19:18:13.499  3757  3807 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 19:18:13.500  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
,08-30 19:18:13.500  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 19:18:13.500  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 19:18:13.500  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 19:18:13.500  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 19:18:13.504  3757  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 19:18:13.504  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 19:18:13.505  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:18:13.505  2715  2769 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 19:18:13.505  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 19:18:13.508  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 19:18:13.509  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:13.510  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 19:18:13.510  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 19:18:13.513  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 19:18:13.513  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 19:18:13.513  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 19:18:13.514  3757  3807 D BluetoothAdapter: STATE_ON
,08-30 19:18:13.516  2715  2769 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 19:18:13.516  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:13.516  2715  2782 D BtGatt.ScanManager: stopping BLe Batch
08-30 19:18:13.516  2715  2727 D BtGatt.GattService: registerClient() - UUID=9a12b740-5275-4b35-a61e-18a51708d9ff
,08-30 19:18:13.517  2715  2769 D BtGatt.GattService: onClientRegistered() - UUID=9a12b740-5275-4b35-a61e-18a51708d9ff, clientIf=5
08-30 19:18:13.518  3757  3769 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 19:18:13.518  2715  2729 D BtGatt.GattService: start scan with filters
,08-30 19:18:13.522  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 19:18:13.522  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 19:18:13.522  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 19:18:13.522  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 19:18:13.522  2715  2769 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 19:18:13.523  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:13.523  2715  2782 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 19:18:13.525  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 19:18:13.525  3757  3757 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 19:18:13.526  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 19:18:13.527  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 19:18:13.529  2715  2769 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 19:18:13.529  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:13.530  3757  3807 I io.jxcore.node.ConnectionHelper: start: OK
08-30 19:18:13.530  2715  2782 D BtGatt.ScanManager: handling starting scan
,08-30 19:18:13.536  2715  2769 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 19:18:13.536  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:13.536  2715  2782 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 19:18:13.542  2715  2769 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 19:18:13.542  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:13.542  2715  2782 D BtGatt.ScanManager: Starting BLE batch scan
08-30 19:18:13.542  2715  2782 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 19:18:13.561  2715  2769 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 19:18:13.562  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:13.568  2715  2769 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 19:18:13.569  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:14.026  3757  3757 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 19:18:14.027  3757  3757 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 19:18:14.027  3757  3757 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 19:18:14.845   871  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 19:18:15.076  2715  2715 D BtGatt.ScanManager: awakened up at time 144151
,08-30 19:18:15.078  2715  2782 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 19:18:15.125  2715  2769 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-30 19:18:15.125  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:15.126  2715  2769 D BtGatt.GattService: current time is 144201656927
,08-30 19:18:15.126  2715  2769 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -88, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -87, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -92, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -67, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
,08-30 19:18:15.128  2715  2769 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-30 19:18:15.128  2715  2769 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-30 19:18:15.129  2715  2769 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-30 19:18:15.130  2715  2769 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 19:18:15.130  2715  2769 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-30 19:18:16.629  2715  2715 D BtGatt.ScanManager: awakened up at time 145704
,08-30 19:18:16.633  2715  2782 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 19:18:16.643  2715  2769 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 19:18:16.643  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:17.871   871  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 19:18:18.159  2715  2715 D BtGatt.ScanManager: awakened up at time 147235
,08-30 19:18:18.162  2715  2782 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 19:18:18.190  2715  2769 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 19:18:18.190  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:18.498  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:18:18.515  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:18:18.520  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:18:18.530  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 19:18:18.531  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
08-30 19:18:18.531  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 19:18:18.531  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:18.531  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 19:18:18.542  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 19:18:18.543  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 19:18:18.543  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 19:18:18.543  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 19:18:18.543  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 19:18:18.544  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 19:18:18.546  3757  3807 D BluetoothAdapter: STATE_ON
08-30 19:18:18.548  2715  3825 D BtGatt.GattService: stopScan() - queue size =1
08-30 19:18:18.550  2715  2727 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 19:18:18.551  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 19:18:18.551  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 19:18:18.552  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 19:18:18.554  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 19:18:18.555  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 19:18:18.557  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 19:18:18.558  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 19:18:18.558  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 19:18:18.558  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 19:18:18.560  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 19:18:18.565  3757  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 19:18:18.565  3757  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 19:18:18.565  3757  3757 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 19:18:18.569  2715  2769 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 19:18:18.569  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:18.570  2715  2782 D BtGatt.ScanManager: stopping BLe Batch
,08-30 19:18:18.579  1510  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 19:18:18.580  1510  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 19:18:18.580  1510  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:18:18.580  1510  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:18:18.583  2715  2769 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 19:18:18.584  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:18.584  2715  2782 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 19:18:18.592  2715  2769 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 19:18:18.592  2715  2769 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:18:18.599  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 19:18:18.600  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 19:18:18.600  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-30 19:18:19.066  3757  3757 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 19:18:19.067  3757  3757 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 19:18:19.067  3757  3757 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 19:18:23.566  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 19:18:23.566  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 19:18:23.567  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 19:18:23.567  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 19:18:23.567  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.568  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 19:18:23.568  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
08-30 19:18:23.568  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:23.569  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:23.569  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:23.569  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.571  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.571  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:23.575  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:18:23.576  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:18:23.576  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 19:18:23.576  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:23.579  3757  3807 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-30 19:18:23.581  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 19:18:23.581  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 19:18:23.582  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 19:18:23.582  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 19:18:23.582  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:23.583  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:23.583  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
08-30 19:18:23.583  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:23.584  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
,08-30 19:18:23.584  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 19:18:23.584  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.585  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.585  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:23.585  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.588  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 19:18:23.589  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 19:18:23.589  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 19:18:23.589  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:23.592  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 19:18:23.593  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 19:18:23.593  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 19:18:23.593  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 19:18:23.594  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:18:23.595  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.595  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.596  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
08-30 19:18:23.596  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 19:18:23.596  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:23.596  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:23.597  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.597  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:23.597  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.598  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.601  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:18:23.602  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:18:23.602  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:23.602  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:23.604  3757  3807 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 19:18:23.605  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 19:18:23.605  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 19:18:23.606  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 19:18:23.607  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:18:23.607  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.607  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.607  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
,08-30 19:18:23.608  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:23.608  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:23.608  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:23.608  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.608  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.609  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.609  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:23.611  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:18:23.612  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:18:23.612  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:23.612  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
,08-30 19:18:23.614  3757  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 19:18:23.615  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 19:18:23.615  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 19:18:23.615  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 19:18:23.616  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 19:18:23.616  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.616  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.617  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
,08-30 19:18:23.617  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:23.618  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:23.618  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:23.618  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.618  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.618  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:23.618  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.619  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:18:23.619  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 19:18:23.619  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:23.619  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
,08-30 19:18:23.620  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 19:18:23.620  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 19:18:23.620  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 19:18:23.620  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 19:18:23.621  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 19:18:23.621  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 19:18:23.621  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 19:18:23.621  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 19:18:23.622  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 19:18:23.622  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 19:18:23.622  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 19:18:23.622  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 19:18:23.623  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:18:23.623  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.623  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:23.623  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
08-30 19:18:23.623  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:23.623  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:23.623  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:23.623  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.624  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.624  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.624  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.625  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:18:23.625  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:18:23.625  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:23.625  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
,08-30 19:18:23.626  3757  3807 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 19:18:23.627  3757  3807 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 19:18:23.627  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-30 19:18:23.633  3757  3807 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 19:18:23.633  3757  3807 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 19:18:23.633  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 19:18:23.633  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 19:18:23.634  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 19:18:23.634  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 19:18:23.634  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-30 19:18:23.634  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 19:18:23.634  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 19:18:23.634  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 19:18:23.634  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 19:18:23.634  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 19:18:23.634  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 19:18:23.634  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 19:18:23.634  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-30 19:18:23.635  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 19:18:23.635  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 19:18:23.635  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 19:18:23.635  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 19:18:23.635  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 19:18:23.635  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 19:18:23.635  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-30 19:18:23.636  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 19:18:23.637  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 19:18:23.637  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 19:18:23.638  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-30 19:18:23.638  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 19:18:23.638  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-30 19:18:23.639  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 19:18:23.639  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 19:18:23.639  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 19:18:23.639  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-30 19:18:23.640  3757  3807 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-30 19:18:23.642  3757  3807 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 19:18:23.642  3757  3807 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-30 19:18:23.643  3757  3807 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 19:18:23.643  3757  3807 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 19:18:23.643  3757  3807 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-30 19:18:23.643  3757  3807 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 19:18:23.644  3757  3807 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 19:18:23.644  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-30 19:18:23.647  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-30 19:18:23.649  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-30 19:18:23.650  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-30 19:18:23.651  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 19:18:23.652  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 19:18:23.652  3757  3807 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-30 19:18:23.652  3757  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 382)
08-30 19:18:23.652  3757  3807 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 19:18:23.653  3757  3807 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 19:18:23.655  3757  3827 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 19:18:23.656  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 19:18:23.657  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 19:18:23.657  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 19:18:23.658  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 19:18:23.658  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.659  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:23.659  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-30 19:18:23.661  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
,08-30 19:18:23.662  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 19:18:23.662  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
,08-30 19:18:23.662  3757  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 382
,08-30 19:18:23.662  3757  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 382),
,08-30 19:18:23.662  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:23.662  2715  2910 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
,08-30 19:18:23.662  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:23.662  3757  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 382)
08-30 19:18:23.662  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:23.663  3757  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 382)
08-30 19:18:23.663  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:23.663  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:23.665  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:18:23.665  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 19:18:23.666  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:23.666  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
,08-30 19:18:23.668  3757  3807 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 19:18:23.670  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 19:18:23.670  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 19:18:23.671  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 19:18:23.671  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:18:23.671  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:23.671  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.672  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
,08-30 19:18:23.672  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:23.672  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
,08-30 19:18:23.672  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:23.672  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:23.672  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.672  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:23.672  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.674  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:18:23.674  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-30 19:18:23.674  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:23.674  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list,
08-30 19:18:23.675  3757  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-30 19:18:23.675  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 19:18:23.675  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 19:18:23.675  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 19:18:23.675  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:18:23.675  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:23.676  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.676  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
,08-30 19:18:23.676  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:23.676  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
,08-30 19:18:23.676  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:23.676  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:23.676  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.676  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:23.676  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.678  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 19:18:23.678  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:18:23.678  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:23.678  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
,08-30 19:18:23.679  3757  3807 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 19:18:23.679  3757  3807 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-30 19:18:23.679  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 19:18:23.679  3757  3807 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 19:18:23.679  3757  3807 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-30 19:18:23.679  3757  3807 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 19:18:23.679  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 19:18:23.680  3757  3807 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 19:18:23.680  3757  3807 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 19:18:23.680  3757  3807 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 19:18:23.680  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 19:18:23.680  3757  3807 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 19:18:23.680  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 19:18:23.680  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 19:18:23.680  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 19:18:23.680  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:18:23.681  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.681  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.681  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
08-30 19:18:23.681  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:23.681  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:23.681  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:23.681  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.681  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.681  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.681  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.683  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:18:23.683  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:18:23.683  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:23.683  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:23.684  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 19:18:23.684  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:23.684  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:23.684  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
08-30 19:18:23.684  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:23.684  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:23.685  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:23.685  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:23.685  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:23.828   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-30 19:18:23.839  1873  1873 I Keyboard.Facilitator: onFinishInput()
,08-30 19:18:23.848   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 19:18:23.848   871   891 I Adreno  : Build Date                       : 10/20/15
08-30 19:18:23.848   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 19:18:23.848   871   891 I Adreno  : Local Branch                     : M14
08-30 19:18:23.848   871   891 I Adreno  : Remote Branch                    : 
08-30 19:18:23.848   871   891 I Adreno  : Remote Branch                    : 
08-30 19:18:23.848   871   891 I Adreno  : Reconstruct Branch               : 
,08-30 19:18:23.902   281   305 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (714 us)
,08-30 19:18:24.537  3757  3757 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 19:18:24.538  3757  3757 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 19:18:24.582   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-30 19:18:24.593  3757  3757 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5837b7a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@e3a9ec3, 16908290=android.view.AbsSavedState$1@e3a9ec3}, android:focusedViewId=100}]}]
,08-30 19:18:24.594  3757  3757 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 19:18:24.595  3757  3757 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 19:18:24.595  3757  3757 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 19:18:24.599   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-30 19:18:24.603   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-30 19:18:24.604   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-30 19:18:24.604   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-30 19:18:24.838   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 19:18:24.841   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-30 19:18:24.848   871  1330 D SurfaceControl: Excessive delay in setPowerMode(): 245ms
08-30 19:18:24.852   871   891 I DreamManagerService: Entering dreamland.
,08-30 19:18:24.853   871   891 I PowerManagerService: Dozing...
,08-30 19:18:24.854   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-30 19:18:24.940   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-30 19:18:24.941   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-30 19:18:24.954   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 19:18:24.970   871  1306 E native  : do suspend false
,08-30 19:18:24.981  1939  3831 D NfcService: Discovery configuration equal, not updating.
,08-30 19:18:24.995   871  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 19:18:25.024   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 19:18:25.032   871  1306 E native  : do suspend true
,08-30 19:18:25.067   376  1276 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-30 19:18:25.068   376  1276 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-30 19:18:25.459   871  1306 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-30 19:18:28.686  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 19:18:28.686  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:28.686  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 19:18:28.687  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:28.687  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:28.687  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
08-30 19:18:28.688  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 19:18:28.688  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 19:18:28.688  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 19:18:28.689  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 19:18:28.689  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:28.689  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:28.690  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
08-30 19:18:28.690  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 19:18:28.690  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:28.691  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:28.691  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:28.691  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:28.692  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:28.692  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:28.696  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:18:28.697  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:18:28.697  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:28.697  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
,08-30 19:18:28.702  3757  3807 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-30 19:18:28.703  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 19:18:28.705  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-30 19:18:28.706  3757  3807 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 19:18:28.706  3757  3807 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 19:18:28.707  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 19:18:28.707  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 19:18:28.707  3757  3757 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-30 19:18:28.707  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 19:18:28.707  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 19:18:28.707  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 19:18:28.707  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 19:18:28.707  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:28.707  3757  3807 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-30 19:18:28.708  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
,08-30 19:18:28.708  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 19:18:28.708  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
,08-30 19:18:28.708  3757  3757 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-30 19:18:28.709  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 19:18:28.709  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 19:18:28.710  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:28.710  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:28.711  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 19:18:28.712  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:28.712  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 19:18:28.712  3757  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 19:18:28.712  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-30 19:18:28.712  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 19:18:28.712  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 19:18:28.712  3757  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 19:18:28.712  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:28.714  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:28.711  3757  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-30 19:18:28.714  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
,08-30 19:18:28.714  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:28.714  3757  3757 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 19:18:28.714  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:28.714  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:28.714  3757  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-30 19:18:28.715  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:28.715  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:28.715  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:28.715  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:28.716  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 19:18:28.716  3757  3757 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 19:18:28.718  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 19:18:28.718  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:28.718  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:28.720  3757  3807 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage,
08-30 19:18:28.720  3757  3807 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 19:18:28.720  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 19:18:28.721  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 19:18:28.721  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 19:18:28.721  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 19:18:28.721  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 19:18:28.721  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 19:18:28.721  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:18:28.721  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:28.721  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:28.721  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
08-30 19:18:28.721  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:28.722  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:28.722  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:28.722  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 19:18:28.722  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:28.722  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 19:18:28.722  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:28.723  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 19:18:28.723  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:18:28.724  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 19:18:28.724  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:28.732  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 19:18:28.733  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 19:18:28.733  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 19:18:28.734  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:18:28.734  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:28.734  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-30 19:18:28.734  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
08-30 19:18:28.735  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 19:18:28.735  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:28.735  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:28.735  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:28.736  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:28.736  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:28.736  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:28.738  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 19:18:28.738  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:18:28.738  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 19:18:28.739  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:28.741  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 19:18:28.741  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 19:18:28.742  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 19:18:28.742  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:18:28.743  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:28.743  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:28.743  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f62610 not in the list
,08-30 19:18:28.743  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:28.744  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:28.744  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:28.744  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:28.745  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:28.745  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:28.745  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:28.747  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:18:28.747  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 19:18:28.747  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:28.748  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c74509 not in the list
08-30 19:18:28.749  3757  3807 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 19:18:28.749  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 19:18:28.749  3757  3807 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-30 19:18:28.749  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 19:18:28.750  3757  3807 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 19:18:28.750  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 19:18:28.753  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-30 19:18:28.753  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 19:18:28.754  3757  3807 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 19:18:28.754  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left,
08-30 19:18:28.754  3757  3807 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 19:18:28.754  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 19:18:28.754  3757  3807 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-30 19:18:28.754  3757  3807 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 19:18:28.755  3757  3807 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 19:18:28.755  3757  3807 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-30 19:18:28.755  3757  3807 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 19:18:28.756  3757  3807 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 19:18:28.756  3757  3807 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 19:18:28.756  3757  3807 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing,
08-30 19:18:28.757  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 19:18:28.757  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9273340 added. We now have 3 listener(s)
,08-30 19:18:28.757  3757  3807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 19:18:28.759  3757  3807 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 19:18:28.759   871  1996 D WifiService: setWifiEnabled: true pid=3757, uid=10000
,08-30 19:18:28.759   871  1996 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 19:18:28.790  2715  2896 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40,
08-30 19:18:28.790  2715  2896 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-30 19:18:29.056  1888  2652 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 19:18:29.215  3757  3757 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 19:18:33.768  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 19:18:33.769  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ace8279 added. We now have 4 listener(s)
08-30 19:18:33.769  3757  3807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 19:18:33.786  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 19:18:33.787  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ace8279 removed from the list
08-30 19:18:33.787  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:33.788  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:33.788  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:33.790  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 19:18:33.791  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8449bbe added. We now have 4 listener(s)
,08-30 19:18:33.791  3757  3807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 19:18:33.794  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 19:18:33.795  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8449bbe removed from the list
08-30 19:18:33.795  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 19:18:33.795  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:33.796  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:33.798  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 19:18:33.798  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f9e641f added. We now have 4 listener(s)
08-30 19:18:33.799  3757  3807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 19:18:33.807   871  1981 D WifiService: setWifiEnabled: false pid=3757, uid=10000
,08-30 19:18:33.808   871  1981 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 19:18:33.819  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 19:18:33.821  2715  2764 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 19:18:33.822  2715  2764 D BluetoothAdapterProperties: Setting state to 13
08-30 19:18:33.822  2715  2764 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 19:18:33.824  2715  2764 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 19:18:33.829  2715  2764 I BluetoothAdapterState: Entering PendingCommandState
,08-30 19:18:33.832  2715  2769 D BluetoothAdapterProperties: Scan Mode:20
,08-30 19:18:33.832  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:33.832  3757  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 19:18:33.832  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:33.832  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:33.832  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:33.832  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:33.832  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:18:33.832  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:18:33.832  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 19:18:33.835  2715  2764 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-30 19:18:33.835  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:33.835  3757  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 19:18:33.835  3757  3807 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 19:18:33.837  2715  2715 D HeadsetService: Received stop request...Stopping profile...
08-30 19:18:33.839   871   871 D BluetoothHeadset: Proxy object disconnected
,08-30 19:18:33.839  2715  2715 V BluetoothAdapterState: isTurningOff()=true
,08-30 19:18:33.839  2715  2715 V BluetoothAdapterState: isTurningOn()=false
,08-30 19:18:33.839   871   871 D BluetoothHeadset: Proxy object disconnected
,08-30 19:18:33.839  2715  2715 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 19:18:33.840  2715  2715 V BluetoothAdapterState: isBleTurningOff()=false
08-30 19:18:33.840   871   871 D BluetoothHeadset: Proxy object disconnected
,08-30 19:18:33.841  1350  1361 D BluetoothHeadset: Proxy object disconnected
,08-30 19:18:33.842  1350  1350 D HeadsetProfile: Bluetooth service disconnected
,08-30 19:18:33.844  1955  2139 D BluetoothHeadset: Proxy object disconnected
,08-30 19:18:33.845  2715  2715 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 19:18:33.845  2715  2896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 19:18:33.845  2715  2896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 19:18:33.846  2715  2896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 19:18:33.846  2715  2769 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 19:18:33.846  2715  2715 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 19:18:33.848  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:18:33.853  1455  1455 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 19:18:33.855  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:18:33.853  2715  2715 D A2dpService: Received stop request...Stopping profile...
08-30 19:18:33.856  2715  2916 D A2dpStateMachine: Exit Disconnected: -1
08-30 19:18:33.856   871  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 19:18:33.856   871  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-30 19:18:33.857   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 19:18:33.857   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 19:18:33.858  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:33.858  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:33.858  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:33.858  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:33.858  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:33.858  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:33.858  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:18:33.858  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:18:33.858  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 19:18:33.859  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:33.859  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 19:18:33.862   871  1306 E native  : do suspend true
,08-30 19:18:33.865  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:33.865  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:33.865  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:33.865  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:33.865  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:33.865  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:33.865  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:18:33.865  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:18:33.865  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 19:18:33.867   871   884 I ActivityManager: Start proc 3840:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-30 19:18:33.869  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:33.869  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 19:18:33.870  2715  2715 D BluetoothMapService: onReceive
08-30 19:18:33.870  2715  2715 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 19:18:33.870  2715  2715 D BluetoothMapService: STATE_TURNING_OFF
08-30 19:18:33.870  2715  2715 V BluetoothAdapterState: isTurningOff()=true
,08-30 19:18:33.871  2715  2715 V BluetoothAdapterState: isTurningOn()=false
08-30 19:18:33.871   871   871 D BluetoothA2dp: Proxy object disconnected
08-30 19:18:33.871  2715  2715 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:18:33.871  2715  2715 V BluetoothAdapterState: isBleTurningOff()=false
08-30 19:18:33.871  2715  2715 D HidService: Received stop request...Stopping profile...
08-30 19:18:33.871  2715  2715 D HidService: Stopping Bluetooth HidService
08-30 19:18:33.873  2715  2769 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 19:18:33.873  2715  2896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 19:18:33.873  2715  2896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 19:18:33.873  2715  2896 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 19:18:33.874  2715  2896 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 19:18:33.874  2715  2896 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 19:18:33.874  2715  2896 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 19:18:33.874  2715  2715 D HealthService: Received stop request...Stopping profile...
08-30 19:18:33.875  2715  2715 D BluetoothMapService: MAP Service closeService in
,08-30 19:18:33.875  2715  2715 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 19:18:33.875  2715  2715 D ObexServerSockets0: shutdown(block = true)
08-30 19:18:33.875  2715  2715 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 19:18:33.875  2715  2715 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 19:18:33.876  2715  2922 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 19:18:33.876  2715  2910 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-30 19:18:33.876  2715  2921 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 19:18:33.876  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:18:33.876  2715  2715 I BtOppRfcommListener: stopping Accept Thread
08-30 19:18:33.876  2715  3442 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 19:18:33.877  2715  3442 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 19:18:33.878  2715  2715 D PanService: Received stop request...Stopping profile...
08-30 19:18:33.879  2715  2715 V BluetoothAdapterState: isTurningOff()=true
08-30 19:18:33.879  2715  2715 V BluetoothAdapterState: isTurningOn()=false
08-30 19:18:33.879  2715  2715 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 19:18:33.879  2715  2715 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 19:18:33.879  2715  2715 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-30 19:18:33.879  2715  2769 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 19:18:33.879  2715  2715 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 19:18:33.880  1350  1350 D BluetoothA2dp: Proxy object disconnected
08-30 19:18:33.880  2715  2715 D BluetoothMapService: Received stop request...Stopping profile...
08-30 19:18:33.880  2715  2715 D BluetoothMapService: stop()
08-30 19:18:33.880  1350  1350 D BluetoothInputDevice: Proxy object disconnected
08-30 19:18:33.880  1350  1350 D HidProfile: Bluetooth service disconnected
08-30 19:18:33.880  1350  1350 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 19:18:33.881  1350  1350 D PanProfile: Bluetooth service disconnected
08-30 19:18:33.881  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:33.881  2715  2715 D BluetoothMapAppObserver: deinitObservers()
,08-30 19:18:33.881  2715  2715 D BluetoothMapAppObserver: removeReceiver()
,08-30 19:18:33.882  1350  1350 D BluetoothMap: Proxy object disconnected
08-30 19:18:33.882  1350  1350 D MapProfile: Bluetooth service disconnected
08-30 19:18:33.883  2715  2715 V BluetoothAdapterState: isTurningOff()=true
08-30 19:18:33.883  2715  2715 V BluetoothAdapterState: isTurningOn()=false
08-30 19:18:33.883  2715  2715 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:18:33.883  2715  2715 V BluetoothAdapterState: isBleTurningOff()=false
08-30 19:18:33.883  2715  2715 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 19:18:33.883  2715  2769 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 19:18:33.884  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:18:33.885  2715  2715 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-30 19:18:33.887  2715  2715 V BluetoothAdapterState: isTurningOff()=true
08-30 19:18:33.887  2715  2715 V BluetoothAdapterState: isTurningOn()=false
,08-30 19:18:33.887  2715  2715 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 19:18:33.887  2715  2715 V BluetoothAdapterState: isBleTurningOff()=false
08-30 19:18:33.887  2715  2715 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 19:18:33.887  2715  2715 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 19:18:33.889  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:18:33.889  2715  2715 D BluetoothMapService: MAP Service closeService in
08-30 19:18:33.889  2715  2715 V BluetoothAdapterState: isTurningOff()=true
08-30 19:18:33.889  2715  2715 V BluetoothAdapterState: isTurningOn()=false
08-30 19:18:33.889  2715  2715 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:18:33.889  2715  2715 V BluetoothAdapterState: isBleTurningOff()=false
08-30 19:18:33.890   871  1875 D DhcpClient: Clearing IP address
,08-30 19:18:33.890  2715  2764 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 19:18:33.890  2715  2764 D BluetoothAdapterProperties: Setting state to 15
08-30 19:18:33.890   372   869 D CommandListener: Clearing all IP addresses on wlan0
08-30 19:18:33.890  2715  2764 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 19:18:33.891   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 19:18:33.891  2715  2764 I BluetoothAdapterState: Entering BleOnState
08-30 19:18:33.891  1350  1361 D BluetoothPan: onBluetoothStateChange on: false
,08-30 19:18:33.891  2715  2715 D BluetoothMapService: cleanup()
08-30 19:18:33.891  2715  2715 D BluetoothMapService: MAP Service closeService in
08-30 19:18:33.892  1350  2074 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 19:18:33.895  1510  2494 V NativeCrypto: Read error: ssl=0x9a6e4200: I/O error during system call, Connection timed out
08-30 19:18:33.898   372   869 D CommandListener: Setting iface cfg
08-30 19:18:33.899  1510  2494 V NativeCrypto: SSL shutdown failed: ssl=0x9a6e4200: I/O error during system call, Broken pipe
08-30 19:18:33.901  1350  1364 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 19:18:33.901   871  1981 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-30 19:18:33.902   871  1865 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-30 19:18:33.902   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 19:18:33.902  1955  2137 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 19:18:33.902   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 19:18:33.902   871  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-30 19:18:33.902   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 19:18:33.902   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-30 19:18:33.903   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 19:18:33.903   871  1306 E native  : do suspend true
08-30 19:18:33.908   405   405 E Parcel  : Reading a NULL string not supported here.
08-30 19:18:33.911   871  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 19:18:33.916   871  1865 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-30 19:18:33.921  1350  1364 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 19:18:33.921   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 19:18:33.922  1350  1361 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 19:18:33.924   871  1886 D DhcpClient: Receive thread stopped
,08-30 19:18:33.934  1350  2074 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 19:18:33.937  2715  2764 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-30 19:18:33.937  2715  2764 D BluetoothAdapterProperties: Setting state to 16
,08-30 19:18:33.937  2715  2764 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 19:18:33.938  2715  2764 D BluetoothAdapterProperties: onBleDisable
,08-30 19:18:33.938  2715  2764 I BluetoothAdapterState: Entering PendingCommandState
,08-30 19:18:33.938  2715  2766 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-30 19:18:33.939  2715  2896 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-30 19:18:33.939  2715  2896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 19:18:33.939  2715  2769 D BluetoothAdapterProperties: Scan Mode:20
08-30 19:18:33.941  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-30 19:18:33.941  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:33.941  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:33.941  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:33.941  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:33.941  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:33.941  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:33.941  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:33.941  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 19:18:33.942  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:33.942  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 19:18:33.943  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:33.943  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:33.943  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:33.943  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:33.943  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:33.943  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:33.943  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:33.943  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:33.943  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 19:18:33.943  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:33.943  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 19:18:33.946  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-30 19:18:33.946  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:33.946  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:33.946  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:33.946  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:33.946  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:33.946  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:33.946  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:33.946  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 19:18:33.946  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:33.946  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 19:18:33.947  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:18:33.948  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:33.949  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:33.955   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 19:18:33.963  3840  3840 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-30 19:18:33.973  3840  3840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 19:18:33.974   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 19:18:33.975   372   869 D CommandListener: Clearing all IP addresses on wlan0
08-30 19:18:33.975   871  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 19:18:33.975   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 19:18:33.976   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-30 19:18:33.979  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:33.980   871  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 19:18:33.980  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:18:33.981  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:18:33.983  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 19:18:33.984  3387  3387 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@fbdee5c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-30 19:18:33.990   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@52dda66:true
,08-30 19:18:33.996   871  2154 I ActivityManager: Start proc 3860:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-30 19:18:33.998   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 19:18:34.001   871  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-30 19:18:34.005  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:34.005  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:34.005  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:34.005  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:34.005  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 19:18:34.005  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:34.005  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:34.005  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:34.005  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 19:18:34.006  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:34.006  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 19:18:34.008  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:34.008  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:34.008  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:34.008  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:34.008  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 19:18:34.008  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:34.008  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:34.008  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:34.008  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 19:18:34.008  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:34.009  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 19:18:34.010  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:34.010  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:34.010  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:34.010  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:34.010  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 19:18:34.010  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:34.010  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:34.010  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:34.010  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 19:18:34.010  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:34.010  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 19:18:34.012  1888  2298 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 19:18:34.040   372   869 E Netd    : netlink response contains error (No such file or directory)
,08-30 19:18:34.041   871  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 19:18:34.049  3860  3860 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-30 19:18:34.055  3840  3840 D LocalBluetoothProfileManager: Adding local MAP profile
,08-30 19:18:34.057  3840  3840 D BluetoothMap: Create BluetoothMap proxy object
,08-30 19:18:34.068  3840  3840 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 19:18:34.079  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:18:34.080  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:18:34.096  1510  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 19:18:34.097  1510  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 19:18:34.097  1510  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:18:34.097  1510  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:18:34.108  3004  3858 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 19:18:34.108  3004  3858 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at jdm.a(PG:82)
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at jcs.o(PG:406)
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at jcn.a(PG:1379)
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at jcs.i(PG:143)
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at blb.a(PG:3937)
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at czp.a(PG:18188)
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at czp.a(PG:9081)
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at czq.run(PG:1686)
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 19:18:34.108  3004  3858 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at jdj.a(PG:4091)
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at jdj.a(PG:1125)
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at jdm.a(PG:77)
08-30 19:18:34.108  3004  3858 E HttpOperation: 	... 12 more
08-30 19:18:34.108  3004  3858 E HttpOperation: Caused by: faj: BadAuthentication
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at fal.a(PG:38)
08-30 19:18:34.108  3004  3858 E HttpOperation: 	at jdj.a(PG:4089)
08-30 19:18:34.108  3004  3858 E HttpOperation: 	... 14 more
,08-30 19:18:34.132  1510  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 19:18:34.132  1510  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 19:18:34.132  1510  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:18:34.132  1510  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:18:34.143  2715  2769 I bt_hci  : shut_down
,08-30 19:18:34.143  2715  2788 D bt_hwcfg: hw_epilog_process
08-30 19:18:34.144  3840  3840 D DockEventReceiver: finishStartingService: stopping service
,08-30 19:18:34.147  2715  2788 I bt_vendor: low_power_mode_cb
,08-30 19:18:34.165  3004  3858 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 19:18:34.165  3004  3858 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at jdm.a(PG:82)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at jcs.o(PG:406)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at jcn.a(PG:1379)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at jcs.i(PG:143)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at hec.a(PG:42)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at hee.a(PG:102)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at czr.a(PG:65)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at kka.a(PG:108)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at czp.a(PG:19176)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at czp.a(PG:9081)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at czq.run(PG:1686)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 19:18:34.165  3004  3858 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at jdj.a(PG:4091)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at jdj.a(PG:1125)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at jdm.a(PG:77)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	... 15 more
08-30 19:18:34.165  3004  3858 E HttpOperation: Caused by: faj: BadAuthentication
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at fal.a(PG:38)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	at jdj.a(PG:4089)
08-30 19:18:34.165  3004  3858 E HttpOperation: 	... 17 more
,08-30 19:18:34.166  3004  3858 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 19:18:34.166  3004  3858 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: ,	at jcs.o(PG:406)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at hec.a(PG:42)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at hee.a(PG:102)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at czr.a(PG:65)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at kka.a(PG:108)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	... 15 more
08-30 19:18:34.166  3004  3858 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at fal.a(PG:38)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 19:18:34.166  3004  3858 E ExperimentLoader: 	... 17 more
,08-30 19:18:34.173  2715  2788 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-30 19:18:34.173  2715  2788 I bt_vendor: epilog_cb
,08-30 19:18:34.173  2715  2788 I bt_hci  : epilog_finished_callback
,08-30 19:18:34.177  2715  2769 I bt_hci_h4: hal_close
,08-30 19:18:34.177  2715  2769 I bt_userial_vendor: device fd = 51 close
,08-30 19:18:34.264   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 162878, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-30 19:18:34.266   871  2000 I ActivityManager: Killing 3212:com.google.android.gm/u0a78 (adj 15): empty #17
,08-30 19:18:34.392  3860  3860 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 19:18:34.392  3860  3860 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 19:18:34.392  3860  3860 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 19:18:34.392  3860  3860 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 19:18:34.393  3860  3860 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 19:18:34.393  3860  3860 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 19:18:34.393  3860  3860 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 19:18:34.393  3860  3860 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 19:18:34.393  3860  3860 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 19:18:34.393  3860  3860 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 19:18:34.496  2715  2766 D bt_stack_manager: event_shut_down_stack finished.
,08-30 19:18:34.496  2715  2764 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 19:18:34.501  3840  3840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 19:18:34.503  2715  2715 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 19:18:34.503  2715  2764 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 19:18:34.505  2715  2715 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 19:18:34.505  2715  2715 D BtGatt.GattService: stop()
,08-30 19:18:34.505  2715  2715 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 19:18:34.510  2715  2715 V BluetoothAdapterState: isTurningOff()=false
08-30 19:18:34.510  2715  2715 V BluetoothAdapterState: isTurningOn()=false
08-30 19:18:34.511  2715  2715 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:18:34.511  2715  2715 V BluetoothAdapterState: isBleTurningOff()=true
08-30 19:18:34.511  2715  2764 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-30 19:18:34.512  2715  2764 D BluetoothAdapterProperties: Setting state to 10
08-30 19:18:34.512  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 19:18:34.512  2715  2764 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 19:18:34.513  2715  2764 I BluetoothAdapterState: Entering OffState
08-30 19:18:34.515   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-30 19:18:34.522  3840  3840 D DockEventReceiver: finishStartingService: stopping service
,08-30 19:18:34.535  2715  2715 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 19:18:34.535  2715  2715 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 19:18:34.535   871  2153 I ActivityManager: Killing 3387:com.google.android.music:main/u0a66 (adj 15): empty #17
08-30 19:18:34.535  2715  2715 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 19:18:34.536  2715  2766 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 19:18:34.539  2715  2766 D bt_stack_manager: event_clean_up_stack finished.
,08-30 19:18:34.546  2715  2715 I art     : System.exit called, status: 0
,08-30 19:18:34.546  2715  2715 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 19:18:34.676  3860  3881 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 19:18:34.685   871  2128 I ActivityManager: Process com.android.bluetooth (pid 2715) has died
,08-30 19:18:34.700   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8771daa:true
,08-30 19:18:34.727  1705  1705 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 19:18:34.731  1705  1705 D SystemUpdateService: onCreate
,08-30 19:18:34.741  1705  1705 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 19:18:34.743  1705  3898 I SystemUpdateService: active receiver: enabled
,08-30 19:18:34.749  1705  3898 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 19:18:34.751  1705  3898 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 19:18:34.751  1705  3898 I SystemUpdateService: now status is 0 (complete)
08-30 19:18:34.751  1705  3898 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 19:18:34.751  1705  3898 I SystemUpdateService: file has been verified
08-30 19:18:34.752  1705  1705 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-30 19:18:34.752  1705  3898 I SystemUpdateService: OTA package size = 12249756
,08-30 19:18:34.756  1705  2462 I iu.UploadsManager: num queued entries: 0
,08-30 19:18:34.757  1705  2462 I iu.UploadsManager: num updated entries: 0
,08-30 19:18:34.757  1705  3898 I SystemUpdateService: showing system update notification
,08-30 19:18:34.759  1705  2462 I iu.SyncManager: NEXT; no task
,08-30 19:18:34.767  1705  1705 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 19:18:34.769  1705  1705 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 19:18:34.781   871  1913 I ActivityManager: Start proc 3901:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-30 19:18:34.785  1705  1705 D SystemUpdateService: onDestroy
,08-30 19:18:34.812  3901  3901 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-30 19:18:34.815  3901  3901 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 19:18:34.820  3901  3901 D SprintDMHelper: simOperator: 
,08-30 19:18:34.820  3901  3901 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 19:18:34.835   871  2154 I ActivityManager: Start proc 3913:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-30 19:18:34.907  2268  3927 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 19:18:34.936   871  1381 I ActivityManager: Start proc 3928:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-30 19:18:34.938   871  2128 I ActivityManager: Killing 2791:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-30 19:18:35.012  3928  3928 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-30 19:18:35.087  3928  3928 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 19:18:35.087  3928  3928 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 19:18:35.087  3928  3928 I GAv4    :   adb logcat -s GAv4
,08-30 19:18:35.104  3928  3928 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 19:18:35.111  3928  3928 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 19:18:35.135  3928  3946 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 19:18:35.247  3928  3928 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-30 19:18:35.286  3928  3928 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 19:18:35.296  3928  3928 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4368-4371)
,08-30 19:18:35.296  3928  3928 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 19:18:35.309  3928  3928 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c79aeb6}
,08-30 19:18:35.310  3928  3928 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 19:18:35.310  3928  3928 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 19:18:35.319  3928  3928 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 19:18:35.320  3928  3928 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 19:18:35.337  3928  3928 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 19:18:35.351  3928  3928 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 19:18:35.351  3928  3928 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 19:18:35.351  3928  3928 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 19:18:35.351  3928  3928 I Adreno  : Build Date                       : 10/20/15
08-30 19:18:35.351  3928  3928 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 19:18:35.351  3928  3928 I Adreno  : Local Branch                     : M14
08-30 19:18:35.351  3928  3928 I Adreno  : Remote Branch                    : 
08-30 19:18:35.351  3928  3928 I Adreno  : Remote Branch                    : 
08-30 19:18:35.351  3928  3928 I Adreno  : Reconstruct Branch               : 
,08-30 19:18:35.429  3928  3928 I NSApplication: Starting up...
,08-30 19:18:35.442  3928  3974 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 19:18:35.474   871  2000 I ActivityManager: Start proc 3979:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-30 19:18:35.475   871  2000 I ActivityManager: Killing 1686:android.process.acore/u0a5 (adj 15): empty #17
,08-30 19:18:35.562  3979  3979 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-30 19:18:35.757   871  2155 I ActivityManager: Killing 3611:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-30 19:18:35.835   871  2000 I ActivityManager: Start proc 3993:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-30 19:18:35.922  3993  3993 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-30 19:18:35.979  3993  3993 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-30 19:18:36.066   871  1981 I ActivityManager: Killing 3626:com.android.musicfx/u0a18 (adj 15): empty #17
,08-30 19:18:38.853   871  1390 D WifiService: setWifiEnabled: true pid=3757, uid=10000
,08-30 19:18:38.854   871  1390 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 19:18:38.864   871  1306 D WifiConfigStore: Loading config and enabling all networks 
,08-30 19:18:38.872  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:38.872  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:38.872  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:38.872  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:38.872  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:38.872  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:38.872  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:38.872  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:38.872  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 19:18:38.872  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:38.872  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 19:18:38.873  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:38.874  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:38.874  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:38.874  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:38.874  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:38.874  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:38.874  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:38.874  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:38.874  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 19:18:38.874  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:38.874  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 19:18:38.878  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:38.879  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:38.879  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:38.879  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:38.879  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:38.879  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:38.879  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:38.879  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:38.879  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 19:18:38.879  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:38.879  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 19:18:38.886   871  1306 D WifiConfigStore: loaded 0 passpoint configs
08-30 19:18:38.888   871  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 19:18:38.889   871  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-30 19:18:38.890   871  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 19:18:38.890   871  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 19:18:38.890   871  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 19:18:38.890   871  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 19:18:38.912   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-30 19:18:38.913   871  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.62 rxSuccessRate=17.62 delta 1000 -> 994
08-30 19:18:38.913   871  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 19:18:38.913   372   869 D CommandListener: Setting iface cfg
08-30 19:18:38.914   871  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '132 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 132 Failed to set address (No such device)'
,08-30 19:18:38.914   871  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 19:18:38.932   871  1306 E native  : do suspend true
,08-30 19:18:38.932   871  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 19:18:38.933   871  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 19:18:38.944   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 19:18:38.944   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 19:18:38.964   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 19:18:39.004   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 19:18:39.008  1455  1455 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 19:18:39.437  1455  1455 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 19:18:39.484  1455  1455 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 19:18:39.486  1455  1455 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 19:18:39.494   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 19:18:39.508   871  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 19:18:39.508   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 19:18:39.508   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 19:18:39.530   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 19:18:39.546   372   869 D CommandListener: Setting iface cfg
,08-30 19:18:39.548   871  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,08-30 19:18:39.556   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 19:18:39.592   871  4028 D DhcpClient: Receive thread started
,08-30 19:18:39.682   871  1306 E native  : do suspend false
,08-30 19:18:39.704   871  1875 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 19:18:39.719   871  4028 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172654, domain null
,08-30 19:18:39.720   871  1875 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172654 seconds
,08-30 19:18:39.723   871  1875 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 19:18:39.744   871  4028 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 19:18:39.745   871  1875 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 19:18:39.750   372   869 D CommandListener: Setting iface cfg
,08-30 19:18:39.761   871  1875 D DhcpClient: Scheduling renewal in 86399s
,08-30 19:18:39.763   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 19:18:39.766   871  1306 E native  : do suspend true
,08-30 19:18:39.780   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 19:18:39.783   871  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 19:18:39.785   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 19:18:39.787   871  1308 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 19:18:39.795   871  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 19:18:39.818   871  2155 I ActivityManager: Killing 3466:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-30 19:18:39.829   871  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 19:18:39.829   871  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-30 19:18:39.832   871  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-30 19:18:39.835   871  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 19:18:39.839   871  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 19:18:39.873   871  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 19:18:39.880   871  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-30 19:18:39.880   871  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-30 19:18:39.881   871  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 19:18:39.882   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 19:18:39.883   871  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-30 19:18:39.883   871  1308 D ConnectivityService:    accepting network in place of null
,08-30 19:18:39.885   871  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 19:18:39.891   871  4027 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168967, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:18:39.932   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 19:18:39.973   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 19:18:39.977   871  4026 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-30 19:18:39.978   871  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 19:18:39.979   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 19:18:39.982   871  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-30 19:18:39.984   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-30 19:18:39.993  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:39.993  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:39.993  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:39.993  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:39.993  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:39.993  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:39.993  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:18:39.993  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:18:39.993  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 19:18:39.993  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:39.993  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 19:18:39.999  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:39.999  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:39.999  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:39.999  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:39.999  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:39.999  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:39.999  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:18:39.999  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:18:39.999  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 19:18:39.999  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:39.999  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 19:18:40.001  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:40.001  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:40.001  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:40.001  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:40.001  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:40.001  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:40.001  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:18:40.001  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:18:40.001  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 19:18:40.001  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:40.001  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 19:18:40.022  1705  1705 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 19:18:40.034  1705  1705 D SystemUpdateService: onCreate
,08-30 19:18:40.044  1705  1705 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 19:18:40.047  3711  4040 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 19:18:40.061   871  4026 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 17:18:40 GMT], X-Android-Received-Millis=[1472577520060], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472577520033]}
,08-30 19:18:40.062   871  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 19:18:40.062   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-30 19:18:40.063   871  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 19:18:40.068   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 19:18:40.091  1705  4041 I SystemUpdateService: active receiver: enabled
,08-30 19:18:40.099  1705  1705 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 19:18:40.102  1705  2462 I iu.UploadsManager: num queued entries: 0
,08-30 19:18:40.102  1705  2462 I iu.UploadsManager: num updated entries: 0
,08-30 19:18:40.103  1705  2462 I iu.SyncManager: NEXT; no task
,08-30 19:18:40.112  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:18:40.150  1705  1705 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 19:18:40.151  1705  1705 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 19:18:40.153  3901  3901 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 19:18:40.159  1705  4044 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 19:18:40.159  1705  4044 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 19:18:40.161  1705  4044 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 19:18:40.162  3901  3901 D SprintDMHelper: simOperator: 
,08-30 19:18:40.162  3901  3901 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 19:18:40.171  1705  4041 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 19:18:40.212  3928  3928 I art     : Waiting for a blocking GC DisableMovingGc
,08-30 19:18:40.212  1705  4041 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-30 19:18:40.212  1705  4041 I SystemUpdateService: now status is 0 (complete)
08-30 19:18:40.212  1705  4041 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 19:18:40.216  3928  3928 I art     : Starting a blocking GC DisableMovingGc
,08-30 19:18:40.213  1705  4041 I SystemUpdateService: file has been verified
,08-30 19:18:40.221  1705  4041 I SystemUpdateService: OTA package size = 12249756
,08-30 19:18:40.277  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:18:40.280  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:18:40.308  2268  4048 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 19:18:40.313  1705  4041 I SystemUpdateService: showing system update notification
,08-30 19:18:40.330  1510  4052 I VacuumService: Vacuum at: now=1472577520330 tag=VacuumService
,08-30 19:18:40.333  3711  4055 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 19:18:40.411  1510  2411 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 19:18:40.411  1510  2411 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 19:18:40.411  1510  2411 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 19:18:40.411  1510  2411 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:18:40.457  1510  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 19:18:40.457  1510  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 19:18:40.458  1510  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:18:40.458  1510  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:18:40.471  3711  4055 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 19:18:40.472  3711  4040 E BooksSync: Soft error
08-30 19:18:40.472  3711  4040 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 19:18:40.472  3711  4040 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 19:18:40.473  3711  4040 E BooksSync: Sync error
08-30 19:18:40.473  3711  4040 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 19:18:40.473  3711  4040 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 19:18:40.473  3711  4040 I BooksSync: Finished books sync
,08-30 19:18:40.485   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 163398, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 19:18:40.562  1705  1705 D SystemUpdateService: onDestroy
,08-30 19:18:40.627  1510  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 19:18:40.627  1510  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 19:18:40.628  1510  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:18:40.628  1510  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:18:40.645  1510  4053 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-30 19:18:40.652  1510  4053 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 19:18:40.700  1510  4053 W Uploader:  no longer exists, so no auth token.
,08-30 19:18:40.730  1705  4044 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-30 19:18:40.814  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:18:40.842  1510  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 19:18:40.842  1510  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 19:18:40.842  1510  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:18:40.842  1510  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:18:40.867  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 19:18:40.867  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 19:18:40.868  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-30 19:18:40.979   871  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 19:18:41.662  1510  4053 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-30 19:18:41.662  1510  4053 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-30 19:18:41.662  1510  4053 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:18:41.662  1510  4053 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:18:41.682  1510  4053 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 19:18:41.682  1510  4053 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 19:18:41.682  1510  4053 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 19:18:41.682  1510  4053 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 19:18:41.682  1510  4053 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-30 19:18:41.682  1510  4053 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-30 19:18:41.682  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-30 19:18:41.682  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-30 19:18:41.682  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-30 19:18:41.682  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-30 19:18:41.682  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-30 19:18:41.682  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-30 19:18:41.682  1510  4053 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-30 19:18:42.002  1510  4053 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-30 19:18:42.003  1510  4053 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-30 19:18:42.003  1510  4053 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:18:42.003  1510  4053 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:18:42.024  1510  4053 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 19:18:42.024  1510  4053 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 19:18:42.024  1510  4053 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 19:18:42.024  1510  4053 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 19:18:42.024  1510  4053 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-30 19:18:42.024  1510  4053 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-30 19:18:42.024  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-30 19:18:42.024  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-30 19:18:42.024  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-30 19:18:42.024  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-30 19:18:42.024  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-30 19:18:42.024  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-30 19:18:42.024  1510  4053 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-30 19:18:42.673  1510  4053 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-30 19:18:42.674  1510  4053 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-30 19:18:42.674  1510  4053 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 19:18:42.674  1510  4053 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:18:42.695  1510  4053 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 19:18:42.695  1510  4053 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 19:18:42.695  1510  4053 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 19:18:42.695  1510  4053 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 19:18:42.695  1510  4053 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-30 19:18:42.695  1510  4053 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-30 19:18:42.695  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-30 19:18:42.695  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-30 19:18:42.695  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-30 19:18:42.695  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-30 19:18:42.695  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-30 19:18:42.695  1510  4053 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-30 19:18:42.695  1510  4053 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-30 19:18:43.860   871   882 D WifiService: setWifiEnabled: false pid=3757, uid=10000
,08-30 19:18:43.861   871   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 19:18:43.902  1455  1455 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 19:18:43.912   871  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 19:18:43.913   871  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-30 19:18:43.913   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
08-30 19:18:43.914   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 19:18:43.945   871  1306 E native  : do suspend true
,08-30 19:18:43.956   871  1875 D DhcpClient: Clearing IP address
08-30 19:18:43.957   372   869 D CommandListener: Clearing all IP addresses on wlan0
,08-30 19:18:43.960   372   869 D CommandListener: Setting iface cfg
,08-30 19:18:43.963  1510  4051 V NativeCrypto: Read error: ssl=0x9a6e4200: I/O error during system call, Connection timed out
,08-30 19:18:43.965   871  4028 D DhcpClient: Receive thread stopped
08-30 19:18:43.966   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 19:18:43.966   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-30 19:18:43.975   405   405 E Parcel  : Reading a NULL string not supported here.
,08-30 19:18:43.976  1510  4051 V NativeCrypto: SSL shutdown failed: ssl=0x9a6e4200: I/O error during system call, Broken pipe
08-30 19:18:43.978   871  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-30 19:18:43.979   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 19:18:43.979   871  1306 E native  : do suspend true
08-30 19:18:43.980   871  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-30 19:18:44.017   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 19:18:44.045   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 19:18:44.045   372   869 D CommandListener: Clearing all IP addresses on wlan0
,08-30 19:18:44.046   871  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 19:18:44.046   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 19:18:44.048   871   888 D Tethering: MasterInitialState.processMessage what=3
08-30 19:18:44.060  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:44.060  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:44.060  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:44.060  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:44.060  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:44.060  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:44.060  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:44.060  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:44.060  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 19:18:44.061  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:44.061  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 19:18:44.066  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:44.066  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:44.066  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-30 19:18:44.066  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:44.066  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:44.066  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:44.066  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:44.066  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:44.066  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 19:18:44.066  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:44.066  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 19:18:44.068  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:44.068  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:44.068  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:44.068  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:44.068  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:18:44.068  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:44.068  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:44.068  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:44.068  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 19:18:44.069  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:44.069  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 19:18:44.071   871  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 19:18:44.075  1705  1705 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 19:18:44.084  1705  1705 D SystemUpdateService: onCreate
,08-30 19:18:44.088   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 19:18:44.091  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:44.091  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:44.091  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:44.091  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:44.091  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 19:18:44.091  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false,
08-30 19:18:44.091  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:44.091  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:44.091  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 19:18:44.091  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:44.091  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
08-30 19:18:44.091   871  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 19:18:44.092  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:44.092  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-30 19:18:44.092  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:44.092  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:44.092  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 19:18:44.092  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:44.092  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:44.092  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:44.092  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 19:18:44.092  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:44.092  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 19:18:44.092  1888  2298 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 19:18:44.093  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:44.093  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:44.093  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:44.093  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:44.093  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 19:18:44.093  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:44.093  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:44.093  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:44.093  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 19:18:44.093  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:44.093  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 19:18:44.101  1705  1705 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 19:18:44.110  1705  4077 I SystemUpdateService: active receiver: enabled
,08-30 19:18:44.114  1705  1705 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 19:18:44.120  1705  2462 I iu.UploadsManager: num queued entries: 0
,08-30 19:18:44.122  1705  4077 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 19:18:44.124  1705  1705 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 19:18:44.126  1705  1705 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 19:18:44.127  1705  2462 I iu.UploadsManager: num updated entries: 0
08-30 19:18:44.128  1705  4077 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 19:18:44.128  1705  4077 I SystemUpdateService: now status is 0 (complete)
08-30 19:18:44.128  1705  4077 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 19:18:44.128  1705  4077 I SystemUpdateService: file has been verified
,08-30 19:18:44.129  1705  2462 I iu.SyncManager: NEXT; no task
08-30 19:18:44.128  1705  4077 I SystemUpdateService: OTA package size = 12249756
,08-30 19:18:44.130  3901  3901 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 19:18:44.136  3901  3901 D SprintDMHelper: simOperator: 
08-30 19:18:44.136  3901  3901 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 19:18:44.142   372   869 E Netd    : netlink response contains error (No such file or directory)
,08-30 19:18:44.143   871  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-30 19:18:44.178  2268  4081 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 19:18:44.193  1705  4077 I SystemUpdateService: showing system update notification
,08-30 19:18:44.202  1705  1705 D SystemUpdateService: onDestroy
,08-30 19:18:47.883   871  1308 D ConnectivityService: handlePromptUnvalidated 101
,08-30 19:18:48.919   871   888 I ActivityManager: Start proc 4086:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 19:18:49.048  4086  4086 D AdapterServiceConfig: Adding HeadsetService
,08-30 19:18:49.049  4086  4086 D AdapterServiceConfig: Adding A2dpService
,08-30 19:18:49.049  4086  4086 D AdapterServiceConfig: Adding HidService
08-30 19:18:49.049  4086  4086 D AdapterServiceConfig: Adding HealthService
,08-30 19:18:49.049  4086  4086 D AdapterServiceConfig: Adding PanService
,08-30 19:18:49.050  4086  4086 D AdapterServiceConfig: Adding GattService
,08-30 19:18:49.050  4086  4086 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 19:18:49.064  4086  4086 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 19:18:49.064   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3074ba9:true
,08-30 19:18:49.069  4086  4086 I bt_bluedroid: init
,08-30 19:18:49.070  4086  4098 I BluetoothAdapterState: Entering OffState
,08-30 19:18:49.075  4086  4099 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 19:18:49.075  4086  4099 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 19:18:49.075  4086  4099 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 19:18:49.076  4086  4099 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 19:18:49.078  4086  4086 I bt_bluedroid: get_profile_interface socket
,08-30 19:18:49.081  4086  4102 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 19:18:49.082  4086  4102 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 19:18:49.084  4086  4086 I bt_bluedroid: get_profile_interface sdp
,08-30 19:18:49.091  4086  4097 I bt_bluedroid: config_hci_snoop_log
,08-30 19:18:49.094   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 19:18:49.107  4086  4098 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 19:18:49.108  4086  4098 D BluetoothAdapterProperties: Setting state to 14
08-30 19:18:49.108  4086  4098 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 19:18:49.113  4086  4098 D BluetoothBondStateMachine: make
,08-30 19:18:49.118  4086  4103 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 19:18:49.128  4086  4098 I BluetoothAdapterState: Entering PendingCommandState
,08-30 19:18:49.130  4086  4086 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 19:18:49.139  4086  4086 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
,08-30 19:18:49.141  4086  4086 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 19:18:49.143  4086  4086 D BtGatt.GattService: Received start request. Starting profile...
,08-30 19:18:49.143  4086  4086 D BtGatt.GattService: start()
,08-30 19:18:49.144  4086  4086 I bt_bluedroid: get_profile_interface gatt
08-30 19:18:49.146  4086  4086 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
08-30 19:18:49.147  4086  4086 D BtGatt.AdvertiseManager: advertise manager created
,08-30 19:18:49.161  4086  4086 V BluetoothAdapterState: isTurningOff()=false
08-30 19:18:49.161  4086  4086 V BluetoothAdapterState: isTurningOn()=false
08-30 19:18:49.161  4086  4086 V BluetoothAdapterState: isBleTurningOn()=true
,08-30 19:18:49.161  4086  4086 V BluetoothAdapterState: isBleTurningOff()=false,
08-30 19:18:49.162  4086  4098 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-30 19:18:49.162  4086  4098 I bt_bluedroid: enable
,08-30 19:18:49.163  4086  4099 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-30 19:18:49.163  4086  4099 I bt_hci  : start_up
08-30 19:18:49.171  4086  4099 I bt_vendor: alloc value 0xb39aa189
08-30 19:18:49.171  4086  4099 I bt_vendor: init
08-30 19:18:49.171  4086  4099 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 19:18:49.172  4086  4099 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 19:18:49.278  4086  4099 D bt_hci  : start_up starting async portion
,08-30 19:18:49.279  4086  4106 I bt_hci  : event_finish_startup
08-30 19:18:49.280  4086  4106 I bt_hci_h4: hal_open
08-30 19:18:49.280  4086  4106 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 19:18:49.294  4086  4106 I bt_userial_vendor: device fd = 51 open
,08-30 19:18:49.321  4086  4106 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 19:18:49.353  4086  4106 D bt_hwcfg: Chipset BCM4354A2
,08-30 19:18:49.353  4086  4106 D bt_hwcfg: Target name = [BCM4354A2]
08-30 19:18:49.354  4086  4106 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 19:18:50.000  4086  4106 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 19:18:50.001  4086  4106 D bt_hwcfg: Settlement delay -- 100 ms
08-30 19:18:50.001  4086  4106 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 19:18:50.118  4086  4106 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 19:18:50.119  4086  4106 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 19:18:50.148  4086  4106 I bt_hwcfg: vendor lib fwcfg completed
08-30 19:18:50.149  4086  4106 I bt_vendor: firmware callback
,08-30 19:18:50.149  4086  4106 I bt_hci  : firmware_config_callback
,08-30 19:18:50.160  4086  4108 I bt_btu  : btu_task pending for preload complete event
,08-30 19:18:50.160  4086  4108 I bt_btu_task: Bluetooth chip preload is complete
08-30 19:18:50.160  4086  4108 I bt_btu  : btu_task received preload complete event
,08-30 19:18:50.170  4086  4108 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 19:18:50.171  4086  4108 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 19:18:50.171  4086  4108 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 19:18:50.171  4086  4108 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 19:18:50.172  4086  4108 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 19:18:50.172  4086  4108 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 19:18:50.172  4086  4108 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-30 19:18:50.172  4086  4108 I         : BTE_InitTraceLevels -- TRC_BTM
,08-30 19:18:50.173  4086  4108 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 19:18:50.173  4086  4108 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 19:18:50.173  4086  4108 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 19:18:50.174  4086  4108 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 19:18:50.174  4086  4108 I         : BTE_InitTraceLevels -- TRC_SMP
,08-30 19:18:50.174  4086  4108 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 19:18:50.175  4086  4108 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 19:18:50.310  4086  4108 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3927d9d
,08-30 19:18:50.310  4086  4108 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3927d9d 
,08-30 19:18:50.320  4086  4102 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 19:18:50.321  4086  4102 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 19:18:50.322  4086  4102 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 19:18:50.327  4086  4102 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 19:18:50.332  4086  4102 D BluetoothAdapterProperties: Scan Mode:20
,08-30 19:18:50.335  4086  4102 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 19:18:50.335  4086  4102 D bt_hci  : do_postload posting postload work item
08-30 19:18:50.336  4086  4106 I bt_hci  : event_postload
,08-30 19:18:50.336  4086  4106 I bt_vendor: sco_config_cb
,08-30 19:18:50.336  4086  4106 I bt_hci  : sco_config_callback postload finished.
08-30 19:18:50.341  4086  4102 D bt_bte_conf: Device ID record 1 : primary
08-30 19:18:50.341  4086  4102 D bt_bte_conf:   vendorId            = 000f
,08-30 19:18:50.342  4086  4102 D bt_bte_conf:   vendorIdSource      = 0001
08-30 19:18:50.342  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:18:50.342  4086  4102 D bt_bte_conf:   product             = 1200
08-30 19:18:50.342  4086  4102 D bt_bte_conf:   version             = 1436
08-30 19:18:50.342  4086  4102 D bt_bte_conf:   clientExecutableURL = 
08-30 19:18:50.342  4086  4102 D bt_bte_conf:   serviceDescription  = 
08-30 19:18:50.343  4086  4102 D bt_bte_conf:   documentationURL    = 
08-30 19:18:50.343  4086  4102 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 19:18:50.343  4086  4099 D bt_stack_manager: event_start_up_stack finished
08-30 19:18:50.346  4086  4098 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-30 19:18:50.347  4086  4098 D BluetoothAdapterProperties: Setting state to 15
08-30 19:18:50.347  4086  4098 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 19:18:50.348  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:18:50.349  4086  4106 I bt_vendor: low_power_mode_cb
,08-30 19:18:50.349  4086  4098 I BluetoothAdapterState: Entering BleOnState
08-30 19:18:50.353  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:18:50.353  4086  4098 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 19:18:50.353  4086  4098 D BluetoothAdapterProperties: Setting state to 11
,08-30 19:18:50.353  4086  4098 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 19:18:50.363  4086  4086 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
,08-30 19:18:50.365  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:50.366  4086  4086 D HeadsetService: Received start request. Starting profile...
,08-30 19:18:50.367  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:50.368  4086  4086 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 19:18:50.368  4086  4086 D HeadsetStateMachine: make
08-30 19:18:50.369  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:50.377  4086  4086 D HeadsetStateMachine: max_hf_connections = 1
,08-30 19:18:50.378  4086  4086 I bt_bluedroid: get_profile_interface handsfree
08-30 19:18:50.378  4086  4102 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 19:18:50.378  4086  4102 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-30 19:18:50.382  4086  4098 I BluetoothAdapterState: Entering PendingCommandState
,08-30 19:18:50.384  4086  4086 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
,08-30 19:18:50.385  4086  4086 D A2dpService: Received start request. Starting profile...
,08-30 19:18:50.386  4086  4086 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 19:18:50.386  4086  4086 I bt_bluedroid: get_profile_interface avrcp
,08-30 19:18:50.393  4086  4086 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 19:18:50.393  4086  4086 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 19:18:50.393  4086  4086 D A2dpStateMachine: make,
08-30 19:18:50.394  4086  4086 I bt_bluedroid: get_profile_interface a2dp
,08-30 19:18:50.395  4086  4102 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 19:18:50.399  4086  4117 D A2dpStateMachine: Enter Disconnected: -2
,08-30 19:18:50.403  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 19:18:50.403  4086  4086 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 19:18:50.405  4086  4086 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
,08-30 19:18:50.407  3840  3840 D BluetoothInputDevice: Proxy object connected,
08-30 19:18:50.407  4086  4086 D HidService: Received start request. Starting profile...
08-30 19:18:50.408  3840  3840 D HidProfile: Bluetooth service connected
08-30 19:18:50.408  4086  4086 I bt_bluedroid: get_profile_interface hidhost
08-30 19:18:50.408  4086  4102 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39093e5
08-30 19:18:50.408  4086  4102 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 19:18:50.409  4086  4086 D HidService: setHidService(): set to: null
,08-30 19:18:50.411  4086  4086 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 19:18:50.412  4086  4086 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
,08-30 19:18:50.413  4086  4086 D HealthService: Received start request. Starting profile...
,08-30 19:18:50.415  4086  4086 I bt_bluedroid: get_profile_interface health
,08-30 19:18:50.416  4086  4086 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 19:18:50.418  4086  4086 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
,08-30 19:18:50.420  4086  4086 D PanService: Received start request. Starting profile...
,08-30 19:18:50.420  3840  3840 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 19:18:50.420  4086  4086 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 19:18:50.420  3840  3840 D PanProfile: Bluetooth service connected
,08-30 19:18:50.420  4086  4086 I bt_bluedroid: get_profile_interface pan
08-30 19:18:50.421  4086  4102 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 19:18:50.427  4086  4086 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
,08-30 19:18:50.429  3840  3840 D BluetoothMap: Proxy object connected
,08-30 19:18:50.429  4086  4086 D BluetoothMapService: Received start request. Starting profile...
08-30 19:18:50.430  4086  4086 D BluetoothMapService: start()
,08-30 19:18:50.430  3840  3840 D MapProfile: Bluetooth service connected
08-30 19:18:50.430  3840  3840 D BluetoothMap: getConnectedDevices()
,08-30 19:18:50.432  3840  3840 D BluetoothMap: Bluetooth is Not enabled
,08-30 19:18:50.434  4086  4086 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 19:18:50.435  4086  4086 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 19:18:50.436  4086  4086 D BluetoothMapAppObserver: createReceiver()
,08-30 19:18:50.437  4086  4086 D BluetoothMapAppObserver: initObservers()
08-30 19:18:50.437  4086  4086 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 19:18:50.444  4086  4086 V BluetoothAdapterState: isTurningOff()=false
,08-30 19:18:50.444  4086  4086 V BluetoothAdapterState: isTurningOn()=true
08-30 19:18:50.444  4086  4086 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:18:50.445  4086  4086 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 19:18:50.449  4086  4086 V BluetoothAdapterState: isTurningOff()=false
,08-30 19:18:50.449  4086  4086 V BluetoothAdapterState: isTurningOn()=true
08-30 19:18:50.449  4086  4115 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 19:18:50.449  4086  4086 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 19:18:50.450  4086  4086 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 19:18:50.450  4086  4086 V BluetoothAdapterState: isTurningOff()=false
08-30 19:18:50.451  4086  4086 V BluetoothAdapterState: isTurningOn()=true
08-30 19:18:50.451  4086  4086 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:18:50.451  4086  4086 V BluetoothAdapterState: isBleTurningOff()=false
08-30 19:18:50.452  4086  4086 V BluetoothAdapterState: isTurningOff()=false
08-30 19:18:50.452  4086  4086 V BluetoothAdapterState: isTurningOn()=true
,08-30 19:18:50.452  4086  4086 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:18:50.452  4086  4086 V BluetoothAdapterState: isBleTurningOff()=false
08-30 19:18:50.453  4086  4086 V BluetoothAdapterState: isTurningOff()=false
08-30 19:18:50.453  4086  4086 V BluetoothAdapterState: isTurningOn()=true
08-30 19:18:50.453  4086  4086 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:18:50.453  4086  4086 V BluetoothAdapterState: isBleTurningOff()=false
08-30 19:18:50.453  4086  4086 V BluetoothAdapterState: isTurningOff()=false
,08-30 19:18:50.454  4086  4086 V BluetoothAdapterState: isTurningOn()=true
08-30 19:18:50.454  4086  4086 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:18:50.454  4086  4086 V BluetoothAdapterState: isBleTurningOff()=false
08-30 19:18:50.456  4086  4098 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-30 19:18:50.456  4086  4098 D BluetoothAdapterProperties: ScanMode =  20
08-30 19:18:50.456  4086  4098 D BluetoothAdapterProperties: State =  11
08-30 19:18:50.458  4086  4102 D BluetoothAdapterProperties: Scan Mode:21
08-30 19:18:50.458  4086  4098 D BluetoothAdapterProperties: Setting state to 12
,08-30 19:18:50.458  4086  4098 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 19:18:50.458  4086  4102 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 19:18:50.459  3840  3852 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 19:18:50.459   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 19:18:50.460  1350  1364 D BluetoothPan: onBluetoothStateChange on: true
,08-30 19:18:50.462  4086  4098 I BluetoothAdapterState: Entering OnState
08-30 19:18:50.463  1350  1350 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 19:18:50.463  1350  1350 D PanProfile: Bluetooth service connected
08-30 19:18:50.463  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:50.463  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:50.463  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:50.463  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 19:18:50.463  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:18:50.463  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:50.463  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:50.463  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 19:18:50.465  3840  3850 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 19:18:50.466  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 19:18:50.468  1350  2074 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 19:18:50.468  4086  4086 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 19:18:50.469  4086  4086 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-30 19:18:50.470  1350  1361 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 19:18:50.471  4086  4086 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 19:18:50.471  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:50.471  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:50.471  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:50.471  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 19:18:50.471  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:18:50.471  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:50.471  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:50.471  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 19:18:50.473   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 19:18:50.474  1955  1976 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 19:18:50.474  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 19:18:50.477   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 19:18:50.477  4086  4086 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 19:18:50.477  1350  1364 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 19:18:50.478   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 19:18:50.478  3840  3852 D BluetoothPan: onBluetoothStateChange on: true
08-30 19:18:50.479  1350  2074 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 19:18:50.479  4086  4086 D ObexServerSockets: Succeed to create listening sockets 
08-30 19:18:50.479  4086  4086 D ObexServerSockets0: startAccept()
,08-30 19:18:50.479  4086  4086 D ObexServerSockets0: prepareForNewConnect()
08-30 19:18:50.480  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:50.480  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:50.480  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:50.480  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 19:18:50.480  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:18:50.480  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:50.480  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:50.480  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 19:18:50.481  3840  3850 D BluetoothMap: onBluetoothStateChange: up=true
08-30 19:18:50.481  1350  1350 D BluetoothMap: Proxy object connected
08-30 19:18:50.481  1350  1350 D MapProfile: Bluetooth service connected
08-30 19:18:50.481  1350  1350 D BluetoothMap: getConnectedDevices()
08-30 19:18:50.482  4086  4086 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-30 19:18:50.482  4086  4086 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 19:18:50.483   871   871 D BluetoothA2dp: Proxy object connected
08-30 19:18:50.483  4086  4123 D ObexServerSockets0: Accepting socket connection...
08-30 19:18:50.484  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 19:18:50.485  1350  1364 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 19:18:50.485  1350  1350 D BluetoothA2dp: Proxy object connected
,08-30 19:18:50.490  4086  4086 D BluetoothMapService: onReceive
08-30 19:18:50.491  4086  4086 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 19:18:50.491  4086  4086 D BluetoothMapService: STATE_ON
,08-30 19:18:50.492  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:18:50.492  4086  4124 D ObexServerSockets0: Accepting socket connection...
08-30 19:18:50.493   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 19:18:50.493  1350  1350 D BluetoothInputDevice: Proxy object connected
,08-30 19:18:50.493  1350  1350 D HidProfile: Bluetooth service connected
,08-30 19:18:50.493  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:18:50.495  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:18:50.495  3840  3840 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 19:18:50.499  3840  3840 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-30 19:18:50.506  3840  3840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 19:18:50.511  3840  3840 D BluetoothA2dp: Proxy object connected
,08-30 19:18:50.512  4086  4086 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 19:18:50.512  4086  4086 D ObexServerSockets0: prepareForNewConnect()
08-30 19:18:50.515  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 19:18:50.519  3840  3840 D DockEventReceiver: finishStartingService: stopping service
,08-30 19:18:50.522  1350  1350 D BluetoothPbap: Proxy object connected
,08-30 19:18:50.522  1350  1350 D PbapServerProfile: Bluetooth service connected
,08-30 19:18:50.522  3840  3840 D BluetoothPbap: Proxy object connected
,08-30 19:18:50.524  3840  3840 D PbapServerProfile: Bluetooth service connected
,08-30 19:18:50.531  4086  4130 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 19:18:50.541  4086  4134 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 19:18:50.542  4086  4134 I BtOppRfcommListener: Accept thread started.
,08-30 19:18:50.561   871   871 D BluetoothHeadset: Proxy object connected
,08-30 19:18:50.561   871   871 D BluetoothHeadset: Proxy object connected
08-30 19:18:50.561   871   871 D BluetoothHeadset: Proxy object connected
,08-30 19:18:50.561  1350  2074 D BluetoothHeadset: Proxy object connected
08-30 19:18:50.562  1350  1350 D HeadsetProfile: Bluetooth service connected
08-30 19:18:50.562  1955  2139 D BluetoothHeadset: Proxy object connected
,08-30 19:18:50.573   871   888 D BluetoothHeadset: Proxy object connected
,08-30 19:18:50.577  1955  1986 D BluetoothHeadset: Proxy object connected
,08-30 19:18:50.578  1350  1361 D BluetoothHeadset: Proxy object connected
,08-30 19:18:50.578   871   888 D BluetoothHeadset: Proxy object connected
08-30 19:18:50.578  1350  1350 D HeadsetProfile: Bluetooth service connected
,08-30 19:18:50.603  3840  3852 D BluetoothHeadset: Proxy object connected
,08-30 19:18:50.603  3840  3840 D HeadsetProfile: Bluetooth service connected
,08-30 19:18:53.885  4086  4098 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 19:18:53.885  4086  4098 D BluetoothAdapterProperties: Setting state to 13
,08-30 19:18:53.885  4086  4098 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 19:18:53.887  4086  4098 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 19:18:53.894  4086  4098 I BluetoothAdapterState: Entering PendingCommandState
08-30 19:18:53.899  4086  4086 D BluetoothMapService: onReceive
08-30 19:18:53.899  4086  4086 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 19:18:53.900  4086  4086 D BluetoothMapService: STATE_TURNING_OFF
08-30 19:18:53.901  4086  4086 D BluetoothMapService: MAP Service closeService in
08-30 19:18:53.901  4086  4086 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 19:18:53.902  4086  4086 D ObexServerSockets0: shutdown(block = true)
,08-30 19:18:53.902  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:53.902  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:53.902  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:53.902  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:53.902  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 19:18:53.902  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:53.902  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-30 19:18:53.902  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:53.902  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 19:18:53.904  4086  4102 D BluetoothAdapterProperties: Scan Mode:20
08-30 19:18:53.904  4086  4098 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-30 19:18:53.906  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:53.906  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 19:18:53.909  4086  4123 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 19:18:53.911  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:53.911  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:53.911  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:53.911  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:53.911  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 19:18:53.911  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:53.911  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:53.911  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:53.911  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 19:18:53.912  4086  4086 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 19:18:53.912  3840  3840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 19:18:53.912  4086  4124 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 19:18:53.913  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:53.913  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 19:18:53.914  4086  4110 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 19:18:53.915  4086  4086 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 19:18:53.917  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 19:18:53.918  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:18:53.918  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:18:53.918  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:18:53.918  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 19:18:53.918  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 19:18:53.918  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:18:53.918  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:18:53.918  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 19:18:53.918  3757  3757 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 19:18:53.918  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 19:18:53.919  4086  4086 D HeadsetService: Received stop request...Stopping profile...
08-30 19:18:53.921   871   871 D BluetoothHeadset: Proxy object disconnected
08-30 19:18:53.921   871   871 D BluetoothHeadset: Proxy object disconnected
08-30 19:18:53.922  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:53.922  3840  3850 D BluetoothHeadset: Proxy object disconnected
,08-30 19:18:53.922   871   871 D BluetoothHeadset: Proxy object disconnected
08-30 19:18:53.923  1350  1361 D BluetoothHeadset: Proxy object disconnected
,08-30 19:18:53.923  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:53.924  1350  1350 D HeadsetProfile: Bluetooth service disconnected
08-30 19:18:53.924  1955  2137 D BluetoothHeadset: Proxy object disconnected
08-30 19:18:53.925  4086  4086 D A2dpService: Received stop request...Stopping profile...
08-30 19:18:53.925  4086  4117 D A2dpStateMachine: Exit Disconnected: -1
08-30 19:18:53.925  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:53.926   871   871 D BluetoothA2dp: Proxy object disconnected
08-30 19:18:53.927  4086  4086 D HidService: Received stop request...Stopping profile...
,08-30 19:18:53.927  4086  4086 D HidService: Stopping Bluetooth HidService
,08-30 19:18:53.931  4086  4086 I BtOppRfcommListener: stopping Accept Thread
,08-30 19:18:53.932  4086  4134 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 19:18:53.932  4086  4134 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 19:18:53.933  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 19:18:53.933  4086  4086 D HealthService: Received stop request...Stopping profile...
08-30 19:18:53.934  3840  3840 D DockEventReceiver: finishStartingService: stopping service
,08-30 19:18:53.934  4086  4086 V BluetoothAdapterState: isTurningOff()=true
,08-30 19:18:53.934  4086  4086 V BluetoothAdapterState: isTurningOn()=false
08-30 19:18:53.934  4086  4086 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:18:53.934  4086  4086 V BluetoothAdapterState: isBleTurningOff()=false
08-30 19:18:53.935  3840  3840 D HeadsetProfile: Bluetooth service disconnected
08-30 19:18:53.935  4086  4086 D PanService: Received stop request...Stopping profile...
08-30 19:18:53.935  3840  3840 D BluetoothA2dp: Proxy object disconnected
08-30 19:18:53.936  3840  3840 D BluetoothInputDevice: Proxy object disconnected
08-30 19:18:53.936  3840  3840 D HidProfile: Bluetooth service disconnected
08-30 19:18:53.936  3840  3840 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 19:18:53.936  3840  3840 D PanProfile: Bluetooth service disconnected
,08-30 19:18:53.939  4086  4086 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 19:18:53.939  4086  4102 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 19:18:53.939  4086  4108 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 19:18:53.939  4086  4108 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 19:18:53.939  4086  4108 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 19:18:53.940  4086  4102 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 19:18:53.940  4086  4086 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 19:18:53.941  4086  4086 D BluetoothMapService: Received stop request...Stopping profile...
08-30 19:18:53.941  4086  4086 D BluetoothMapService: stop()
,08-30 19:18:53.942  4086  4086 D BluetoothMapAppObserver: deinitObservers()
08-30 19:18:53.942  4086  4086 D BluetoothMapAppObserver: removeReceiver()
,08-30 19:18:53.944  4086  4086 V BluetoothAdapterState: isTurningOff()=true
,08-30 19:18:53.944  4086  4086 V BluetoothAdapterState: isTurningOn()=false
08-30 19:18:53.944  4086  4086 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:18:53.944  4086  4086 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 19:18:53.946  4086  4108 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 19:18:53.946  4086  4108 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 19:18:53.946  4086  4108 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 19:18:53.946  1350  1350 D BluetoothA2dp: Proxy object disconnected
08-30 19:18:53.946  4086  4108 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 19:18:53.946  4086  4108 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 19:18:53.947  4086  4108 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 19:18:53.947  4086  4102 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-30 19:18:53.947  1350  1350 D BluetoothInputDevice: Proxy object disconnected
,08-30 19:18:53.947  1350  1350 D HidProfile: Bluetooth service disconnected
08-30 19:18:53.947  4086  4086 V BluetoothAdapterState: isTurningOff()=true
08-30 19:18:53.947  4086  4086 V BluetoothAdapterState: isTurningOn()=false
08-30 19:18:53.947  4086  4086 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:18:53.948  4086  4086 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 19:18:53.947  1350  1350 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 19:18:53.948  1350  1350 D PanProfile: Bluetooth service disconnected
08-30 19:18:53.948  4086  4086 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 19:18:53.948  1350  1350 D BluetoothMap: Proxy object disconnected
08-30 19:18:53.948  1350  1350 D MapProfile: Bluetooth service disconnected
08-30 19:18:53.948  4086  4102 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 19:18:53.948  4086  4086 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 19:18:53.949  3840  3840 D BluetoothMap: Proxy object disconnected
08-30 19:18:53.949  3840  3840 D MapProfile: Bluetooth service disconnected
08-30 19:18:53.950  1350  1350 D BluetoothPbap: Proxy object disconnected
08-30 19:18:53.951  1350  1350 D PbapServerProfile: Bluetooth service disconnected
,08-30 19:18:53.952  4086  4086 V BluetoothAdapterState: isTurningOff()=true
08-30 19:18:53.952  4086  4086 V BluetoothAdapterState: isTurningOn()=false
08-30 19:18:53.952  4086  4086 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:18:53.952  3840  3840 D BluetoothPbap: Proxy object disconnected
08-30 19:18:53.952  3840  3840 D PbapServerProfile: Bluetooth service disconnected
,08-30 19:18:53.952  4086  4086 V BluetoothAdapterState: isBleTurningOff()=false
08-30 19:18:53.952  4086  4086 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 19:18:53.953  4086  4102 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 19:18:53.953  4086  4086 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-30 19:18:53.953  4086  4086 V BluetoothAdapterState: isTurningOff()=true
08-30 19:18:53.953  4086  4086 V BluetoothAdapterState: isTurningOn()=false
08-30 19:18:53.953  4086  4086 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:18:53.953  4086  4086 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 19:18:53.955  4086  4086 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-30 19:18:53.955  4086  4086 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 19:18:53.957  4086  4086 D BluetoothMapService: MAP Service closeService in
,08-30 19:18:53.957  4086  4086 V BluetoothAdapterState: isTurningOff()=true
08-30 19:18:53.957  4086  4086 V BluetoothAdapterState: isTurningOn()=false
08-30 19:18:53.958  4086  4086 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:18:53.958  4086  4086 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 19:18:53.958  4086  4098 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-30 19:18:53.958  4086  4098 D BluetoothAdapterProperties: Setting state to 15
08-30 19:18:53.958  4086  4098 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 19:18:53.959  4086  4098 I BluetoothAdapterState: Entering BleOnState
08-30 19:18:53.959  3840  3852 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 19:18:53.959  4086  4086 D BluetoothMapService: cleanup()
08-30 19:18:53.959  4086  4086 D BluetoothMapService: MAP Service closeService in
08-30 19:18:53.959   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 19:18:53.959  1350  1361 D BluetoothPan: onBluetoothStateChange on: false
,08-30 19:18:53.960  3840  3850 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 19:18:53.960  1350  2074 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 19:18:53.961  1350  1364 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 19:18:53.961  3840  3852 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 19:18:53.962   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 19:18:53.962  1955  1976 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 19:18:53.962   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 19:18:53.962  1350  1361 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 19:18:53.962   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 19:18:53.963  3840  3850 D BluetoothPan: onBluetoothStateChange on: false
08-30 19:18:53.963  3840  3852 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 19:18:53.963  1350  2074 D BluetoothMap: onBluetoothStateChange: up=false
08-30 19:18:53.964  3840  3850 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 19:18:53.964  1350  1364 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 19:18:53.965  4086  4098 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-30 19:18:53.965  4086  4098 D BluetoothAdapterProperties: Setting state to 16
08-30 19:18:53.965  4086  4098 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 19:18:53.966  4086  4098 D BluetoothAdapterProperties: onBleDisable
,08-30 19:18:53.967  4086  4098 I BluetoothAdapterState: Entering PendingCommandState
08-30 19:18:53.967  4086  4099 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-30 19:18:53.968  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:53.968  4086  4108 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 19:18:53.968  4086  4108 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 19:18:53.969  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:53.969  3840  3840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 19:18:53.970  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:53.972  4086  4102 D BluetoothAdapterProperties: Scan Mode:20
08-30 19:18:53.975  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:53.975  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:53.976  3840  3840 D DockEventReceiver: finishStartingService: stopping service
,08-30 19:18:53.978  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 19:18:53.978  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:18:54.172  4086  4102 I bt_hci  : shut_down
,08-30 19:18:54.173  4086  4106 D bt_hwcfg: hw_epilog_process
,08-30 19:18:54.185  4086  4106 I bt_vendor: low_power_mode_cb
,08-30 19:18:54.204  4086  4106 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 19:18:54.205  4086  4106 I bt_vendor: epilog_cb
,08-30 19:18:54.205  4086  4106 I bt_hci  : epilog_finished_callback
,08-30 19:18:54.212  4086  4102 I bt_hci_h4: hal_close
,08-30 19:18:54.213  4086  4102 I bt_userial_vendor: device fd = 51 close
,08-30 19:18:54.344  4086  4099 D bt_stack_manager: event_shut_down_stack finished.
,08-30 19:18:54.345  4086  4098 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 19:18:54.350  4086  4098 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 19:18:54.351  4086  4086 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 19:18:54.352  4086  4086 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 19:18:54.353  4086  4086 D BtGatt.GattService: stop()
08-30 19:18:54.353  4086  4086 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 19:18:54.358  4086  4086 V BluetoothAdapterState: isTurningOff()=false
08-30 19:18:54.358  4086  4086 V BluetoothAdapterState: isTurningOn()=false
08-30 19:18:54.358  4086  4086 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:18:54.359  4086  4086 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 19:18:54.360  4086  4098 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 19:18:54.360  4086  4098 D BluetoothAdapterProperties: Setting state to 10
,08-30 19:18:54.361  4086  4098 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 19:18:54.363  4086  4098 I BluetoothAdapterState: Entering OffState
,08-30 19:18:54.365   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 19:18:54.385  4086  4086 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 19:18:54.386  4086  4086 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 19:18:54.386  4086  4099 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-30 19:18:54.386  4086  4086 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 19:18:54.389  4086  4099 D bt_stack_manager: event_clean_up_stack finished.
,08-30 19:18:54.391  4086  4086 I art     : System.exit called, status: 0
,08-30 19:18:54.392  4086  4086 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 19:18:54.454   871   881 I ActivityManager: Process com.android.bluetooth (pid 4086) has died
,08-30 19:18:58.882  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 19:18:58.882  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:58.886  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 19:18:58.887  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f9e641f removed from the list
,08-30 19:18:58.887  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 19:18:58.888  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:18:58.888  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:18:58.891  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 19:18:58.891  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dabcd35 added. We now have 4 listener(s)
,08-30 19:18:58.892  3757  3807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 19:18:58.893  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:18:58.894  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dabcd35 removed from the list
08-30 19:18:58.894  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:18:58.894  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:18:58.895  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:18:58.897  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 19:18:58.897  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6aab5ca added. We now have 4 listener(s)
08-30 19:18:58.898  3757  3807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 19:19:01.086  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:19:01.097  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:19:01.100  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:19:01.157  1510  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 19:19:01.158  1510  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 19:19:01.158  1510  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:19:01.158  1510  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:19:01.203  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 19:19:01.204  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 19:19:01.205  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-30 19:19:03.912  3757  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:19:03.960   871   888 I ActivityManager: Start proc 4145:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 19:19:04.119  4145  4145 D AdapterServiceConfig: Adding HeadsetService
08-30 19:19:04.119  4145  4145 D AdapterServiceConfig: Adding A2dpService
08-30 19:19:04.120  4145  4145 D AdapterServiceConfig: Adding HidService
08-30 19:19:04.120  4145  4145 D AdapterServiceConfig: Adding HealthService
08-30 19:19:04.120  4145  4145 D AdapterServiceConfig: Adding PanService
08-30 19:19:04.120  4145  4145 D AdapterServiceConfig: Adding GattService
08-30 19:19:04.120  4145  4145 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 19:19:04.134  4145  4145 D BluetoothAdapterState: make() - Creating AdapterState
08-30 19:19:04.134   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6ebc1b4:true
,08-30 19:19:04.139  4145  4145 I bt_bluedroid: init
,08-30 19:19:04.140  4145  4157 I BluetoothAdapterState: Entering OffState
,08-30 19:19:04.146  4145  4158 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 19:19:04.147  4145  4158 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 19:19:04.147  4145  4158 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 19:19:04.148  4145  4158 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 19:19:04.150  4145  4145 I bt_bluedroid: get_profile_interface socket
,08-30 19:19:04.152  4145  4161 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 19:19:04.154  4145  4161 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 19:19:04.155  4145  4145 I bt_bluedroid: get_profile_interface sdp
,08-30 19:19:04.162  4145  4156 I bt_bluedroid: config_hci_snoop_log
,08-30 19:19:04.163   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 19:19:04.174  4145  4157 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 19:19:04.174  4145  4157 D BluetoothAdapterProperties: Setting state to 14
08-30 19:19:04.174  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-30 19:19:04.176  4145  4157 D BluetoothBondStateMachine: make
,08-30 19:19:04.179  4145  4162 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 19:19:04.185  4145  4157 I BluetoothAdapterState: Entering PendingCommandState
08-30 19:19:04.185  4145  4145 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 19:19:04.188  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
,08-30 19:19:04.189  4145  4145 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 19:19:04.189  4145  4145 D BtGatt.GattService: Received start request. Starting profile...
08-30 19:19:04.189  4145  4145 D BtGatt.GattService: start()
08-30 19:19:04.190  4145  4145 I bt_bluedroid: get_profile_interface gatt
,08-30 19:19:04.190  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
08-30 19:19:04.191  4145  4145 D BtGatt.AdvertiseManager: advertise manager created
,08-30 19:19:04.201  4145  4145 V BluetoothAdapterState: isTurningOff()=false
,08-30 19:19:04.201  4145  4145 V BluetoothAdapterState: isTurningOn()=false
08-30 19:19:04.201  4145  4145 V BluetoothAdapterState: isBleTurningOn()=true
08-30 19:19:04.201  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
08-30 19:19:04.202  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 19:19:04.202  4145  4157 I bt_bluedroid: enable
08-30 19:19:04.203  4145  4158 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 19:19:04.203  4145  4158 I bt_hci  : start_up
,08-30 19:19:04.212  4145  4158 I bt_vendor: alloc value 0xb39aa189
08-30 19:19:04.212  4145  4158 I bt_vendor: init
,08-30 19:19:04.212  4145  4158 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 19:19:04.213  4145  4158 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 19:19:04.320  4145  4158 D bt_hci  : start_up starting async portion
,08-30 19:19:04.321  4145  4165 I bt_hci  : event_finish_startup
08-30 19:19:04.322  4145  4165 I bt_hci_h4: hal_open
08-30 19:19:04.322  4145  4165 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 19:19:04.334  4145  4165 I bt_userial_vendor: device fd = 51 open
,08-30 19:19:04.363  4145  4165 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 19:19:04.394  4145  4165 D bt_hwcfg: Chipset BCM4354A2
08-30 19:19:04.395  4145  4165 D bt_hwcfg: Target name = [BCM4354A2]
,08-30 19:19:04.395  4145  4165 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 19:19:05.088  4145  4165 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 19:19:05.090  4145  4165 D bt_hwcfg: Settlement delay -- 100 ms
08-30 19:19:05.090  4145  4165 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 19:19:05.206  4145  4165 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 19:19:05.208  4145  4165 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 19:19:05.238  4145  4165 I bt_hwcfg: vendor lib fwcfg completed
,08-30 19:19:05.238  4145  4165 I bt_vendor: firmware callback
,08-30 19:19:05.238  4145  4165 I bt_hci  : firmware_config_callback
,08-30 19:19:05.251  4145  4167 I bt_btu  : btu_task pending for preload complete event
,08-30 19:19:05.251  4145  4167 I bt_btu_task: Bluetooth chip preload is complete
,08-30 19:19:05.251  4145  4167 I bt_btu  : btu_task received preload complete event
,08-30 19:19:05.261  4145  4167 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 19:19:05.261  4145  4167 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 19:19:05.261  4145  4167 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 19:19:05.262  4145  4167 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 19:19:05.262  4145  4167 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-30 19:19:05.262  4145  4167 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 19:19:05.263  4145  4167 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-30 19:19:05.263  4145  4167 I         : BTE_InitTraceLevels -- TRC_BTM
,08-30 19:19:05.263  4145  4167 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 19:19:05.263  4145  4167 I         : BTE_InitTraceLevels -- TRC_PAN
,08-30 19:19:05.264  4145  4167 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 19:19:05.264  4145  4167 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 19:19:05.264  4145  4167 I         : BTE_InitTraceLevels -- TRC_SMP
,08-30 19:19:05.264  4145  4167 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 19:19:05.265  4145  4167 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 19:19:05.400  4145  4167 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3927d9d
,08-30 19:19:05.400  4145  4167 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3927d9d 
,08-30 19:19:05.424  4145  4161 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 19:19:05.426  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 19:19:05.426  4145  4161 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 19:19:05.429  4145  4161 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 19:19:05.433  4145  4161 D BluetoothAdapterProperties: Scan Mode:20
,08-30 19:19:05.433  4145  4161 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 19:19:05.434  4145  4161 D bt_hci  : do_postload posting postload work item
08-30 19:19:05.434  4145  4165 I bt_hci  : event_postload
08-30 19:19:05.435  4145  4165 I bt_vendor: sco_config_cb
,08-30 19:19:05.435  4145  4165 I bt_hci  : sco_config_callback postload finished.
,08-30 19:19:05.439  4145  4161 D bt_bte_conf: Device ID record 1 : primary
08-30 19:19:05.439  4145  4161 D bt_bte_conf:   vendorId            = 000f
,08-30 19:19:05.439  4145  4161 D bt_bte_conf:   vendorIdSource      = 0001
,08-30 19:19:05.440  4145  4161 D bt_bte_conf:   product             = 1200
08-30 19:19:05.440  4145  4161 D bt_bte_conf:   version             = 1436
,08-30 19:19:05.440  4145  4161 D bt_bte_conf:   clientExecutableURL = 
,08-30 19:19:05.440  4145  4161 D bt_bte_conf:   serviceDescription  = 
08-30 19:19:05.441  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:19:05.441  4145  4161 D bt_bte_conf:   documentationURL    = 
,08-30 19:19:05.442  4145  4161 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 19:19:05.442  4145  4158 D bt_stack_manager: event_start_up_stack finished
,08-30 19:19:05.445  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:19:05.445  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-30 19:19:05.445  4145  4157 D BluetoothAdapterProperties: Setting state to 15
,08-30 19:19:05.445  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 19:19:05.446  4145  4157 I BluetoothAdapterState: Entering BleOnState
,08-30 19:19:05.446  4145  4165 I bt_vendor: low_power_mode_cb
08-30 19:19:05.451  4145  4157 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-30 19:19:05.451  4145  4157 D BluetoothAdapterProperties: Setting state to 11
08-30 19:19:05.452  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 19:19:05.462  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
,08-30 19:19:05.465  4145  4145 D HeadsetService: Received start request. Starting profile...
08-30 19:19:05.468  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:19:05.470  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:19:05.474  4145  4145 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 19:19:05.474  4145  4145 D HeadsetStateMachine: make
,08-30 19:19:05.481  4145  4157 I BluetoothAdapterState: Entering PendingCommandState
,08-30 19:19:05.484  4145  4145 D HeadsetStateMachine: max_hf_connections = 1
,08-30 19:19:05.484  4145  4145 I bt_bluedroid: get_profile_interface handsfree
,08-30 19:19:05.485  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 19:19:05.486  4145  4161 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-30 19:19:05.490  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
,08-30 19:19:05.491  4145  4145 D A2dpService: Received start request. Starting profile...
08-30 19:19:05.491  4145  4145 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 19:19:05.492  4145  4145 I bt_bluedroid: get_profile_interface avrcp
,08-30 19:19:05.497  4145  4145 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 19:19:05.498  4145  4145 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 19:19:05.498  4145  4145 D A2dpStateMachine: make
,08-30 19:19:05.500  4145  4145 I bt_bluedroid: get_profile_interface a2dp
,08-30 19:19:05.500  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 19:19:05.504  4145  4177 D A2dpStateMachine: Enter Disconnected: -2
,08-30 19:19:05.506  4145  4145 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 19:19:05.507  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
08-30 19:19:05.507  4145  4145 D HidService: Received start request. Starting profile...
08-30 19:19:05.507  4145  4145 I bt_bluedroid: get_profile_interface hidhost
08-30 19:19:05.508  4145  4145 D HidService: setHidService(): set to: null
08-30 19:19:05.508  4145  4161 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39093e5
08-30 19:19:05.508  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-30 19:19:05.508  4145  4145 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 19:19:05.508  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 19:19:05.509  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
08-30 19:19:05.509  4145  4145 D HealthService: Received start request. Starting profile...
,08-30 19:19:05.511  4145  4145 I bt_bluedroid: get_profile_interface health
08-30 19:19:05.511  4145  4145 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 19:19:05.512  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
,08-30 19:19:05.513  4145  4145 D PanService: Received start request. Starting profile...
08-30 19:19:05.513  4145  4145 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-30 19:19:05.513  4145  4145 I bt_bluedroid: get_profile_interface pan
08-30 19:19:05.513  4145  4161 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 19:19:05.517  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
,08-30 19:19:05.518  4145  4145 D BluetoothMapService: Received start request. Starting profile...
,08-30 19:19:05.518  4145  4145 D BluetoothMapService: start()
08-30 19:19:05.520  4145  4145 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 19:19:05.521  4145  4145 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 19:19:05.521  4145  4145 D BluetoothMapAppObserver: createReceiver()
,08-30 19:19:05.523  4145  4145 D BluetoothMapAppObserver: initObservers()
08-30 19:19:05.523  4145  4145 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 19:19:05.532  4145  4145 V BluetoothAdapterState: isTurningOff()=false
08-30 19:19:05.532  4145  4145 V BluetoothAdapterState: isTurningOn()=true
08-30 19:19:05.532  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:19:05.532  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 19:19:05.534  4145  4145 V BluetoothAdapterState: isTurningOff()=false
08-30 19:19:05.534  4145  4145 V BluetoothAdapterState: isTurningOn()=true
,08-30 19:19:05.534  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:19:05.534  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
08-30 19:19:05.534  4145  4145 V BluetoothAdapterState: isTurningOff()=false
08-30 19:19:05.534  4145  4145 V BluetoothAdapterState: isTurningOn()=true
08-30 19:19:05.534  4145  4175 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 19:19:05.534  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 19:19:05.534  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 19:19:05.536  4145  4145 V BluetoothAdapterState: isTurningOff()=false
,08-30 19:19:05.536  4145  4145 V BluetoothAdapterState: isTurningOn()=true
08-30 19:19:05.536  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
08-30 19:19:05.536  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
08-30 19:19:05.537  4145  4145 V BluetoothAdapterState: isTurningOff()=false
,08-30 19:19:05.537  4145  4145 V BluetoothAdapterState: isTurningOn()=true
,08-30 19:19:05.537  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 19:19:05.537  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
08-30 19:19:05.537  4145  4145 V BluetoothAdapterState: isTurningOff()=false
08-30 19:19:05.537  4145  4145 V BluetoothAdapterState: isTurningOn()=true
08-30 19:19:05.537  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 19:19:05.537  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
08-30 19:19:05.537  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 19:19:05.537  4145  4157 D BluetoothAdapterProperties: ScanMode =  20
08-30 19:19:05.537  4145  4157 D BluetoothAdapterProperties: State =  11
08-30 19:19:05.539  4145  4161 D BluetoothAdapterProperties: Scan Mode:21
08-30 19:19:05.539  4145  4161 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 19:19:05.540  4145  4157 D BluetoothAdapterProperties: Setting state to 12
08-30 19:19:05.540  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 19:19:05.540  3840  3850 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 19:19:05.541  4145  4157 I BluetoothAdapterState: Entering OnState
08-30 19:19:05.543   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 19:19:05.543  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:19:05.543  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:19:05.543  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:19:05.543  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 19:19:05.543  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:19:05.543  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:19:05.543  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:19:05.543  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 19:19:05.543  1350  1361 D BluetoothPan: onBluetoothStateChange on: true
08-30 19:19:05.545  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 19:19:05.548  1350  1350 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 19:19:05.548  3840  3850 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 19:19:05.548  1350  1350 D PanProfile: Bluetooth service connected
08-30 19:19:05.549  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:19:05.549  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:19:05.549  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:19:05.549  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 19:19:05.549  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:19:05.549  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:19:05.549  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:19:05.549  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 19:19:05.551  4145  4145 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 19:19:05.551  1350  2074 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 19:19:05.551  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 19:19:05.551  4145  4145 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 19:19:05.553  4145  4145 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 19:19:05.553  1350  1361 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 19:19:05.555  3840  3852 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 19:19:05.555  4145  4145 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 19:19:05.556  4145  4145 D ObexServerSockets: Succeed to create listening sockets 
08-30 19:19:05.556  4145  4145 D ObexServerSockets0: startAccept()
08-30 19:19:05.556  4145  4145 D ObexServerSockets0: prepareForNewConnect()
,08-30 19:19:05.558   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 19:19:05.558  1955  1986 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 19:19:05.559   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 19:19:05.559  4145  4145 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 19:19:05.559  4145  4145 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 19:19:05.560  1350  1364 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 19:19:05.560  3840  3840 D BluetoothInputDevice: Proxy object connected
08-30 19:19:05.560  3840  3840 D HidProfile: Bluetooth service connected
08-30 19:19:05.560   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 19:19:05.561  4145  4183 D ObexServerSockets0: Accepting socket connection...
08-30 19:19:05.561  3840  3850 D BluetoothPan: onBluetoothStateChange on: true
08-30 19:19:05.561  4145  4182 D ObexServerSockets0: Accepting socket connection...
08-30 19:19:05.563  3840  3852 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 19:19:05.563  1350  2074 D BluetoothMap: onBluetoothStateChange: up=true
08-30 19:19:05.565  1350  1350 D BluetoothA2dp: Proxy object connected
08-30 19:19:05.565  3840  3852 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 19:19:05.565   871   871 D BluetoothA2dp: Proxy object connected
08-30 19:19:05.567  1350  1364 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 19:19:05.568  1350  1350 D BluetoothMap: Proxy object connected
08-30 19:19:05.568  1350  1350 D MapProfile: Bluetooth service connected
08-30 19:19:05.568  1350  1350 D BluetoothMap: getConnectedDevices()
,08-30 19:19:05.569  3840  3840 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 19:19:05.569  3840  3840 D PanProfile: Bluetooth service connected
08-30 19:19:05.569  3840  3840 D BluetoothA2dp: Proxy object connected
08-30 19:19:05.570  1350  1350 D BluetoothInputDevice: Proxy object connected
08-30 19:19:05.570  1350  1350 D HidProfile: Bluetooth service connected
08-30 19:19:05.570   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 19:19:05.572  4145  4145 D BluetoothMapService: onReceive
08-30 19:19:05.572  4145  4145 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 19:19:05.572  4145  4145 D BluetoothMapService: STATE_ON
08-30 19:19:05.572  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:19:05.574  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:19:05.575  3840  3840 D BluetoothMap: Proxy object connected
08-30 19:19:05.575  3840  3840 D MapProfile: Bluetooth service connected
08-30 19:19:05.575  3840  3840 D BluetoothMap: getConnectedDevices()
,08-30 19:19:05.583  3840  3840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 19:19:05.588  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 19:19:05.589  3840  3840 D DockEventReceiver: finishStartingService: stopping service
,08-30 19:19:05.596  3840  3840 D BluetoothPbap: Proxy object connected
,08-30 19:19:05.596  3840  3840 D PbapServerProfile: Bluetooth service connected
08-30 19:19:05.596  4145  4145 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 19:19:05.596  4145  4145 D ObexServerSockets0: prepareForNewConnect()
,08-30 19:19:05.601  1350  1350 D BluetoothPbap: Proxy object connected
,08-30 19:19:05.601  1350  1350 D PbapServerProfile: Bluetooth service connected
,08-30 19:19:05.604  4145  4188 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 19:19:05.618  4145  4192 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 19:19:05.619  4145  4192 I BtOppRfcommListener: Accept thread started.
,08-30 19:19:05.644   871   871 D BluetoothHeadset: Proxy object connected
,08-30 19:19:05.644   871   871 D BluetoothHeadset: Proxy object connected
,08-30 19:19:05.645  3840  3850 D BluetoothHeadset: Proxy object connected
,08-30 19:19:05.645  3840  3840 D HeadsetProfile: Bluetooth service connected
,08-30 19:19:05.645   871   871 D BluetoothHeadset: Proxy object connected
08-30 19:19:05.645  1350  1361 D BluetoothHeadset: Proxy object connected
08-30 19:19:05.646  1350  1350 D HeadsetProfile: Bluetooth service connected
08-30 19:19:05.646  1955  2137 D BluetoothHeadset: Proxy object connected
,08-30 19:19:05.658   871   888 D BluetoothHeadset: Proxy object connected
,08-30 19:19:05.659  1955  1976 D BluetoothHeadset: Proxy object connected
,08-30 19:19:05.660  1350  2074 D BluetoothHeadset: Proxy object connected
,08-30 19:19:05.660  1350  1350 D HeadsetProfile: Bluetooth service connected
08-30 19:19:05.660   871   888 D BluetoothHeadset: Proxy object connected
,08-30 19:19:05.664  3840  3852 D BluetoothHeadset: Proxy object connected
,08-30 19:19:05.664  3840  3840 D HeadsetProfile: Bluetooth service connected
,08-30 19:19:08.931  3757  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:19:08.931  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:19:08.931  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:19:08.931  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 19:19:08.931  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:19:08.931  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:19:08.931  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:19:08.931  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 19:19:08.938  3757  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 19:19:08.939  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:19:08.939  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6aab5ca removed from the list
,08-30 19:19:08.940  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:19:08.940  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:08.940  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:19:08.943  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 19:19:08.943  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e4f233b added. We now have 4 listener(s)
,08-30 19:19:08.944  3757  3807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 19:19:08.972   871  1390 D WifiService: setWifiEnabled: false pid=3757, uid=10000
,08-30 19:19:08.972   871  1390 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 19:19:13.986  3757  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:19:13.987   871  2155 D WifiService: setWifiEnabled: true pid=3757, uid=10000
08-30 19:19:13.987   871  2155 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 19:19:14.007   871  1306 D WifiConfigStore: Loading config and enabling all networks 
,08-30 19:19:14.021  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:19:14.021  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:19:14.021  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:19:14.021  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:19:14.021  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:19:14.021  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:19:14.021  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:19:14.021  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 19:19:14.025  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 19:19:14.030  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:19:14.030  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:19:14.030  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:19:14.030  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:19:14.030  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:19:14.030  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 19:19:14.030  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 19:19:14.030  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 19:19:14.033  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 19:19:14.039   871  1306 D WifiConfigStore: loaded 0 passpoint configs
,08-30 19:19:14.040   871  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 19:19:14.041   871  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 19:19:14.042   871  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-30 19:19:14.042   871  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-30 19:19:14.042   871  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 19:19:14.042   871  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 19:19:14.054   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 19:19:14.055   871  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 19:19:14.055   372   869 D CommandListener: Setting iface cfg
,08-30 19:19:14.056   871  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,08-30 19:19:14.056   871  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 19:19:14.113   871  1306 E native  : do suspend true
,08-30 19:19:14.128   871  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 19:19:14.129   871  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 19:19:14.152   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 19:19:15.556   871  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 19:19:15.705   871  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.75 rxSuccessRate=11.62 delta 1000 -> 994
,08-30 19:19:15.708   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-30 19:19:15.708   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 19:19:15.729   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 19:19:15.783   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 19:19:15.785  1455  1455 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 19:19:16.218  1455  1455 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 19:19:16.265  1455  1455 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 19:19:16.265  1455  1455 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
08-30 19:19:16.269   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 19:19:16.277   871  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 19:19:16.277   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 19:19:16.278   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 19:19:16.295   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 19:19:16.316   372   869 D CommandListener: Setting iface cfg
,08-30 19:19:16.316   871  1306 D WifiStateMachine: Start Dhcp Watchdog 3
,08-30 19:19:16.332   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 19:19:16.352   871  4202 D DhcpClient: Receive thread started
,08-30 19:19:16.448   871  1306 E native  : do suspend false
,08-30 19:19:16.476   871  1875 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 19:19:16.490   871  4202 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172763, domain null
,08-30 19:19:16.491   871  1875 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172763 seconds
,08-30 19:19:16.494   871  1875 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 19:19:16.507   871  4202 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 19:19:16.509   871  1875 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 19:19:16.516   372   869 D CommandListener: Setting iface cfg
,08-30 19:19:16.528   871  1875 D DhcpClient: Scheduling renewal in 86399s
08-30 19:19:16.528   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 19:19:16.531   871  1306 E native  : do suspend true
,08-30 19:19:16.558   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 19:19:16.563   871  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 19:19:16.564   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 19:19:16.568   871  1308 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 19:19:16.576   871  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 19:19:16.634   871  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 19:19:16.634   871  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 19:19:16.637   871  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 19:19:16.638   871  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-30 19:19:16.639   871  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 19:19:16.650   871  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 19:19:16.656   871  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-30 19:19:16.657   871  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-30 19:19:16.657   871  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-30 19:19:16.657   871  1308 D ConnectivityService:    accepting network in place of null
08-30 19:19:16.657   871  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 19:19:16.658   871  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 19:19:16.658   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 19:19:16.671   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=205746, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:19:16.688   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 19:19:16.737   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 19:19:16.739   871  4200 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.142,2a00:1450:4001:80e::200e
,08-30 19:19:16.745   871  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-30 19:19:16.745   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 19:19:16.749   871  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-30 19:19:16.751   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-30 19:19:16.768  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:19:16.768  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:19:16.768  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:19:16.768  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:19:16.768  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:19:16.768  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:19:16.768  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:19:16.768  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 19:19:16.774  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 19:19:16.781  1705  1705 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 19:19:16.783  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:19:16.783  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:19:16.783  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:19:16.783  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:19:16.783  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:19:16.783  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:19:16.783  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:19:16.783  3757  3757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 19:19:16.786  3757  3757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 19:19:16.788  1705  1705 D SystemUpdateService: onCreate
,08-30 19:19:16.798  3711  4211 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 19:19:16.800  1705  1705 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 19:19:16.818  1705  4212 I SystemUpdateService: active receiver: enabled
,08-30 19:19:16.825  1705  1705 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 19:19:16.829   871  4200 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 17:19:16 GMT], X-Android-Received-Millis=[1472577556829], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472577556780]}
,08-30 19:19:16.830   871  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 19:19:16.830   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-30 19:19:16.830   871  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 19:19:16.831   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 19:19:16.840  1705  2462 I iu.UploadsManager: num queued entries: 0
,08-30 19:19:16.840  1705  2462 I iu.UploadsManager: num updated entries: 0
08-30 19:19:16.841  1705  2462 I iu.SyncManager: NEXT; no task
,08-30 19:19:16.843  1705  1705 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 19:19:16.844  1705  1705 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-30 19:19:16.846  3901  3901 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 19:19:16.851  1705  4214 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 19:19:16.851  1705  4214 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 19:19:16.854  3901  3901 D SprintDMHelper: simOperator: 
,08-30 19:19:16.854  3901  3901 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 19:19:16.860  1705  4214 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 19:19:16.861  1705  4212 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 19:19:16.884  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:19:16.886  1705  4212 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 19:19:16.886  1705  4212 I SystemUpdateService: now status is 0 (complete)
,08-30 19:19:16.886  1705  4212 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 19:19:16.886  1705  4212 I SystemUpdateService: file has been verified
,08-30 19:19:16.886  1705  4212 I SystemUpdateService: OTA package size = 12249756
,08-30 19:19:16.889  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:19:16.913  1705  4212 I SystemUpdateService: showing system update notification
,08-30 19:19:16.989  3711  4221 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 19:19:17.015  2268  4218 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 19:19:17.018  1510  2145 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 19:19:17.018  1510  2145 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 19:19:17.018  1510  2145 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 19:19:17.018  1510  2145 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:19:17.053  1510  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 19:19:17.053  1510  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 19:19:17.053  1510  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 19:19:17.053  1510  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:19:17.065  3711  4221 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 19:19:17.066  3711  4211 E BooksSync: Soft error
08-30 19:19:17.066  3711  4211 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 19:19:17.066  3711  4211 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 19:19:17.066  3711  4211 E BooksSync: Sync error
08-30 19:19:17.066  3711  4211 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 19:19:17.066  3711  4211 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 19:19:17.066  3711  4211 I BooksSync: Finished books sync
,08-30 19:19:17.072  1705  1705 D SystemUpdateService: onDestroy
,08-30 19:19:17.073  1510  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 19:19:17.075  1510  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-30 19:19:17.075  1510  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 19:19:17.075  1510  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:19:17.079   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 201275, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 19:19:17.091  1705  4214 E MDM     : [184] SitrepService.a: Error sending sitrep.
,08-30 19:19:17.746   871  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-30 19:19:19.013  3757  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 19:19:19.013  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:19:19.013  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:19:19.013  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:19:19.013  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:19:19.013  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:19:19.013  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:19:19.013  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 19:19:19.020  3757  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 19:19:19.021  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:19:19.022  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e4f233b removed from the list
,08-30 19:19:19.022  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:19:19.022  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:19.023  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:19:19.035  3757  4226 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-30 19:19:19.035  3757  4226 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 19:19:22.042  3757  4227 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-30 19:19:22.043  3757  4226 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-30 19:19:22.044  3757  4227 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-30 19:19:22.044  3757  4226 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 19:19:22.045  3757  4227 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 19:19:22.045  3757  4226 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 19:19:22.046  3757  4227 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 19:19:22.048  3757  4226 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 19:19:22.051  3757  4229 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 413, name: IncomingSocketThread/Sender)
08-30 19:19:22.051  3757  4227 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-30 19:19:22.054  3757  4226 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 19:19:22.060  3757  4230 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 414, name: OutgoingSocketThread/Sender)
,08-30 19:19:22.062  3757  4231 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 415, name: IncomingSocketThread/Receiver)
,08-30 19:19:22.063  3757  4231 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 415, thread name: IncomingSocketThread/Receiver)
,08-30 19:19:22.064  3757  4231 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-30 19:19:22.065  3757  4231 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 415, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-30 19:19:22.066  3757  4232 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 416, name: OutgoingSocketThread/Receiver)
,08-30 19:19:22.068  3757  4232 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 416, thread name: OutgoingSocketThread/Receiver)
08-30 19:19:22.068  3757  4232 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 19:19:22.068  3757  4232 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 416, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-30 19:19:23.880  1873  1928 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-30 19:19:23.881  1873  1928 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-30 19:19:23.913  1510  1510 I ConfigService: onCreate
,08-30 19:19:24.664   871  1308 D ConnectivityService: handlePromptUnvalidated 102
,08-30 19:19:25.042  3757  3807 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 19:19:25.045  3757  3807 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 19:19:25.052  3757  3807 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5837b7a Bundle[{}]
08-30 19:19:25.053  3757  3807 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 19:19:25.053  3757  3807 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-30 19:19:25.054  3757  3807 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 19:19:25.054  3757  3807 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 19:19:25.055  3757  3807 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 19:19:25.055  3757  3807 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 19:19:25.059  3757  3807 I System.out: Running OutgoingSocketThread
,08-30 19:19:25.063  3757  4234 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-30 19:19:25.063  3757  4234 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 19:19:28.072  3757  4236 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-30 19:19:28.073  3757  4236 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 19:19:28.073  3757  4234 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-30 19:19:28.073  3757  4236 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 19:19:28.074  3757  4234 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 19:19:28.074  3757  4234 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 19:19:28.074  3757  4236 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 19:19:28.077  3757  4234 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 19:19:28.081  3757  4238 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: IncomingSocketThread/Sender)
,08-30 19:19:28.083  3757  4236 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-30 19:19:28.083  3757  4234 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 19:19:28.086  3757  4239 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: OutgoingSocketThread/Sender)
08-30 19:19:28.089  3757  4241 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: OutgoingSocketThread/Receiver)
08-30 19:19:28.091  3757  4241 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 428, thread name: OutgoingSocketThread/Receiver)
,08-30 19:19:28.091  3757  4241 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 19:19:28.092  3757  4241 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 428, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-30 19:19:28.093  3757  4240 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: IncomingSocketThread/Receiver)
08-30 19:19:28.095  3757  4240 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: IncomingSocketThread/Receiver)
08-30 19:19:28.095  3757  4240 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 19:19:28.095  3757  4240 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-30 19:19:28.393  1510  2095 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 19:19:28.984  1510  1510 I ConfigService: onDestroy
,08-30 19:19:31.075  3757  3807 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 437)
,08-30 19:19:31.078  3757  3807 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-30 19:19:31.078  3757  3807 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 438)
,08-30 19:19:31.084  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 19:19:31.084  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f102a58 added. We now have 3 listener(s)
,08-30 19:19:31.086  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 19:19:31.086  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 19:19:31.086  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 19:19:31.086  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 19:19:31.086  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed907b1 added. We now have 4 listener(s)
,08-30 19:19:31.086  3757  3807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 19:19:31.087  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 19:19:31.090  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 19:19:31.097  3757  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 19:19:31.097  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:19:31.097  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:19:31.097  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:19:31.097  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:19:31.097  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:19:31.097  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:19:31.097  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 19:19:31.102  3757  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 19:19:31.103  3757  3807 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 19:19:31.103  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 19:19:31.103  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 19:19:31.103  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 19:19:31.103  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 19:19:31.103  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:31.104  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 19:19:31.104  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 19:19:31.104  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f102a58 removed from the list
,08-30 19:19:31.104  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:19:31.104  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed907b1 removed from the list
08-30 19:19:31.107  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:19:31.110  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:19:31.111  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 19:19:31.111  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:19:31.111  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:31.111  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:19:31.114  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:19:31.114  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:19:31.114  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:19:31.114  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed907b1 not in the list
08-30 19:19:31.114  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:31.114  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:19:31.116  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:19:31.116  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:19:31.117  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:19:31.117  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed907b1 not in the list
08-30 19:19:31.117  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:19:31.117  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:31.117  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:19:31.117  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f102a58 not in the list
08-30 19:19:31.118  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 19:19:31.118  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@982b817 added. We now have 3 listener(s)
,08-30 19:19:31.120  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 19:19:31.120  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 19:19:31.120  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 19:19:31.120  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 19:19:31.120  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9899404 added. We now have 4 listener(s)
08-30 19:19:31.120  3757  3807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 19:19:31.121  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 19:19:31.127  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 19:19:31.134  3757  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 19:19:31.134  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:19:31.134  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:19:31.134  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:19:31.134  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:19:31.134  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:19:31.134  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:19:31.134  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 19:19:31.138  3757  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 19:19:31.138  3757  3807 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 19:19:31.139  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 19:19:31.139  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 19:19:31.140  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 19:19:31.141  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 19:19:31.141  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 19:19:31.143  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:19:31.145  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:19:31.150  3757  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 19:19:31.150  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 19:19:31.155  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 19:19:31.156  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 19:19:31.156  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 19:19:31.162  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 19:19:31.162  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 19:19:31.162  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 19:19:31.163  3757  3807 D BluetoothAdapter: STATE_ON
,08-30 19:19:31.166  4145  4173 D BtGatt.GattService: registerClient() - UUID=b24d2591-4d53-49d1-a6c0-8e77e4cf0dda
,08-30 19:19:31.168  4145  4161 D BtGatt.GattService: onClientRegistered() - UUID=b24d2591-4d53-49d1-a6c0-8e77e4cf0dda, clientIf=5
,08-30 19:19:31.169  3757  3823 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 19:19:31.172  4145  4174 D BtGatt.GattService: start scan with filters
,08-30 19:19:31.177  4145  4164 D BtGatt.ScanManager: handling starting scan
,08-30 19:19:31.177  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 19:19:31.177  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 19:19:31.178  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 19:19:31.178  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 19:19:31.180  4145  4164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efb459c
08-30 19:19:31.183  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 19:19:31.184  3757  3757 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 19:19:31.184  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 19:19:31.186  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 19:19:31.188  3757  3807 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 19:19:31.189  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 19:19:31.189  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 19:19:31.189  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:31.189  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 19:19:31.189  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 19:19:31.189  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 19:19:31.189  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 19:19:31.189  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 19:19:31.190  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 19:19:31.190  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 19:19:31.190  3757  3807 D BluetoothAdapter: STATE_ON
08-30 19:19:31.191  4145  4174 D BtGatt.GattService: stopScan() - queue size =1
,08-30 19:19:31.192  4145  4156 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 19:19:31.192  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 19:19:31.192  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 19:19:31.192  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 19:19:31.193  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 19:19:31.193  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 19:19:31.194  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 19:19:31.194  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 19:19:31.194  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 19:19:31.195  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 19:19:31.195  4145  4161 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 19:19:31.195  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 19:19:31.195  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 19:19:31.196  3757  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 19:19:31.196  3757  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 19:19:31.197  3757  3757 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 19:19:31.197  4145  4164 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 19:19:31.214  4145  4161 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 19:19:31.214  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:19:31.215  4145  4164 D BtGatt.ScanManager: Starting BLE batch scan
08-30 19:19:31.216  4145  4164 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 19:19:31.245  4145  4161 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 19:19:31.245  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:19:31.261  4145  4161 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 19:19:31.262  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:19:31.291  4145  4161 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 19:19:31.292  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 19:19:31.292  4145  4164 D BtGatt.ScanManager: stopping BLe Batch
,08-30 19:19:31.315  4145  4161 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 19:19:31.316  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:19:31.317  4145  4164 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 19:19:31.339  4145  4161 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 19:19:31.340  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:19:31.698  3757  3757 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 19:19:31.698  3757  3757 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 19:19:31.698  3757  3757 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 19:19:34.198  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 19:19:34.198  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 19:19:34.198  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 19:19:34.200  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:19:34.200  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:34.200  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 19:19:34.200  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 19:19:34.201  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@982b817 removed from the list
,08-30 19:19:34.201  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:19:34.201  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9899404 removed from the list
08-30 19:19:34.202  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:19:34.202  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:19:34.204  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:19:34.204  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:19:34.207  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:19:34.208  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 19:19:34.208  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:19:34.208  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9899404 not in the list
08-30 19:19:34.209  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:34.209  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:19:34.213  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:19:34.213  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 19:19:34.213  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:19:34.214  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9899404 not in the list
08-30 19:19:34.214  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 19:19:34.215  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:34.215  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:19:34.215  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@982b817 not in the list
08-30 19:19:34.216  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 19:19:34.216  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@797fbe9 added. We now have 3 listener(s)
08-30 19:19:34.218  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 19:19:34.218  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 19:19:34.218  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 19:19:34.218  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 19:19:34.218  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ad706e added. We now have 4 listener(s)
08-30 19:19:34.219  3757  3807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 19:19:34.219  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 19:19:34.223  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 19:19:34.230  3757  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 19:19:34.230  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:19:34.230  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:19:34.230  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:19:34.230  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:19:34.230  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:19:34.230  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:19:34.230  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 19:19:34.232  3757  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 19:19:34.232  3757  3807 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 19:19:34.232  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 19:19:34.233  3757  3807 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,08-30 19:19:34.233  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-30 19:19:34.233  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 19:19:34.233  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-30 19:19:34.234  3757  3807 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 19:19:34.234  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 19:19:34.235  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 19:19:34.236  3757  3807 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-30 19:19:34.236  3757  3807 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 19:19:34.236  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 19:19:34.236  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-30 19:19:34.236  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 19:19:34.236  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 19:19:34.237  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:19:34.239  3757  4242 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 19:19:34.240  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:19:34.240  3757  3757 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-30 19:19:34.242  3757  4242 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-30 19:19:34.245  3757  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 19:19:34.245  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 19:19:34.249  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 19:19:34.250  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 19:19:34.250  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 19:19:34.252  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-30 19:19:34.252  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 19:19:34.253  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-30 19:19:34.254  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 19:19:34.254  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 19:19:34.254  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-30 19:19:34.256  3757  3807 D BluetoothAdapter: STATE_ON
,08-30 19:19:34.259  4145  4155 D BtGatt.GattService: registerClient() - UUID=736540a4-2205-4b7a-95f6-291409caa9a3
,08-30 19:19:34.259  4145  4161 D BtGatt.GattService: onClientRegistered() - UUID=736540a4-2205-4b7a-95f6-291409caa9a3, clientIf=5
08-30 19:19:34.260  3757  3769 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-30 19:19:34.262  4145  4163 D BtGatt.AdvertiseManager: message : 0
,08-30 19:19:34.266  4145  4163 D BtGatt.AdvertiseManager: starting multi advertising
,08-30 19:19:34.277  4145  4161 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-30 19:19:34.286  4145  4161 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-30 19:19:34.288  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-30 19:19:34.288  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 19:19:34.290  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 19:19:34.292  3757  3757 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 19:19:34.292  3757  3757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-30 19:19:34.292  3757  3757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-30 19:19:34.292  3757  3757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-30 19:19:34.293  3757  3757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-30 19:19:34.293  3757  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-30 19:19:34.296  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 19:19:34.297  3757  3757 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 19:19:34.298  3757  3757 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 19:19:34.799  3757  3757 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-30 19:19:34.799  3757  3757 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 19:19:34.799  3757  3757 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 19:19:37.297  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 19:19:37.298  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-30 19:19:37.298  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 19:19:37.298  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 19:19:37.298  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-30 19:19:37.299  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 19:19:37.300  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 19:19:37.300  3757  4242 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-30 19:19:37.300  3757  3807 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 19:19:37.300  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 19:19:37.300  3757  3757 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-30 19:19:37.301  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 19:19:37.301  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 19:19:37.301  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 19:19:37.301  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 19:19:37.300  3757  4242 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-30 19:19:37.302  3757  4242 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-30 19:19:37.304  3757  3807 D BluetoothAdapter: STATE_ON
08-30 19:19:37.305  3757  3807 D BluetoothLeScanner: could not find callback wrapper
08-30 19:19:37.305  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 19:19:37.305  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-30 19:19:37.308  4145  4163 D BtGatt.AdvertiseManager: message : 1
08-30 19:19:37.310  4145  4163 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-30 19:19:37.335  4145  4161 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-30 19:19:37.335  4145  4161 D BtGatt.GattService: Client app is not null!
08-30 19:19:37.336  4145  4173 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 19:19:37.337  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 19:19:37.337  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-30 19:19:37.337  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-30 19:19:37.337  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-30 19:19:37.338  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-30 19:19:37.339  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 19:19:37.339  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 19:19:37.340  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 19:19:37.340  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 19:19:37.343  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:19:37.343  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:19:37.343  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 19:19:37.343  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 19:19:37.343  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@797fbe9 removed from the list
08-30 19:19:37.343  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:19:37.343  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ad706e removed from the list
08-30 19:19:37.344  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:19:37.344  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:19:37.344  3757  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 19:19:37.344  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:37.344  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:19:37.346  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:19:37.346  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:19:37.347  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:19:37.347  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ad706e not in the list
08-30 19:19:37.347  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:37.347  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:19:37.349  3757  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 19:19:37.349  3757  3757 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 19:19:37.349  3757  3757 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 19:19:37.350  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:19:37.350  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:19:37.350  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:19:37.350  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ad706e not in the list
08-30 19:19:37.350  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 19:19:37.350  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:37.350  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:19:37.350  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@797fbe9 not in the list
08-30 19:19:37.351  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 19:19:37.351  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cb512b added. We now have 3 listener(s)
08-30 19:19:37.354  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 19:19:37.355  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 19:19:37.355  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 19:19:37.355  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 19:19:37.355  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ed988 added. We now have 4 listener(s)
08-30 19:19:37.355  3757  3807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 19:19:37.356  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 19:19:37.360  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 19:19:37.368  3757  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 19:19:37.368  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:19:37.368  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:19:37.368  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:19:37.368  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:19:37.368  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:19:37.368  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:19:37.368  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 19:19:37.371  3757  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 19:19:37.372  3757  3807 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 19:19:37.372  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 19:19:37.373  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 19:19:37.373  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 19:19:37.373  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 19:19:37.373  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 19:19:37.376  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:19:37.379  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:19:37.381  3757  3807 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 19:19:37.381  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 19:19:37.389  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 19:19:37.390  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 19:19:37.390  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 19:19:37.395  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 19:19:37.395  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 19:19:37.396  3757  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 19:19:37.396  3757  3807 D BluetoothAdapter: STATE_ON
,08-30 19:19:37.400  4145  4156 D BtGatt.GattService: registerClient() - UUID=0be7f420-bd7d-4c82-a2fc-0788ca5de05b
08-30 19:19:37.400  4145  4161 D BtGatt.GattService: onClientRegistered() - UUID=0be7f420-bd7d-4c82-a2fc-0788ca5de05b, clientIf=5
08-30 19:19:37.401  3757  3769 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 19:19:37.401  4145  4155 D BtGatt.GattService: start scan with filters
08-30 19:19:37.406  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 19:19:37.406  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 19:19:37.406  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 19:19:37.406  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 19:19:37.406  4145  4164 D BtGatt.ScanManager: handling starting scan
08-30 19:19:37.411  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 19:19:37.411  3757  3757 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 19:19:37.412  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 19:19:37.415  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 19:19:37.425  4145  4161 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 19:19:37.425  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 19:19:37.425  4145  4164 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 19:19:37.439  4145  4161 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 19:19:37.439  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 19:19:37.440  4145  4164 D BtGatt.ScanManager: Starting BLE batch scan
08-30 19:19:37.440  4145  4164 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 19:19:37.464  4145  4161 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 19:19:37.465  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:19:37.482  4145  4161 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 19:19:37.483  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:19:37.850  3757  3757 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 19:19:37.912  3757  3757 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 19:19:37.912  3757  3757 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 19:19:37.912  3757  3757 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 19:19:38.987  4145  4145 D BtGatt.ScanManager: awakened up at time 228062
08-30 19:19:38.990  4145  4164 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 19:19:39.053  4145  4161 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
,08-30 19:19:39.053  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 19:19:39.054  4145  4161 D BtGatt.GattService: current time is 228129886806
,08-30 19:19:39.056  4145  4161 D BtGatt.GattService: Batch record : [87, 45, 110, 28, -13, -4, 1, -128, -70, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85, 0, 37, -47, 14, -113, 116, -46, 1, -128, -82, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 85, -35, 28, 42, 84, 1, -128, -60, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, -126, -22, -96, 83, -39, -56, 1, -128, -60, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65, 0, 71, -122, -77, 84, 69, -12, 1, -128, -85, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -83, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -89, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -87, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -126, -22, -96, 83, -39, -56, 1, -128, -60, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65, 0]
,08-30 19:19:39.059  4145  4161 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85]
,08-30 19:19:39.061  4145  4161 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-30 19:19:39.062  4145  4161 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
,08-30 19:19:39.063  4145  4161 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65]
08-30 19:19:39.063  4145  4161 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 19:19:39.064  4145  4161 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-30 19:19:39.065  4145  4161 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 19:19:39.066  4145  4161 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 19:19:39.066  4145  4161 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65]
,08-30 19:19:39.073  3757  3757 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 1], added - the peer count is 1
,08-30 19:19:39.075  3757  3757 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:75:41 1], added - the peer count is 2
,08-30 19:19:39.077  3757  3757 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 3
,08-30 19:19:39.078  3757  3757 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 08:EC:A9:50:75:41 1] updated - the peer count is 3
08-30 19:19:39.078  3757  3757 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
,08-30 19:19:39.079  3757  3757 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:75:41 1], Bluetooth address: 08:EC:A9:50:75:41, device name: '', device address: ''
08-30 19:19:39.079  3757  3757 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,08-30 19:19:39.848   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=228923, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:19:40.427  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 19:19:40.428  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 19:19:40.428  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 19:19:40.428  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:40.429  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 19:19:40.429  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 19:19:40.430  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 19:19:40.430  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 19:19:40.430  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 19:19:40.431  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 19:19:40.431  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 19:19:40.433  3757  3807 D BluetoothAdapter: STATE_ON
08-30 19:19:40.436  4145  4155 D BtGatt.GattService: stopScan() - queue size =1
08-30 19:19:40.440  4145  4174 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 19:19:40.442  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 19:19:40.442  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 19:19:40.444  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 19:19:40.445  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 19:19:40.445  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 19:19:40.450  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-30 19:19:40.450  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 19:19:40.451  3757  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 19:19:40.451  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 19:19:40.453  4145  4145 D BtGatt.ScanManager: awakened up at time 229529
08-30 19:19:40.454  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 19:19:40.454  3757  3807 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
08-30 19:19:40.457  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:19:40.457  3757  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 19:19:40.457  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:40.457  3757  3757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 19:19:40.457  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 19:19:40.457  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 19:19:40.457  3757  3757 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 19:19:40.458  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cb512b removed from the list
08-30 19:19:40.458  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:19:40.458  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ed988 removed from the list
08-30 19:19:40.458  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:19:40.459  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:19:40.460  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:40.460  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:19:40.464  4145  4161 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 19:19:40.463  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:19:40.464  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 19:19:40.464  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:19:40.464  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:19:40.465  4145  4164 D BtGatt.ScanManager: stopping BLe Batch
08-30 19:19:40.465  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ed988 not in the list
,08-30 19:19:40.465  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:19:40.465  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:19:40.469  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 19:19:40.469  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:19:40.469  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:19:40.469  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ed988 not in the list
08-30 19:19:40.469  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:19:40.469  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 19:19:40.469  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:19:40.470  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cb512b not in the list
08-30 19:19:40.470  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 19:19:40.471  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2ab159 added. We now have 3 listener(s)
08-30 19:19:40.472  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 19:19:40.473  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 19:19:40.473  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 19:19:40.473  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 19:19:40.473  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10cd11e added. We now have 4 listener(s)
08-30 19:19:40.473  3757  3807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 19:19:40.474  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 19:19:40.480  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 19:19:40.481  4145  4161 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 19:19:40.481  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 19:19:40.482  4145  4164 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 19:19:40.489  3757  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 19:19:40.489  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 19:19:40.489  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 19:19:40.489  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 19:19:40.489  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 19:19:40.489  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 19:19:40.489  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 19:19:40.489  3757  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 19:19:40.492  3757  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 19:19:40.493  3757  3807 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 19:19:40.495  3757  3807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 19:19:40.495  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 19:19:40.495  3757  3807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 19:19:40.495  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 19:19:40.495  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:40.495  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 19:19:40.495  3757  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 19:19:40.496  3757  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2ab159 removed from the list
08-30 19:19:40.496  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:19:40.496  3757  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10cd11e removed from the list
,08-30 19:19:40.500  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 19:19:40.500  3757  3807 D io.jxcore.node.ConnectivityMonitor: stop
08-30 19:19:40.500  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:19:40.501  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:40.501  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 19:19:40.502  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:19:40.502  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:19:40.502  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:19:40.503  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10cd11e not in the list
08-30 19:19:40.503  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:40.503  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:19:40.504  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 19:19:40.505  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 19:19:40.505  3757  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 19:19:40.505  3757  3807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10cd11e not in the list
08-30 19:19:40.505  3757  3807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 19:19:40.505  3757  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 19:19:40.505  3757  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 19:19:40.505  3757  3807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2ab159 not in the list
,08-30 19:19:40.506  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 19:19:40.506  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 19:19:40.506  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 19:19:40.506  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 19:19:40.507  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 19:19:40.507  3757  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 19:19:40.508  4145  4161 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-30 19:19:40.508  4145  4161 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 19:19:40.509  4145  4161 D BtGatt.GattService: current time is 229584903037
,08-30 19:19:40.509  4145  4161 D BtGatt.GattService: Batch record : [87, 45, 110, 28, -13, -4, 1, -128, -71, 29, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85, 0],
08-30 19:19:40.509  3757  3757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 19:19:40.510  4145  4161 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85]
,08-30 19:19:40.958  3757  3757 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 19:19:42.525  3757  4243 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 447, name: My test thread name)
,08-30 19:19:44.523  3757  3807 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 447
,08-30 19:19:44.523  3757  3807 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 447, name: My test thread name)
,08-30 19:19:44.530  3757  4244 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 448, name: My test thread name)
,08-30 19:19:44.531  3757  4244 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 448, thread name: My test thread name)
,08-30 19:19:44.531  3757  4244 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 448, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-30 19:19:44.536  3757  3807 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 19:19:44.544  3757  4245 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 452, name: My test thread name)
,08-30 19:19:44.545  3757  4245 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 452, thread name: My test thread name): Test exception.
,08-30 19:19:44.545  3757  4245 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 452, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-30 19:19:44.549  3757  3807 I jxcore-log: Total number of executed tests:  82
08-30 19:19:44.549  3757  3807 I jxcore-log: 
,08-30 19:19:44.549  3757  3807 I jxcore-log: Number of passed tests:  82
08-30 19:19:44.549  3757  3807 I jxcore-log: 
08-30 19:19:44.550  3757  3807 I jxcore-log: Number of failed tests:  0
08-30 19:19:44.550  3757  3807 I jxcore-log: 
08-30 19:19:44.550  3757  3807 I jxcore-log: Number of ignored tests:  0
08-30 19:19:44.550  3757  3807 I jxcore-log: 
08-30 19:19:44.550  3757  3807 I jxcore-log: Total duration:  101371
08-30 19:19:44.550  3757  3807 I jxcore-log: 
,08-30 19:19:44.552  3757  3807 I jxcore-log: Unit Test app is loaded,
08-30 19:19:44.552  3757  3807 I jxcore-log: 
,08-30 19:19:44.560  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.560  3757  3807 I jxcore-log: 
,08-30 19:19:44.565  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.565  3757  3807 I jxcore-log: 
08-30 19:19:44.566  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.566  3757  3807 I jxcore-log: 
08-30 19:19:44.567  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.567  3757  3807 I jxcore-log: 
,08-30 19:19:44.568  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 19:19:44.568  3757  3807 I jxcore-log: 
,08-30 19:19:44.570  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 19:19:44.570  3757  3807 I jxcore-log: 
,08-30 19:19:44.573  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.573  3757  3807 I jxcore-log: 
,08-30 19:19:44.574  3757  3757 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 19:19:44.575  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.575  3757  3807 I jxcore-log: 
,08-30 19:19:44.576  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 19:19:44.576  3757  3807 I jxcore-log: 
,08-30 19:19:44.577  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 19:19:44.577  3757  3807 I jxcore-log: 
,08-30 19:19:44.578  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 19:19:44.578  3757  3807 I jxcore-log: 
08-30 19:19:44.579  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.579  3757  3807 I jxcore-log: 
08-30 19:19:44.579  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.579  3757  3807 I jxcore-log: 
,08-30 19:19:44.580  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.580  3757  3807 I jxcore-log: 
08-30 19:19:44.581  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 19:19:44.581  3757  3807 I jxcore-log: 
,08-30 19:19:44.582  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 19:19:44.582  3757  3807 I jxcore-log: 
08-30 19:19:44.583  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 19:19:44.583  3757  3807 I jxcore-log: 
,08-30 19:19:44.585  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 19:19:44.585  3757  3807 I jxcore-log: 
,08-30 19:19:44.586  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 19:19:44.586  3757  3807 I jxcore-log: 
08-30 19:19:44.586  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 19:19:44.586  3757  3807 I jxcore-log: 
08-30 19:19:44.587  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 19:19:44.587  3757  3807 I jxcore-log: 
,08-30 19:19:44.588  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 19:19:44.588  3757  3807 I jxcore-log: 
,08-30 19:19:44.589  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 19:19:44.589  3757  3807 I jxcore-log: 
08-30 19:19:44.590  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.590  3757  3807 I jxcore-log: 
,08-30 19:19:44.590  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.590  3757  3807 I jxcore-log: 
,08-30 19:19:44.592  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.592  3757  3807 I jxcore-log: 
08-30 19:19:44.593  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 19:19:44.593  3757  3807 I jxcore-log: 
08-30 19:19:44.593  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 19:19:44.593  3757  3807 I jxcore-log: 
,08-30 19:19:44.594  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 19:19:44.594  3757  3807 I jxcore-log: 
,08-30 19:19:44.595  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 19:19:44.595  3757  3807 I jxcore-log: 
08-30 19:19:44.596  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 19:19:44.596  3757  3807 I jxcore-log: 
08-30 19:19:44.596  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
,08-30 19:19:44.596  3757  3807 I jxcore-log: 
08-30 19:19:44.597  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 19:19:44.597  3757  3807 I jxcore-log: 
,08-30 19:19:44.598  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 19:19:44.598  3757  3807 I jxcore-log: 
,08-30 19:19:44.599  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 19:19:44.599  3757  3807 I jxcore-log: 
08-30 19:19:44.600  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 19:19:44.600  3757  3807 I jxcore-log: 
08-30 19:19:44.600  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 19:19:44.600  3757  3807 I jxcore-log: 
,08-30 19:19:44.602  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 19:19:44.602  3757  3807 I jxcore-log: 
,08-30 19:19:44.602  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 19:19:44.602  3757  3807 I jxcore-log: 
08-30 19:19:44.603  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 19:19:44.603  3757  3807 I jxcore-log: 
08-30 19:19:44.603  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 19:19:44.603  3757  3807 I jxcore-log: 
08-30 19:19:44.604  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 19:19:44.604  3757  3807 I jxcore-log: 
,08-30 19:19:44.604  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 19:19:44.604  3757  3807 I jxcore-log: 
,08-30 19:19:44.605  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.605  3757  3807 I jxcore-log: 
08-30 19:19:44.605  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.605  3757  3807 I jxcore-log: 
08-30 19:19:44.606  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.606  3757  3807 I jxcore-log: 
08-30 19:19:44.606  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.606  3757  3807 I jxcore-log: 
08-30 19:19:44.607  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.607  3757  3807 I jxcore-log: 
08-30 19:19:44.607  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 19:19:44.607  3757  3807 I jxcore-log: 
08-30 19:19:44.608  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-30 19:19:44.608  3757  3807 I jxcore-log: 
08-30 19:19:44.608  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 19:19:44.608  3757  3807 I jxcore-log: 
08-30 19:19:44.609  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.609  3757  3807 I jxcore-log: 
08-30 19:19:44.609  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 19:19:44.609  3757  3807 I jxcore-log: 
08-30 19:19:44.610  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 19:19:44.610  3757  3807 I jxcore-log: 
08-30 19:19:44.611  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 19:19:44.611  3757  3807 I jxcore-log: 
08-30 19:19:44.613  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 19:19:44.613  3757  3807 I jxcore-log: 
,08-30 19:19:44.615  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 19:19:44.615  3757  3807 I jxcore-log: 
,08-30 19:19:44.617  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 19:19:44.617  3757  3807 I jxcore-log: 
,08-30 19:19:44.619  3757  3807 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 19:19:44.619  3757  3807 I jxcore-log: 
,08-30 19:19:44.628  3757  3807 I jxcore-log: My device name is: motorola-Nexus 6
08-30 19:19:44.628  3757  3807 I jxcore-log: 
,08-30 19:19:44.669  3757  4243 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 447, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-30 19:19:46.135   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=235210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 19:19:47.168  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 19:19:47.168  3757  3807 I jxcore-log: 
,08-30 19:19:47.633  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 19:19:47.633  3757  3807 I jxcore-log: 
,08-30 19:19:47.659  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 19:19:47.659  3757  3807 I jxcore-log: 
,08-30 19:19:49.170  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 19:19:49.170  3757  3807 I jxcore-log: 
,08-30 19:19:49.424  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-30 19:19:49.424  3757  3807 I jxcore-log: 
,08-30 19:19:49.429  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-30 19:19:49.429  3757  3807 I jxcore-log: 
,08-30 19:19:49.436  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
08-30 19:19:49.436  3757  3807 I jxcore-log: 
,08-30 19:19:49.515  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-30 19:19:49.515  3757  3807 I jxcore-log: 
,08-30 19:19:49.535  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-30 19:19:49.535  3757  3807 I jxcore-log: 
,08-30 19:19:49.540  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
08-30 19:19:49.540  3757  3807 I jxcore-log: 
,08-30 19:19:49.780  3711  4246 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 19:19:49.819  3711  4247 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 19:19:49.834  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:19:49.839  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:19:49.868  1510  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 19:19:49.868  1510  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 19:19:49.869  1510  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:19:49.869  1510  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:19:49.895  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:19:49.897  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:19:49.926  1510  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 19:19:49.926  1510  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 19:19:49.926  1510  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 19:19:49.926  1510  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:19:49.944  3711  4247 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 19:19:49.945  3711  4246 E BooksSync: Soft error
08-30 19:19:49.945  3711  4246 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 19:19:49.945  3711  4246 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 19:19:49.946  3711  4246 E BooksSync: Sync error
08-30 19:19:49.946  3711  4246 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 19:19:49.946  3711  4246 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 19:19:49.946  3711  4246 I BooksSync: Finished books sync
,08-30 19:19:49.958   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 238716, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 19:19:50.498  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
08-30 19:19:50.498  3757  3807 I jxcore-log: 
,08-30 19:19:50.670  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-30 19:19:50.670  3757  3807 I jxcore-log: 
,08-30 19:19:51.058  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-30 19:19:51.058  3757  3807 I jxcore-log: 
,08-30 19:19:51.070  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-30 19:19:51.070  3757  3807 I jxcore-log: 
,08-30 19:19:51.081  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-30 19:19:51.081  3757  3807 I jxcore-log: 
,08-30 19:19:51.090  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-30 19:19:51.090  3757  3807 I jxcore-log: 
,08-30 19:19:51.182  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-30 19:19:51.182  3757  3807 I jxcore-log: 
,08-30 19:19:51.232  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-30 19:19:51.232  3757  3807 I jxcore-log: 
,08-30 19:19:51.240  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-30 19:19:51.240  3757  3807 I jxcore-log: 
,08-30 19:19:51.248  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-30 19:19:51.248  3757  3807 I jxcore-log: 
,08-30 19:19:51.269  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-30 19:19:51.269  3757  3807 I jxcore-log: 
,08-30 19:19:51.275  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-30 19:19:51.275  3757  3807 I jxcore-log: 
,08-30 19:19:51.281  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js,
08-30 19:19:51.281  3757  3807 I jxcore-log: 
,08-30 19:19:51.298  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-30 19:19:51.298  3757  3807 I jxcore-log: 
,08-30 19:19:51.326  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-30 19:19:51.326  3757  3807 I jxcore-log: 
,08-30 19:19:51.337  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-30 19:19:51.337  3757  3807 I jxcore-log: ,
,08-30 19:19:51.351  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-30 19:19:51.351  3757  3807 I jxcore-log: 
,08-30 19:19:51.363  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-30 19:19:51.363  3757  3807 I jxcore-log: 
,08-30 19:19:51.380  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-30 19:19:51.380  3757  3807 I jxcore-log: 
,08-30 19:19:51.391  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-30 19:19:51.391  3757  3807 I jxcore-log: 
,08-30 19:19:51.396  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-30 19:19:51.396  3757  3807 I jxcore-log: 
,08-30 19:19:51.429  3757  3807 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-30 19:19:51.429  3757  3807 I jxcore-log: 
,08-30 19:19:51.440  3757  3807 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-30 19:19:51.442  3757  3807 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-30 19:19:51.442  3757  3807 I jxcore-log: 
,08-30 19:20:08.789   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=257864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:20:14.922   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=263997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 19:20:20.218  3047  4249 V KeepSync: Connecting to GoogleApiClient
08-30 19:20:20.219   871  2155 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 19:20:20.277  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:20:20.279  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:20:20.321  1510  2411 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-30 19:20:20.321  1510  2411 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 19:20:20.321  1510  2411 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:20:20.321  1510  2411 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:20:20.345  1705  4250 V BaseAuthAsyncOperation: access token request failed
,08-30 19:20:20.346  3047  4249 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 19:20:20.399  1510  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-30 19:20:20.399  1510  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-30 19:20:20.399  1510  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:20:20.399  1510  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:20:20.414  3047  4249 E KeepSync: IOException
08-30 19:20:20.414  3047  4249 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 19:20:20.414  3047  4249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
,08-30 19:20:20.414  3047  4249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 19:20:20.414  3047  4249 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 19:20:20.414  3047  4249 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 19:20:20.414  3047  4249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 19:20:20.414  3047  4249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 19:20:20.414  3047  4249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 19:20:20.414  3047  4249 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 19:20:20.414  3047  4249 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 19:20:20.414  3047  4249 E KeepSync: 	,at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 19:20:20.414  3047  4249 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 19:20:20.414  3047  4249 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 19:20:20.414  3047  4249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 19:20:20.414  3047  4249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 19:20:20.414  3047  4249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 19:20:20.414  3047  4249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 19:20:20.414  3047  4249 E KeepSync: 	... 10 more
08-30 19:20:20.414  3047  4249 W KeepSync: Sync result 2
,08-30 19:20:20.427   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 249780, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 19:20:37.589   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=286664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:20:45.295   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=294370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 19:20:50.843  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:20:50.845  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:20:50.883  1510  2145 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 19:20:50.883  1510  2145 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 19:20:50.883  1510  2145 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 19:20:50.883  1510  2145 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:20:50.900  3004  4257 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 19:20:50.900  3004  4257 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at jdm.a(PG:82)
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at jcs.o(PG:406)
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at jcn.a(PG:1379)
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at jcs.i(PG:143)
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at blb.a(PG:3937)
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at czp.a(PG:18188)
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at czp.a(PG:9081)
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at czq.run(PG:1686)
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 19:20:50.900  3004  4257 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at jdj.a(PG:4091)
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at jdj.a(PG:1125)
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at jdm.a(PG:77)
08-30 19:20:50.900  3004  4257 E HttpOperation: 	... 12 more
08-30 19:20:50.900  3004  4257 E HttpOperation: Caused by: faj: BadAuthentication
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at fal.a(PG:38)
08-30 19:20:50.900  3004  4257 E HttpOperation: 	at jdj.a(PG:4089)
08-30 19:20:50.900  3004  4257 E HttpOperation: 	... 14 more
,08-30 19:20:50.966  1510  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 19:20:50.966  1510  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 19:20:50.966  1510  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:20:50.967  1510  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:20:50.999  3004  4257 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 19:20:50.999  3004  4257 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at jdm.a(PG:82)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at jcs.o(PG:406)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at jcn.a(PG:1379)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at jcs.i(PG:143)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at hec.a(PG:42)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at hee.a(PG:102)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at czr.a(PG:65)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at kka.a(PG:108)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at czp.a(PG:19176)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at czp.a(PG:9081)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at czq.run(PG:1686)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 19:20:50.999  3004  4257 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at jdj.a(PG:4091)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at jdj.a(PG:1125)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at jdm.a(PG:77)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	... 15 more
08-30 19:20:50.999  3004  4257 E HttpOperation: Caused by: faj: BadAuthentication
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at fal.a(PG:38)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	at jdj.a(PG:4089)
08-30 19:20:50.999  3004  4257 E HttpOperation: 	... 17 more
08-30 19:20:51.000  3004  4257 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 19:20:51.000  3004  4257 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at hec.a(PG:42)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at hee.a(PG:102)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at czr.a(PG:65)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at kka.a(PG:108)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	... 15 more
08-30 19:20:51.000  3004  4257 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at fal.a(PG:38)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 19:20:51.000  3004  4257 E ExperimentLoader: 	... 17 more
,08-30 19:20:51.179   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 293648, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-30 19:20:51.243  3047  4259 V KeepSync: Connecting to GoogleApiClient
08-30 19:20:51.243   871  1381 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 19:20:51.301  1510  2145 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-30 19:20:51.301  1510  2145 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 19:20:51.301  1510  2145 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:20:51.301  1510  2145 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:20:51.333  1705  4260 V BaseAuthAsyncOperation: access token request failed
08-30 19:20:51.334  3047  4259 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 19:20:51.368  1510  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-30 19:20:51.368  1510  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-30 19:20:51.368  1510  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:20:51.368  1510  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:20:51.385  3047  4259 E KeepSync: IOException
08-30 19:20:51.385  3047  4259 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 19:20:51.385  3047  4259 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 19:20:51.385  3047  4259 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 19:20:51.385  3047  4259 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 19:20:51.385  3047  4259 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 19:20:51.385  3047  4259 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 19:20:51.385  3047  4259 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 19:20:51.385  3047  4259 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 19:20:51.385  3047  4259 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 19:20:51.385  3047  4259 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 19:20:51.385  3047  4259 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 19:20:51.385  3047  4259 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 19:20:51.385  3047  4259 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 19:20:51.385  3047  4259 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 19:20:51.385  3047  4259 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 19:20:51.385  3047  4259 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 19:20:51.385  3047  4259 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 19:20:51.385  3047  4259 E KeepSync: 	... 10 more
08-30 19:20:51.385  3047  4259 W KeepSync: Sync result 2
,08-30 19:20:51.392   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 299936, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 19:21:21.548  3711  4270 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 19:21:21.570  3711  4271 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 19:21:21.584  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:21:21.586  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:21:21.622  1510  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 19:21:21.622  1510  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 19:21:21.622  1510  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:21:21.623  1510  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:21:21.657  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:21:21.659  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:21:21.692  1510  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 19:21:21.693  1510  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 19:21:21.693  1510  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:21:21.693  1510  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:21:21.712  3711  4271 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 19:21:21.713  3711  4270 E BooksSync: Soft error
08-30 19:21:21.713  3711  4270 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 19:21:21.713  3711  4270 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 19:21:21.714  3711  4270 E BooksSync: Sync error
08-30 19:21:21.714  3711  4270 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 19:21:21.714  3711  4270 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 19:21:21.714  3711  4270 I BooksSync: Finished books sync
,08-30 19:21:21.725   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 304156, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 19:21:21.947  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:21:21.949  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:21:21.980  1510  2145 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 19:21:21.980  1510  2145 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 19:21:21.980  1510  2145 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:21:21.980  1510  2145 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:21:22.000  3004  4273 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 19:21:22.000  3004  4273 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at jdm.a(PG:82)
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at jcs.o(PG:406)
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at jcn.a(PG:1379)
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at jcs.i(PG:143)
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at blb.a(PG:3937)
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at czp.a(PG:18188)
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at czp.a(PG:9081)
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at czq.run(PG:1686)
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 19:21:22.000  3004  4273 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at jdj.a(PG:4091)
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at jdj.a(PG:1125)
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at jdm.a(PG:77)
08-30 19:21:22.000  3004  4273 E HttpOperation: 	... 12 more
08-30 19:21:22.000  3004  4273 E HttpOperation: Caused by: faj: BadAuthentication
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at fal.a(PG:38)
08-30 19:21:22.000  3004  4273 E HttpOperation: 	at jdj.a(PG:4089)
08-30 19:21:22.000  3004  4273 E HttpOperation: 	... 14 more
,08-30 19:21:22.042  1510  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 19:21:22.042  1510  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 19:21:22.043  1510  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:21:22.043  1510  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 19:21:22.057  3004  4273 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 19:21:22.057  3004  4273 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at jdm.a(PG:82)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at jcs.o(PG:406)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at jcn.a(PG:1379)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at jcs.i(PG:143)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at hec.a(PG:42)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at hee.a(PG:102)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at czr.a(PG:65)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at kka.a(PG:108)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at czp.a(PG:19176)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at czp.a(PG:9081)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at czq.run(PG:1686)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 19:21:22.057  3004  4273 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at jdj.a(PG:4091)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at jdj.a(PG:1125)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at jdm.a(PG:77)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	... 15 more
08-30 19:21:22.057  3004  4273 E HttpOperation: Caused by: faj: BadAuthentication
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at fal.a(PG:38)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	at jdj.a(PG:4089)
08-30 19:21:22.057  3004  4273 E HttpOperation: 	... 17 more
,08-30 19:21:22.057  3004  4273 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 19:21:22.057  3004  4273 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at hec.a(PG:42)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at hee.a(PG:102)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at czr.a(PG:65)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at kka.a(PG:108)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	... 15 more
08-30 19:21:22.057  3004  4273 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at fal.a(PG:38)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 19:21:22.057  3004  4273 E ExperimentLoader: 	... 17 more
,08-30 19:21:22.185   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 330797, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-30 19:21:24.415   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=333490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:21:30.656   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=339731, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:21:35.251  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:21:35.265  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:21:35.269  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:21:35.332  1510  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-30 19:21:35.333  1510  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-30 19:21:35.333  1510  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 19:21:35.333  1510  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:21:35.376  1510  2011 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 19:21:35.376  1510  2011 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 19:21:35.376  1510  2011 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 19:21:35.376  1510  2011 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-30 19:21:35.376  1510  2011 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-30 19:21:35.376  1510  2011 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-30 19:21:35.376  1510  2011 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-30 19:21:35.389  3508  3540 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 19:21:35.389  3508  3540 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-30 19:21:35.389  3508  3540 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-30 19:21:35.389  3508  3540 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-30 19:21:35.389  3508  3540 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-30 19:21:35.389  3508  3540 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-30 19:21:35.389  3508  3540 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-30 19:21:52.408  3047  4280 V KeepSync: Connecting to GoogleApiClient
,08-30 19:21:52.408   871  1995 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 19:21:52.466  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:21:52.472  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:21:52.504  1510  2145 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 19:21:52.504  1510  2145 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 19:21:52.504  1510  2145 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:21:52.504  1510  2145 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:21:52.528  1705  4281 V BaseAuthAsyncOperation: access token request failed
,08-30 19:21:52.529  3047  4280 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 19:21:52.581  1510  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 19:21:52.581  1510  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-30 19:21:52.581  1510  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:21:52.581  1510  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:21:52.606  3047  4280 E KeepSync: IOException
08-30 19:21:52.606  3047  4280 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 19:21:52.606  3047  4280 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 19:21:52.606  3047  4280 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 19:21:52.606  3047  4280 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 19:21:52.606  3047  4280 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 19:21:52.606  3047  4280 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 19:21:52.606  3047  4280 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 19:21:52.606  3047  4280 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 19:21:52.606  3047  4280 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 19:21:52.606  3047  4280 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 19:21:52.606  3047  4280 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 19:21:52.606  3047  4280 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 19:21:52.606  3047  4280 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 19:21:52.606  3047  4280 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 19:21:52.606  3047  4280 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 19:21:52.606  3047  4280 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 19:21:52.606  3047  4280 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 19:21:52.606  3047  4280 E KeepSync: 	... 10 more
,08-30 19:21:52.607  3047  4280 W KeepSync: Sync result 2
,08-30 19:21:52.613   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 361334, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 19:22:13.429   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=382504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:22:20.788   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=389864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:22:23.591  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:22:23.593  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:22:23.618  1510  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-30 19:22:23.618  1510  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 19:22:23.618  1510  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:22:23.618  1510  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:22:23.637  3004  4284 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 19:22:23.637  3004  4284 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at jdm.a(PG:82)
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at jcs.o(PG:406)
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at jcn.a(PG:1379)
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at jcs.i(PG:143)
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at blb.a(PG:3937)
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at czp.a(PG:18188)
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at czp.a(PG:9081)
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at czq.run(PG:1686)
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 19:22:23.637  3004  4284 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at jdj.a(PG:4091)
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at jdj.a(PG:1125)
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at jdm.a(PG:77)
08-30 19:22:23.637  3004  4284 E HttpOperation: 	... 12 more
08-30 19:22:23.637  3004  4284 E HttpOperation: Caused by: faj: BadAuthentication
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at fal.a(PG:38)
08-30 19:22:23.637  3004  4284 E HttpOperation: 	at jdj.a(PG:4089)
08-30 19:22:23.637  3004  4284 E HttpOperation: 	... 14 more
,08-30 19:22:23.709  1510  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 19:22:23.709  1510  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 19:22:23.709  1510  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 19:22:23.709  1510  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:22:23.755  3004  4284 E HttpOperation: [getmobileexperiments] Unexpected exception,
08-30 19:22:23.755  3004  4284 E HttpOperation: java.io.IOException: Cannot obtain authentication token,
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at jdm.a(PG:82)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at jcs.o(PG:406)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at jcn.a(PG:1379)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at jcs.i(PG:143)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at hec.a(PG:42)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at hee.a(PG:102)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at czr.a(PG:65)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at kka.a(PG:108)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at czp.a(PG:19176)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at czp.a(PG:9081)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at czq.run(PG:1686)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 19:22:23.755  3004  4284 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at jdj.a(PG:4091)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at jdj.a(PG:1125)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at jdm.a(PG:77)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	... 15 more
08-30 19:22:23.755  3004  4284 E HttpOperation: Caused by: faj: BadAuthentication
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at fal.a(PG:38)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	at jdj.a(PG:4089)
08-30 19:22:23.755  3004  4284 E HttpOperation: 	... 17 more
,08-30 19:22:23.756  3004  4284 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 19:22:23.756  3004  4284 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at hec.a(PG:42)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at hee.a(PG:102)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at czr.a(PG:65)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at kka.a(PG:108)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	... 15 more
08-30 19:22:23.756  3004  4284 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at fal.a(PG:38)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 19:22:23.756  3004  4284 E ExperimentLoader: 	... 17 more
,08-30 19:22:23.846   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 392344, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-30 19:22:38.496   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=407571, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:22:45.135   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=414210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:23:03.562   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=432637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:23:10.935   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=440010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:23:28.629   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=457704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:23:32.019  3711  4289 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 19:23:32.042  3711  4290 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 19:23:32.058  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:23:32.061  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:23:32.100  1510  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 19:23:32.100  1510  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 19:23:32.100  1510  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:23:32.100  1510  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:23:32.146  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:23:32.150  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:23:32.199  1510  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 19:23:32.200  1510  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 19:23:32.200  1510  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 19:23:32.200  1510  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:23:32.219  3711  4290 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 19:23:32.220  3711  4289 E BooksSync: Soft error
08-30 19:23:32.220  3711  4289 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 19:23:32.220  3711  4289 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 19:23:32.220  3711  4289 E BooksSync: Sync error
08-30 19:23:32.220  3711  4289 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 19:23:32.220  3711  4289 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 19:23:32.220  3711  4289 I BooksSync: Finished books sync
,08-30 19:23:32.229   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 461045, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 19:23:35.989   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=465063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:23:53.695   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=482770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:24:01.055   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=490130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:24:02.463  3047  4294 V KeepSync: Connecting to GoogleApiClient
,08-30 19:24:02.463   871  1390 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 19:24:02.530  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:24:02.536  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:24:02.572  1510  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-30 19:24:02.573  1510  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-30 19:24:02.573  1510  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:24:02.573  1510  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:24:02.598  1705  4295 V BaseAuthAsyncOperation: access token request failed
,08-30 19:24:02.599  3047  4294 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 19:24:02.660  1510  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 19:24:02.660  1510  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-30 19:24:02.660  1510  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:24:02.660  1510  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:24:02.682  3047  4294 E KeepSync: IOException
08-30 19:24:02.682  3047  4294 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 19:24:02.682  3047  4294 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 19:24:02.682  3047  4294 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 19:24:02.682  3047  4294 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 19:24:02.682  3047  4294 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 19:24:02.682  3047  4294 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 19:24:02.682  3047  4294 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 19:24:02.682  3047  4294 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 19:24:02.682  3047  4294 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 19:24:02.682  3047  4294 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 19:24:02.682  3047  4294 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 19:24:02.682  3047  4294 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 19:24:02.682  3047  4294 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 19:24:02.682  3047  4294 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 19:24:02.682  3047  4294 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 19:24:02.682  3047  4294 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 19:24:02.682  3047  4294 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 19:24:02.682  3047  4294 E KeepSync: 	... 10 more
08-30 19:24:02.682  3047  4294 W KeepSync: Sync result 2
,08-30 19:24:02.696   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 483421, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 19:24:18.762   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=507837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:24:23.988   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=513063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:24:33.102  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:24:33.105  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:24:33.133  1510  2411 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 19:24:33.134  1510  2411 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 19:24:33.134  1510  2411 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:24:33.134  1510  2411 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:24:33.151  3004  4298 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 19:24:33.151  3004  4298 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at jdm.a(PG:82)
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at jcs.o(PG:406)
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at jcn.a(PG:1379)
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at jcs.i(PG:143)
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at blb.a(PG:3937)
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at czp.a(PG:18188)
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at czp.a(PG:9081)
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at czq.run(PG:1686)
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 19:24:33.151  3004  4298 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at jdj.a(PG:4091)
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at jdj.a(PG:1125)
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at jdm.a(PG:77)
08-30 19:24:33.151  3004  4298 E HttpOperation: 	... 12 more
08-30 19:24:33.151  3004  4298 E HttpOperation: Caused by: faj: BadAuthentication
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at fal.a(PG:38)
08-30 19:24:33.151  3004  4298 E HttpOperation: 	at jdj.a(PG:4089)
08-30 19:24:33.151  3004  4298 E HttpOperation: 	... 14 more
,08-30 19:24:33.193  1510  2411 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 19:24:33.194  1510  2411 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 19:24:33.194  1510  2411 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:24:33.194  1510  2411 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:24:33.209  3004  4298 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 19:24:33.209  3004  4298 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at jdm.a(PG:82)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at jcs.o(PG:406)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at jcn.a(PG:1379)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at jcs.i(PG:143)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at hec.a(PG:42)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at hee.a(PG:102)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at czr.a(PG:65)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at kka.a(PG:108)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at czp.a(PG:19176)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at czp.a(PG:9081)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at czq.run(PG:1686)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 19:24:33.209  3004  4298 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at jdj.a(PG:4091)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at jdj.a(PG:1125)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at jdm.a(PG:77)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	... 15 more
08-30 19:24:33.209  3004  4298 E HttpOperation: Caused by: faj: BadAuthentication
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at fal.a(PG:38)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	at jdj.a(PG:4089)
08-30 19:24:33.209  3004  4298 E HttpOperation: 	... 17 more
,08-30 19:24:33.209  3004  4298 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 19:24:33.209  3004  4298 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at hec.a(PG:42)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at hee.a(PG:102)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at czr.a(PG:65)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at kka.a(PG:108)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	... 15 more
08-30 19:24:33.209  3004  4298 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at fal.a(PG:38)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 19:24:33.209  3004  4298 E ExperimentLoader: 	... 17 more
,08-30 19:24:33.338   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 515090, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-30 19:24:43.829   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=532904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:24:51.215   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=540290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:25:08.949   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=558024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:25:16.308   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=565383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:25:32.163  1510  2095 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 19:25:34.015   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=583090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:25:41.002   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=590077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:25:59.082   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=608157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:26:06.415   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=615490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:26:24.149   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=633224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:26:31.482   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=640557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:26:49.162   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=658237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:26:56.548   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=665623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:27:14.228   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=683303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:27:21.616   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=690690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:27:39.296   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=708371, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:27:46.655   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=715730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:28:04.362   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=733437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:28:11.722   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=740797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:28:29.429   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=758504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:28:36.789   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=765864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:28:54.495   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=783570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:29:01.842   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=790917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:29:19.562   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=808637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:29:26.909   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=815984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:29:44.629   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=833704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:29:51.975   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=841050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:30:09.642   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=858717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:30:17.042   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=866117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:30:34.709   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=883784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:30:42.095   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=891170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:30:46.735   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=895810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:31:07.162   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=916237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:31:11.788   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=920863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:31:32.202   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=941277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:31:36.842   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=945917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:31:57.269   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=966344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:32:01.895   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=970970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:32:22.335   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=991410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:32:26.948   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=996023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:32:47.389   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1016464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:32:52.015   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1021090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:33:12.442   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1041517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:33:17.081   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1046157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:33:37.509   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1066584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:33:42.148   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1071223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:34:02.576   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1091651, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:34:07.215   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1096290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:34:17.186  3508  3508 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,08-30 19:34:17.222  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:34:17.236  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:34:17.239  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:34:17.319  1510  2411 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-30 19:34:17.320  1510  2411 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-30 19:34:17.320  1510  2411 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:34:17.320  1510  2411 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:34:17.385  3508  3508 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-30 19:34:17.417  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:34:17.517  1510  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-30 19:34:17.518  1510  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-30 19:34:17.518  1510  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:34:17.519  1510  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:34:17.630  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:34:17.679  1510  2145 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-30 19:34:17.679  1510  2145 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-30 19:34:17.679  1510  2145 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 19:34:17.680  1510  2145 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:34:17.729  3508  3508 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-30 19:34:18.007  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:34:18.064  1510  2411 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-30 19:34:18.064  1510  2411 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-30 19:34:18.064  1510  2411 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:34:18.064  1510  2411 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:34:18.119  3508  3508 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-30 19:34:18.120  3508  3508 D Finsky  : [1] WearSupportService.startHygiene: disabled
,08-30 19:34:18.125  3508  3508 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,08-30 19:34:18.135  3508  3557 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-30 19:34:18.140  3508  3508 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,08-30 19:34:22.215   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1111290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:34:32.282   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1121357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:34:33.023  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:34:33.039  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:34:33.045  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:34:33.102  1510  2411 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 19:34:33.102  1510  2411 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 19:34:33.103  1510  2411 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:34:33.103  1510  2411 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:34:33.147  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 19:34:33.148  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 19:34:33.148  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,08-30 19:34:52.695   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1141770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:34:53.333  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:34:53.346  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:34:53.348  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:34:53.404  1510  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 19:34:53.404  1510  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 19:34:53.405  1510  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:34:53.406  1510  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:34:53.457  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 19:34:53.458  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 19:34:53.459  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-30 19:34:57.322   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1146397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:35:13.679  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:35:13.686  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:35:13.687  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:35:13.728  1510  2411 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 19:35:13.729  1510  2411 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 19:35:13.729  1510  2411 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 19:35:13.729  1510  2411 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:35:13.762  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 19:35:13.763  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 19:35:13.763  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-30 19:35:17.748   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1166823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:35:22.388   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1171463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:35:33.997  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:35:34.010  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:35:34.012  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:35:34.046  1510  2411 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 19:35:34.047  1510  2411 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 19:35:34.047  1510  2411 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:35:34.047  1510  2411 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:35:34.082  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 19:35:34.082  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 19:35:34.083  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-30 19:35:42.815   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1191890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:35:49.615   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1198690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:35:54.326  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:35:54.337  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:35:54.342  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:35:54.378  1510  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 19:35:54.378  1510  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 19:35:54.378  1510  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 19:35:54.379  1510  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:35:54.416  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 19:35:54.417  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 19:35:54.417  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-30 19:36:07.882   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1216956, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:36:10.008   871   883 I UsageStatsService: User[0] Flushing usage stats to disk
,08-30 19:36:14.681   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1223756, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:36:14.690  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:36:14.700  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:36:14.703  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 19:36:14.766  1510  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 19:36:14.767  1510  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 19:36:14.767  1510  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 19:36:14.767  1510  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 19:36:14.825  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 19:36:14.825  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 19:36:14.826  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-30 19:36:17.574  1510  2095 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 19:36:32.935   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1242010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:36:39.735   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1248810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:36:58.015   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1267090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:37:04.815   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1273890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:37:23.082   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1292157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:37:29.882   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1298957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:37:48.149   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1317224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:37:54.948   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1324023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:38:13.215   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1342290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:38:20.015   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1349090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:38:38.269   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1367344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:38:45.055   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1374130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:39:03.322   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1392397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:39:10.122   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1399197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:39:28.415   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1417490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:39:35.215   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1424290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:39:53.482   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1442557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:40:00.282   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1449357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:40:18.535   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1467610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:40:25.348   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1474423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:40:43.602   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1492677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 19:40:53.215   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1502290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 19:41:08.682   871  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1517757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,TIME-OUT KILL (timeout was 1400000ms),08-30 19:41:16.918  4353  4353 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 19:41:16.923  4353  4353 D AndroidRuntime: CheckJNI is OFF
08-30 19:41:16.965  4353  4353 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 19:41:17.012  4353  4353 I Radio-JNI: register_android_hardware_Radio DONE
08-30 19:41:17.034  4353  4353 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-30 19:41:17.047   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-30 19:41:17.047   871   884 I ActivityManager: Killing 3757:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-30 19:41:17.163   871  1381 I WindowState: WIN DEATH: Window{2835d79 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 19:41:17.164   871  1307 D WifiService: Client connection lost with reason: 4
08-30 19:41:17.164   871  2153 D GraphicsStats: Buffer count: 2
08-30 19:41:17.205   871   894 W PackageSettings: Skipping PackageSetting{f0bb6f9 com.example.hello/10273} due to missing metadata
08-30 19:41:17.234   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-30 19:41:17.234   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-30 19:41:17.235   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-30 19:41:17.235   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 19:41:17.235   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 19:41:17.235   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 19:41:17.235   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 19:41:17.235   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 19:41:17.235   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 19:41:17.235   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 19:41:17.235   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 19:41:17.235   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 19:41:17.235   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 19:41:17.235   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 19:41:17.235   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 19:41:17.235   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 19:41:17.235   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 19:41:17.235   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 19:41:17.235   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 19:41:17.235   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 19:41:17.235   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 19:41:17.235   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 19:41:17.235   871   884 I ActivityManager:   Force finishing activity ActivityRecord{e695b86 u0 com.test.thalitest/.MainActivity t2}
08-30 19:41:17.236   871   894 I art     : Starting a blocking GC Explicit
08-30 19:41:17.258   871   881 W ActivityManager: Spurious death for ProcessRecord{63e3cd6 0:com.test.thalitest/u0a0}, curProc for 3757: null
08-30 19:41:17.302   871   894 I art     : Explicit concurrent mark sweep GC freed 37069(3MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 1.088ms total 63.800ms
08-30 19:41:17.363   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-30 19:41:17.370  4353  4353 I art     : System.exit called, status: 0
08-30 19:41:17.370  4353  4353 I AndroidRuntime: VM exiting with result code 0.
08-30 19:41:17.385   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-30 19:41:17.409   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-30 19:41:17.416  4145  4145 D BluetoothMapAppObserver: onReceive
08-30 19:41:17.416  4145  4145 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-30 19:41:17.421  3597  3597 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-30 19:41:17.421  1873  1873 I Keyboard.Facilitator: resetDictionaries() : en_US
08-30 19:41:17.423  1888  2224 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 19:41:17.445  1873  4366 I Keyboard.Facilitator.DecoderInitializer: run()
08-30 19:41:17.449  1873  4366 I Decoder : createOrResetDecoder
08-30 19:41:17.452  1955  1955 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-30 19:41:17.459   871  2153 I ActivityManager: Start proc 4367:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-30 19:41:17.467   871  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 19:41:17.506  1510  1510 I ConfigService: onCreate
08-30 19:41:17.527  4367  4367 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 19:41:17.532  1510  4380 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 19:41:17.532  1510  4380 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-30 19:41:17.538   871  1684 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3757 uid 10000
08-30 19:41:17.539  1873  1873 I Keyboard.Facilitator: onFinishInput()
08-30 19:41:17.548  1510  4380 W SQLiteOpenHelper: Opened config.db in read-only mode
08-30 19:41:17.559  1873  4366 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-30 19:41:17.567   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 19:41:17.582  1964  2068 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-30 19:41:17.590  1873  4366 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-30 19:41:17.592  1873  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-30 19:41:17.592  1873  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-30 19:41:17.594   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-30 19:41:17.595   871   883 E PackageManager: Failed to write settings, restoring backup
08-30 19:41:17.595   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 19:41:17.595   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 19:41:17.595   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 19:41:17.595   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 19:41:17.595   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 19:41:17.595   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 19:41:17.595   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 19:41:17.595   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 19:41:17.596  1873  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-30 19:41:17.596  1873  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-30 19:41:17.599   871  1996 I ActivityManager: Start proc 4385:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-30 19:41:17.599  1873  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-30 19:41:17.599   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-30 19:41:17.599   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 19:41:17.599   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 19:41:17.599   871   884 E DropBoxManagerService: 	... 13 more
--------- beginning of crash
08-30 19:41:17.599  1964  2068 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 19:41:17.599  1964  2068 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1964
08-30 19:41:17.599  1964  2068 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 19:41:17.599  1964  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 19:41:17.599  1964  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 19:41:17.599  1964  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 19:41:17.599  1964  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 19:41:17.599  1964  2068 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 19:41:17.599  1964  2068 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 19:41:17.599  1964  2068 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 19:41:17.599  1964  2068 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 19:41:17.599  1964  2068 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 19:41:17.599  1964  2068 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 19:41:17.599  1964  2068 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 19:41:17.599  1873  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 19:41:17.601   871  2000 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 19:41:17.602   871  4390 E DropBoxManagerService: Can't write: system_app_crash
08-30 19:41:17.602   871  4390 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-30 19:41:17.602   871  4390 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 19:41:17.602   871  4390 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 19:41:17.602   871  4390 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 19:41:17.602   871  4390 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 19:41:17.602   871  4390 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 19:41:17.602   871  4390 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 19:41:17.602   871  4390 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 19:41:17.602   871  4390 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 19:41:17.602   871  4390 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 19:41:17.602   871  4390 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 19:41:17.602   871  4390 E DropBoxManagerService: 	... 5 more
08-30 19:41:17.606  1964  2068 I Process : Sending signal. PID: 1964 SIG: 9
08-30 19:41:17.613  4367  4367 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-30 19:41:17.615  1873  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-30 19:41:17.615  1873  4366 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 19:41:17.615  1873  4366 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-30 19:41:17.615  1873  4366 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-30 19:41:17.615  1873  4366 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 19:41:17.615  1873  4366 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-30 19:41:17.643   871  1981 I ActivityManager: Start proc 4399:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-30 19:41:17.668  4399  4399 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-30 19:41:17.677  4367  4411 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 19:41:17.705  4367  4411 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 19:41:17.705  4367  4411 E AndroidRuntime: Process: android.process.acore, PID: 4367
08-30 19:41:17.705  4367  4411 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 19:41:17.705  4367  4411 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 19:41:17.708   871  4416 E DropBoxManagerService: Can't write: system_app_crash
08-30 19:41:17.708   871  4416 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-30 19:41:17.708   871  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 19:41:17.708   871  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 19:41:17.708   871  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 19:41:17.708   871  4416 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 19:41:17.708   871  4416 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 19:41:17.708   871  4416 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 19:41:17.708   871  4416 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 19:41:17.708   871  4416 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 19:41:17.708   871  4416 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 19:41:17.708   871  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 19:41:17.708   871  4416 E DropBoxManagerService: 	... 5 more
08-30 19:41:17.711  1510  1510 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-30 19:41:17.712  1510  1510 D AndroidRuntime: Shutting down VM
08-30 19:41:17.713  1510  1510 E AndroidRuntime: FATAL EXCEPTION: main
08-30 19:41:17.713  1510  1510 E AndroidRuntime: Process: com.google.process.gapps, PID: 1510
08-30 19:41:17.713  1510  1510 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 19:41:17.713  1510  1510 E AndroidRuntime: 	... 8 more
08-30 19:41:17.715   871  4417 E DropBoxManagerService: Can't write: system_app_crash
08-30 19:41:17.715   871  4417 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-30 19:41:17.715   871  4417 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 19:41:17.715   871  4417 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 19:41:17.715   871  4417 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 19:41:17.715   871  4417 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 19:41:17.715   871  4417 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 19:41:17.715   871  4417 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 19:41:17.715   871  4417 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 19:41:17.715   871  4417 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 19:41:17.715   871  4417 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 19:41:17.715   871  4417 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 19:41:17.715   871  4417 E DropBoxManagerService: 	... 5 more
08-30 19:41:17.716  4367  4411 I Process : Sending signal. PID: 4367 SIG: 9
08-30 19:41:17.717  1510  1510 I Process : Sending signal. PID: 1510 SIG: 9
08-30 19:41:17.732   871  2129 D GraphicsStats: Buffer count: 1
08-30 19:41:17.732   871  2154 I WindowState: WIN DEATH: Window{78a09c4 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-30 19:41:17.743   871  1913 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1964) has died
08-30 19:41:17.744   871  1913 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-30 19:41:17.746   871  1913 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-30 19:41:17.765   871   884 I ActivityManager: Start proc 4419:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 19:41:17.767   279   279 E lowmemorykiller: Error writing /proc/4367/oom_score_adj; errno=22
08-30 19:41:17.775   871  1996 I ActivityManager: Killing 3650:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-30 19:41:17.813   871  1307 D WifiService: Client connection lost with reason: 4
08-30 19:41:17.838   871   882 I ActivityManager: Process com.google.process.gapps (pid 1510) has died
08-30 19:41:17.838   871   882 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-30 19:41:17.838   871   882 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-30 19:41:17.839   871   882 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
08-30 19:41:17.840   871  1913 I ActivityManager: Process android.process.acore (pid 4367) has died
08-30 19:41:17.841   871  1913 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30998ms
08-30 19:41:17.854   871  2129 I ActivityManager: Start proc 4432:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
08-30 19:41:17.874  1705  1705 W RocketImpressions: ClearcutLogger connection suspended: 1
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 19:41:17.881  4419  4419 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 19:41:17.882  4419  4419 D AndroidRuntime: Shutting down VM

```
