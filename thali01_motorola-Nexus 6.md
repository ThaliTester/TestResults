#### Test 79763830bc83054_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-25 10:46:23.625   873  1863 D NetlinkSocketObserver: NeighborEvent{elapsedMs=113117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-25 10:46:24.957  3833  3833 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-25 10:46:24.962  3833  3833 D AndroidRuntime: CheckJNI is OFF
08-25 10:46:25.005  3833  3833 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-25 10:46:25.056  3833  3833 I Radio-JNI: register_android_hardware_Radio DONE
08-25 10:46:25.078  3833  3833 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 10:46:25.082   873  2176 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 10:46:25.111  2021  3096 W SearchService: Abort, client detached.
08-25 10:46:25.119  2021  2349 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@ee52d81
08-25 10:46:25.119  2021  2021 I HotwordDetector: Closing mic
08-25 10:46:25.119  2021  2357 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-25 10:46:25.125  3833  3833 D AndroidRuntime: Shutting down VM
08-25 10:46:25.153   873  1382 I ActivityManager: Start proc 3842:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-25 10:46:25.182   377  2359 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-25 10:46:25.183   377  2359 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-25 10:46:25.187   377  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-25 10:46:25.189  2021  2352 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-25 10:46:25.189  2021  2356 I MicroRecognitionRnrImpl: Detection finished
08-25 10:46:25.230  3842  3842 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-25 10:46:25.269  3842  3842 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-25 10:46:25.283  3842  3842 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4773-4775)
08-25 10:46:25.283  3842  3842 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 10:46:25.298  3842  3842 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {39d33aa}
08-25 10:46:25.298  3842  3842 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 10:46:25.298  3842  3842 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 10:46:25.308  3842  3842 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-25 10:46:25.310  3842  3842 E SysUtils: ApplicationContext is null in ApplicationStatus
08-25 10:46:25.331  3842  3842 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-25 10:46:25.362  3842  3842 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 10:46:25.362  3842  3842 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 10:46:25.362  3842  3842 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 10:46:25.362  3842  3842 I Adreno  : Build Date                       : 10/20/15
08-25 10:46:25.362  3842  3842 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 10:46:25.362  3842  3842 I Adreno  : Local Branch                     : M14
08-25 10:46:25.362  3842  3842 I Adreno  : Remote Branch                    : 
08-25 10:46:25.362  3842  3842 I Adreno  : Remote Branch                    : 
08-25 10:46:25.362  3842  3842 I Adreno  : Reconstruct Branch               : 
,08-25 10:46:25.405   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d8173f0:true
,08-25 10:46:25.453  3842  3842 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-25 10:46:25.468  3842  3842 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-25 10:46:25.555  3842  3882 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-25 10:46:25.569  3842  3868 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-25 10:46:25.613  3842  3882 I OpenGLRenderer: Initialized EGL, version 1.4
,08-25 10:46:25.667   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +541ms
,08-25 10:46:25.668  1864  1864 I Keyboard.Facilitator: onFinishInput()
,08-25 10:46:25.736  3842  3842 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3842
,08-25 10:46:25.848  3842  3842 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 10:46:25.942   873   883 I ActivityManager: Killing 2976:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-25 10:46:25.985   873   883 I ActivityManager: Killing 3243:com.google.android.gm/u0a78 (adj 15): empty #18
,08-25 10:46:26.096  3842  3884 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1682048720
,08-25 10:46:26.101  3842  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 10:46:26.101  3842  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 10:46:26.101  3842  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 10:46:26.101  3842  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 10:46:26.101  3842  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-25 10:46:26.101  3842  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d6f330e added. We now have 1 listener(s)
08-25 10:46:26.103  3842  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-25 10:46:26.105  3842  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 10:46:26.105  3842  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:46:26.106  3842  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 10:46:26.108  3842  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 10:46:26.108  3842  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 10:46:26.108  3842  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 10:46:26.108  3842  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-25 10:46:26.108  3842  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 10:46:26.108  3842  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 10:46:26.108  3842  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 10:46:26.108  3842  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 10:46:26.108  3842  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 10:46:26.108  3842  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 10:46:26.108  3842  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 10:46:26.108  3842  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 10:46:26.108  3842  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 10:46:26.108  3842  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-25 10:46:26.108  3842  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df788c5 added. We now have 1 listener(s)
,08-25 10:46:26.109  3842  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:46:26.111   873  1306 D WifiService: New client listening to asynchronous messages
,08-25 10:46:26.113  3842  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 10:46:26.113  3842  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-25 10:46:26.113  3842  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2,
,08-25 10:46:26.113  3842  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-25 10:46:26.113  3842  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-25 10:46:26.116  3842  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:46:26.116  3842  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-25 10:46:26.122  3842  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-25 10:46:26.122  3842  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:26.122  3842  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-25 10:46:26.122  3842  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:26.122  3842  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:26.122  3842  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:26.122  3842  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:26.122  3842  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:26.122  3842  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:46:26.122  3842  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 10:46:26.122  3842  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 10:46:26.123  3842  3884 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 10:46:26.223  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:26.226  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:26.229  3842  3842 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 10:46:26.979  3842  3892 W jxcore-log: Initializing JXcore engine
,08-25 10:46:26.980  3842  3892 W jxcore-log: JXcore engine is ready
,08-25 10:46:27.017  3892  3892 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8989 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-25 10:46:27.017  3892  3892 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10202]" dev="sockfs" ino=10202 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-25 10:46:27.017  3892  3892 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-25 10:46:27.017  3892  3892 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27079]" dev="sockfs" ino=27079 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-25 10:46:27.028  3842  3892 W jxcore-log: Starting JXcore engine
,08-25 10:46:27.104  3842  3892 W jxcore-log: Platform android
08-25 10:46:27.104  3842  3892 W jxcore-log: 
,08-25 10:46:27.104  3842  3892 W jxcore-log: Process ARCH arm
08-25 10:46:27.104  3842  3892 W jxcore-log: 
,08-25 10:46:27.317  3842  3892 I jxcore-log: JXcore Cordova bridge is ready!
08-25 10:46:27.317  3842  3892 I jxcore-log: 
,08-25 10:46:27.317  3842  3892 W jxcore-log: JXcore engine is started
,08-25 10:46:27.327  3842  3884 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-25 10:46:27.330  3842  3842 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 10:46:32.349   873  1305 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-25 10:46:37.168  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 10:46:37.168  3842  3892 I jxcore-log: 
,08-25 10:46:37.170  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 10:46:37.170  3842  3892 I jxcore-log: 
,08-25 10:46:37.184  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:37.184  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:37.184  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:37.184  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:37.184  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:37.184  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:37.184  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:37.184  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 10:46:37.192  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 10:46:37.199  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 10:46:37.199  3842  3892 I jxcore-log: 
,08-25 10:46:37.206  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 10:46:37.206  3842  3892 I jxcore-log: 
,08-25 10:46:37.423  3065  3901 V KeepSync: Connecting to GoogleApiClient
08-25 10:46:37.423   873  1965 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-25 10:46:37.459  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 10:46:37.460  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 10:46:37.477  1505  2019 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-25 10:46:37.477  1505  2019 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-25 10:46:37.477  1505  2019 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 10:46:37.477  1505  2019 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 10:46:37.500  1714  3902 V BaseAuthAsyncOperation: access token request failed
,08-25 10:46:37.501  3065  3901 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-25 10:46:37.541  1505  2970 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-25 10:46:37.541  1505  2970 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-25 10:46:37.542  1505  2970 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 10:46:37.542  1505  2970 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 10:46:37.567  3065  3901 E KeepSync: IOException
08-25 10:46:37.567  3065  3901 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-25 10:46:37.567  3065  3901 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-25 10:46:37.567  3065  3901 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-25 10:46:37.567  3065  3901 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-25 10:46:37.567  3065  3901 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-25 10:46:37.567  3065  3901 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-25 10:46:37.567  3065  3901 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-25 10:46:37.567  3065  3901 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-25 10:46:37.567  3065  3901 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-25 10:46:37.567  3065  3901 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-25 10:46:37.567  3065  3901 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-25 10:46:37.567  3065  3901 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-25 10:46:37.567  3065  3901 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-25 10:46:37.567  3065  3901 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-25 10:46:37.567  3065  3901 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 10:46:37.567  3065  3901 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 10:46:37.567  3065  3901 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-25 10:46:37.567  3065  3901 E KeepSync: 	... 10 more
08-25 10:46:37.567  3065  3901 W KeepSync: Sync result 2
,08-25 10:46:37.578   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 126767, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-25 10:46:37.730  3842  3892 D executeNativeTests: Running unit tests
,08-25 10:46:37.788  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:46:37.788  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e added. We now have 2 listener(s)
,08-25 10:46:37.789  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 10:46:37.789  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 10:46:37.789  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 10:46:37.789  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 10:46:37.789  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f added. We now have 2 listener(s)
08-25 10:46:37.790  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:46:37.790  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 10:46:37.793  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:46:37.810  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:37.810  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:37.810  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:37.810  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:37.810  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:37.810  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:37.810  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:37.810  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 10:46:37.814  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 10:46:37.814  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:46:37.816  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 10:46:37.817  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 10:46:37.817  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 10:46:37.817  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:37.819  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:37.819  3842  3892 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-25 10:46:37.820  3842  3892 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 10:46:37.820  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 10:46:37.820  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 10:46:37.820  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 10:46:37.820  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:37.821  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 10:46:37.821  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:37.821  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:37.821  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:37.821  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:46:37.821  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-25 10:46:37.821  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e removed from the list
08-25 10:46:37.821  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:37.821  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f removed from the list
,08-25 10:46:37.821  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:37.822  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:37.822  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:37.822  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:37.823  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 10:46:37.823  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:37.823  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:37.824  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:37.825  3842  3892 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-25 10:46:37.825  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 10:46:37.826  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:37.826  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:37.826  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:37.826  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:37.826  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:37.826  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
,08-25 10:46:37.826  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:37.826  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:37.826  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:37.826  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:37.826  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:37.826  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:37.826  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:37.828  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 10:46:37.828  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 10:46:37.828  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:37.828  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:37.832  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 10:46:37.832  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 10:46:37.832  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 10:46:37.832  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 10:46:37.832  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 10:46:37.832  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 10:46:37.832  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 10:46:37.832  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 10:46:37.832  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 10:46:37.833  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 10:46:37.834  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 10:46:37.834  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:37.834  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:37.834  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:37.834  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:37.834  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:37.834  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:37.834  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
08-25 10:46:37.834  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:37.834  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:37.834  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:37.834  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:37.834  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:37.834  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:37.834  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:37.836  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:37.836  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:37.836  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:37.836  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:37.837  3842  3892 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 10:46:37.838  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:46:37.843  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:37.843  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:37.843  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:37.843  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:37.843  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:37.843  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:37.843  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:37.843  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:46:37.845  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:37.846  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:46:37.846  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:46:37.846  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 10:46:37.846  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 10:46:37.846  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:46:37.846  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 10:46:37.848  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:37.850  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:37.853  3842  3892 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 10:46:37.853  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 10:46:37.862  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 10:46:37.865  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 10:46:37.865  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 10:46:37.868  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-25 10:46:37.870  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-25 10:46:37.870  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 10:46:37.870  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 10:46:37.871  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 10:46:37.871  3842  3892 D BluetoothAdapter: STATE_ON
08-25 10:46:37.875  2693  2703 D BtGatt.GattService: registerClient() - UUID=2a313761-21da-4f0f-b8c3-df7724813b1c
08-25 10:46:37.876  2693  2720 D BtGatt.GattService: onClientRegistered() - UUID=2a313761-21da-4f0f-b8c3-df7724813b1c, clientIf=5
08-25 10:46:37.878  3842  3854 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 10:46:37.879  2693  2705 D BtGatt.GattService: start scan with filters
08-25 10:46:37.883  2693  2740 D BtGatt.ScanManager: handling starting scan
08-25 10:46:37.883  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 10:46:37.883  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 10:46:37.883  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 10:46:37.884  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-25 10:46:37.885  2693  2740 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
08-25 10:46:37.886  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 10:46:37.886  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 10:46:37.887  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 10:46:37.888  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-25 10:46:37.890  3842  3892 I io.jxcore.node.ConnectionHelper: start: OK
08-25 10:46:37.900  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:37.900  3842  3892 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 10:46:37.900  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:37.901  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 10:46:37.901  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:37.900  2693  2720 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 10:46:37.903  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 10:46:37.903  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 10:46:37.903  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 10:46:37.903  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 10:46:37.903  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:46:37.904  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 10:46:37.908  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 10:46:37.908  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 10:46:37.909  3842  3892 D BluetoothAdapter: STATE_ON
08-25 10:46:37.909  2693  2740 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 10:46:37.911  2693  2705 D BtGatt.GattService: stopScan() - queue size =1
,08-25 10:46:37.912  2693  2899 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 10:46:37.912  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 10:46:37.912  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 10:46:37.912  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 10:46:37.912  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 10:46:37.912  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 10:46:37.914  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 10:46:37.914  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 10:46:37.914  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 10:46:37.915  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 10:46:37.915  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:46:37.916  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:46:37.916  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 10:46:37.916  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 10:46:37.917  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 10:46:37.917  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:37.917  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:46:37.917  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
,08-25 10:46:37.917  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:37.917  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
,08-25 10:46:37.917  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:37.917  2693  2720 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-25 10:46:37.917  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:37.917  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:46:37.917  3842  3892 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 10:46:37.918  2693  2740 D BtGatt.ScanManager: Starting BLE batch scan
,08-25 10:46:37.918  2693  2740 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 10:46:37.918  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:46:37.923  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:37.923  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:37.923  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:37.923  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:37.923  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:37.923  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:37.923  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:37.923  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 10:46:37.926  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 10:46:37.926  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 10:46:37.926  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 10:46:37.926  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 10:46:37.926  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 10:46:37.927  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:46:37.927  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 10:46:37.928  2693  2720 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 10:46:37.928  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:46:37.930  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:37.931  3842  3892 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 10:46:37.931  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 10:46:37.932  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:37.932  2693  2720 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 10:46:37.933  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:46:37.936  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 10:46:37.937  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 10:46:37.937  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 10:46:37.939  2693  2720 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 10:46:37.939  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:46:37.939  2693  2740 D BtGatt.ScanManager: stopping BLe Batch
,08-25 10:46:37.940  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 10:46:37.940  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 10:46:37.940  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 10:46:37.941  3842  3892 D BluetoothAdapter: STATE_ON
08-25 10:46:37.942  2693  2705 D BtGatt.GattService: registerClient() - UUID=afdf7855-7903-46d8-ba1b-28f097f72217
08-25 10:46:37.943  2693  2720 D BtGatt.GattService: onClientRegistered() - UUID=afdf7855-7903-46d8-ba1b-28f097f72217, clientIf=5
08-25 10:46:37.943  3842  3854 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 10:46:37.943  2693  2885 D BtGatt.GattService: start scan with filters
08-25 10:46:37.944  2693  2720 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 10:46:37.944  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:46:37.945  2693  2740 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 10:46:37.946  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 10:46:37.946  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 10:46:37.946  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 10:46:37.946  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 10:46:37.949  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 10:46:37.950  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 10:46:37.950  2693  2720 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 10:46:37.950  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:46:37.950  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 10:46:37.951  2693  2740 D BtGatt.ScanManager: handling starting scan
,08-25 10:46:37.952  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 10:46:37.955  3842  3892 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 10:46:37.956  2693  2720 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 10:46:37.956  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:46:37.957  2693  2740 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 10:46:37.957  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:37.957  3842  3892 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 10:46:37.957  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:37.957  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 10:46:37.957  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:37.957  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 10:46:37.958  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 10:46:37.958  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 10:46:37.958  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 10:46:37.958  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 10:46:37.958  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 10:46:37.958  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 10:46:37.958  3842  3892 D BluetoothAdapter: STATE_ON
,08-25 10:46:37.959  2693  2705 D BtGatt.GattService: stopScan() - queue size =1
08-25 10:46:37.960  2693  2885 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 10:46:37.960  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:46:37.960  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 10:46:37.961  2693  2720 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 10:46:37.961  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:46:37.960  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 10:46:37.961  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 10:46:37.961  2693  2740 D BtGatt.ScanManager: Starting BLE batch scan
08-25 10:46:37.961  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 10:46:37.961  2693  2740 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 10:46:37.962  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 10:46:37.962  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 10:46:37.963  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 10:46:37.963  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 10:46:37.963  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:46:37.964  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:46:37.964  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:46:37.964  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 10:46:37.964  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:37.964  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:37.964  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:46:37.964  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
08-25 10:46:37.964  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:37.965  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:37.965  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:37.965  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:37.965  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:37.965  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:37.966  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:37.966  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:37.966  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:46:37.966  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
,08-25 10:46:37.967  3842  3892 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 10:46:37.969  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:46:37.969  2693  2720 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 10:46:37.969  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:46:37.972  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:37.972  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:37.972  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:37.972  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:37.972  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:37.972  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:37.972  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:37.972  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 10:46:37.973  2693  2720 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 10:46:37.973  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:46:37.974  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 10:46:37.974  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 10:46:37.977  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:37.977  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:46:37.977  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 10:46:37.977  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 10:46:37.977  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:46:37.977  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 10:46:37.978  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:37.979  2693  2720 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 10:46:37.979  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:46:37.979  2693  2740 D BtGatt.ScanManager: stopping BLe Batch
08-25 10:46:37.980  3842  3892 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 10:46:37.980  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 10:46:37.984  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 10:46:37.985  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 10:46:37.985  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 10:46:37.985  2693  2720 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 10:46:37.986  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:46:37.986  2693  2740 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 10:46:37.988  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 10:46:37.988  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 10:46:37.988  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 10:46:37.989  3842  3892 D BluetoothAdapter: STATE_ON
,08-25 10:46:37.989  2693  2720 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 10:46:37.990  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:46:37.991  2693  2705 D BtGatt.GattService: registerClient() - UUID=5fc2c934-da49-4609-b3e7-b7de8020746b
,08-25 10:46:37.992  2693  2720 D BtGatt.GattService: onClientRegistered() - UUID=5fc2c934-da49-4609-b3e7-b7de8020746b, clientIf=5
,08-25 10:46:37.992  3842  3852 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 10:46:37.993  2693  2885 D BtGatt.GattService: start scan with filters
,08-25 10:46:37.996  2693  2740 D BtGatt.ScanManager: handling starting scan
,08-25 10:46:37.996  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 10:46:37.996  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 10:46:37.996  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 10:46:37.996  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 10:46:37.998  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 10:46:37.999  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 10:46:37.999  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 10:46:38.000  2693  2720 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 10:46:38.000  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:46:38.000  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-25 10:46:38.000  2693  2740 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 10:46:38.002  3842  3892 I io.jxcore.node.ConnectionHelper: start: OK
08-25 10:46:38.005  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 10:46:38.005  3842  3892 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 10:46:38.005  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:38.005  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 10:46:38.005  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.005  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 10:46:38.005  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 10:46:38.005  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-25 10:46:38.005  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 10:46:38.005  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 10:46:38.005  2693  2720 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 10:46:38.005  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:46:38.005  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 10:46:38.005  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 10:46:38.006  2693  2740 D BtGatt.ScanManager: Starting BLE batch scan
08-25 10:46:38.006  2693  2740 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 10:46:38.006  3842  3892 D BluetoothAdapter: STATE_ON
08-25 10:46:38.006  2693  2885 D BtGatt.GattService: stopScan() - queue size =1
08-25 10:46:38.007  2693  2703 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 10:46:38.007  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:46:38.007  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 10:46:38.007  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 10:46:38.008  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 10:46:38.008  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 10:46:38.008  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 10:46:38.009  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 10:46:38.009  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 10:46:38.009  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 10:46:38.009  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:46:38.010  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:46:38.010  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:46:38.010  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 10:46:38.011  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 10:46:38.011  3842  3892 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 10:46:38.011  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:38.011  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:38.011  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:38.011  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:38.011  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:46:38.011  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
08-25 10:46:38.011  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:46:38.011  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.012  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:38.012  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:38.012  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.012  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.013  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 10:46:38.013  2693  2720 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 10:46:38.013  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:46:38.013  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:38.013  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:46:38.014  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.014  3842  3892 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 10:46:38.015  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 10:46:38.015  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:38.015  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:38.015  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 10:46:38.015  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:38.015  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.015  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
,08-25 10:46:38.015  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.015  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.015  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:38.015  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:38.015  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.015  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.015  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:38.016  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:38.016  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:38.016  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:46:38.016  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.017  2693  2720 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 10:46:38.017  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:46:38.017  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-25 10:46:38.017  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:38.018  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 10:46:38.018  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:38.018  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:38.018  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:38.018  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.018  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
,08-25 10:46:38.018  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:46:38.018  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.018  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:38.018  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:38.018  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.018  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.019  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:38.019  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:38.019  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:38.019  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.019  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.020  3842  3892 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-25 10:46:38.020  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:38.020  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 10:46:38.020  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 10:46:38.022  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:38.022  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.022  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-25 10:46:38.022  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
,08-25 10:46:38.022  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.022  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.022  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop,
,08-25 10:46:38.022  2693  2720 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 10:46:38.022  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:46:38.022  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.022  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.022  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:38.023  2693  2740 D BtGatt.ScanManager: stopping BLe Batch
08-25 10:46:38.023  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.023  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 10:46:38.023  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:38.023  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.023  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.024  3842  3892 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 10:46:38.024  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:38.024  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:38.024  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:38.025  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:38.025  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.025  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.025  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
08-25 10:46:38.025  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.025  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.025  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:38.025  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.025  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.025  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.025  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.026  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:38.026  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:38.026  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.026  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.027  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 10:46:38.027  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 10:46:38.027  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 10:46:38.027  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 10:46:38.027  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 10:46:38.027  3842,  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 10:46:38.027  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:38.027  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:38.027  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:38.027  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:38.028  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.028  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.028  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
08-25 10:46:38.028  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.028  2693  2720 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 10:46:38.028  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:46:38.028  2693  2740 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 10:46:38.028  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.028  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:38.028  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.028  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.029  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.029  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.030  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:38.030  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:38.030  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.030  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.030  3842  3892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 10:46:38.031  3842  3892 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 10:46:38.031  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 10:46:38.033  3842  3892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 10:46:38.033  2693  2720 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 10:46:38.033  2693  2720 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:46:38.033  3842  3892 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 10:46:38.033  3842  3892 D io.jxcore.node.C,onnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 10:46:38.033  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 10:46:38.033  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 10:46:38.033  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 10:46:38.033  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 10:46:38.033  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 10:46:38.033  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 10:46:38.033  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 10:46:38.033  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 10:46:38.033  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 10:46:38.033  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 10:46:38.034  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 10:46:38.035  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 10:46:38.035  3842  3892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 10:46:38.035  3842  3892 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 10:46:38.035  3842  3892 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 10:46:38.035  3842  3892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 10:46:38.035  3842  3892 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 10:46:38.035  3842  3892 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 10:46:38.035  3842  3892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 10:46:38.035  3842  3892 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 10:46:38.035  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 10:46:38.038  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 10:46:38.039  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 10:46:38.039  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 10:46:38.039  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 10:46:38.039  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 10:46:38.039  3842  3892 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 10:46:38.039  3842  3892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 10:46:38.040  3842  3892 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 10:46:38.040  3842  3903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
08-25 10:46:38.040  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:38.040  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:38.040  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:38.040  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:38.040  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.040  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.040  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 10:46:38.041  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
08-25 10:46:38.041  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.041  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.041  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:38.041  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.041  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.041  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.041  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.042  3842  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
08-25 10:46:38.042  3842  3903 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 10:46:38.043  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:38.043  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:38.043  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.043  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.044  3842  3892 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 10:46:38.044  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:38.044  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:38.044  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:38.044  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:38.044  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.044  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.045  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
08-25 10:46:38.045  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.045  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.045  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:38.045  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.045  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.045  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.045  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.046  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:38.046  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:38.046  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.046  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.046  3842  3892 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 10:46:38.047  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:38.047  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:38.047  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:38.047  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:38.047  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.047  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.047  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
08-25 10:46:38.047  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.047  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.047  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:38.047  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.047  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.047  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.047  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.048  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:38.048  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:38.048  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.048  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.049  3842  3892 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 10:46:38.049  3842  3892 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 10:46:38.049  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 10:46:38.049  3842  3892 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 10:46:38.049  3842  3892 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 10:46:38.049  3842  3892 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 10:46:38.049  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 10:46:38.049  3842  3892 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 10:46:38.049  3842  3892 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 10:46:38.049  3842  3892 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 10:46:38.049  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 10:46:38.049  3842  3892 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 10:46:38.049  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:38.049  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:38.049  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:38.050  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:38.050  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.050  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.050  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
08-25 10:46:38.050  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.050  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.050  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:38.050  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.050  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.050  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.050  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.051  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:38.051  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:38.051  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.051  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.051  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:38.051  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.051  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.051  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
08-25 10:46:38.051  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.051  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.052  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:38.052  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.052  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.052  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.052  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.052  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:38.052  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.052  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.052  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
08-25 10:46:38.052  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:38.052  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:38.052  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:38.052  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:38.052  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.052  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.052  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
08-25 10:46:38.052  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.053  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.053  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:38.053  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.053  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.053  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.053  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.054  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:38.054  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:38.054  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.054  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.055  3842  3892 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 10:46:38.055  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:46:38.056  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 10:46:38.056  3842  3892 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 10:46:38.056  3842  3892 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 10:46:38.057  3842  3842 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 10:46:38.057  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 10:46:38.057  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 10:46:38.057  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:38.057  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 10:46:38.057  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 10:46:38.057  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 10:46:38.057  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.057  3842  3892 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 10:46:38.057  3842  3905 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 10:46:38.057  3842  3842 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 10:46:38.057  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
08-25 10:46:38.057  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.058  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 10:46:38.058  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 10:46:38.058  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 10:46:38.058  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.058  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.059  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 10:46:38.059  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:46:38.059  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:46:38.059  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 10:46:38.059  3842  3905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-25 10:46:38.059  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.059  3842  3905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 10:46:38.059  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:38.059  3842  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 10:46:38.059  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:38.059  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:38.059  3842  3842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 10:46:38.059  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:38.059  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.059  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.059  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
08-25 10:46:38.060  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.060  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.060  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:38.060  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.060  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.060  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.060  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.061  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:38.061  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:38.061  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.061  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.062  3842  3892 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 10:46:38.062  3842  3892 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 10:46:38.062  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 10:46:38.062  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 10:46:38.062  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:38.062  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:38.062  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:38.063  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:38.063  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.063  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.063  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
08-25 10:46:38.063  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.063  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.063  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:38.063  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.063  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.063  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.063  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.064  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:38.064  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:38.064  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.064  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.067  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:38.067  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:38.067  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:38.067  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:38.067  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.067  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.067  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
08-25 10:46:38.067  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.067  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.067  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:38.067  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.067  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.067  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.067  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.068  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:38.068  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:38.068  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.068  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.069  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:38.069  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:38.069  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:38.069  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:38.069  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.069  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.069  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afa2a5e not in the list
08-25 10:46:38.069  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.069  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.069  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:38.069  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.069  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.069  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:38.069  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:38.070  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:38.070  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:38.070  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:38.071  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@820de3f not in the list
08-25 10:46:38.071  3842  3892 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 10:46:38.071  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 10:46:38.071  3842  3892 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 10:46:38.071  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 10:46:38.071  3842  3892 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 10:46:38.071  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 10:46:38.073  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 10:46:38.073  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 10:46:38.073  3842  3892 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 10:46:38.073  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 10:46:38.074  3842  3892 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 10:46:38.074  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 10:46:38.074  3842  3892 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 10:46:38.074  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 10:46:38.074  3842  3892 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 10:46:38.074  3842  3892 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 10:46:38.074  3842  3892 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 10:46:38.075  3842  3892 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 10:46:38.075  3842  3892 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 10:46:38.075  3842  3892 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 10:46:38.075  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:46:38.075  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a9a909 added. We now have 2 listener(s)
08-25 10:46:38.075  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:46:38.076  3842  3892 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 10:46:38.077   873  1690 D WifiService: setWifiEnabled: true pid=3842, uid=10000
08-25 10:46:38.077   873  1690 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 10:46:38.077  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:46:38.077  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cb3e70e added. We now have 3 listener(s)
08-25 10:46:38.078  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:46:38.081  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:46:38.081  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bd3d52f added. We now have 4 listener(s)
08-25 10:46:38.081  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:46:38.082  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:46:38.082  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@580473c added. We now have 5 listener(s)
08-25 10:46:38.082  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:46:38.084   873  2176 D WifiService: setWifiEnabled: false pid=3842, uid=10000
08-25 10:46:38.084   873  2176 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 10:46:38.087  2693  2716 D BluetoothAdapterState: Current state: ON, message: 23
08-25 10:46:38.087  2693  2716 D BluetoothAdapterProperties: Setting state to 13
08-25 10:46:38.087  2693  2716 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 10:46:38.088  2693  2716 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 10:46:38.088  2693  2716 I BluetoothAdapterState: Entering PendingCommandState
08-25 10:46:38.089  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:46:38.089  2693  2693 D BluetoothMapService: onReceive
08-25 10:46:38.089  2693  2693 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:38.089  2693  2693 D BluetoothMapService: STATE_TURNING_OFF
08-25 10:46:38.089  2693  2693 D BluetoothMapService: MAP Service closeService in
08-25 10:46:38.089  2693  2693 D BluetoothMapMasInstance0: MAP Service shutdown
08-25 10:46:38.089  2693  2693 D ObexServerSockets0: shutdown(block = true)
08-25 10:46:38.090  2693  2693 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 10:46:38.090  2693  2693 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 10:46:38.090  2693  2900 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-25 10:46:38.090  2693  2882 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-25 10:46:38.091  2693  2901 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-25 10:46:38.091  2693  2693 I BtOppRfcommListener: stopping Accept Thread
08-25 10:46:38.091  2693  3475 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 10:46:38.091  2693  3475 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 10:46:38.095  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:38.095  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:38.095  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:38.095  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:38.095  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:38.095  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:38.095  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:38.095  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:38.095  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:46:38.095  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:38.095  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:38.095  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:46:38.098  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:38.100  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:38.103  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:38.103  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:38.103  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:38.103  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:38.103  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:38.103  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:38.103  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:38.103  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:38.103  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:46:38.104  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:38.104  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:38.106  1451  1451 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 10:46:38.106  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:38.108   873  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 10:46:38.109   873  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-25 10:46:38.109   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 10:46:38.109   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 10:46:38.111   873   886 I ActivityManager: Start proc 3908:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-25 10:46:38.111  2693  2720 D BluetoothAdapterProperties: Scan Mode:20
08-25 10:46:38.112  2693  2716 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-25 10:46:38.118  2693  2693 D HeadsetService: Received stop request...Stopping profile...
,08-25 10:46:38.119   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 10:46:38.119   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 10:46:38.119  1360  2050 D BluetoothHeadset: Proxy object disconnected
08-25 10:46:38.120   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 10:46:38.120  1360  1360 D HeadsetProfile: Bluetooth service disconnected
08-25 10:46:38.120  1954  1971 D BluetoothHeadset: Proxy object disconnected
08-25 10:46:38.121   873  1878 D DhcpClient: Clearing IP address
,08-25 10:46:38.121   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-25 10:46:38.121  2693  2693 D A2dpService: Received stop request...Stopping profile...
08-25 10:46:38.121  2693  2891 D A2dpStateMachine: Exit Disconnected: -1
08-25 10:46:38.123   873   873 D BluetoothA2dp: Proxy object disconnected
08-25 10:46:38.123  1360  1360 D BluetoothA2dp: Proxy object disconnected
08-25 10:46:38.124  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:38.124  2693  2693 D HidService: Received stop request...Stopping profile...
08-25 10:46:38.124  2693  2693 D HidService: Stopping Bluetooth HidService
,08-25 10:46:38.124   373   871 D CommandListener: Setting iface cfg
,08-25 10:46:38.125  1360  1360 D BluetoothInputDevice: Proxy object disconnected
,08-25 10:46:38.125  1360  1360 D HidProfile: Bluetooth service disconnected
,08-25 10:46:38.125  2693  2693 D HealthService: Received stop request...Stopping profile...
,08-25 10:46:38.126  1505  2462 V NativeCrypto: Read error: ssl=0x9b420000: I/O error during system call, Connection timed out
08-25 10:46:38.126  2693  2693 D PanService: Received stop request...Stopping profile...
08-25 10:46:38.127  1505  2462 V NativeCrypto: SSL shutdown failed: ssl=0x9b420000: I/O error during system call, Broken pipe
08-25 10:46:38.128  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:38.129   873  1880 D DhcpClient: Receive thread stopped
,08-25 10:46:38.129  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 10:46:38.129  1360  1360 D PanProfile: Bluetooth service disconnected
,08-25 10:46:38.129  2693  2693 D BluetoothMapService: Received stop request...Stopping profile...
,08-25 10:46:38.129  2693  2693 D BluetoothMapService: stop()
,08-25 10:46:38.130   873   884 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-25 10:46:38.130   873  1860 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-25 10:46:38.131   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 10:46:38.132   873  1305 D WifiStateMachine: Start Disconnecting Watchdog 1
08-25 10:46:38.132   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-25 10:46:38.133   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 10:46:38.132   873  1860 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-25 10:46:38.134   401   401 E Parcel  : Reading a NULL string not supported here.
08-25 10:46:38.135   373   871 D CommandListener: Clearing all IP addresses on wlan0
08-25 10:46:38.131  2693  2693 D BluetoothMapAppObserver: deinitObservers()
08-25 10:46:38.137  2693  2693 D BluetoothMapAppObserver: removeReceiver()
08-25 10:46:38.139   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
08-25 10:46:38.140   873  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 10:46:38.142  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:38.142  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:38.142  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:38.142  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:38.142  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:38.142  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:38.142  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:38.142  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:38.142  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:46:38.143  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:38.143  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:46:38.144  1360  1360 D BluetoothMap: Proxy object disconnected
08-25 10:46:38.144  1360  1360 D MapProfile: Bluetooth service disconnected
08-25 10:46:38.144  2693  2693 V BluetoothAdapterState: isTurningOff()=true
08-25 10:46:38.144  2693  2693 V BluetoothAdapterState: isTurningOn()=false
08-25 10:46:38.144  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:38.144  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:38.145  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:38.145  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:38.145  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:38.145  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:38.145  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:38.1,45  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:38.145  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:38.145  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:38.145  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:46:38.145  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:38.146  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:46:38.146  2693  2693 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 10:46:38.146  2693  2693 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-25 10:46:38.146  2693  2693 V BluetoothAdapterState: isTurningOff()=true
08-25 10:46:38.146  2693  2693 V BluetoothAdapterState: isTurningOn()=false
08-25 10:46:38.146  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:38.146  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 10:46:38.147  2693  2860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 10:46:38.147  2693  2860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 10:46:38.147  2693  2860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 10:46:38.147  1887  2326 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:46:38.147  2693  2720 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-25 10:46:38.147  2693  2720 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-25 10:46:38.148  2693  2693 V BluetoothAdapterState: isTurningOff()=true
08-25 10:46:38.148  2693  2693 V BluetoothAdapterState: isTurningOn()=false
08-25 10:46:38.148  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:38.148  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:38.148  2693  2693 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 10:46:38.148  2693  2693 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 10:46:38.148  2693  2693 V BluetoothAdapterState: isTurningOff()=true
08-25 10:46:38.148  2693  2693 V BluetoothAdapterState: isTurningOn()=false
08-25 10:46:38.148  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:38.148  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:38.148   873  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 10:46:38.148  2693  2693 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 10:46:38.149  2693  2860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 10:46:38.149  2693  2860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 10:46:38.149  2693  2860 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 10:46:38.149  2693  2860 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:46:38.149  2693  2860 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 10:46:38.149  2693  2860 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:46:38.149  2693  2720 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 10:46:38.149  2693  2720 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 10:46:38.149  2693  2720 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-25 10:46:38.149  2693  2693 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 10:46:38.150  2693  2693 V BluetoothAdapterState: isTurningOff()=true
08-25 10:46:38.150  2693  2693 V BluetoothAdapterState: isTurningOn()=false
08-25 10:46:38.150  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:38.150  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:38.151  2693  2693 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 10:46:38.151  2693  2693 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 10:46:38.152  2693  2693 D BluetoothMapService: MAP Service closeService in
08-25 10:46:38.152  2693  2693 V BluetoothAdapterState: isTurningOff()=true
08-25 10:46:38.152  2693  2693 V BluetoothAdapterState: isTurningOn()=false
08-25 10:46:38.153  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:38.153  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:38.153  2693  2716 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-25 10:46:38.153  2693  2716 D BluetoothAdapterProperties: Setting state to 15
08-25 10:46:38.153  2693  2716 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 10:46:38.153  2693  2716 I BluetoothAdapterState: Entering BleOnState
08-25 10:46:38.153  2693  2693 D BluetoothMapService: clea,nup()
08-25 10:46:38.153  2693  2693 D BluetoothMapService: MAP Service closeService in
08-25 10:46:38.153  1360  1374 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 10:46:38.154  1360  2050 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:46:38.154   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:46:38.154  1954  2184 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:46:38.155   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 10:46:38.155   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:46:38.155  1360  1381 D BluetoothMap: onBluetoothStateChange: up=false
08-25 10:46:38.156  1360  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 10:46:38.156  1360  2050 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 10:46:38.157  1360  1381 D BluetoothPan: onBluetoothStateChange on: false
08-25 10:46:38.157   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:46:38.157  2693  2716 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-25 10:46:38.157  2693  2716 D BluetoothAdapterProperties: Setting state to 16
08-25 10:46:38.157  2693  2716 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-25 10:46:38.158  2693  2716 D BluetoothAdapterProperties: onBleDisable
08-25 10:46:38.158  2693  2716 I BluetoothAdapterState: Entering PendingCommandState
08-25 10:46:38.158  2693  2717 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-25 10:46:38.159  3842  3903 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
08-25 10:46:38.159  2693  2860 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-25 10:46:38.159  2693  2860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 10:46:38.160  2693  2720 D BluetoothAdapterProperties: Scan Mode:20
08-25 10:46:38.163  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:38.163  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:38.163  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:38.163  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:38.163  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:38.163  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:38.163  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:38.163  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:38.163  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:46:38.164  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:38.165  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:38.166  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:38.179   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 10:46:38.190  3908  3908 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-25 10:46:38.195   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 10:46:38.196   873  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-25 10:46:38.196   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 10:46:38.197   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-25 10:46:38.201  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:38.202  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:38.202  3420  3420 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@d6f330e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-25 10:46:38.203  2021  2021 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-25 10:46:38.209  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 10:46:38.216  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 10:46:38.219   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@72564a4:true
,08-25 10:46:38.232   873  2179 I ActivityManager: Start proc 3928:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-25 10:46:38.244   373   871 E Netd    : netlink response contains error (No such file or directory)
08-25 10:46:38.246   873  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 10:46:38.257  3908  3908 D LocalBluetoothProfileManager: Adding local MAP profile
,08-25 10:46:38.260  3908  3908 D BluetoothMap: Create BluetoothMap proxy object
,08-25 10:46:38.268  3908  3908 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-25 10:46:38.270  3928  3928 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-25 10:46:38.278  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,08-25 10:46:38.285   873  2178 I ActivityManager: Killing 2309:com.google.android.talk/u0a61 (adj 15): empty #17
,08-25 10:46:38.362  2693  2720 I bt_hci  : shut_down
,08-25 10:46:38.369  2693  2748 I bt_vendor: low_power_mode_cb
,08-25 10:46:38.373  2693  2748 D bt_hwcfg: hw_epilog_process
,08-25 10:46:38.396  2693  2748 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-25 10:46:38.396  2693  2748 I bt_vendor: epilog_cb
08-25 10:46:38.396  2693  2748 I bt_hci  : epilog_finished_callback
,08-25 10:46:38.401  3928  3928 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 10:46:38.401  3928  3928 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 10:46:38.401  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 10:46:38.402  3928  3928 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 10:46:38.402  3928  3928 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 10:46:38.402  2693  2720 I bt_hci_h4: hal_close
08-25 10:46:38.402  3928  3928 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.r.k.d(PG:583)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 10:46:38.402  3928  3928 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 10:46:38.402  2693  2720 I bt_userial_vendor: device fd = 51 close
08-25 10:46:38.402  3928  3928 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 10:46:38.402  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 10:46:38.405  3928  3928 D StrictMode: StrictMode policy violation; ~duration=53 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 10:46:38.405  3928  3928 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 10:46:38.405  3928  3928 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 10:46:38.421   873  1522 I ActivityManager: Start proc 3956:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-25 10:46:38.422   873  1522 I ActivityManager: Killing 3603:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-25 10:46:38.525  3956  3956 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-25 10:46:38.528  2693  2717 D bt_stack_manager: event_shut_down_stack finished.
,08-25 10:46:38.528  2693  2716 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 10:46:38.533  2693  2693 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 10:46:38.533  2693  2716 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-25 10:46:38.535  2693  2693 D BtGatt.GattService: Received stop request...Stopping profile...
,08-25 10:46:38.535  2693  2693 D BtGatt.GattService: stop()
,08-25 10:46:38.535  2693  2693 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 10:46:38.539  2693  2693 V BluetoothAdapterState: isTurningOff()=false
,08-25 10:46:38.539  2693  2693 V BluetoothAdapterState: isTurningOn()=false
08-25 10:46:38.539  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:38.539  2693  2693 V BluetoothAdapterState: isBleTurningOff()=true
08-25 10:46:38.540  2693  2716 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-25 10:46:38.541  2693  2716 D BluetoothAdapterProperties: Setting state to 10
08-25 10:46:38.541  2693  2716 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-25 10:46:38.543   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-25 10:46:38.543  2693  2716 I BluetoothAdapterState: Entering OffState
,08-25 10:46:38.559  3842  3842 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 10:46:38.568  2693  2693 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-25 10:46:38.568  2693  2693 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-25 10:46:38.568  2693  2717 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 10:46:38.569  2693  2717 D bt_stack_manager: event_clean_up_stack finished.
08-25 10:46:38.569  2693  2693 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 10:46:38.581  2693  2693 I art     : System.exit called, status: 0
,08-25 10:46:38.581  2693  2693 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 10:46:38.652   873  2113 I ActivityManager: Process com.android.bluetooth (pid 2693) has died
,08-25 10:46:38.743  3956  3977 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-25 10:46:38.743  3956  3977 I Babel_SMS: MmsConfig.loadMmsSettings
08-25 10:46:38.744  3956  3977 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-25 10:46:38.744  3956  3977 I Babel_SMS: MmsConfig.loadFromDatabase
,08-25 10:46:38.782  3956  3977 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-25 10:46:38.782  3956  3977 I Babel_SMS: MmsConfig.loadFromResources
,08-25 10:46:38.783  3956  3977 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-25 10:46:38.787  3956  3977 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-25 10:46:38.834  3956  3956 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 10:46:38.836  3956  3956 I Babel_Crash: startup - clean
,08-25 10:46:38.872  3956  3956 I Babel_telephony: TeleModule.launchCompleted
,08-25 10:46:38.886   873  1522 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-25 10:46:38.895  3956  3956 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-25 10:46:38.908  3956  3956 W Babel   : BAM#gBA: invalid account id: -1
,08-25 10:46:38.909  3956  3956 W Babel   : BAM#gBA: invalid account id: -1
08-25 10:46:38.909  3956  3956 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-25 10:46:38.913  3956  3983 I Babel   : deleted: false for 0
,08-25 10:46:38.923   873  1382 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-25 10:46:38.983   873  2178 I ActivityManager: Start proc 3986:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-25 10:46:39.038  3986  3986 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-25 10:46:39.074  3956  3956 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 10:46:39.125  3986  3986 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-25 10:46:39.154  3956  3956 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-25 10:46:39.161  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 10:46:39.167  3956  3956 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 10:46:39.183  3956  3956 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 10:46:39.202  3956  3956 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 10:46:39.207  3956  3956 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 10:46:39.209   873  2177 I ActivityManager: Start proc 4012:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-25 10:46:39.218  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,08-25 10:46:39.224  3956  3956 I vclib   : onServiceConnected
,08-25 10:46:39.231   873  2177 I ActivityManager: Killing 3420:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-25 10:46:39.261  3928  3950 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-25 10:46:39.283   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@48f09c:true
,08-25 10:46:39.387  4012  4012 D AdapterServiceConfig: Adding HeadsetService
,08-25 10:46:39.388  4012  4012 D AdapterServiceConfig: Adding A2dpService
,08-25 10:46:39.389  4012  4012 D AdapterServiceConfig: Adding HidService
,08-25 10:46:39.390  4012  4012 D AdapterServiceConfig: Adding HealthService
08-25 10:46:39.390  4012  4012 D AdapterServiceConfig: Adding PanService
08-25 10:46:39.390  4012  4012 D AdapterServiceConfig: Adding GattService
08-25 10:46:39.391  4012  4012 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 10:46:39.395   873   883 I ActivityManager: Killing 3489:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-25 10:46:39.435  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 10:46:39.449  1714  1714 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 10:46:39.453  1714  1714 D SystemUpdateService: onCreate
,08-25 10:46:39.456  1714  1714 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 10:46:39.467  1714  4024 I SystemUpdateService: active receiver: enabled
,08-25 10:46:39.495  1714  4024 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 10:46:39.497  1714  4024 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-25 10:46:39.497  1714  1714 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-25 10:46:39.498  1714  4024 I SystemUpdateService: now status is 0 (complete)
08-25 10:46:39.498  1714  4024 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 10:46:39.498  1714  4024 I SystemUpdateService: file has been verified
,08-25 10:46:39.498  1714  4024 I SystemUpdateService: OTA package size = 12249756
,08-25 10:46:39.501  1714  2438 I iu.UploadsManager: num queued entries: 0
08-25 10:46:39.501  1714  2438 I iu.UploadsManager: num updated entries: 0
,08-25 10:46:39.502  1714  2438 I iu.SyncManager: NEXT; no task
,08-25 10:46:39.505  1714  4024 I SystemUpdateService: showing system update notification
,08-25 10:46:39.520  1714  1714 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 10:46:39.522  1714  1714 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 10:46:39.522  1714  1714 D SystemUpdateService: onDestroy
,08-25 10:46:39.547   873  1522 I ActivityManager: Start proc 4026:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-25 10:46:39.581  4026  4026 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-25 10:46:39.584  4026  4026 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:39.594  4026  4026 D SprintDMHelper: simOperator: 
,08-25 10:46:39.594  4026  4026 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 10:46:39.612   873  1522 I ActivityManager: Start proc 4038:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-25 10:46:39.612   873  1522 I ActivityManager: Killing 3531:android.process.acore/u0a5 (adj 15): empty #17
,08-25 10:46:39.733   873  1965 I ActivityManager: Start proc 4053:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-25 10:46:39.738  3956  4052 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-25 10:46:39.743   873  1382 I ActivityManager: Killing 3695:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-25 10:46:39.838  4053  4053 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-25 10:46:39.902  4053  4053 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-25 10:46:39.902  4053  4053 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-25 10:46:39.902  4053  4053 I GAv4    :   adb logcat -s GAv4
,08-25 10:46:39.920  4053  4053 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-25 10:46:39.930  4053  4053 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-25 10:46:39.962  4053  4071 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-25 10:46:40.070  4053  4053 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-25 10:46:40.103  4053  4053 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-25 10:46:40.114  4053  4053 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 9600-9607)
,08-25 10:46:40.114  4053  4053 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 10:46:40.123  4053  4053 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a947bbe}
,08-25 10:46:40.124  4053  4053 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 10:46:40.124  4053  4053 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 10:46:40.133  4053  4053 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-25 10:46:40.134  4053  4053 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 10:46:40.154  4053  4053 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-25 10:46:40.167  4053  4053 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 10:46:40.167  4053  4053 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 10:46:40.167  4053  4053 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 10:46:40.167  4053  4053 I Adreno  : Build Date                       : 10/20/15
08-25 10:46:40.167  4053  4053 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 10:46:40.167  4053  4053 I Adreno  : Local Branch                     : M14
08-25 10:46:40.167  4053  4053 I Adreno  : Remote Branch                    : 
08-25 10:46:40.167  4053  4053 I Adreno  : Remote Branch                    : 
08-25 10:46:40.167  4053  4053 I Adreno  : Reconstruct Branch               : 
,08-25 10:46:40.234  4053  4053 I NSApplication: Starting up...
,08-25 10:46:40.241  4053  4099 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-25 10:46:40.279   873  1382 I ActivityManager: Start proc 4104:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-25 10:46:40.280   873  1382 I ActivityManager: Killing 3711:com.android.musicfx/u0a18 (adj 15): empty #17
,08-25 10:46:40.375  4104  4104 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-25 10:46:40.574   873  2113 I ActivityManager: Killing 2134:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-25 10:46:41.098   873  2177 D WifiService: setWifiEnabled: true pid=3842, uid=10000
08-25 10:46:41.099   873  2177 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 10:46:41.112   873  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-25 10:46:41.120  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 10:46:41.120  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:41.120  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:41.120  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:41.120  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:41.120  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:41.120  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:41.120  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:41.120  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:41.120  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:41.121  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:41.124  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 10:46:41.125  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:41.125  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:41.125  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:41.125  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:41.125  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:41.125  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:41.125  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:41.125  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:41.125  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:41.125  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:41.161   873  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-25 10:46:41.163   873  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-25 10:46:41.165   873  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-25 10:46:41.167   873  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 10:46:41.168   873  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-25 10:46:41.168   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-25 10:46:41.168   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 10:46:41.182   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-25 10:46:41.184   373   871 D CommandListener: Setting iface cfg
08-25 10:46:41.185   873  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-25 10:46:41.186   873  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 10:46:41.188   873  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-25 10:46:41.196   873  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 10:46:41.197   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 10:46:41.208   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 10:46:42.705   873  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=1.45 rxSuccessRate=1.94 delta 1000 -> 1000
,08-25 10:46:42.713   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-25 10:46:42.713   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 10:46:42.737   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 10:46:42.816   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 10:46:42.818  1451  1451 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 10:46:43.239  1451  1451 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 10:46:43.278  1451  1451 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 10:46:43.279  1451  1451 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 10:46:43.281   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 10:46:43.296   873  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 10:46:43.296   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 10:46:43.296   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 10:46:43.322   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 10:46:43.336   373   871 D CommandListener: Setting iface cfg
,08-25 10:46:43.337   873  1305 D WifiStateMachine: Start Dhcp Watchdog 2
,08-25 10:46:43.349   873  1307 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-25 10:46:43.350   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 10:46:43.400   873  4129 D DhcpClient: Receive thread started
,08-25 10:46:43.485   873  1305 E native  : do suspend false
,08-25 10:46:43.507   873  1878 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 10:46:43.522   873  4129 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172689, domain null
,08-25 10:46:43.523   873  1878 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172689 seconds
,08-25 10:46:43.527   873  1878 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 10:46:43.542   873  4129 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 10:46:43.543   873  1878 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-25 10:46:43.548   373   871 D CommandListener: Setting iface cfg
,08-25 10:46:43.557   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-25 10:46:43.558   873  1878 D DhcpClient: Scheduling renewal in 86399s
,08-25 10:46:43.572   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 10:46:43.575   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 10:46:43.575   873  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 10:46:43.576   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 10:46:43.579   873  1307 D ConnectivityService: Adding iface wlan0 to network 101
08-25 10:46:43.597   873  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 10:46:43.639   873  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-25 10:46:43.639   873  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-25 10:46:43.641   873  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-25 10:46:43.643   873  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-25 10:46:43.646   873  1307 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-25 10:46:43.660   873  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 10:46:43.669   873  1307 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-25 10:46:43.669   873  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-25 10:46:43.669   873  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-25 10:46:43.669   873  1307 D ConnectivityService:    accepting network in place of null
08-25 10:46:43.669   873  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-25 10:46:43.670   873  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-25 10:46:43.670   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 10:46:43.680   873  4128 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133173, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 10:46:43.709   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 10:46:43.739   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 10:46:43.744   873  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 10:46:43.744   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:43.746   873  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-25 10:46:43.747   873   890 D Tethering: MasterInitialState.processMessage what=3
08-25 10:46:43.751   873  4127 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:814::200e
,08-25 10:46:43.767  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:43.767  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:43.767  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:43.767  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:43.767  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:43.767  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:43.767  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:43.767  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:43.767  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:46:43.767  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:43.767  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:43.770  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:43.771  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:43.771  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:43.771  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:43.771  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:43.771  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:43.771  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:43.771  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:43.771  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:46:43.771  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:43.771  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 10:46:43.774  2021  2021 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-25 10:46:43.778  1714  1714 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 10:46:43.781  1714  1714 D SystemUpdateService: onCreate
,08-25 10:46:43.785  1714  1714 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 10:46:43.788  1714  4139 I SystemUpdateService: active receiver: enabled
,08-25 10:46:43.791  1714  4139 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 10:46:43.795  1714  4139 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-25 10:46:43.796  1714  4139 I SystemUpdateService: now status is 0 (complete)
08-25 10:46:43.796  1714  4139 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 10:46:43.796  1714  4139 I SystemUpdateService: file has been verified
,08-25 10:46:43.796  1714  4139 I SystemUpdateService: OTA package size = 12249756
,08-25 10:46:43.804  1714  4139 I SystemUpdateService: showing system update notification
,08-25 10:46:43.808  1714  1714 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 10:46:43.810  1714  2438 I iu.UploadsManager: num queued entries: 0
08-25 10:46:43.812  1714  2438 I iu.UploadsManager: num updated entries: 0
08-25 10:46:43.812  1714  2438 I iu.SyncManager: NEXT; no task
,08-25 10:46:43.815  1714  1714 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-25 10:46:43.816  1714  1714 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 10:46:43.818  1714  4143 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-25 10:46:43.818  1714  4143 W BaseAppContext: Using Auth Proxy for data requests.
,08-25 10:46:43.820  1714  4143 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,08-25 10:46:43.820  4026  4026 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:43.822  1714  1714 D SystemUpdateService: onDestroy
,08-25 10:46:43.826  4026  4026 D SprintDMHelper: simOperator: 
08-25 10:46:43.826  4026  4026 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 10:46:43.828  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 10:46:43.831  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 10:46:43.837   873  4127 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 08:46:43 GMT], X-Android-Received-Millis=[1472114803837], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472114803803]}
,08-25 10:46:43.838   873  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-25 10:46:43.838   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-25 10:46:43.839   873  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 10:46:43.840   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 10:46:43.864  1505  2287 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-25 10:46:43.864  1505  2287 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-25 10:46:43.866  1505  2287 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 10:46:43.867  1505  2287 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 10:46:43.888  1714  4143 E MDM     : [177] SitrepService.a: Error sending sitrep.
,08-25 10:46:43.969  3956  4146 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 10:46:44.105   873  1979 D WifiService: setWifiEnabled: false pid=3842, uid=10000
,08-25 10:46:44.106   873  1979 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 10:46:44.130  1451  1451 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 10:46:44.139   873  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-25 10:46:44.139   873  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-25 10:46:44.139   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 10:46:44.139   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 10:46:44.152   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-25 10:46:44.152   873  1878 D DhcpClient: Clearing IP address
,08-25 10:46:44.152  1714  1714 I GCM     : Message from null null
,08-25 10:46:44.155  1714  1714 E GCM     : Dropping message from null
,08-25 10:46:44.156   373   871 D CommandListener: Setting iface cfg
,08-25 10:46:44.164   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-25 10:46:44.164   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-25 10:46:44.167   873  1305 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-25 10:46:44.169   401   401 E Parcel  : Reading a NULL string not supported here.
08-25 10:46:44.169   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 10:46:44.171   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-25 10:46:44.172   873  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-25 10:46:44.172  1505  4152 V NativeCrypto: Read error: ssl=0x9a8be400: I/O error during system call, Connection timed out
08-25 10:46:44.174  1505  4152 V NativeCrypto: SSL shutdown failed: ssl=0x9a8be400: I/O error during system call, Broken pipe
08-25 10:46:44.177   873  4129 D DhcpClient: Receive thread stopped
,08-25 10:46:44.181   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 10:46:44.185   873  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-25 10:46:44.187  1887  2326 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 10:46:44.187  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 10:46:44.188  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:44.188  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:44.188  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:44.188  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:44.188  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:44.188  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:44.188  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:44.188  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:44.188  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 10:46:44.188  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:44.189  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 10:46:44.189  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:44.189  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:44.189  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:44.189  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:44.189  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:44.189  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:44.189  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:44.189  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:44.189  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 10:46:44.189  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:44.222   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 10:46:44.246   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-25 10:46:44.247   873  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 10:46:44.247   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:44.249   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-25 10:46:44.253  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:44.254  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:44.258  2021  2021 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-25 10:46:44.261  1714  1714 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 10:46:44.264  1714  1714 D SystemUpdateService: onCreate
,08-25 10:46:44.266  1714  1714 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 10:46:44.268  1714  4162 I SystemUpdateService: active receiver: enabled
,08-25 10:46:44.273  1714  4162 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 10:46:44.274  1714  1714 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-25 10:46:44.276  1714  4162 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-25 10:46:44.277  1714  4162 I SystemUpdateService: now status is 0 (complete)
,08-25 10:46:44.277  1714  4162 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-25 10:46:44.278  1714  4162 I SystemUpdateService: file has been verified
,08-25 10:46:44.279  1714  4162 I SystemUpdateService: OTA package size = 12249756
,08-25 10:46:44.281  1714  2438 I iu.UploadsManager: num queued entries: 0
08-25 10:46:44.281  1714  1714 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 10:46:44.282  1714  2438 I iu.UploadsManager: num updated entries: 0
,08-25 10:46:44.283  1714  1714 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 10:46:44.283  1714  2438 I iu.SyncManager: NEXT; no task
,08-25 10:46:44.289  1714  4162 I SystemUpdateService: showing system update notification
,08-25 10:46:44.292  4026  4026 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:44.296  4026  4026 D SprintDMHelper: simOperator: 
,08-25 10:46:44.296  4026  4026 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 10:46:44.303  1714  1714 D SystemUpdateService: onDestroy
,08-25 10:46:44.307  3956  4166 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-25 10:46:44.325   373   871 E Netd    : netlink response contains error (No such file or directory)
,08-25 10:46:44.326   873  1307 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-25 10:46:44.384   873  2178 I ActivityManager: Killing 3733:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-25 10:46:44.743   873  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-25 10:46:47.151   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c251945:true
,08-25 10:46:47.153  4012  4012 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 10:46:47.160  4012  4169 I BluetoothAdapterState: Entering OffState
,08-25 10:46:47.160  4012  4012 I bt_bluedroid: init
,08-25 10:46:47.166  4012  4170 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-25 10:46:47.167  4012  4170 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-25 10:46:47.167  4012  4170 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-25 10:46:47.168  4012  4170 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 10:46:47.169  4012  4012 I bt_bluedroid: get_profile_interface socket
,08-25 10:46:47.172  4012  4012 I bt_bluedroid: get_profile_interface sdp
,08-25 10:46:47.176  4012  4023 I bt_bluedroid: config_hci_snoop_log
,08-25 10:46:47.177  4012  4173 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-25 10:46:47.178   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.,
,08-25 10:46:47.180  4012  4173 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 10:46:47.184  4012  4169 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 10:46:47.184  4012  4169 D BluetoothAdapterProperties: Setting state to 14
08-25 10:46:47.184  4012  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-25 10:46:47.188  4012  4169 D BluetoothBondStateMachine: make
,08-25 10:46:47.191  4012  4174 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 10:46:47.199  4012  4012 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 10:46:47.201  4012  4169 I BluetoothAdapterState: Entering PendingCommandState
,08-25 10:46:47.206  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
,08-25 10:46:47.208  4012  4012 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 10:46:47.208  4012  4012 D BtGatt.GattService: Received start request. Starting profile...
,08-25 10:46:47.209  4012  4012 D BtGatt.GattService: start()
,08-25 10:46:47.209  4012  4012 I bt_bluedroid: get_profile_interface gatt
,08-25 10:46:47.210  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
,08-25 10:46:47.210  4012  4012 D BtGatt.AdvertiseManager: advertise manager created
,08-25 10:46:47.221  4012  4012 V BluetoothAdapterState: isTurningOff()=false
,08-25 10:46:47.221  4012  4012 V BluetoothAdapterState: isTurningOn()=false
,08-25 10:46:47.221  4012  4012 V BluetoothAdapterState: isBleTurningOn()=true
08-25 10:46:47.221  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:47.222  4012  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-25 10:46:47.222  4012  4169 I bt_bluedroid: enable
,08-25 10:46:47.222  4012  4170 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-25 10:46:47.223  4012  4170 I bt_hci  : start_up
,08-25 10:46:47.230  4012  4170 I bt_vendor: alloc value 0xb39e9189
08-25 10:46:47.230  4012  4170 I bt_vendor: init
,08-25 10:46:47.230  4012  4170 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-25 10:46:47.231  4012  4170 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 10:46:47.339  4012  4170 D bt_hci  : start_up starting async portion
,08-25 10:46:47.339  4012  4177 I bt_hci  : event_finish_startup
08-25 10:46:47.339  4012  4177 I bt_hci_h4: hal_open
,08-25 10:46:47.340  4012  4177 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 10:46:47.346  4012  4177 I bt_userial_vendor: device fd = 51 open
,08-25 10:46:47.381  4012  4177 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 10:46:47.413  4012  4177 D bt_hwcfg: Chipset BCM4354A2
,08-25 10:46:47.413  4012  4177 D bt_hwcfg: Target name = [BCM4354A2]
,08-25 10:46:47.414  4012  4177 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 10:46:48.076  4012  4177 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 10:46:48.077  4012  4177 D bt_hwcfg: Settlement delay -- 100 ms
,08-25 10:46:48.077  4012  4177 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 10:46:48.194  4012  4177 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 10:46:48.195  4012  4177 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 10:46:48.225  4012  4177 I bt_hwcfg: vendor lib fwcfg completed
,08-25 10:46:48.226  4012  4177 I bt_vendor: firmware callback
08-25 10:46:48.226  4012  4177 I bt_hci  : firmware_config_callback
,08-25 10:46:48.238  4012  4179 I bt_btu  : btu_task pending for preload complete event
,08-25 10:46:48.238  4012  4179 I bt_btu_task: Bluetooth chip preload is complete
08-25 10:46:48.238  4012  4179 I bt_btu  : btu_task received preload complete event
,08-25 10:46:48.248  4012  4179 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 10:46:48.248  4012  4179 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 10:46:48.248  4012  4179 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-25 10:46:48.249  4012  4179 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 10:46:48.249  4012  4179 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 10:46:48.249  4012  4179 I         : BTE_InitTraceLevels -- TRC_A2D
,08-25 10:46:48.250  4012  4179 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 10:46:48.250  4012  4179 I         : BTE_InitTraceLevels -- TRC_BTM
,08-25 10:46:48.250  4012  4179 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 10:46:48.251  4012  4179 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 10:46:48.251  4012  4179 I         : BTE_InitTraceLevels -- TRC_SDP
,08-25 10:46:48.251  4012  4179 I         : BTE_InitTraceLevels -- TRC_GATT
,08-25 10:46:48.251  4012  4179 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 10:46:48.252  4012  4179 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 10:46:48.252  4012  4179 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 10:46:48.385  4012  4179 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3966d9d
,08-25 10:46:48.385  4012  4179 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3966d9d 
,08-25 10:46:48.396  4012  4173 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 10:46:48.397  4012  4173 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 10:46:48.398  4012  4173 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 10:46:48.402  4012  4173 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 10:46:48.405  4012  4173 D BluetoothAdapterProperties: Scan Mode:20
,08-25 10:46:48.408  4012  4173 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 10:46:48.411  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:48.413  4012  4173 D bt_hci  : do_postload posting postload work item
,08-25 10:46:48.413  4012  4177 I bt_hci  : event_postload
,08-25 10:46:48.413  4012  4177 I bt_vendor: sco_config_cb
08-25 10:46:48.414  4012  4177 I bt_hci  : sco_config_callback postload finished.
08-25 10:46:48.415  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:48.422  4012  4173 D bt_bte_conf: Device ID record 1 : primary
,08-25 10:46:48.422  4012  4173 D bt_bte_conf:   vendorId            = 000f
,08-25 10:46:48.422  4012  4177 I bt_vendor: low_power_mode_cb
08-25 10:46:48.422  4012  4173 D bt_bte_conf:   vendorIdSource      = 0001
08-25 10:46:48.422  4012  4173 D bt_bte_conf:   product             = 1200
08-25 10:46:48.423  4012  4173 D bt_bte_conf:   version             = 1436
08-25 10:46:48.423  4012  4173 D bt_bte_conf:   clientExecutableURL = 
08-25 10:46:48.423  4012  4173 D bt_bte_conf:   serviceDescription  = 
08-25 10:46:48.423  4012  4173 D bt_bte_conf:   documentationURL    = 
,08-25 10:46:48.424  4012  4173 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 10:46:48.425  4012  4170 D bt_stack_manager: event_start_up_stack finished
,08-25 10:46:48.428  4012  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-25 10:46:48.428  4012  4169 D BluetoothAdapterProperties: Setting state to 15
,08-25 10:46:48.428  4012  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-25 10:46:48.429  4012  4169 I BluetoothAdapterState: Entering BleOnState
,08-25 10:46:48.445  4012  4169 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-25 10:46:48.446  4012  4169 D BluetoothAdapterProperties: Setting state to 11
08-25 10:46:48.446  4012  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-25 10:46:48.453  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
,08-25 10:46:48.455  4012  4012 D HeadsetService: Received start request. Starting profile...
,08-25 10:46:48.458  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:48.459  4012  4012 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-25 10:46:48.460  4012  4012 D HeadsetStateMachine: make
,08-25 10:46:48.462  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:48.475  4012  4169 I BluetoothAdapterState: Entering PendingCommandState
,08-25 10:46:48.482  4012  4012 D HeadsetStateMachine: max_hf_connections = 1
,08-25 10:46:48.482  4012  4012 I bt_bluedroid: get_profile_interface handsfree
,08-25 10:46:48.482  4012  4173 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-25 10:46:48.482  4012  4173 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-25 10:46:48.490  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
,08-25 10:46:48.491  4012  4012 D A2dpService: Received start request. Starting profile...,
,08-25 10:46:48.492  4012  4012 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-25 10:46:48.492  4012  4012 I bt_bluedroid: get_profile_interface avrcp
,08-25 10:46:48.501  4012  4012 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 10:46:48.502  4012  4012 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-25 10:46:48.502  4012  4012 D A2dpStateMachine: make
08-25 10:46:48.504  4012  4012 I bt_bluedroid: get_profile_interface a2dp
08-25 10:46:48.505  4012  4173 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 10:46:48.508  4012  4188 D A2dpStateMachine: Enter Disconnected: -2
,08-25 10:46:48.511  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 10:46:48.512  4012  4012 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 10:46:48.513  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
,08-25 10:46:48.516  4012  4012 D HidService: Received start request. Starting profile...
,08-25 10:46:48.516  4012  4012 I bt_bluedroid: get_profile_interface hidhost
08-25 10:46:48.516  4012  4173 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39483e5
08-25 10:46:48.516  4012  4012 D HidService: setHidService(): set to: null
08-25 10:46:48.516  4012  4173 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-25 10:46:48.517  4012  4012 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 10:46:48.517  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
,08-25 10:46:48.518  4012  4012 D HealthService: Received start request. Starting profile...
,08-25 10:46:48.520  4012  4012 I bt_bluedroid: get_profile_interface health
08-25 10:46:48.520  4012  4012 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 10:46:48.521  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
,08-25 10:46:48.518  3908  3908 D BluetoothInputDevice: Proxy object connected
,08-25 10:46:48.526  4012  4012 D PanService: Received start request. Starting profile...
08-25 10:46:48.526  4012  4012 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 10:46:48.526  4012  4012 I bt_bluedroid: get_profile_interface pan
08-25 10:46:48.527  4012  4173 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 10:46:48.533  3908  3908 D HidProfile: Bluetooth service connected
,08-25 10:46:48.534  3908  3908 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 10:46:48.535  3908  3908 D PanProfile: Bluetooth service connected
,08-25 10:46:48.535  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
,08-25 10:46:48.537  4012  4012 D BluetoothMapService: Received start request. Starting profile...
08-25 10:46:48.537  3908  3908 D BluetoothMap: Proxy object connected
,08-25 10:46:48.537  4012  4012 D BluetoothMapService: start()
08-25 10:46:48.538  3908  3908 D MapProfile: Bluetooth service connected
,08-25 10:46:48.538  3908  3908 D BluetoothMap: getConnectedDevices()
,08-25 10:46:48.538   873   882 I art     : Background partial concurrent mark sweep GC freed 64994(4MB) AllocSpace objects, 16(500KB) LOS objects, 33% free, 29MB/43MB, paused 2.179ms total 106.293ms
,08-25 10:46:48.541  3908  3908 D BluetoothMap: Bluetooth is Not enabled
,08-25 10:46:48.541  4012  4012 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-25 10:46:48.542  4012  4012 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-25 10:46:48.542  4012  4012 D BluetoothMapAppObserver: createReceiver()
,08-25 10:46:48.544  4012  4012 D BluetoothMapAppObserver: initObservers()
08-25 10:46:48.544  4012  4012 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 10:46:48.553  4012  4186 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-25 10:46:48.554  4012  4012 V BluetoothAdapterState: isTurningOff()=false
,08-25 10:46:48.554  4012  4012 V BluetoothAdapterState: isTurningOn()=true
,08-25 10:46:48.554  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:48.554  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:48.555  4012  4012 V BluetoothAdapterState: isTurningOff()=false
08-25 10:46:48.555  4012  4012 V BluetoothAdapterState: isTurningOn()=true
08-25 10:46:48.556  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 10:46:48.556  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:48.557  4012  4012 V BluetoothAdapterState: isTurningOff()=false
08-25 10:46:48.557  4012  4012 V BluetoothAdapterState: isTurningOn()=true
08-25 10:46:48.557  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:48.557  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:48.557  4012  4012 V BluetoothAdapterState: isTurningOff()=false
08-25 10:46:48.557  4012  4012 V BluetoothAdapterState: isTurningOn()=true
,08-25 10:46:48.557  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:48.558  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:48.558  4012  4012 V BluetoothAdapterState: isTurningOff()=false
08-25 10:46:48.558  4012  4012 V BluetoothAdapterState: isTurningOn()=true
08-25 10:46:48.558  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:48.558  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:48.558  4012  4012 V BluetoothAdapterState: isTurningOff()=false
08-25 10:46:48.558  4012  4012 V BluetoothAdapterState: isTurningOn()=true
08-25 10:46:48.558  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:48.558  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 10:46:48.559  4012  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 10:46:48.559  4012  4169 D BluetoothAdapterProperties: ScanMode =  20
,08-25 10:46:48.559  4012  4169 D BluetoothAdapterProperties: State =  11
08-25 10:46:48.560  4012  4173 D BluetoothAdapterProperties: Scan Mode:21
08-25 10:46:48.561  4012  4169 D BluetoothAdapterProperties: Setting state to 12
08-25 10:46:48.561  4012  4173 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 10:46:48.561  4012  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 10:46:48.562  4012  4169 I BluetoothAdapterState: Entering OnState
,08-25 10:46:48.562  3908  3920 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 10:46:48.562  3908  3918 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 10:46:48.564  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:48.564  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:48.564  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:48.564  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:48.564  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:48.564  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:48.564  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:48.564  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:48.565  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:48.566  1360  1381 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 10:46:48.568  1360  2050 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 10:46:48.568   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 10:46:48.568  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:48.568  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:48.568  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:48.568  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:48.568  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:48.568  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:48.568  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:48.568  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:46:48.568  1954  2184 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 10:46:48.569  3908  3920 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 10:46:48.569   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 10:46:48.570  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:46:48.570  3908  3918 D BluetoothPan: onBluetoothStateChange on: true
,08-25 10:46:48.570   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 10:46:48.570   873   873 D BluetoothA2dp: Proxy object connected
08-25 10:46:48.570  1360  1374 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 10:46:48.572  1360  1360 D BluetoothMap: Proxy object connected
,08-25 10:46:48.572  1360  1360 D MapProfile: Bluetooth service connected
,08-25 10:46:48.572  1360  1360 D BluetoothMap: getConnectedDevices()
08-25 10:46:48.572  1360  1374 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 10:46:48.573  4012  4012 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 10:46:48.573  1360  1360 D BluetoothA2dp: Proxy object connected
08-25 10:46:48.573  4012  4012 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-25 10:46:48.573  1360  1381 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 10:46:48.574  4012  4012 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 10:46:48.574  1360  1360 D BluetoothInputDevice: Proxy object connected
,08-25 10:46:48.574  1360  1360 D HidProfile: Bluetooth service connected
08-25 10:46:48.575  1360  1374 D BluetoothPan: onBluetoothStateChange on: true
08-25 10:46:48.576  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 10:46:48.576  1360  1360 D PanProfile: Bluetooth service connected
08-25 10:46:48.576  4012  4012 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 10:46:48.576   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 10:46:48.577   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 10:46:48.578  4012  4012 D ObexServerSockets: Succeed to create listening sockets 
08-25 10:46:48.578  4012  4012 D ObexServerSockets0: startAccept()
08-25 10:46:48.578  4012  4012 D ObexServerSockets0: prepareForNewConnect()
,08-25 10:46:48.580  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:48.580  4012  4012 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-25 10:46:48.580  4012  4012 D BluetoothSdpJni: SDP Create record success - handle: 0
08-25 10:46:48.581  4012  4012 D BluetoothMapService: onReceive
08-25 10:46:48.581  4012  4012 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:48.581  4012  4012 D BluetoothMapService: STATE_ON
08-25 10:46:48.582  4012  4195 D ObexServerSockets0: Accepting socket connection...
08-25 10:46:48.582  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:48.582  3908  3908 D LocalBluetoothProfileManager: Adding local A2DP profile
08-25 10:46:48.583  4012  4197 D ObexServerSockets0: Accepting socket connection...
,08-25 10:46:48.585  3908  3908 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-25 10:46:48.591  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 10:46:48.593  3908  3908 D BluetoothA2dp: Proxy object connected
,08-25 10:46:48.597  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 10:46:48.599  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,08-25 10:46:48.604  3908  3908 D BluetoothPbap: Proxy object connected
,08-25 10:46:48.605  3908  3908 D PbapServerProfile: Bluetooth service connected
,08-25 10:46:48.609  1360  1360 D BluetoothPbap: Proxy object connected
,08-25 10:46:48.609  1360  1360 D PbapServerProfile: Bluetooth service connected
,08-25 10:46:48.610  4012  4012 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 10:46:48.610  4012  4012 D ObexServerSockets0: prepareForNewConnect()
,08-25 10:46:48.620  4012  4201 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 10:46:48.633  4012  4205 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 10:46:48.634  4012  4205 I BtOppRfcommListener: Accept thread started.
,08-25 10:46:48.672   873   873 D BluetoothHeadset: Proxy object connected
,08-25 10:46:48.672   873   873 D BluetoothHeadset: Proxy object connected
,08-25 10:46:48.673  1360  2050 D BluetoothHeadset: Proxy object connected
,08-25 10:46:48.673  1360  1360 D HeadsetProfile: Bluetooth service connected
,08-25 10:46:48.674   873   873 D BluetoothHeadset: Proxy object connected
08-25 10:46:48.674  1954  1980 D BluetoothHeadset: Proxy object connected
08-25 10:46:48.676   873   890 D BluetoothHeadset: Proxy object connected
,08-25 10:46:48.688  3908  3920 D BluetoothHeadset: Proxy object connected
08-25 10:46:48.691  3908  3908 D HeadsetProfile: Bluetooth service connected
,08-25 10:46:50.124  4012  4169 D BluetoothAdapterState: Current state: ON, message: 23
,08-25 10:46:50.125  4012  4169 D BluetoothAdapterProperties: Setting state to 13
,08-25 10:46:50.125  4012  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-25 10:46:50.131  4012  4169 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 10:46:50.136  4012  4169 I BluetoothAdapterState: Entering PendingCommandState
,08-25 10:46:50.142  4012  4012 D BluetoothMapService: onReceive
08-25 10:46:50.143  4012  4012 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:50.143  4012  4012 D BluetoothMapService: STATE_TURNING_OFF
,08-25 10:46:50.144  4012  4012 D BluetoothMapService: MAP Service closeService in
08-25 10:46:50.144  4012  4012 D BluetoothMapMasInstance0: MAP Service shutdown
,08-25 10:46:50.145  4012  4012 D ObexServerSockets0: shutdown(block = true)
08-25 10:46:50.146  4012  4195 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-25 10:46:50.147  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:50.148  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:50.148  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:50.148  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:50.148  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:50.148  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:50.148  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:50.148  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:50.148  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:50.149  4012  4012 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 10:46:50.150  4012  4197 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-25 10:46:50.150  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:50.151  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:50.153  4012  4173 D BluetoothAdapterProperties: Scan Mode:20
08-25 10:46:50.154  4012  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-25 10:46:50.160  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 10:46:50.161  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:50.161  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:50.161  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:50.161  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:50.161  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:50.161  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:50.161  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:50.161  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:46:50.162  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 10:46:50.163  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 10:46:50.163  4012  4182 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-25 10:46:50.163  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:50.164  4012  4012 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 10:46:50.165  4012  4012 I BtOppRfcommListener: stopping Accept Thread
08-25 10:46:50.165  4012  4205 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 10:46:50.166  4012  4205 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 10:46:50.167  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:50.169  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:50.173  4012  4012 D HeadsetService: Received stop request...Stopping profile...
,08-25 10:46:50.175   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 10:46:50.175   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 10:46:50.176  1360  1381 D BluetoothHeadset: Proxy object disconnected
08-25 10:46:50.176   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 10:46:50.176  3908  3918 D BluetoothHeadset: Proxy object disconnected
08-25 10:46:50.176  4012  4012 D A2dpService: Received stop request...Stopping profile...
,08-25 10:46:50.177  1954  1971 D BluetoothHeadset: Proxy object disconnected
08-25 10:46:50.177  1360  1360 D HeadsetProfile: Bluetooth service disconnected
08-25 10:46:50.177  4012  4188 D A2dpStateMachine: Exit Disconnected: -1
,08-25 10:46:50.181   873   873 D BluetoothA2dp: Proxy object disconnected
,08-25 10:46:50.182  1360  1360 D BluetoothA2dp: Proxy object disconnected
,08-25 10:46:50.183  4012  4012 D HidService: Received stop request...Stopping profile...
,08-25 10:46:50.183  4012  4012 D HidService: Stopping Bluetooth HidService
,08-25 10:46:50.185  1360  1360 D BluetoothInputDevice: Proxy object disconnected
08-25 10:46:50.185  1360  1360 D HidProfile: Bluetooth service disconnected
,08-25 10:46:50.187  4012  4012 D HealthService: Received stop request...Stopping profile...
,08-25 10:46:50.190  4012  4012 D PanService: Received stop request...Stopping profile...
,08-25 10:46:50.195  3908  3908 D DockEventReceiver: finishStartingService: stopping service
08-25 10:46:50.195  4012  4012 V BluetoothAdapterState: isTurningOff()=true
,08-25 10:46:50.195  4012  4012 V BluetoothAdapterState: isTurningOn()=false
08-25 10:46:50.195  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:50.195  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:50.195  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 10:46:50.196  4012  4012 D BluetoothMapService: Received stop request...Stopping profile...
08-25 10:46:50.196  1360  1360 D PanProfile: Bluetooth service disconnected
,08-25 10:46:50.196  4012  4012 D BluetoothMapService: stop()
08-25 10:46:50.196  4012  4012 D BluetoothMapAppObserver: deinitObservers()
08-25 10:46:50.196  4012  4012 D BluetoothMapAppObserver: removeReceiver()
08-25 10:46:50.196  3908  3908 D HeadsetProfile: Bluetooth service disconnected
08-25 10:46:50.197  3908  3908 D BluetoothA2dp: Proxy object disconnected
08-25 10:46:50.197  3908  3908 D BluetoothInputDevice: Proxy object disconnected
,08-25 10:46:50.197  3908  3908 D HidProfile: Bluetooth service disconnected
08-25 10:46:50.197  3908  3908 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 10:46:50.197  3908  3908 D PanProfile: Bluetooth service disconnected
,08-25 10:46:50.202  3908  3908 D BluetoothMap: Proxy object disconnected
,08-25 10:46:50.202  3908  3908 D MapProfile: Bluetooth service disconnected
08-25 10:46:50.203  4012  4012 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 10:46:50.204  4012  4179 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 10:46:50.204  4012  4179 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 10:46:50.204  4012  4179 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 10:46:50.204  4012  4173 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-25 10:46:50.204  4012  4173 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
08-25 10:46:50.206  1360  1360 D BluetoothMap: Proxy object disconnected
,08-25 10:46:50.206  1360  1360 D MapProfile: Bluetooth service disconnected
08-25 10:46:50.204  4012  4012 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-25 10:46:50.208  4012  4012 V BluetoothAdapterState: isTurningOff()=true
,08-25 10:46:50.208  4012  4012 V BluetoothAdapterState: isTurningOn()=false
08-25 10:46:50.208  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:50.209  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:50.211  4012  4179 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 10:46:50.211  4012  4179 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 10:46:50.211  4012  4179 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 10:46:50.211  4012  4179 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:46:50.211  4012  4179 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 10:46:50.211  4012  4012 V BluetoothAdapterState: isTurningOff()=true
,08-25 10:46:50.211  4012  4179 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:46:50.211  4012  4012 V BluetoothAdapterState: isTurningOn()=false
,08-25 10:46:50.211  4012  4173 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-25 10:46:50.211  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:50.211  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 10:46:50.212  4012  4012 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-25 10:46:50.212  4012  4012 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 10:46:50.212  4012  4173 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 10:46:50.212  4012  4012 V BluetoothAdapterState: isTurningOff()=true
08-25 10:46:50.212  4012  4012 V BluetoothAdapterState: isTurningOn()=false
08-25 10:46:50.212  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:50.212  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:50.212  4012  4012 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-25 10:46:50.212  4012  4173 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-25 10:46:50.212  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 10:46:50.212  4012  4012 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 10:46:50.213  4012  4012 V BluetoothAdapterState: isTurningOff()=true
08-25 10:46:50.213  4012  4012 V BluetoothAdapterState: isTurningOn()=false
,08-25 10:46:50.213  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 10:46:50.213  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:50.213  4012  4012 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 10:46:50.213  4012  4012 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 10:46:50.214  4012  4012 D BluetoothMapService: MAP Service closeService in
08-25 10:46:50.214  4012  4012 V BluetoothAdapterState: isTurningOff()=true
08-25 10:46:50.214  4012  4012 V BluetoothAdapterState: isTurningOn()=false
,08-25 10:46:50.214  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:50.214  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:50.214  4012  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-25 10:46:50.214  4012  4169 D BluetoothAdapterProperties: Setting state to 15
08-25 10:46:50.215  4012  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 10:46:50.215  4012  4169 I BluetoothAdapterState: Entering BleOnState
08-25 10:46:50.215  3908  3920 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 10:46:50.216  4012  4012 D BluetoothMapService: cleanup()
08-25 10:46:50.216  3908  3918 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 10:46:50.216  4012  4012 D BluetoothMapService: MAP Service closeService in
08-25 10:46:50.217  1360  1374 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 10:46:50.218  1360  2050 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:46:50.218   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:46:50.218  1954  1980 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 10:46:50.220  3908  3920 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:46:50.220  3908  3918 D BluetoothMap: onBluetoothStateChange: up=false
08-25 10:46:50.222   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 10:46:50.222  3908  3920 D BluetoothPan: onBluetoothStateChange on: false
,08-25 10:46:50.223   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:46:50.223  1360  1374 D BluetoothMap: onBluetoothStateChange: up=false
08-25 10:46:50.223  3908  3918 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 10:46:50.226  1360  2050 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 10:46:50.226  1360  1381 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 10:46:50.227  1360  1374 D BluetoothPan: onBluetoothStateChange on: false
,08-25 10:46:50.227   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 10:46:50.227  4012  4169 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-25 10:46:50.227  4012  4169 D BluetoothAdapterProperties: Setting state to 16
08-25 10:46:50.227  4012  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-25 10:46:50.228  4012  4169 D BluetoothAdapterProperties: onBleDisable
,08-25 10:46:50.229  4012  4169 I BluetoothAdapterState: Entering PendingCommandState
08-25 10:46:50.229  4012  4170 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-25 10:46:50.229  4012  4179 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-25 10:46:50.230  4012  4179 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 10:46:50.231  4012  4173 D BluetoothAdapterProperties: Scan Mode:20
08-25 10:46:50.231  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:50.232  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:50.234  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:50.235  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:50.235  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 10:46:50.242  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 10:46:50.242  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,08-25 10:46:50.431  4012  4173 I bt_hci  : shut_down
,08-25 10:46:50.448  4012  4177 I bt_vendor: low_power_mode_cb
,08-25 10:46:50.449  4012  4177 D bt_hwcfg: hw_epilog_process
,08-25 10:46:50.469  4012  4177 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-25 10:46:50.469  4012  4177 I bt_vendor: epilog_cb
08-25 10:46:50.469  4012  4177 I bt_hci  : epilog_finished_callback
,08-25 10:46:50.478  4012  4173 I bt_hci_h4: hal_close
,08-25 10:46:50.480  4012  4173 I bt_userial_vendor: device fd = 51 close
,08-25 10:46:50.601  4012  4170 D bt_stack_manager: event_shut_down_stack finished.
,08-25 10:46:50.602  4012  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 10:46:50.612  4012  4169 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-25 10:46:50.612  4012  4012 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 10:46:50.616  4012  4012 D BtGatt.GattService: Received stop request...Stopping profile...
,08-25 10:46:50.616  4012  4012 D BtGatt.GattService: stop()
,08-25 10:46:50.617  4012  4012 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 10:46:50.622  4012  4012 V BluetoothAdapterState: isTurningOff()=false
,08-25 10:46:50.622  4012  4012 V BluetoothAdapterState: isTurningOn()=false
,08-25 10:46:50.623  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 10:46:50.623  4012  4012 V BluetoothAdapterState: isBleTurningOff()=true
,08-25 10:46:50.624  4012  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-25 10:46:50.624  4012  4169 D BluetoothAdapterProperties: Setting state to 10
08-25 10:46:50.625  4012  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-25 10:46:50.626  4012  4169 I BluetoothAdapterState: Entering OffState
,08-25 10:46:50.628   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-25 10:46:50.641  4012  4012 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-25 10:46:50.644  4012  4012 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-25 10:46:50.645  4012  4170 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-25 10:46:50.645  4012  4012 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 10:46:50.650  4012  4170 D bt_stack_manager: event_clean_up_stack finished.
,08-25 10:46:50.653  4012  4012 I art     : System.exit called, status: 0
,08-25 10:46:50.653  4012  4012 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 10:46:50.708   873  1382 I ActivityManager: Process com.android.bluetooth (pid 4012) has died
,08-25 10:46:51.676   873  1307 D ConnectivityService: handlePromptUnvalidated 101
,08-25 10:46:53.122  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:53.122  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:56.130  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:46:56.131  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c4b661a added. We now have 6 listener(s)
08-25 10:46:56.131  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:46:56.135  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:46:56.136  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@752954b added. We now have 7 listener(s)
,08-25 10:46:56.136  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:46:56.138  3842  3892 I System.out: IsBluetoothEnabled
,08-25 10:46:56.148  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:56.174   873   890 I ActivityManager: Start proc 4216:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-25 10:46:56.296  4216  4216 D AdapterServiceConfig: Adding HeadsetService
08-25 10:46:56.296  4216  4216 D AdapterServiceConfig: Adding A2dpService
08-25 10:46:56.296  4216  4216 D AdapterServiceConfig: Adding HidService
08-25 10:46:56.296  4216  4216 D AdapterServiceConfig: Adding HealthService
08-25 10:46:56.296  4216  4216 D AdapterServiceConfig: Adding PanService
08-25 10:46:56.297  4216  4216 D AdapterServiceConfig: Adding GattService
,08-25 10:46:56.297  4216  4216 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 10:46:56.311   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4c23c4e:true
,08-25 10:46:56.312  4216  4216 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 10:46:56.317  4216  4216 I bt_bluedroid: init
,08-25 10:46:56.318  4216  4228 I BluetoothAdapterState: Entering OffState
,08-25 10:46:56.321  4216  4229 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 10:46:56.322  4216  4229 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 10:46:56.322  4216  4229 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 10:46:56.322  4216  4229 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 10:46:56.323  4216  4216 I bt_bluedroid: get_profile_interface socket
08-25 10:46:56.324  4216  4216 I bt_bluedroid: get_profile_interface sdp
,08-25 10:46:56.329  4216  4232 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-25 10:46:56.330  4216  4227 I bt_bluedroid: config_hci_snoop_log
,08-25 10:46:56.331   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-25 10:46:56.336  4216  4232 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 10:46:56.338  4216  4228 D BluetoothAdapterState: Current state: OFF, message: 0
08-25 10:46:56.338  4216  4228 D BluetoothAdapterProperties: Setting state to 14
08-25 10:46:56.339  4216  4228 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-25 10:46:56.343  4216  4228 D BluetoothBondStateMachine: make
,08-25 10:46:56.346  4216  4233 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 10:46:56.354  4216  4216 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-25 10:46:56.353  4216  4228 I BluetoothAdapterState: Entering PendingCommandState
,08-25 10:46:56.356  4216  4216 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
08-25 10:46:56.357  4216  4216 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 10:46:56.358  4216  4216 D BtGatt.GattService: Received start request. Starting profile...
08-25 10:46:56.358  4216  4216 D BtGatt.GattService: start()
08-25 10:46:56.358  4216  4216 I bt_bluedroid: get_profile_interface gatt
08-25 10:46:56.359  4216  4216 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
08-25 10:46:56.359  4216  4216 D BtGatt.AdvertiseManager: advertise manager created
,08-25 10:46:56.371  4216  4216 V BluetoothAdapterState: isTurningOff()=false
08-25 10:46:56.371  4216  4216 V BluetoothAdapterState: isTurningOn()=false
08-25 10:46:56.371  4216  4216 V BluetoothAdapterState: isBleTurningOn()=true
08-25 10:46:56.371  4216  4216 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:56.372  4216  4228 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-25 10:46:56.372  4216  4228 I bt_bluedroid: enable
,08-25 10:46:56.373  4216  4229 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-25 10:46:56.374  4216  4229 I bt_hci  : start_up
,08-25 10:46:56.381  4216  4229 I bt_vendor: alloc value 0xb3a39189
08-25 10:46:56.381  4216  4229 I bt_vendor: init
,08-25 10:46:56.381  4216  4229 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-25 10:46:56.381  4216  4229 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 10:46:56.488  4216  4229 D bt_hci  : start_up starting async portion
,08-25 10:46:56.490  4216  4236 I bt_hci  : event_finish_startup
08-25 10:46:56.490  4216  4236 I bt_hci_h4: hal_open
,08-25 10:46:56.491  4216  4236 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 10:46:56.500  4216  4236 I bt_userial_vendor: device fd = 51 open
,08-25 10:46:56.530  4216  4236 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 10:46:56.563  4216  4236 D bt_hwcfg: Chipset BCM4354A2
,08-25 10:46:56.563  4216  4236 D bt_hwcfg: Target name = [BCM4354A2]
,08-25 10:46:56.564  4216  4236 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 10:46:57.233  4216  4236 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 10:46:57.235  4216  4236 D bt_hwcfg: Settlement delay -- 100 ms
,08-25 10:46:57.235  4216  4236 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 10:46:57.353  4216  4236 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 10:46:57.354  4216  4236 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 10:46:57.383  4216  4236 I bt_hwcfg: vendor lib fwcfg completed
,08-25 10:46:57.383  4216  4236 I bt_vendor: firmware callback
08-25 10:46:57.384  4216  4236 I bt_hci  : firmware_config_callback
,08-25 10:46:57.396  4216  4238 I bt_btu  : btu_task pending for preload complete event
,08-25 10:46:57.396  4216  4238 I bt_btu_task: Bluetooth chip preload is complete
08-25 10:46:57.397  4216  4238 I bt_btu  : btu_task received preload complete event
,08-25 10:46:57.409  4216  4238 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 10:46:57.410  4216  4238 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 10:46:57.410  4216  4238 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 10:46:57.410  4216  4238 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-25 10:46:57.411  4216  4238 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 10:46:57.411  4216  4238 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 10:46:57.411  4216  4238 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-25 10:46:57.411  4216  4238 I         : BTE_InitTraceLevels -- TRC_BTM
,08-25 10:46:57.412  4216  4238 I         : BTE_InitTraceLevels -- TRC_GAP
,08-25 10:46:57.412  4216  4238 I         : BTE_InitTraceLevels -- TRC_PAN
,08-25 10:46:57.412  4216  4238 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 10:46:57.412  4216  4238 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 10:46:57.413  4216  4238 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 10:46:57.413  4216  4238 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 10:46:57.414  4216  4238 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 10:46:57.545  4216  4238 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39b6d9d
,08-25 10:46:57.545  4216  4238 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39b6d9d 
,08-25 10:46:57.555  4216  4232 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 10:46:57.556  4216  4232 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 10:46:57.557  4216  4232 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-25 10:46:57.561  4216  4232 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 10:46:57.566  4216  4232 D BluetoothAdapterProperties: Scan Mode:20
,08-25 10:46:57.567  4216  4232 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 10:46:57.568  4216  4232 D bt_hci  : do_postload posting postload work item
08-25 10:46:57.568  4216  4236 I bt_hci  : event_postload
,08-25 10:46:57.568  4216  4236 I bt_vendor: sco_config_cb
08-25 10:46:57.568  4216  4236 I bt_hci  : sco_config_callback postload finished.
,08-25 10:46:57.572  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:57.572  4216  4232 D bt_bte_conf: Device ID record 1 : primary
08-25 10:46:57.572  4216  4232 D bt_bte_conf:   vendorId            = 000f
,08-25 10:46:57.573  4216  4232 D bt_bte_conf:   vendorIdSource      = 0001
08-25 10:46:57.573  4216  4232 D bt_bte_conf:   product             = 1200
,08-25 10:46:57.573  4216  4232 D bt_bte_conf:   version             = 1436
08-25 10:46:57.573  4216  4232 D bt_bte_conf:   clientExecutableURL = 
08-25 10:46:57.573  4216  4232 D bt_bte_conf:   serviceDescription  = 
08-25 10:46:57.574  4216  4232 D bt_bte_conf:   documentationURL    = 
08-25 10:46:57.574  4216  4232 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 10:46:57.574  4216  4229 D bt_stack_manager: event_start_up_stack finished
08-25 10:46:57.578  4216  4236 I bt_vendor: low_power_mode_cb
08-25 10:46:57.578  4216  4228 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-25 10:46:57.579  4216  4228 D BluetoothAdapterProperties: Setting state to 15
08-25 10:46:57.579  4216  4228 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-25 10:46:57.580  4216  4228 I BluetoothAdapterState: Entering BleOnState
08-25 10:46:57.586  4216  4228 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-25 10:46:57.587  4216  4228 D BluetoothAdapterProperties: Setting state to 11
08-25 10:46:57.587  4216  4228 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-25 10:46:57.597  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:57.598  4216  4216 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
08-25 10:46:57.599  4216  4216 D HeadsetService: Received start request. Starting profile...
,08-25 10:46:57.602  4216  4216 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 10:46:57.602  4216  4216 D HeadsetStateMachine: make
,08-25 10:46:57.615  4216  4228 I BluetoothAdapterState: Entering PendingCommandState
,08-25 10:46:57.616  4216  4216 D HeadsetStateMachine: max_hf_connections = 1
08-25 10:46:57.616  4216  4216 I bt_bluedroid: get_profile_interface handsfree
,08-25 10:46:57.617  4216  4232 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-25 10:46:57.618  4216  4232 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-25 10:46:57.621  4216  4216 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
08-25 10:46:57.622  4216  4216 D A2dpService: Received start request. Starting profile...
08-25 10:46:57.623  4216  4216 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 10:46:57.623  4216  4216 I bt_bluedroid: get_profile_interface avrcp
,08-25 10:46:57.635  4216  4216 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 10:46:57.636  4216  4216 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 10:46:57.636  4216  4216 D A2dpStateMachine: make
,08-25 10:46:57.638  4216  4216 I bt_bluedroid: get_profile_interface a2dp
,08-25 10:46:57.640  4216  4232 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 10:46:57.641  4216  4216 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 10:46:57.642  4216  4247 D A2dpStateMachine: Enter Disconnected: -2
,08-25 10:46:57.643  4216  4216 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
08-25 10:46:57.644  4216  4216 D HidService: Received start request. Starting profile...
08-25 10:46:57.644  4216  4216 I bt_bluedroid: get_profile_interface hidhost
08-25 10:46:57.644  4216  4216 D HidService: setHidService(): set to: null
,08-25 10:46:57.646  4216  4232 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39983e5
,08-25 10:46:57.646  4216  4232 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-25 10:46:57.648  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 10:46:57.649  4216  4216 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 10:46:57.649  4216  4216 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
08-25 10:46:57.650  4216  4216 D HealthService: Received start request. Starting profile...
,08-25 10:46:57.653  4216  4216 I bt_bluedroid: get_profile_interface health
,08-25 10:46:57.656  4216  4216 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 10:46:57.657  4216  4216 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
08-25 10:46:57.658  4216  4216 D PanService: Received start request. Starting profile...
08-25 10:46:57.658  4216  4216 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 10:46:57.658  4216  4216 I bt_bluedroid: get_profile_interface pan
,08-25 10:46:57.660  4216  4232 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 10:46:57.668  4216  4216 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
,08-25 10:46:57.670  4216  4216 D BluetoothMapService: Received start request. Starting profile...
,08-25 10:46:57.670  4216  4216 D BluetoothMapService: start()
,08-25 10:46:57.676  4216  4216 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-25 10:46:57.677  4216  4216 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-25 10:46:57.677  4216  4216 D BluetoothMapAppObserver: createReceiver()
08-25 10:46:57.678  4216  4216 D BluetoothMapAppObserver: initObservers()
,08-25 10:46:57.678  4216  4216 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 10:46:57.685  4216  4216 V BluetoothAdapterState: isTurningOff()=false
08-25 10:46:57.685  4216  4216 V BluetoothAdapterState: isTurningOn()=true
08-25 10:46:57.685  4216  4216 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:57.685  4216  4216 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:57.686  4216  4245 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-25 10:46:57.687  4216  4216 V BluetoothAdapterState: isTurningOff()=false
,08-25 10:46:57.687  4216  4216 V BluetoothAdapterState: isTurningOn()=true
08-25 10:46:57.687  4216  4216 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:57.687  4216  4216 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 10:46:57.687  4216  4216 V BluetoothAdapterState: isTurningOff()=false
,08-25 10:46:57.687  4216  4216 V BluetoothAdapterState: isTurningOn()=true
08-25 10:46:57.687  4216  4216 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:57.688  4216  4216 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 10:46:57.689  4216  4216 V BluetoothAdapterState: isTurningOff()=false
08-25 10:46:57.689  4216  4216 V BluetoothAdapterState: isTurningOn()=true
08-25 10:46:57.689  4216  4216 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 10:46:57.689  4216  4216 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 10:46:57.690  4216  4216 V BluetoothAdapterState: isTurningOff()=false
,08-25 10:46:57.690  4216  4216 V BluetoothAdapterState: isTurningOn()=true
,08-25 10:46:57.691  4216  4216 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 10:46:57.691  4216  4216 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:57.691  4216  4216 V BluetoothAdapterState: isTurningOff()=false
08-25 10:46:57.691  4216  4216 V BluetoothAdapterState: isTurningOn()=true
,08-25 10:46:57.691  4216  4216 V BluetoothAdapterState: isBleTurningOn()=false
08-25 10:46:57.692  4216  4216 V BluetoothAdapterState: isBleTurningOff()=false
08-25 10:46:57.692  4216  4228 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 10:46:57.692  4216  4228 D BluetoothAdapterProperties: ScanMode =  20
08-25 10:46:57.692  4216  4228 D BluetoothAdapterProperties: State =  11
,08-25 10:46:57.693  4216  4228 D BluetoothAdapterProperties: Setting state to 12
08-25 10:46:57.693  4216  4228 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 10:46:57.694  3908  3920 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 10:46:57.695  4216  4228 I BluetoothAdapterState: Entering OnState
08-25 10:46:57.695  4216  4232 D BluetoothAdapterProperties: Scan Mode:21
,08-25 10:46:57.696  4216  4232 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 10:46:57.698  3908  3918 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 10:46:57.700  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:57.700  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:57.700  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:57.700  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:57.700  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:57.700  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:57.700  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:57.700  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:46:57.700  1360  1374 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 10:46:57.701  3908  3908 D BluetoothInputDevice: Proxy object connected
,08-25 10:46:57.701  3908  3908 D HidProfile: Bluetooth service connected
08-25 10:46:57.703  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:46:57.705  4216  4216 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 10:46:57.706  4216  4216 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-25 10:46:57.708  1360  1381 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 10:46:57.709   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 10:46:57.709  1954  1971 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 10:46:57.710  3908  3920 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 10:46:57.711  3908  3918 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 10:46:57.711  4216  4216 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 10:46:57.713   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 10:46:57.714  3908  4252 D BluetoothPan: onBluetoothStateChange on: true
,08-25 10:46:57.716  4216  4216 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 10:46:57.718   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 10:46:57.718  1360  2050 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 10:46:57.719  4216  4216 D ObexServerSockets: Succeed to create listening sockets 
08-25 10:46:57.719  4216  4216 D ObexServerSockets0: startAccept()
08-25 10:46:57.720  4216  4216 D ObexServerSockets0: prepareForNewConnect()
08-25 10:46:57.720  3908  3920 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 10:46:57.721  1360  1374 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 10:46:57.723  1360  1381 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 10:46:57.725  1360  1360 D BluetoothInputDevice: Proxy object connected
,08-25 10:46:57.725  1360  1374 D BluetoothPan: onBluetoothStateChange on: true
08-25 10:46:57.725  1360  1360 D HidProfile: Bluetooth service connected
,08-25 10:46:57.726  4216  4216 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-25 10:46:57.727  4216  4254 D ObexServerSockets0: Accepting socket connection...
,08-25 10:46:57.727   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 10:46:57.727  4216  4216 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-25 10:46:57.729  4216  4255 D ObexServerSockets0: Accepting socket connection...
08-25 10:46:57.729   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 10:46:57.732  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:57.736  1360  1360 D BluetoothMap: Proxy object connected
,08-25 10:46:57.736  1360  1360 D MapProfile: Bluetooth service connected
,08-25 10:46:57.736  1360  1360 D BluetoothMap: getConnectedDevices()
08-25 10:46:57.736   873   873 D BluetoothA2dp: Proxy object connected
08-25 10:46:57.738  4216  4216 D BluetoothMapService: onReceive
,08-25 10:46:57.738  4216  4216 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:57.739  4216  4216 D BluetoothMapService: STATE_ON
,08-25 10:46:57.742  1360  1360 D BluetoothA2dp: Proxy object connected
,08-25 10:46:57.743  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 10:46:57.745  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 10:46:57.745  1360  1360 D PanProfile: Bluetooth service connected
,08-25 10:46:57.750  3908  3908 D BluetoothMap: Proxy object connected
,08-25 10:46:57.750  3908  3908 D MapProfile: Bluetooth service connected
08-25 10:46:57.750  3908  3908 D BluetoothMap: getConnectedDevices()
,08-25 10:46:57.757  1505  1505 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 10:46:57.760  3908  3908 D BluetoothA2dp: Proxy object connected
,08-25 10:46:57.763  3908  3908 D BluetoothPan: BluetoothPAN Proxy object connected
,08-25 10:46:57.763  3908  3908 D PanProfile: Bluetooth service connected
,08-25 10:46:57.766  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,08-25 10:46:57.780  1360  1360 D BluetoothPbap: Proxy object connected
,08-25 10:46:57.780  1360  1360 D PbapServerProfile: Bluetooth service connected
,08-25 10:46:57.780  3908  3908 D BluetoothPbap: Proxy object connected
08-25 10:46:57.780  3908  3908 D PbapServerProfile: Bluetooth service connected
,08-25 10:46:57.782  4216  4216 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 10:46:57.783  4216  4216 D ObexServerSockets0: prepareForNewConnect()
,08-25 10:46:57.796  4216  4260 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 10:46:57.811   873   873 D BluetoothHeadset: Proxy object connected
,08-25 10:46:57.811   873   873 D BluetoothHeadset: Proxy object connected
,08-25 10:46:57.811  1360  2050 D BluetoothHeadset: Proxy object connected
08-25 10:46:57.811   873   873 D BluetoothHeadset: Proxy object connected
08-25 10:46:57.811  1360  1360 D HeadsetProfile: Bluetooth service connected
08-25 10:46:57.812  3908  3920 D BluetoothHeadset: Proxy object connected
08-25 10:46:57.813  1954  2184 D BluetoothHeadset: Proxy object connected
08-25 10:46:57.815  4216  4264 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 10:46:57.816  3908  3908 D HeadsetProfile: Bluetooth service connected
08-25 10:46:57.818  4216  4264 I BtOppRfcommListener: Accept thread started.
08-25 10:46:57.818   873   890 D BluetoothHeadset: Proxy object connected
,08-25 10:46:57.828   873   890 D BluetoothHeadset: Proxy object connected
,08-25 10:46:58.174  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:58.174  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:58.174  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:58.174  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:58.174  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:58.174  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:58.174  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:58.174  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:58.181  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:58.184  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 10:46:58.185  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aa89b28 added. We now have 8 listener(s)
,08-25 10:46:58.185  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:46:58.191   873   883 D WifiService: setWifiEnabled: false pid=3842, uid=10000
08-25 10:46:58.192   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 10:46:58.203  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:58.204   873  1382 D WifiService: setWifiEnabled: true pid=3842, uid=10000
,08-25 10:46:58.205   873  1382 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 10:46:58.221   873  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-25 10:46:58.235  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:58.235  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:58.235  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:58.235  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:58.235  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:58.235  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:58.235  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:58.235  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:58.242  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:58.271   873  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-25 10:46:58.273   873  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-25 10:46:58.275   873  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-25 10:46:58.278   873  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 10:46:58.278   873  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-25 10:46:58.279   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-25 10:46:58.279   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 10:46:58.307   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-25 10:46:58.308   873  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.93 rxSuccessRate=1.16 delta 1000 -> 1000
,08-25 10:46:58.309   373   871 D CommandListener: Setting iface cfg
,08-25 10:46:58.311   873  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-25 10:46:58.311   873  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 10:46:58.321   873  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-25 10:46:58.322   873  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 10:46:58.338   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-25 10:46:58.338   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 10:46:58.363   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 10:46:58.411   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 10:46:58.413  1451  1451 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 10:46:58.885  1451  1451 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 10:46:58.931  1451  1451 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 10:46:58.932  1451  1451 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 10:46:58.942   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 10:46:58.953   873  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} },
08-25 10:46:58.954   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 10:46:58.954   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 10:46:58.973   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 10:46:58.986   373   871 D CommandListener: Setting iface cfg
,08-25 10:46:58.989   873  1305 D WifiStateMachine: Start Dhcp Watchdog 3
,08-25 10:46:59.008   873  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-25 10:46:59.009   873  1307 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-25 10:46:59.013   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 10:46:59.028   873  4275 D DhcpClient: Receive thread started
,08-25 10:46:59.116   873  1305 E native  : do suspend false
,08-25 10:46:59.138   873  1878 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 10:46:59.153   873  4275 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172784, domain null
,08-25 10:46:59.154   873  1878 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172784 seconds
,08-25 10:46:59.157   873  1878 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 10:46:59.173   873  4275 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 10:46:59.174   873  1878 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 10:46:59.179   373   871 D CommandListener: Setting iface cfg
,08-25 10:46:59.191   873  1878 D DhcpClient: Scheduling renewal in 86399s
,08-25 10:46:59.192   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-25 10:46:59.207   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 10:46:59.210   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
08-25 10:46:59.212   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 10:46:59.215   873  1307 D ConnectivityService: Adding iface wlan0 to network 102
,08-25 10:46:59.222   873  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 10:46:59.240  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:59.240  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:59.240  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:59.240  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:59.240  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:59.240  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:59.240  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:59.240  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:59.243  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:59.247  3842  3892 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-25 10:46:59.248  3842  3892 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-25 10:46:59.251  3842  3892 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@58b8950 Bundle[{}]
08-25 10:46:59.252  3842  3892 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 10:46:59.252  3842  3892 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-25 10:46:59.253  3842  3892 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-25 10:46:59.254  3842  3892 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 10:46:59.254  3842  3892 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-25 10:46:59.255  3842  3892 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-25 10:46:59.259  3842  3892 I System.out: Running OutgoingSocketThread
,08-25 10:46:59.262  3842  4278 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 423)
,08-25 10:46:59.262  3842  4278 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40139
08-25 10:46:59.262  3842  4278 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 10:46:59.269   873  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 10:46:59.269   873  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-25 10:46:59.270   873  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-25 10:46:59.271   873  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-25 10:46:59.272   873  1307 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-25 10:46:59.278   873  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-25 10:46:59.282   873  1307 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-25 10:46:59.282   873  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-25 10:46:59.282   873  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-25 10:46:59.282   873  1307 D ConnectivityService:    accepting network in place of null
08-25 10:46:59.282   873  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-25 10:46:59.283   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 10:46:59.283   873  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 10:46:59.288   873  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=148780, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 10:46:59.315   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 10:46:59.345   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 10:46:59.350   873  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-25 10:46:59.350   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:59.352   873  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-25 10:46:59.355   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-25 10:46:59.361   873  4271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:804::200e
,08-25 10:46:59.390  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:59.390  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:59.390  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:59.390  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:59.390  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:59.390  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:59.390  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:59.390  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 10:46:59.392  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 10:46:59.394  2021  2021 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-25 10:46:59.400  1714  1714 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 10:46:59.409  1714  1714 D SystemUpdateService: onCreate
,08-25 10:46:59.414  1714  1714 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 10:46:59.426  1714  4285 I SystemUpdateService: active receiver: enabled
,08-25 10:46:59.434  1714  1714 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 10:46:59.438  1714  2438 I iu.UploadsManager: num queued entries: 0
,08-25 10:46:59.439  1714  2438 I iu.UploadsManager: num updated entries: 0
,08-25 10:46:59.441  1714  4285 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 10:46:59.442   873  4271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 08:46:59 GMT], X-Android-Received-Millis=[1472114819441], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472114819412]}
,08-25 10:46:59.443   873  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 10:46:59.443   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-25 10:46:59.443   873  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102],
,08-25 10:46:59.444   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 10:46:59.447  1714  1714 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 10:46:59.448  1714  1714 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 10:46:59.450  4026  4026 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:59.456  1714  4288 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-25 10:46:59.456  1714  4288 W BaseAppContext: Using Auth Proxy for data requests.
,08-25 10:46:59.459  4026  4026 D SprintDMHelper: simOperator: 
,08-25 10:46:59.459  4026  4026 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 10:46:59.460  1714  4288 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-25 10:46:59.466  1714  4285 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-25 10:46:59.468  1714  4285 I SystemUpdateService: now status is 0 (complete)
,08-25 10:46:59.469  1714  4285 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-25 10:46:59.469  1714  4285 I SystemUpdateService: file has been verified
,08-25 10:46:59.470  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
08-25 10:46:59.473  1505  1505 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 10:46:59.481  1714  4285 I SystemUpdateService: OTA package size = 12249756
,08-25 10:46:59.503  1714  2438 I iu.SyncManager: NEXT; no task
,08-25 10:46:59.521  1714  4285 I SystemUpdateService: showing system update notification
,08-25 10:46:59.537  1505  2019 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-25 10:46:59.537  1505  2019 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-25 10:46:59.537  1505  2019 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 10:46:59.537  1505  2019 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 10:46:59.542  1714  1714 D SystemUpdateService: onDestroy
,08-25 10:46:59.562  1714  4288 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-25 10:46:59.619  3956  4291 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 10:46:59.778  1505  4295 I GCM     : Ack for not saved message 107
,08-25 10:47:00.262  3842  3892 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 424)
,08-25 10:47:00.263  3842  3892 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 424)
,08-25 10:47:00.275  3842  3892 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 429)
,08-25 10:47:00.278  3842  3892 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-25 10:47:00.279  3842  3892 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-25 10:47:00.286  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 10:47:00.286  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2007041 added. We now have 2 listener(s)
,08-25 10:47:00.293  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 10:47:00.293  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 10:47:00.293  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 10:47:00.294  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:47:00.294  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa9c9e6 added. We now have 9 listener(s),
08-25 10:47:00.294  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:47:00.295  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 10:47:00.302  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:47:00.311  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:47:00.311  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:47:00.311  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:47:00.311  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:47:00.311  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:47:00.311  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:47:00.311  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:47:00.311  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 10:47:00.315  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 10:47:00.315  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 10:47:00.315  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:47:00.315  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38041d4 added. We now have 3 listener(s)
,08-25 10:47:00.318  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 10:47:00.320  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:47:00.320  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 10:47:00.321  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 10:47:00.331  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:47:00.331  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa2cf7d added. We now have 10 listener(s)
08-25 10:47:00.331  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:47:00.332  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 10:47:00.332  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:47:00.332  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 10:47:00.332  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 10:47:00.332  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:47:00.332  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:47:00.332  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:47:00.332  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:47:00.332  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2007041 removed from the list
,08-25 10:47:00.332  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:47:00.332  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa9c9e6 removed from the list
08-25 10:47:00.332  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:47:00.333  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:47:00.333  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:47:00.333  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:47:00.336  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:47:00.336  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:47:00.337  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:47:00.337  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa9c9e6 not in the list
08-25 10:47:00.337  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:47:00.338  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:47:00.339  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:47:00.339  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 10:47:00.339  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:47:00.339  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa2cf7d removed from the list
08-25 10:47:00.339  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:47:00.339  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:47:00.340  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:47:00.340  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:47:00.340  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38041d4 removed from the list
08-25 10:47:00.340  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:47:00.341  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b389e72 added. We now have 2 listener(s)
,08-25 10:47:00.342  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 10:47:00.342  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 10:47:00.343  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 10:47:00.343  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:47:00.343  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58e62c3 added. We now have 9 listener(s)
,08-25 10:47:00.343  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:47:00.343  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 10:47:00.355  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:47:00.361  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:47:00.361  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:47:00.361  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:47:00.361  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:47:00.361  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:47:00.361  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:47:00.361  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:47:00.361  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 10:47:00.363  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 10:47:00.363  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:47:00.364  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:47:00.364  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@811e679 added. We now have 3 listener(s)
,08-25 10:47:00.365  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:47:00.367  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:47:00.367  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 10:47:00.367  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:47:00.367  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 10:47:00.367  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:47:00.367  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6e2fbe added. We now have 10 listener(s)
08-25 10:47:00.368  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:47:00.368  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 10:47:00.368  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 10:47:00.368  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 10:47:00.368  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:47:00.368  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 10:47:00.371  3842  3892 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 10:47:00.371  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 10:47:00.375  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 10:47:00.375  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 10:47:00.375  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 10:47:00.378  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 10:47:00.378  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 10:47:00.379  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 10:47:00.379  3842  3892 D BluetoothAdapter: STATE_ON
,08-25 10:47:00.382  4216  4256 D BtGatt.GattService: registerClient() - UUID=d685dc3c-317e-424e-baf4-79015a8683c3
,08-25 10:47:00.383  4216  4232 D BtGatt.GattService: onClientRegistered() - UUID=d685dc3c-317e-424e-baf4-79015a8683c3, clientIf=5
,08-25 10:47:00.383  3842  3854 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 10:47:00.384  4216  4227 D BtGatt.GattService: start scan with filters
08-25 10:47:00.387  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 10:47:00.387  4216  4235 D BtGatt.ScanManager: handling starting scan
08-25 10:47:00.387  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 10:47:00.387  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 10:47:00.387  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-25 10:47:00.389  4216  4235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6ad22e4
,08-25 10:47:00.390  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 10:47:00.390  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 10:47:00.390  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 10:47:00.391  4216  4232 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 10:47:00.391  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:47:00.392  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 10:47:00.392  4216  4235 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 10:47:00.395  3842  3892 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 10:47:00.395  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 10:47:00.395  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 10:47:00.395  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:47:00.395  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 10:47:00.395  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 10:47:00.395  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-25 10:47:00.395  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 10:47:00.395  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 10:47:00.397  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 10:47:00.397  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 10:47:00.397  4216  4232 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
08-25 10:47:00.398  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:47:00.398  3842  3892 D BluetoothAdapter: STATE_ON
,08-25 10:47:00.398  4216  4235 D BtGatt.ScanManager: Starting BLE batch scan
08-25 10:47:00.398  4216  4256 D BtGatt.GattService: stopScan() - queue size =1
,08-25 10:47:00.398  4216  4235 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 10:47:00.399  4216  4227 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 10:47:00.399  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 10:47:00.399  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 10:47:00.399  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 10:47:00.399  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 10:47:00.399  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
08-25 10:47:00.400  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 10:47:00.400  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 10:47:00.400  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 10:47:00.400  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 10:47:00.401  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:47:00.402  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:47:00.402  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 10:47:00.402  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 10:47:00.404  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:47:00.404  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 10:47:00.404  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 10:47:00.404  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 10:47:00.405  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:47:00.405  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:47:00.405  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 10:47:00.405  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b389e72 removed from the list
,08-25 10:47:00.405  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:47:00.405  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58e62c3 removed from the list
08-25 10:47:00.405  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 10:47:00.405  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:47:00.405  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:47:00.405  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:47:00.406  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 10:47:00.406  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:47:00.406  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:47:00.406  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58e62c3 not in the list
08-25 10:47:00.406  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:47:00.406  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:47:00.407  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 10:47:00.407  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:47:00.407  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:47:00.407  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6e2fbe removed from the list
,08-25 10:47:00.407  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:47:00.408  4216  4232 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 10:47:00.408  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:47:00.408  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:47:00.408  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:47:00.408  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:47:00.408  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@811e679 removed from the list
,08-25 10:47:00.408  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 10:47:00.408  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d989ca added. We now have 2 listener(s)
08-25 10:47:00.410  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 10:47:00.410  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:47:00.410  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:47:00.410  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:47:00.410  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd7673b added. We now have 9 listener(s)
,08-25 10:47:00.410  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:47:00.411  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 10:47:00.413  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:47:00.413  4216  4232 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 10:47:00.413  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:47:00.417  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:47:00.417  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:47:00.417  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:47:00.417  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:47:00.417  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:47:00.417  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:47:00.417  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:47:00.417  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:47:00.418  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:47:00.419  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:47:00.420  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 10:47:00.420  4216  4232 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 10:47:00.420  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca4ebb1 added. We now have 3 listener(s)
08-25 10:47:00.420  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:47:00.420  4216  4235 D BtGatt.ScanManager: stopping BLe Batch
08-25 10:47:00.421  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 10:47:00.421  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:47:00.421  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:47:00.421  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:47:00.421  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dee7896 added. We now have 10 listener(s)
08-25 10:47:00.421  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:47:00.422  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 10:47:00.422  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:47:00.422  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 10:47:00.422  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 10:47:00.422  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:47:00.422  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 10:47:00.423  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:47:00.425  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:47:00.425  3842  3892 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 10:47:00.426  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 10:47:00.428  4216  4232 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 10:47:00.428  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:47:00.428  4216  4235 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 10:47:00.428  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 10:47:00.429  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 10:47:00.429  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 10:47:00.431  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 10:47:00.431  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 10:47:00.432  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 10:47:00.432  3842  3892 D BluetoothAdapter: STATE_ON
,08-25 10:47:00.433  4216  4232 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-25 10:47:00.433  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:47:00.434  4216  4244 D BtGatt.GattService: registerClient() - UUID=1b23f1c3-22eb-4351-8c93-51a54e065fe2
08-25 10:47:00.434  4216  4232 D BtGatt.GattService: onClientRegistered() - UUID=1b23f1c3-22eb-4351-8c93-51a54e065fe2, clientIf=5
08-25 10:47:00.434  3842  3852 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 10:47:00.435  4216  4256 D BtGatt.GattService: start scan with filters
,08-25 10:47:00.436  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 10:47:00.436  4216  4235 D BtGatt.ScanManager: handling starting scan
08-25 10:47:00.436  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 10:47:00.436  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 10:47:00.437  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 10:47:00.438  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 10:47:00.439  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 10:47:00.439  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 10:47:00.440  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 10:47:00.442  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 10:47:00.442  3842  3892 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-25 10:47:00.443  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:47:00.443  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 10:47:00.443  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:47:00.443  4216  4232 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 10:47:00.443  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:47:00.443  4216  4235 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 10:47:00.443  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:47:00.443  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:47:00.443  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 10:47:00.444  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:47:00.444  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d989ca removed from the list
08-25 10:47:00.444  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:47:00.444  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd7673b removed from the list
08-25 10:47:00.444  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:47:00.444  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:47:00.444  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:47:00.444  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 10:47:00.444  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:47:00.444  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:47:00.445  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 10:47:00.445  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:47:00.445  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:47:00.445  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd7673b not in the list
08-25 10:47:00.445  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 10:47:00.445  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 10:47:00.445  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 10:47:00.445  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 10:47:00.445  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 10:47:00.446  3842  3892 D BluetoothAdapter: STATE_ON
08-25 10:47:00.446  4216  4227 D BtGatt.GattService: stopScan() - queue size =1
,08-25 10:47:00.447  4216  4232 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 10:47:00.447  4216  4256 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 10:47:00.447  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:47:00.447  4216  4235 D BtGatt.ScanManager: Starting BLE batch scan
08-25 10:47:00.447  4216  4235 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 10:47:00.447  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 10:47:00.447  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 10:47:00.447  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 10:47:00.447  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 10:47:00.447  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 10:47:00.449  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 10:47:00.449  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 10:47:00.449  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 10:47:00.450  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 10:47:00.450  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:47:00.451  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:47:00.451  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 10:47:00.451  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 10:47:00.451  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:47:00.451  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 10:47:00.451  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:47:00.451  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dee7896 removed from the list
08-25 10:47:00.451  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:47:00.451  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:47:00.451  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:47:00.451  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:47:00.451  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca4ebb1 removed from the list
,08-25 10:47:00.452  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:47:00.452  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8918822 added. We now have 2 listener(s)
,08-25 10:47:00.453  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 10:47:00.453  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:47:00.453  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:47:00.454  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 10:47:00.454  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bd82b3 added. We now have 9 listener(s)
08-25 10:47:00.454  4216  4232 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 10:47:00.454  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:47:00.454  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:47:00.454  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 10:47:00.456  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:47:00.458  4216  4232 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 10:47:00.458  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:47:00.459  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:47:00.459  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:47:00.459  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:47:00.459  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:47:00.459  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:47:00.459  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:47:00.459  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:47:00.459  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:47:00.460  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:47:00.460  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 10:47:00.460  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:47:00.461  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7c5fe9 added. We now have 3 listener(s)
,08-25 10:47:00.462  4216  4232 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 10:47:00.462  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:47:00.462  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:47:00.462  4216  4235 D BtGatt.ScanManager: stopping BLe Batch
08-25 10:47:00.462  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 10:47:00.463  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:47:00.463  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:47:00.463  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:47:00.463  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@764046e added. We now have 10 listener(s)
08-25 10:47:00.463  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:47:00.463  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 10:47:00.463  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 10:47:00.463  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 10:47:00.463  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:47:00.463  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 10:47:00.464  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:47:00.465  3842  3892 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 10:47:00.465  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 10:47:00.467  4216  4232 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 10:47:00.467  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:47:00.467  4216  4235 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 10:47:00.468  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 10:47:00.468  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 10:47:00.468  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 10:47:00.470  4216  4232 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 10:47:00.470  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:47:00.471  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 10:47:00.471  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 10:47:00.471  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 10:47:00.471  3842  3892 D BluetoothAdapter: STATE_ON
,08-25 10:47:00.473  4216  4226 D BtGatt.GattService: registerClient() - UUID=5aa0cf0d-1187-4b54-b66e-dc416c373b8d
,08-25 10:47:00.473  4216  4232 D BtGatt.GattService: onClientRegistered() - UUID=5aa0cf0d-1187-4b54-b66e-dc416c373b8d, clientIf=5
08-25 10:47:00.473  3842  3852 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 10:47:00.473  4216  4256 D BtGatt.GattService: start scan with filters
,08-25 10:47:00.475  4216  4235 D BtGatt.ScanManager: handling starting scan
,08-25 10:47:00.475  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 10:47:00.475  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 10:47:00.475  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 10:47:00.475  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 10:47:00.477  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 10:47:00.477  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 10:47:00.478  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 10:47:00.479  4216  4232 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 10:47:00.479  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:47:00.479  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-25 10:47:00.479  4216  4235 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 10:47:00.482  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 10:47:00.482  4216  4232 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 10:47:00.482  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:47:00.482  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:47:00.482  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:47:00.482  4216  4235 D BtGatt.ScanManager: Starting BLE batch scan
08-25 10:47:00.482  4216  4235 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 10:47:00.483  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:47:00.483  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:47:00.483  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 10:47:00.483  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:47:00.483  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8918822 removed from the list
08-25 10:47:00.483  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:47:00.483  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bd82b3 removed from the list
08-25 10:47:00.483  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 10:47:00.483  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:47:00.483  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 10:47:00.483  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 10:47:00.483  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:47:00.483  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:47:00.484  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:47:00.484  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:47:00.484  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:47:00.484  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9bd82b3 not in the list
08-25 10:47:00.485  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 10:47:00.485  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 10:47:00.485  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 10:47:00.485  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 10:47:00.485  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 10:47:00.486  3842  3892 D BluetoothAdapter: STATE_ON
08-25 10:47:00.486  4216  4227 D BtGatt.GattService: stopScan() - queue size =1
08-25 10:47:00.486  4216  4226 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 10:47:00.487  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:47:00.487  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 10:47:00.487  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 10:47:00.487  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 10:47:00.487  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 10:47:00.488  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 10:47:00.488  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 10:47:00.488  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 10:47:00.488  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 10:47:00.488  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:47:00.489  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 10:47:00.489  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:47:00.489  4216  4232 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 10:47:00.489  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:47:00.489  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 10:47:00.489  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:47:00.489  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:47:00.489  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:47:00.489  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@764046e removed from the list
08-25 10:47:00.489  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:47:00.490  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:47:00.490  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:47:00.490  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:47:00.490  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7c5fe9 removed from the list
08-25 10:47:00.490  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:47:00.490  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cff97a added. We now have 2 listener(s)
,08-25 10:47:00.492  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 10:47:00.492  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:47:00.492  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:47:00.492  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:47:00.492  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ec952b added. We now have 9 listener(s)
08-25 10:47:00.492  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:47:00.493  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 10:47:00.493  4216  4232 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 10:47:00.493  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:47:00.495  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:47:00.497  4216  4232 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 10:47:00.497  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:47:00.497  4216  4235 D BtGatt.ScanManager: stopping BLe Batch
08-25 10:47:00.498  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:47:00.498  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:47:00.498  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:47:00.498  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:47:00.498  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:47:00.498  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:47:00.498  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:47:00.498  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 10:47:00.500  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 10:47:00.500  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 10:47:00.501  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 10:47:00.501  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d72321 added. We now have 3 listener(s)
,08-25 10:47:00.502  4216  4232 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 10:47:00.502  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:47:00.502  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 10:47:00.502  4216  4235 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 10:47:00.503  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 10:47:00.503  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 10:47:00.503  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:47:00.503  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:47:00.503  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d43346 added. We now have 10 listener(s)
08-25 10:47:00.503  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:47:00.503  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 10:47:00.503  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:47:00.503  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:47:00.503  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:47:00.503  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:47:00.503  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:47:00.504  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:47:00.504  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 10:47:00.504  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cff97a removed from the list
08-25 10:47:00.504  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:47:00.504  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ec952b removed from the list
08-25 10:47:00.504  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:47:00.504  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:47:00.504  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:47:00.504  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:47:00.505  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 10:47:00.505  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:47:00.505  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:47:00.505  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ec952b not in the list
08-25 10:47:00.505  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:47:00.505  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:47:00.506  4216  4232 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 10:47:00.506  4216  4232 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 10:47:00.506  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:47:00.506  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 10:47:00.506  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:47:00.506  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d43346 removed from the list
08-25 10:47:00.506  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:47:00.506  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:47:00.506  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:47:00.506  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:47:00.506  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d72321 removed from the list
08-25 10:47:00.507  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-25 10:47:00.507  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 10:47:00.508  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 10:47:00.508  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:47:00.508  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 10:47:00.508  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 10:47:00.512  3842  4298 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: My test thread name)
,08-25 10:47:00.512  3842  4298 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 437, thread name: My test thread name)
08-25 10:47:00.512  3842  4298 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 437, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 10:47:00.513  3842  4299 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: My test thread name)
,08-25 10:47:00.513  3842  4299 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: My test thread name)
08-25 10:47:00.513  3842  4299 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 10:47:00.515  3842  3892 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-25 10:47:00.515  3842  3892 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 10:47:00.515  3842  3892 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-25 10:47:00.515  3842  3892 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-25 10:47:00.515  3842  3892 D com.test.thalitest.ThaliTestRunner: Total duration: 22729 ms
,08-25 10:47:00.516  3842  3892 I jxcore-log: Total number of executed tests:  80
08-25 10:47:00.516  3842  3892 I jxcore-log: 
,08-25 10:47:00.516  3842  3892 I jxcore-log: Number of passed tests:  80
08-25 10:47:00.516  3842  3892 I jxcore-log: 
08-25 10:47:00.517  3842  3892 I jxcore-log: Number of failed tests:  0
08-25 10:47:00.517  3842  3892 I jxcore-log: 
08-25 10:47:00.517  3842  3892 I jxcore-log: Number of ignored tests:  0
08-25 10:47:00.517  3842  3892 I jxcore-log: 
08-25 10:47:00.517  3842  3892 I jxcore-log: Total duration:  22729
08-25 10:47:00.517  3842  3892 I jxcore-log: 
,08-25 10:47:00.517  3842  3892 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 10:47:00.517  3842  3892 I jxcore-log: 
,08-25 10:47:00.522  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:47:00.522  3842  3892 I jxcore-log: 
08-25 10:47:00.525  3842  3842 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-25 10:47:00.526  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:47:00.526  3842  3892 I jxcore-log: 
,08-25 10:47:00.526  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:47:00.526  3842  3892 I jxcore-log: 
08-25 10:47:00.527  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:47:00.527  3842  3892 I jxcore-log: 
08-25 10:47:00.528  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:47:00.528  3842  3892 I jxcore-log: 
08-25 10:47:00.528  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:47:00.528  3842  3892 I jxcore-log: 
08-25 10:47:00.530  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:47:00.530  3842  3892 I jxcore-log: 
08-25 10:47:00.531  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 10:47:00.531  3842  3892 I jxcore-log: 
,08-25 10:47:00.531  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 10:47:00.531  3842  3892 I jxcore-log: 
08-25 10:47:00.532  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 10:47:00.532  3842  3892 I jxcore-log: 
,08-25 10:47:00.532  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 10:47:00.532  3842  3892 I jxcore-log: 
,08-25 10:47:00.533  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 10:47:00.533  3842  3892 I jxcore-log: 
,08-25 10:47:00.534  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:47:00.534  3842  3892 I jxcore-log: 
08-25 10:47:00.534  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:47:00.534  3842  3892 I jxcore-log: 
,08-25 10:47:00.535  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 10:47:00.535  3842  3892 I jxcore-log: 
,08-25 10:47:00.535  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 10:47:00.535  3842  3892 I jxcore-log: 
08-25 10:47:00.536  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 10:47:00.536  3842  3892 I jxcore-log: 
,08-25 10:47:00.536  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 10:47:00.536  3842  3892 I jxcore-log: 
08-25 10:47:00.536  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 10:47:00.536  3842  3892 I jxcore-log: 
,08-25 10:47:00.537  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 10:47:00.537  3842  3892 I jxcore-log: 
,08-25 10:47:00.537  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 10:47:00.537  3842  3892 I jxcore-log: 
08-25 10:47:00.538  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 10:47:00.538  3842  3892 I jxcore-log: 
,08-25 10:47:00.538  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 10:47:00.538  3842  3892 I jxcore-log: 
08-25 10:47:00.539  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 10:47:00.539  3842  3892 I jxcore-log: 
,08-25 10:47:00.539  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:47:00.539  3842  3892 I jxcore-log: 
,08-25 10:47:00.539  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:47:00.539  3842  3892 I jxcore-log: 
08-25 10:47:00.540  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:47:00.540  3842  3892 I jxcore-log: 
,08-25 10:47:00.540  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:47:00.540  3842  3892 I jxcore-log: 
,08-25 10:47:00.541  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:47:00.541  3842  3892 I jxcore-log: 
,08-25 10:47:00.541  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:47:00.541  3842  3892 I jxcore-log: 
,08-25 10:47:00.543   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-25 10:47:00.545  1864  1864 I Keyboard.Facilitator: onFinishInput()
,08-25 10:47:00.561   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 10:47:00.561   873   893 I Adreno  : Build Date                       : 10/20/15
08-25 10:47:00.561   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 10:47:00.561   873   893 I Adreno  : Local Branch                     : M14
08-25 10:47:00.561   873   893 I Adreno  : Remote Branch                    : 
08-25 10:47:00.561   873   893 I Adreno  : Remote Branch                    : 
08-25 10:47:00.561   873   893 I Adreno  : Reconstruct Branch               : 
,08-25 10:47:00.574   280   360 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (173 us)
,08-25 10:47:00.903  3842  3842 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 10:47:00.910  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 10:47:00.910  3842  3892 I jxcore-log: 
,08-25 10:47:00.951  3842  3842 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 10:47:00.955  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 10:47:00.955  3842  3892 I jxcore-log: 
,08-25 10:47:00.990  3842  3842 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 10:47:00.995  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 10:47:00.995  3842  3892 I jxcore-log: 
,08-25 10:47:01.137  3842  3842 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 10:47:01.137  3842  3842 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-25 10:47:01.172  3842  3842 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@58b8950 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@11d5907, 16908290=android.view.AbsSavedState$1@11d5907}, android:focusedViewId=100}]}]
,08-25 10:47:01.172  3842  3842 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-25 10:47:01.172  3842  3842 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 10:47:01.172  3842  3842 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-25 10:47:01.173   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-25 10:47:01.179   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-25 10:47:01.182   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-25 10:47:01.183   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-25 10:47:01.186   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-25 10:47:01.219  4300  4300 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-25 10:47:01.223  4300  4300 D AndroidRuntime: CheckJNI is OFF
,08-25 10:47:01.271  4300  4300 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-25 10:47:01.313  4300  4300 I Radio-JNI: register_android_hardware_Radio DONE
,08-25 10:47:01.335  4300  4300 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-25 10:47:01.345   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-25 10:47:01.346   873   886 I ActivityManager: Killing 3842:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-25 10:47:01.413   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-25 10:47:01.415   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-25 10:47:01.418   873  1331 D SurfaceControl: Excessive delay in setPowerMode(): 236ms
,08-25 10:47:01.459   873   896 W PackageSettings: Skipping PackageSetting{3c10a21 com.example.hello/10273} due to missing metadata
,08-25 10:47:01.484   873   896 I art     : Starting a blocking GC Explicit
,08-25 10:47:01.503   873  1306 D WifiService: Client connection lost with reason: 4
,08-25 10:47:01.504   873  1689 D GraphicsStats: Buffer count: 2
,08-25 10:47:01.504   873  1382 I WindowState: WIN DEATH: Window{891b920 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 10:47:01.541   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-25 10:47:01.541   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-25 10:47:01.542   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-25 10:47:01.542   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-25 10:47:01.542   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-25 10:47:01.542   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-25 10:47:01.542   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-25 10:47:01.542   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-25 10:47:01.542   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-25 10:47:01.542   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-25 10:47:01.542   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-25 10:47:01.542   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-25 10:47:01.542   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-25 10:47:01.542   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-25 10:47:01.542   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-25 10:47:01.542   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-25 10:47:01.542   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-25 10:47:01.542   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-25 10:47:01.542   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:47:01.542   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:47:01.542   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 10:47:01.542   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-25 10:47:01.543   873   886 I ActivityManager:   Force finishing activity ActivityRecord{3152dc1 u0 com.test.thalitest/.MainActivity t2}
,08-25 10:47:01.557   873   896 I art     : Explicit concurrent mark sweep GC freed 13178(915KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 4.034ms total 72.953ms
,08-25 10:47:01.561   873  1955 W ActivityManager: Spurious death for ProcessRecord{b5c8acd 0:com.test.thalitest/u0a0}, curProc for 3842: null
,08-25 10:47:01.562   873   893 I DreamManagerService: Entering dreamland.
08-25 10:47:01.562   873   893 I PowerManagerService: Dozing...
,08-25 10:47:01.563   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-25 10:47:01.580   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-25 10:47:01.584  4300  4300 I art     : System.exit called, status: 0
,08-25 10:47:01.584  4300  4300 I AndroidRuntime: VM exiting with result code 0.
,08-25 10:47:01.589   377  1314 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-25 10:47:01.589   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-25 10:47:01.589   377  1314 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-25 10:47:01.597   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 10:47:01.606   873   873 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-25 10:47:01.607   873  1305 E native  : do suspend false
,08-25 10:47:01.614   873  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 10:47:01.614  4216  4216 D BluetoothMapAppObserver: onReceive
,08-25 10:47:01.614  4216  4216 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-25 10:47:01.616  1887  2300 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-25 10:47:01.616  3681  3681 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-25 10:47:01.618  1864  1864 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-25 10:47:01.624   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 10:47:01.630  1864  4315 I Keyboard.Facilitator.DecoderInitializer: run()
,08-25 10:47:01.634  1864  4315 I Decoder : createOrResetDecoder
,08-25 10:47:01.665   873  1979 I ActivityManager: Start proc 4318:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-25 10:47:01.670  1505  1505 I ConfigService: onCreate
,08-25 10:47:01.671  1954  1954 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-25 10:47:01.698  1864  4315 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-25 10:47:01.703  4318  4318 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-25 10:47:01.732   873  1522 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3842 uid 10000
,08-25 10:47:01.734  1864  1864 I Keyboard.Facilitator: onFinishInput()
,08-25 10:47:01.736   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-25 10:47:01.741  1864  4315 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-25 10:47:01.742   873  1332 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
,08-25 10:47:01.742   873  1332 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-25 10:47:01.742   873  1332 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
08-25 10:47:01.742   873  1332 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
08-25 10:47:01.743  1864  4315 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-25 10:47:01.743   873  1332 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
08-25 10:47:01.743   873  1332 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
,08-25 10:47:01.743  1864  4315 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-25 10:47:01.743   873  1332 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
08-25 10:47:01.743   873  1332 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
08-25 10:47:01.743   873  1332 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
08-25 10:47:01.743   873  1332 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-25 10:47:01.743   873  1332 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
,08-25 10:47:01.744   873  1332 W System.err: 	... 4 more
08-25 10:47:01.744   873  1332 D skia    : ------- write threw an exception
,08-25 10:47:01.745  1864  4315 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-25 10:47:01.745  1864  4315 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-25 10:47:01.746  1864  4315 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-25 10:47:01.746  1864  4315 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-25 10:47:01.747  1864  4315 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-25 10:47:01.747  1864  4315 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-25 10:47:01.747  1864  4315 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-25 10:47:01.748  1864  4315 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-25 10:47:01.748  1864  4315 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-25 10:47:01.748  1864  4315 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-25 10:47:01.771  1974  2044 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-25 10:47:01.772  4318  4318 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-25 10:47:01.777   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-25 10:47:01.778   873   885 E PackageManager: Failed to write settings, restoring backup
08-25 10:47:01.778   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-25 10:47:01.778   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-25 10:47:01.778   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-25 10:47:01.778   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-25 10:47:01.778   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-25 10:47:01.778   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:47:01.778   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:47:01.778   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 10:47:01.780  4318  4333 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:47:01.780  4318  4333 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: ,	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:47:01.780  4318  4333 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 10:47:01.782   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-25 10:47:01.782   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-25 10:47:01.782   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 10:47:01.782   873   886 E DropBoxManagerService: 	... 13 more
,08-25 10:47:01.785   873  1522 I ActivityManager: Start proc 4335:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-25 10:47:01.785  1974  2044 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-25 10:47:01.785  1974  2044 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1974
08-25 10:47:01.785  1974  2044 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 10:47:01.785  1974  2044 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 10:47:01.785  1974  2044 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-25 10:47:01.785  1974  2044 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-25 10:47:01.785  1974  2044 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 10:47:01.785  1974  2044 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-25 10:47:01.785  1974  2044 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-25 10:47:01.785  1974  2044 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-25 10:47:01.785  1974  2044 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 10:47:01.785  1974  2044 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 10:47:01.785  1974  2044 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:47:01.785  1974  2044 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 10:47:01.788   873  2179 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 10:47:01.788   873  4342 E DropBoxManagerService: Can't write: system_app_crash
08-25 10:47:01.788   873  4342 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-25 10:47:01.788   873  4342 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 10:47:01.788   873  4342 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 10:47:01.788   873  4342 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 10:47:01.788   873  4342 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 10:47:01.788   873  4342 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 10:47:01.788   873  4342 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 10:47:01.788   873  4342 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 10:47:01.788   873  4342 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 10:47:01.788   873  4342 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 10:47:01.788   873  4342 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 10:47:01.788   873  4342 E DropBoxManagerService: 	... 5 more
08-25 10:47:01.794  1942  4341 D NfcService: Discovery configuration equal, not updating.
08-25 10:47:01.796  1974  2044 I Process : Sending signal. PID: 1974 SIG: 9
,08-25 10:47:01.815   873  1382 I ActivityManager: Start proc 4351:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-25 10:47:01.821   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-25 10:47:01.821   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
08-25 10:47:01.822  4318  4350 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-25 10:47:01.827   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 10:47:01.828   873  1305 E native  : do suspend true
,08-25 10:47:01.835   873  1690 W BroadcastQueue: Skipping deliver [foreground] BroadcastRecord{f6aa8ec u-1 android.intent.action.SCREEN_OFF} to ReceiverList{3629355 1974 com.google.android.googlequicksearchbox/10028/u0 remote:e07ce0c}: process crashing
,08-25 10:47:01.863  4351  4351 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-25 10:47:01.880  1505  1505 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-25 10:47:01.880  1505  1505 D AndroidRuntime: Shutting down VM
08-25 10:47:01.881  1505  1505 E AndroidRuntime: FATAL EXCEPTION: main
08-25 10:47:01.881  1505  1505 E AndroidRuntime: Process: com.google.process.gapps, PID: 1505
08-25 10:47:01.881  1505  1505 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-25 10:47:01.881  1505  1505 E AndroidRuntime: 	... 8 more
08-25 10:47:01.883  1505  1505 I Process : Sending signal. PID: 1505 SIG: 9
08-25 10:47:01.884   873  4369 E DropBoxManagerService: Can't write: system_app_crash
08-25 10:47:01.884   873  4369 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-25 10:47:01.884   873  4369 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 10:47:01.884   873  4369 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 10:47:01.884   873  4369 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 10:47:01.884   873  4369 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 10:47:01.884   873  4369 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 10:47:01.884   873  4369 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 10:47:01.884   873  4369 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file ,system)
08-25 10:47:01.884   873  4369 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 10:47:01.884   873  4369 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 10:47:01.884   873  4369 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 10:47:01.884   873  4369 E DropBoxManagerService: 	... 5 more
,08-25 10:47:01.903  1714  4370 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
,08-25 10:47:01.904  1714  4370 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@d7e51be
08-25 10:47:01.904   873  2176 I ActivityManager: Process com.google.process.gapps (pid 1505) early provider death
,08-25 10:47:01.929   873  1306 D WifiService: Client connection lost with reason: 4
,08-25 10:47:01.931   873  2176 I ActivityManager: Process com.google.process.gapps (pid 1505) has died
,08-25 10:47:01.932   873  2176 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
,08-25 10:47:01.932   873  2176 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
,08-25 10:47:01.932   873  2176 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
08-25 10:47:01.932   873  2176 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 30999ms
08-25 10:47:01.934   873  1955 W ActivityManager: Spurious death for ProcessRecord{3ea6ea9 0:com.google.process.gapps/u0a11}, curProc for 1505: null
,08-25 10:47:01.946   873   884 I ActivityManager: Start proc 4372:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-25 10:47:01.951  1714  1714 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-25 10:47:01.957  4318  4333 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-25 10:47:01.963  4318  4350 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:47:01.963  4318  4350 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 10:47:01.964  4318  4350 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-25 10:47:01.964  4318  4350 E AndroidRuntime: Process: android.process.acore, PID: 4318
08-25 10:47:01.964  4318  4350 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:47:01.964  4318  4350 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 10:47:01.966   873  4385 E DropBoxManagerService: Can't write: system_app_crash
08-25 10:47:01.966   873  4385 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-25 10:47:01.966   873  4385 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 10:47:01.966   873  4385 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 10:47:01.966   873  4385 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 10:47:01.966   873  4385 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerServ,ice.java:211)
08-25 10:47:01.966   873  4385 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 10:47:01.966   873  4385 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 10:47:01.966   873  4385 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 10:47:01.966   873  4385 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 10:47:01.966   873  4385 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 10:47:01.966   873  4385 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 10:47:01.966   873  4385 E DropBoxManagerService: 	... 5 more
08-25 10:47:01.967   873  2112 D GraphicsStats: Buffer count: 1
08-25 10:47:01.967   873  1979 I WindowState: WIN DEATH: Window{e5cf53f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-25 10:47:01.974  4318  4350 I Process : Sending signal. PID: 4318 SIG: 9
08-25 10:47:01.977  4372  4372 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-25 10:47:01.984  4372  4372 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-25 10:47:01.986  4372  4372 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 10:47:01.986  4372  4372 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 10:47:01.986  4372  4372 D AndroidRuntime: Shutting down VM
08-25 10:47:01.986  4372  4372 E AndroidRuntime: FATAL EXCEPTION: main
08-25 10:47:01.986  4372  4372 E AndroidRuntime: Process: com.google.process.gapps, PID: 4372
08-25 10:47:01.986  4372  4372 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
,08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 10:47:01.986  4372  4372 E AndroidRuntime: 	... 10 more
,08-25 10:47:01.993   873  2113 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1974) has died
,08-25 10:47:01.993   873  2113 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-25 10:47:01.995   873  2113 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-25 10:47:02.001   873  4387 E DropBoxManagerService: Can't write: system_app_crash
08-25 10:47:02.001   873  4387 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-25 10:47:02.001   873  4387 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 10:47:02.001   873  4387 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 10:47:02.001   873  4387 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 10:47:02.001   873  4387 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 10:47:02.001   873  4387 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 10:47:02.001   873  4387 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 10:47:02.001   873  4387 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 10:47:02.001   873  4387 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 10:47:02.001   873  4387 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 10:47:02.001   873  4387 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 10:47:02.001   873  4387 E DropBoxManagerService: 	... 5 more
,08-25 10:47:02.010   873   886 I ActivityManager: Start proc 4388:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 10:47:02.012  4372  4372 I Process : Sending signal. PID: 4372 SIG: 9
,08-25 10:47:02.012  1714  1714 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-25 10:47:02.012  1714  1714 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-25 10:47:02.021  1714  1714 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-25 10:47:02.022  1714  1714 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-25 10:47:02.026   873   891 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 116)
,08-25 10:47:02.026   873   891 W DisplayManagerService: Failed to notify process 4318 that displays changed, assuming it died.
08-25 10:47:02.026   873   891 W DisplayManagerService: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-25 10:47:02.026   873   891 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 10:47:02.026   873   891 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:503)
08-25 10:47:02.026   873   891 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
08-25 10:47:02.026   873   891 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1166)
08-25 10:47:02.026   873   891 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1004)
08-25 10:47:02.026   873   891 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.-wrap6(DisplayManagerService.java)
08-25 10:47:02.026   873   891 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1099)
08-25 10:47:02.026   873   891 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:47:02.026   873   891 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:47:02.026   873   891 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 10:47:02.026   873   891 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-25 10:47:02.026   873   891 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 116)
08-25 10:47:02.027   873   891 W DisplayManagerService: Failed to notify process 4372 that displays changed, assuming it died.
08-25 10:47:02.027   873   891 W DisplayManagerService: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-25 10:47:02.027   873   891 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 10:47:02.027   873   891 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:503)
08-25 10:47:02.027   873   891 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
08-25 10:47:02.027   873   891 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1166)
08-25 10:47:02.027   873   891 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1004)
08-25 10:47:02.027   873   891 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.-wrap6(DisplayManagerService.java)
08-25 10:47:02.027   873   891 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1099)
08-25 10:47:02.027   873   891 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:47:02.027   873   891 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:47:02.027   873   891 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 10:47:02.027   873   891 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-25 10:47:02.032  1714  4401 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-25 10:47:02.036   873  2176 I ActivityManager: Process android.process.acore (pid 4318) has died
,08-25 10:47:02.036   873  2176 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-25 10:47:02.038   873  2113 I ActivityManager: Process com.google.process.gapps (pid 4372) has died
,08-25 10:47:02.038   873  2113 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{a6acf2e u0 com.google.android.gms/.config.ConfigService}
08-25 10:47:02.038  2021  4399 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-25 10:47:02.038   873  2113 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{9092f26 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
08-25 10:47:02.038   873  2113 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{6e13abc u0 com.google.android.gms/.gcm.GcmService}
08-25 10:47:02.038   873  2113 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{5c17135 u0 com.google.android.gms/.auth.GetToken}
08-25 10:47:02.049   873  2113 I ActivityManager: Start proc 4403:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-25 10:47:02.051  1714  4401 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-25 10:47:02.051  1714  4401 E AndroidRuntime: Process: com.google.android.gms, PID: 1714
08-25 10:47:02.051  1714  4401 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 10:47:02.051  1714  4401 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-25 10:47:02.056  1714  4401 I Process : Sending signal. PID: 1714 SIG: 9
,08-25 10:47:02.059   873  4411 E DropBoxManagerService: Can't write: system_app_crash
08-25 10:47:02.059   873  4411 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
08-25 10:47:02.059   873  4411 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 10:47:02.059   873  4411 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 10:47:02.059   873  4411 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 10:47:02.059   873  4411 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 10:47:02.059   873  4411 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 10:47:02.059   873  4411 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 10:47:02.059   873  4411 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 10:47:02.059   873  4411 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 10:47:02.059   873  4411 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 10:47:02.059   873  4411 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 10:47:02.059   873  4411 E DropBoxManagerService: 	... 5 more
,08-25 10:47:02.070  4388  4388 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 10:47:02.070  4388  4388 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 10:47:02.071  4388  4388 D AndroidRuntime: Shutting down VM
08-25 10:47:02.073   278   278 E lowmemorykiller: Error writing /proc/1714/oom_score_adj; errno=22
08-25 10:47:02.078  4388  4388 E AndroidRuntime: FATAL EXCEPTION: main
08-25 10:47:02.078  4388  4388 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4388
08-25 10:47:02.078  4388  4388 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 10:47:02.078  4388  4388 E AndroidRuntime: 	... 10 more
08-25 10:47:02.080   873  2180 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-25 10:47:02.087  4403  4403 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-25 10:47:02.089   873  4416 E DropBoxManagerService: Can't write: system_app_crash
08-25 10:47:02.089   873  4416 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
08-25 10:47:02.089   873  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 10:47:02.089   873  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 10:47:02.089   873  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 10:47:02.089   873  4416 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 10:47:02.089   873  4416 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 10:47:02.089   873  4416 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 10:47:02.089   873  4416 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 10:47:02.089   873  4416 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 10:47:02.089   873  4416 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 10:47:02.089   873  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 10:47:02.089   873  4416 E DropBoxManagerService: 	... 5 more
08-25 10:47:02.091   873   886 I ActivityManager: Start proc 4417:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
08-25 10:47:02.091  4388  4388 I Process : Sending signal. PID: 4388 SIG: 9
08-25 10:47:02.093  4403  4403 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 10:47:02.095  4403  4403 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 10:47:02.095  4403  4403 D AndroidRuntime: Shutting down VM
08-25 10:47:02.096  4403  4403 E AndroidRuntime: FATAL EXCEPTION: main
08-25 10:47:02.096  4403  4403 E AndroidRuntime: Process: com.google.process.gapps, PID: 4403
08-25 10:47:02.096  4403  4403 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-25 1,0:47:02.096  4403  4403 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 10:47:02.096  4403  4403 E AndroidRuntime: 	... 10 more
08-25 10:47:02.098   873  2178 W ActivityManager: Process com.google.process.gapps has crashed too many times: killing!
08-25 10:47:02.098   873  2178 I ActivityManager: Killing 4403:com.google.process.gapps/u0a11 (adj 1): crash
08-25 10:47:02.100   873  4428 E DropBoxManagerService: Can't write: system_app_crash
08-25 10:47:02.100   873  4428 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop135.tmp: open failed: EROFS (Read-only file system)
08-25 10:47:02.100   873  4428 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 10:47:02.100   873  4428 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 10:47:02.100   873  4428 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 10:47:02.100   873  4428 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 10:47:02.100   873  4428 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 10:47:02.100   873  4428 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 10:47:02.100   873  4428 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 10:47:02.100   873  4428 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 10:47:02.100   873  4428 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 10:47:02.100   873  4428 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 10:47:02.100   873  4428 E DropBoxManagerService: 	... 5 more
08-25 10:47:02.115  2021  4399 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error

```
