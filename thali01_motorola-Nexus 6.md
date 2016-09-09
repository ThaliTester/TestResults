#### Test 84656631b22d743_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-09 19:49:55.303  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:49:55.313  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 19:49:55.315  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 19:49:55.341  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-09 19:49:55.341  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 19:49:55.341  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:49:55.341  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-09 19:49:55.372  3586  3586 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-09 19:49:55.372  3586  3586 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 19:49:55.372  3586  3586 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-09 19:49:55.786   875  2094 D NetlinkSocketObserver: NeighborEvent{elapsedMs=122930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
09-09 19:49:55.951  3839  3839 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 19:49:55.957  3839  3839 D AndroidRuntime: CheckJNI is OFF
09-09 19:49:56.007  3839  3839 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 19:49:56.059  3839  3839 I Radio-JNI: register_android_hardware_Radio DONE
09-09 19:49:56.081  3839  3839 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-09 19:49:56.087   875  2046 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 19:49:56.124  2067  2084 W SearchService: Abort, client detached.
09-09 19:49:56.128  3839  3839 D AndroidRuntime: Shutting down VM
09-09 19:49:56.136  2067  2340 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@20933f5
09-09 19:49:56.137  2067  2067 I HotwordDetector: Closing mic
09-09 19:49:56.136  2067  2351 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-09 19:49:56.145   875  2047 I ActivityManager: Start proc 3848:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-09 19:49:56.188   376  2353 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-09 19:49:56.189   376  2353 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-09 19:49:56.193   376  1282 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-09 19:49:56.196  2067  2345 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-09 19:49:56.196  2067  2350 I MicroRecognitionRnrImpl: Detection finished
09-09 19:49:56.229  3848  3848 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-09 19:49:56.252  3848  3848 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-09 19:49:56.260  3848  3848 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3401-3404)
09-09 19:49:56.260  3848  3848 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 19:49:56.276  3848  3848 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {520c9fc}
09-09 19:49:56.276  3848  3848 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 19:49:56.277  3848  3848 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 19:49:56.284  3848  3848 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 19:49:56.286  3848  3848 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 19:49:56.306  3848  3848 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 19:49:56.317  3848  3848 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 19:49:56.317  3848  3848 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 19:49:56.317  3848  3848 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 19:49:56.317  3848  3848 I Adreno  : Build Date                       : 10/20/15
09-09 19:49:56.317  3848  3848 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 19:49:56.317  3848  3848 I Adreno  : Local Branch                     : M14
09-09 19:49:56.317  3848  3848 I Adreno  : Remote Branch                    : 
09-09 19:49:56.317  3848  3848 I Adreno  : Remote Branch                    : 
09-09 19:49:56.317  3848  3848 I Adreno  : Reconstruct Branch               : 
,09-09 19:49:56.373   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8e8133a:true
,09-09 19:49:56.423  3848  3848 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 19:49:56.442  3848  3848 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-09 19:49:56.450   875  1310 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-09 19:49:56.487  3848  3886 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-09 19:49:56.499  3848  3873 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-09 19:49:56.548  3848  3886 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 19:49:56.648   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +517ms
,09-09 19:49:56.649  1899  1899 I Keyboard.Facilitator: onFinishInput()
,09-09 19:49:56.725  3848  3848 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3848
,09-09 19:49:56.909  3848  3848 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 19:49:56.949   875  1396 I ActivityManager: Killing 3286:com.google.android.gm/u0a78 (adj 15): empty #17
,09-09 19:49:57.012   875  1396 I ActivityManager: Killing 3187:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-09 19:49:57.186  3848  3888 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1714685648
,09-09 19:49:57.193  3848  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 19:49:57.193  3848  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 19:49:57.193  3848  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 19:49:57.193  3848  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 19:49:57.193  3848  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 19:49:57.193  3848  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9a5ac0 added. We now have 1 listener(s)
,09-09 19:49:57.197  3848  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-09 19:49:57.199  3848  3888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 19:49:57.200  3848  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 19:49:57.200  3848  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 19:49:57.210  3848  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 19:49:57.210  3848  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 19:49:57.210  3848  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 19:49:57.210  3848  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61,
09-09 19:49:57.210  3848  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 19:49:57.210  3848  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 19:49:57.210  3848  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 19:49:57.210  3848  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 19:49:57.210  3848  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 19:49:57.210  3848  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 19:49:57.210  3848  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 19:49:57.210  3848  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 19:49:57.210  3848  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 19:49:57.210  3848  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 19:49:57.210  3848  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48b519f added. We now have 1 listener(s)
09-09 19:49:57.210  3848  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 19:49:57.215   875  1311 D WifiService: New client listening to asynchronous messages
,09-09 19:49:57.217  3848  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 19:49:57.217  3848  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 19:49:57.217  3848  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-09 19:49:57.218  3848  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-09 19:49:57.218  3848  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 19:49:57.225  3848  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 19:49:57.225  3848  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-09 19:49:57.234  3848  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-09 19:49:57.234  3848  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 19:49:57.234  3848  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:49:57.234  3848  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:49:57.234  3848  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:49:57.234  3848  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:49:57.234  3848  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:49:57.234  3848  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:49:57.234  3848  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 19:49:57.235  3848  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 19:49:57.235  3848  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 19:49:57.237  3848  3888 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 19:49:57.239  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:49:57.244  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:49:57.283  3848  3848 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 19:49:58.156  3848  3897 W jxcore-log: Initializing JXcore engine
,09-09 19:49:58.156  3848  3897 W jxcore-log: JXcore engine is ready
,09-09 19:49:58.204  3897  3897 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8825 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-09 19:49:58.204  3897  3897 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10878]" dev="sockfs" ino=10878 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-09 19:49:58.204  3897  3897 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-09 19:49:58.204  3897  3897 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27688]" dev="sockfs" ino=27688 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-09 19:49:58.219  3848  3897 W jxcore-log: Starting JXcore engine
,09-09 19:49:58.318  3848  3897 W jxcore-log: Platform android
09-09 19:49:58.318  3848  3897 W jxcore-log: 
,09-09 19:49:58.318  3848  3897 W jxcore-log: Process ARCH arm
09-09 19:49:58.318  3848  3897 W jxcore-log: 
,09-09 19:49:58.543  3848  3897 I jxcore-log: JXcore Cordova bridge is ready!
09-09 19:49:58.543  3848  3897 I jxcore-log: 
,09-09 19:49:58.544  3848  3897 W jxcore-log: JXcore engine is started
,09-09 19:49:58.550  3848  3888 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 19:49:58.556  3848  3848 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 19:50:01.439  3079  3907 V KeepSync: Connecting to GoogleApiClient
,09-09 19:50:01.440   875  1692 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 19:50:01.488  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:50:01.491  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:50:01.525  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 19:50:01.526  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-09 19:50:01.526  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 19:50:01.526  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:50:01.552  1715  3908 V BaseAuthAsyncOperation: access token request failed
,09-09 19:50:01.553  3079  3907 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 19:50:01.629  1504  1956 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 19:50:01.629  1504  1956 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 19:50:01.629  1504  1956 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 19:50:01.630  1504  1956 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:50:01.655  3079  3907 E KeepSync: IOException
09-09 19:50:01.655  3079  3907 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 19:50:01.655  3079  3907 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 19:50:01.655  3079  3907 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 19:50:01.655  3079  3907 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 19:50:01.655  3079  3907 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 19:50:01.655  3079  3907 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 19:50:01.655  3079  3907 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 19:50:01.655  3079  3907 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 19:50:01.655  3079  3907 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 19:50:01.655  3079  3907 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 19:50:01.655  3079  3907 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 19:50:01.655  3079  3907 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 19:50:01.655  3079  3907 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 19:50:01.655  3079  3907 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 19:50:01.655  3079  3907 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 19:50:01.655  3079  3907 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 19:50:01.655  3079  3907 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 19:50:01.655  3079  3907 E KeepSync: 	... 10 more
,09-09 19:50:01.656  3079  3907 W KeepSync: Sync result 2
,09-09 19:50:01.666   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 128497, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 19:50:02.079   875  2094 D NetlinkSocketObserver: NeighborEvent{elapsedMs=129223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 19:50:02.145  1715  3908 I art     : Waiting for a blocking GC DisableMovingGc
,09-09 19:50:02.163  1715  3908 I art     : WaitForGcToComplete blocked for 18.819ms for cause DisableMovingGc
,09-09 19:50:02.164  1715  3908 I art     : Starting a blocking GC DisableMovingGc
,09-09 19:50:15.570  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:50:15.583  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:50:15.587  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:50:15.629  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 19:50:15.629  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 19:50:15.630  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 19:50:15.630  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:50:15.661  3586  3586 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 19:50:15.662  3586  3586 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 19:50:15.662  3586  3586 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-09 19:50:16.341  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 19:50:16.341  3848  3897 I jxcore-log: 
,09-09 19:50:16.344  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 19:50:16.344  3848  3897 I jxcore-log: 
,09-09 19:50:16.355  3848  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 19:50:16.355  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:16.355  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:16.355  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:16.355  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:50:16.355  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:50:16.355  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:50:16.355  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 19:50:16.366  3848  3897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 19:50:16.372  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 19:50:16.372  3848  3897 I jxcore-log: 
,09-09 19:50:16.377  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 19:50:16.377  3848  3897 I jxcore-log: 
,09-09 19:50:16.414  3848  3897 I jxcore-log: Running unit tests
09-09 19:50:16.414  3848  3897 I jxcore-log: 
,09-09 19:50:16.415  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 19:50:16.415  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@931cb3b added. We now have 2 listener(s)
09-09 19:50:16.416  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 19:50:16.417  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 19:50:16.417  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 19:50:16.417  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 19:50:16.417  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1b258 added. We now have 2 listener(s)
09-09 19:50:16.417  3848  3897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 19:50:16.417  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 19:50:16.424  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 19:50:16.433  3848  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 19:50:16.433  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:16.433  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:16.433  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:16.433  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:50:16.433  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:50:16.433  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:50:16.433  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 19:50:16.437  3848  3897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 19:50:16.437  3848  3897 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 19:50:16.437  3848  3897 D executeNativeTests: Running unit tests
,09-09 19:50:16.452  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:50:16.454  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:50:16.513  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 19:50:16.513  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 added. We now have 3 listener(s)
09-09 19:50:16.514  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 19:50:16.514  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 19:50:16.514  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 19:50:16.514  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 19:50:16.514  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 added. We now have 3 listener(s)
09-09 19:50:16.514  3848  3897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 19:50:16.516  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 19:50:16.523  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 19:50:16.535  3848  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 19:50:16.535  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:16.535  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:16.535  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:16.535  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:50:16.535  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:50:16.535  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:50:16.535  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 19:50:16.540  3848  3897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 19:50:16.541  3848  3897 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 19:50:16.545  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 19:50:16.547  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
,09-09 19:50:16.547  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 19:50:16.547  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 19:50:16.549  3848  3897 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-09 19:50:16.550  3848  3897 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-09 19:50:16.550  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:50:16.550  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 19:50:16.550  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 19:50:16.550  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 19:50:16.550  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 19:50:16.551  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 19:50:16.551  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:16.551  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 19:50:16.552  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:16.552  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:50:16.552  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:16.552  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 19:50:16.552  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 19:50:16.552  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 removed from the list
09-09 19:50:16.552  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:16.552  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 removed from the list
09-09 19:50:16.552  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:16.552  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:16.553  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 19:50:16.553  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:16.554  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:50:16.554  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:50:16.554  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:16.554  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:16.556  3848  3897 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-09 19:50:16.556  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 19:50:16.557  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:16.557  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 19:50:16.557  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:16.557  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:16.557  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:16.557  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
,09-09 19:50:16.557  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:16.557  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:16.557  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:16.557  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:16.557  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:16.557  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:16.557  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:16.559  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:50:16.559  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 19:50:16.559  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:16.559  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:16.567  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 19:50:16.567  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 19:50:16.567  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 19:50:16.567  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 19:50:16.568  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-09 19:50:16.568  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 19:50:16.568  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 19:50:16.568  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 19:50:16.568  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 19:50:16.568  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 19:50:16.569  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 19:50:16.569  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 19:50:16.569  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 19:50:16.569  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-09 19:50:16.569  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 19:50:16.569  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 19:50:16.569  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 19:50:16.569  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 19:50:16.569  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 19:50:16.569  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-09 19:50:16.569  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 19:50:16.569  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 19:50:16.570  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 19:50:16.570  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 19:50:16.570  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 19:50:16.570  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 19:50:16.570  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-09 19:50:16.570  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 19:50:16.570  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 19:50:16.570  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 19:50:16.571  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 19:50:16.571  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 19:50:16.571  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:16.571  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 19:50:16.571  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 19:50:16.571  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:16.571  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:16.571  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:16.571  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:16.571  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:16.571  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:16.571  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:16.571  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:16.571  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:16.571  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:50:16.576  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:50:16.576  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:50:16.576  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:16.576  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:16.577  3848  3897 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 19:50:16.581  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 19:50:16.588  3848  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 19:50:16.588  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:16.588  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:16.588  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:16.588  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:50:16.588  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:50:16.588  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:50:16.588  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 19:50:16.590  3848  3897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 19:50:16.591  3848  3897 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 19:50:16.591  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 19:50:16.591  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 19:50:16.591  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 19:50:16.591  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 19:50:16.592  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 19:50:16.594  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:50:16.598  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:50:16.598  3848  3897 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 19:50:16.598  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 19:50:16.606  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 19:50:16.609  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 19:50:16.609  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 19:50:16.612  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-09 19:50:16.617  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-09 19:50:16.617  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 19:50:16.617  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 19:50:16.618  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 19:50:16.619  3848  3897 D BluetoothAdapter: STATE_ON
,09-09 19:50:16.624  2720  2732 D BtGatt.GattService: registerClient() - UUID=0d266aaa-a12e-4ff7-addb-aa72d959a9b0
,09-09 19:50:16.625  2720  2772 D BtGatt.GattService: onClientRegistered() - UUID=0d266aaa-a12e-4ff7-addb-aa72d959a9b0, clientIf=5
,09-09 19:50:16.626  3848  3859 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 19:50:16.628  2720  2927 D BtGatt.GattService: start scan with filters
,09-09 19:50:16.636  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 19:50:16.637  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 19:50:16.637  2720  2777 D BtGatt.ScanManager: handling starting scan
,09-09 19:50:16.637  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 19:50:16.637  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 19:50:16.641  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 19:50:16.641  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 19:50:16.642  3848  3848 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 19:50:16.642  2720  2777 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
,09-09 19:50:16.644  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 19:50:16.647  3848  3897 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 19:50:16.651  2720  2772 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 19:50:16.651  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:50:16.653  2720  2777 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 19:50:16.662  2720  2772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 19:50:16.662  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:50:16.663  2720  2777 D BtGatt.ScanManager: Starting BLE batch scan
09-09 19:50:16.664  2720  2777 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 19:50:16.682  2720  2772 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 19:50:16.682  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:50:16.689  2720  2772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 19:50:16.689  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:50:17.143  3848  3848 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 19:50:17.144  3848  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 19:50:17.144  3848  3848 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 19:50:18.198  2720  2720 D BtGatt.ScanManager: awakened up at time 145342
,09-09 19:50:18.203  2720  2777 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 19:50:18.250  2720  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-09 19:50:18.250  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 19:50:18.251  2720  2772 D BtGatt.GattService: current time is 145395668815
09-09 19:50:18.251  2720  2772 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -90, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -85, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -61, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -79, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -66, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
09-09 19:50:18.253  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-09 19:50:18.254  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-09 19:50:18.255  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,09-09 19:50:18.255  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-09 19:50:18.255  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,09-09 19:50:19.755  2720  2720 D BtGatt.ScanManager: awakened up at time 146899
,09-09 19:50:19.758  2720  2777 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 19:50:19.768  2720  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 19:50:19.768  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:50:21.270  2720  2720 D BtGatt.ScanManager: awakened up at time 148415
,09-09 19:50:21.273  2720  2777 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 19:50:21.303  2720  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-09 19:50:21.303  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 19:50:21.303  2720  2772 D BtGatt.GattService: current time is 148448388546
09-09 19:50:21.304  2720  2772 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -95, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -85, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-09 19:50:21.305  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-09 19:50:21.306  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 19:50:21.657  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 19:50:21.658  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 19:50:21.658  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 19:50:21.659  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 19:50:21.659  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 19:50:21.659  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 19:50:21.660  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 19:50:21.660  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 19:50:21.660  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 19:50:21.662  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 19:50:21.662  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 19:50:21.665  3848  3897 D BluetoothAdapter: STATE_ON
09-09 19:50:21.668  2720  2732 D BtGatt.GattService: stopScan() - queue size =1
09-09 19:50:21.672  2720  2927 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 19:50:21.674  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 19:50:21.674  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 19:50:21.675  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 19:50:21.675  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 19:50:21.675  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 19:50:21.680  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 19:50:21.682  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 19:50:21.683  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 19:50:21.684  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 19:50:21.686  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 19:50:21.688  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:21.688  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 19:50:21.688  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 19:50:21.689  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:21.689  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:21.689  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:21.689  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:21.689  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:21.689  3848  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 19:50:21.689  3848  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 19:50:21.690  3848  3848 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 19:50:21.692  2720  2772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 19:50:21.692  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 19:50:21.693  2720  2777 D BtGatt.ScanManager: stopping BLe Batch
,09-09 19:50:21.706  2720  2772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 19:50:21.707  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 19:50:21.707  2720  2777 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 19:50:21.734  2720  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
09-09 19:50:21.734  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:50:21.734  2720  2772 D BtGatt.GattService: current time is 148879119995
09-09 19:50:21.735  2720  2772 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -86, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -80, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-09 19:50:21.735  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-09 19:50:21.736  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-09 19:50:22.191  3848  3848 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 19:50:25.740   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-09 19:50:25.751  1899  1899 I Keyboard.Facilitator: onFinishInput()
,09-09 19:50:25.764   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 19:50:25.764   875   895 I Adreno  : Build Date                       : 10/20/15
09-09 19:50:25.764   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 19:50:25.764   875   895 I Adreno  : Local Branch                     : M14
09-09 19:50:25.764   875   895 I Adreno  : Remote Branch                    : 
09-09 19:50:25.764   875   895 I Adreno  : Remote Branch                    : 
09-09 19:50:25.764   875   895 I Adreno  : Reconstruct Branch               : 
,09-09 19:50:25.787   281   360 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (180 us)
,09-09 19:50:26.399  3848  3848 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 19:50:26.399  3848  3848 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 19:50:26.432   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-09 19:50:26.436  3848  3848 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5211732 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@4f09959, 16908290=android.view.AbsSavedState$1@4f09959}, android:focusedViewId=100}]}]
,09-09 19:50:26.436  3848  3848 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-09 19:50:26.436  3848  3848 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 19:50:26.436  3848  3848 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-09 19:50:26.439   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-09 19:50:26.444   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,09-09 19:50:26.444   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
09-09 19:50:26.444   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-09 19:50:26.482   875   884 I art     : Background partial concurrent mark sweep GC freed 42424(2MB) AllocSpace objects, 14(364KB) LOS objects, 33% free, 29MB/43MB, paused 1.792ms total 108.909ms
,09-09 19:50:26.681   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-09 19:50:26.685   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
09-09 19:50:26.691  3848  3897 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 19:50:26.692   875  1337 D SurfaceControl: Excessive delay in setPowerMode(): 248ms
,09-09 19:50:26.698  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 19:50:26.698   875   895 I DreamManagerService: Entering dreamland.
,09-09 19:50:26.699   875   895 I PowerManagerService: Dozing...
,09-09 19:50:26.700   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-09 19:50:26.714  3848  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 19:50:26.714  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:26.714  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:26.714  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:26.714  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:50:26.714  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:50:26.714  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:50:26.714  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 19:50:26.720  3848  3897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 19:50:26.720  3848  3897 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 19:50:26.721  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 19:50:26.721  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 19:50:26.722  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 19:50:26.722  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 19:50:26.722  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 19:50:26.726  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:50:26.728  3848  3897 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 19:50:26.728  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 19:50:26.731  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:50:26.735  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 19:50:26.736  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 19:50:26.737  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 19:50:26.744  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 19:50:26.744  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 19:50:26.744  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 19:50:26.745  3848  3897 D BluetoothAdapter: STATE_ON
,09-09 19:50:26.753  2720  2927 D BtGatt.GattService: registerClient() - UUID=c38d2b04-e4f5-4ec8-9d23-227660558f30
,09-09 19:50:26.755  2720  2772 D BtGatt.GattService: onClientRegistered() - UUID=c38d2b04-e4f5-4ec8-9d23-227660558f30, clientIf=5
,09-09 19:50:26.755  3848  3860 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 19:50:26.755  2720  2732 D BtGatt.GattService: start scan with filters
09-09 19:50:26.756   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-09 19:50:26.756   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-09 19:50:26.759  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 19:50:26.759  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 19:50:26.759  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 19:50:26.759  2720  2777 D BtGatt.ScanManager: handling starting scan
09-09 19:50:26.759  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 19:50:26.766   875  1310 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 19:50:26.768  2720  2772 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 19:50:26.768  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 19:50:26.768  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 19:50:26.768  2720  2777 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 19:50:26.768  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 19:50:26.768  3848  3848 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 19:50:26.775  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 19:50:26.775  2720  2772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 19:50:26.775  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:50:26.775  2720  2777 D BtGatt.ScanManager: Starting BLE batch scan
09-09 19:50:26.775  2720  2777 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 19:50:26.781   875  1310 E native  : do suspend false
,09-09 19:50:26.782  1974  3919 D NfcService: Discovery configuration equal, not updating.
09-09 19:50:26.783  3848  3897 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 19:50:26.785  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 19:50:26.786  3848  3897 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 19:50:26.786  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:26.786  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 19:50:26.786  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:26.786  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 19:50:26.786  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 19:50:26.786  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 19:50:26.786  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 19:50:26.786  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 19:50:26.787  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 19:50:26.787  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 19:50:26.788  3848  3897 D BluetoothAdapter: STATE_ON
09-09 19:50:26.789  2720  2732 D BtGatt.GattService: stopScan() - queue size =1
,09-09 19:50:26.790  2720  2772 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 19:50:26.790  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:50:26.792  2720  2735 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 19:50:26.792  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 19:50:26.793  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 19:50:26.793  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 19:50:26.793  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 19:50:26.793  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 19:50:26.794  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 19:50:26.794  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 19:50:26.794  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 19:50:26.794  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 19:50:26.795  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 19:50:26.796  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:26.796  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:26.796  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 19:50:26.796  3848  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 19:50:26.796  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:26.796  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:26.796  3848  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 19:50:26.796  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:26.796  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:26.796  3848  3848 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 19:50:26.796  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:26.797  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 19:50:26.797  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:26.798  2720  2772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 19:50:26.798  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 19:50:26.798  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 19:50:26.798  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:50:26.798  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:26.798  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
,09-09 19:50:26.799  3848  3897 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 19:50:26.802  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 19:50:26.804   875  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 19:50:26.811  2720  2772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 19:50:26.811  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 19:50:26.811  3848  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 19:50:26.811  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:26.811  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:26.811  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:26.811  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:50:26.811  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:50:26.811  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:50:26.811  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 19:50:26.811  2720  2777 D BtGatt.ScanManager: stopping BLe Batch
,09-09 19:50:26.817  3848  3897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 19:50:26.818  3848  3897 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 19:50:26.819  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 19:50:26.819  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 19:50:26.819  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 19:50:26.819  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 19:50:26.819  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 19:50:26.821  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:50:26.822  2720  2772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 19:50:26.822  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 19:50:26.822  2720  2777 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 19:50:26.824   875  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 19:50:26.826  3848  3897 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 19:50:26.826  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 19:50:26.826  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:50:26.827  2720  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 19:50:26.827  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:50:26.829   875  1310 E native  : do suspend true
,09-09 19:50:26.830  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 19:50:26.831  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 19:50:26.831  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 19:50:26.836  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 19:50:26.836  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 19:50:26.836  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 19:50:26.837  3848  3897 D BluetoothAdapter: STATE_ON
,09-09 19:50:26.840  2720  2927 D BtGatt.GattService: registerClient() - UUID=bc400d42-0899-41df-8542-a8b68f40aaa7
,09-09 19:50:26.840  2720  2772 D BtGatt.GattService: onClientRegistered() - UUID=bc400d42-0899-41df-8542-a8b68f40aaa7, clientIf=5
09-09 19:50:26.841  3848  3859 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 19:50:26.841  2720  2732 D BtGatt.GattService: start scan with filters
,09-09 19:50:26.844  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 19:50:26.844  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 19:50:26.844  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 19:50:26.845  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 19:50:26.845  2720  2777 D BtGatt.ScanManager: handling starting scan
,09-09 19:50:26.848  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 19:50:26.848  3848  3848 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 19:50:26.849  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 19:50:26.850  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 19:50:26.851  2720  2772 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 19:50:26.852  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 19:50:26.852  2720  2777 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 19:50:26.853  3848  3897 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 19:50:26.857  2720  2772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 19:50:26.857  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:50:26.858  2720  2777 D BtGatt.ScanManager: Starting BLE batch scan
09-09 19:50:26.858  2720  2777 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 19:50:26.870  2720  2772 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 19:50:26.870  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:50:26.878  2720  2772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 19:50:26.878  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:50:26.889   376  1283 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-09 19:50:26.889   376  1283 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-09 19:50:27.272   875  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-09 19:50:27.350  3848  3848 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 19:50:27.350  3848  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 19:50:27.351  3848  3848 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 19:50:28.386  2720  2720 D BtGatt.ScanManager: awakened up at time 155530
,09-09 19:50:28.389  2720  2777 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 19:50:28.441  2720  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-09 19:50:28.442  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:50:28.443  2720  2772 D BtGatt.GattService: current time is 155587516825
,09-09 19:50:28.444  2720  2772 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -85, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -83, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -79, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -85, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -79, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -90, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 19:50:28.445  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 19:50:28.447  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-09 19:50:28.448  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-09 19:50:28.449  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-09 19:50:28.450  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-09 19:50:28.451  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-09 19:50:29.944  2720  2720 D BtGatt.ScanManager: awakened up at time 157089
,09-09 19:50:29.950  2720  2777 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 19:50:29.959  2720  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 19:50:29.959  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:50:31.461  2720  2720 D BtGatt.ScanManager: awakened up at time 158605
,09-09 19:50:31.464  2720  2777 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 19:50:31.501  2720  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,09-09 19:50:31.502  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:50:31.502  2720  2772 D BtGatt.GattService: current time is 158647218291
09-09 19:50:31.503  2720  2772 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -85, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -97, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -84, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 19:50:31.504  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-09 19:50:31.505  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-09 19:50:31.506  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 19:50:31.853  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 19:50:31.854  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:31.854  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 19:50:31.854  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:31.854  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 19:50:31.854  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 19:50:31.854  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 19:50:31.854  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 19:50:31.854  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 19:50:31.855  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 19:50:31.855  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 19:50:31.858  3848  3897 D BluetoothAdapter: STATE_ON
,09-09 19:50:31.859  2720  2735 D BtGatt.GattService: stopScan() - queue size =1
,09-09 19:50:31.860  2720  2927 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 19:50:31.860  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 19:50:31.861  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 19:50:31.861  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 19:50:31.861  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-09 19:50:31.861  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 19:50:31.862  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 19:50:31.862  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 19:50:31.862  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 19:50:31.862  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 19:50:31.863  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 19:50:31.864  3848  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 19:50:31.865  3848  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 19:50:31.865  3848  3848 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 19:50:31.868  2720  2772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 19:50:31.868  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 19:50:31.868  2720  2777 D BtGatt.ScanManager: stopping BLe Batch
,09-09 19:50:31.876  2720  2772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 19:50:31.876  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 19:50:31.877  2720  2777 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 19:50:31.898  2720  2772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-09 19:50:31.898  2720  2772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 19:50:31.898  2720  2772 D BtGatt.GattService: current time is 159043032570
09-09 19:50:31.899  2720  2772 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -86, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -86, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -80, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -86, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -96, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -84, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-09 19:50:31.899  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-09 19:50:31.899  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-09 19:50:31.899  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-09 19:50:31.900  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-09 19:50:31.900  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-09 19:50:31.900  2720  2772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 19:50:31.908  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:50:31.910  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:50:31.944  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 19:50:31.944  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 19:50:31.945  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:50:31.945  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:50:31.971  3029  3925 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 19:50:31.971  3029  3925 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at jdm.a(PG:82)
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at jcs.o(PG:406)
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at jcn.a(PG:1379)
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at jcs.i(PG:143)
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at blb.a(PG:3937)
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at czp.a(PG:18188)
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at czp.a(PG:9081)
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at czq.run(PG:1686)
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 19:50:31.971  3029  3925 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at jdj.a(PG:4091)
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at jdj.a(PG:1125)
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at jdm.a(PG:77)
09-09 19:50:31.971  3029  3925 E HttpOperation: 	... 12 more
09-09 19:50:31.971  3029  3925 E HttpOperation: Caused by: faj: BadAuthentication
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at fal.a(PG:38)
09-09 19:50:31.971  3029  3925 E HttpOperation: 	at jdj.a(PG:4089)
09-09 19:50:31.971  3029  3925 E HttpOperation: 	... 14 more
,09-09 19:50:32.049  1504  2257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 19:50:32.049  1504  2257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 19:50:32.049  1504  2257 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:50:32.050  1504  2257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:50:32.086  3029  3925 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 19:50:32.086  3029  3925 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at jdm.a(PG:82)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at jcs.o(PG:406)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at jcn.a(PG:1379)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at jcs.i(PG:143)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at hec.a(PG:42)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at hee.a(PG:102)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at czr.a(PG:65)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at kka.a(PG:108)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at czp.a(PG:19176)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at czp.a(PG:9081)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at czq.run(PG:1686)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 19:50:32.086  3029  3925 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at jdj.a(PG:4091)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at jdj.a(PG:1125)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at jdm.a(PG:77)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	... 15 more
09-09 19:50:32.086  3029  3925 E HttpOperation: Caused by: faj: BadAuthentication
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at fal.a(PG:38)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	at jdj.a(PG:4089)
09-09 19:50:32.086  3029  3925 E HttpOperation: 	... 17 more
,09-09 19:50:32.087  3029  3925 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 19:50:32.087  3029  3925 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at hec.a(PG:42)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at hee.a(PG:102)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at czr.a(PG:65)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at kka.a(PG:108)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	... 15 more
09-09 19:50:32.087  3029  3925 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at fal.a(PG:38)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 19:50:32.087  3029  3925 E ExperimentLoader: 	... 17 more
,09-09 19:50:32.139  1865  2653 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 19:50:32.246   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 130136, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-09 19:50:32.366  3848  3848 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 19:50:32.366  3848  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:32.366  3848  3848 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 19:50:35.822  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:50:36.071  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:50:36.080  1504  3929 I VacuumService: Vacuum at: now=1473443436079 tag=VacuumService
,09-09 19:50:36.128  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 19:50:36.128  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 19:50:36.128  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:50:36.129  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:50:36.148  3586  3586 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 19:50:36.148  3586  3586 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 19:50:36.148  3586  3586 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-09 19:50:36.219  1504  3930 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-09 19:50:36.221  1504  3930 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 19:50:36.248  1504  3930 W Uploader:  no longer exists, so no auth token.
,09-09 19:50:36.466   875  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-09 19:50:36.866  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 19:50:36.866  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:36.867  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 19:50:36.868  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 19:50:36.868  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.868  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 19:50:36.868  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
,09-09 19:50:36.869  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.869  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
,09-09 19:50:36.869  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 19:50:36.869  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:50:36.871  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 19:50:36.871  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:50:36.874  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 19:50:36.874  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 19:50:36.874  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.875  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.876  3848  3897 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-09 19:50:36.878  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 19:50:36.878  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:36.879  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 19:50:36.879  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 19:50:36.880  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 19:50:36.880  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.880  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
,09-09 19:50:36.880  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 19:50:36.881  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.881  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:36.881  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.881  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.882  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.882  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.884  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:50:36.885  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:50:36.885  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.886  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.887  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 19:50:36.887  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 19:50:36.887  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:36.887  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 19:50:36.887  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:36.888  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.888  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.888  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:36.888  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.888  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.888  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:36.888  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.888  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.888  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.888  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.890  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:50:36.890  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:50:36.890  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.890  3848  3897 E org.thaliproject.p2p.btconnector,lib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.890  3848  3897 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 19:50:36.891  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 19:50:36.891  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:36.891  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 19:50:36.891  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:36.891  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.891  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.891  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:36.891  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.891  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.892  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:36.892  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.892  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.892  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.892  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.893  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:50:36.893  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:50:36.893  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.893  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.894  3848  3897 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 19:50:36.894  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 19:50:36.894  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:36.894  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 19:50:36.895  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:36.895  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.895  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.895  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:36.895  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.895  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.895  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:36.895  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.895  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.895  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.895  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.896  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:50:36.896  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:50:36.897  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.897  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.897  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 19:50:36.899  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 19:50:36.899  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 19:50:36.899  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 19:50:36.900  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 19:50:36.900  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 19:50:36.900  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 19:50:36.901  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 19:50:36.901  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 19:50:36.901  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 19:50:36.901  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:36.902  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 19:50:36.902  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:36.902  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.903  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.903  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:36.903  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.903  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.904  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:36.904  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.904  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.904  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.904  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.906  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:50:36.906  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:50:36.906  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.906  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.907  3848  3897 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 19:50:36.907  3848  3897 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 19:50:36.908  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 19:50:36.911  3848  3897 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 19:50:36.912  3848  3897 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 19:50:36.912  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 19:50:36.912  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 19:50:36.912  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 19:50:36.912  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 19:50:36.912  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 19:50:36.912  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 19:50:36.912  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 19:50:36.912  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 19:50:36.912  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 19:50:36.912  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 19:50:36.912  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 19:50:36.912  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 19:50:36.913  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 19:50:36.913  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 19:50:36.913  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 19:50:36.913  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 19:50:36.913  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 19:50:36.913  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 19:50:36.913  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 19:50:36.913  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 19:50:36.913  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 19:50:36.913  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 19:50:36.913  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 19:50:36.913  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 19:50:36.913  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 19:50:36.913  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 19:50:36.914  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 19:50:36.914  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 19:50:36.914  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 19:50:36.914  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 19:50:36.914  3848  3897 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 19:50:36.914  3848  3897 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 19:50:36.914  3848  3897 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 19:50:36.915  3848  3897 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 19:50:36.915  3848  3897 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 19:50:36.915  3848  3897 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 19:50:36.915  3848  3897 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 19:50:36.915  3848  3897 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 19:50:36.915  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 19:50:36.917  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 19:50:36.918  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 19:50:36.918  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 19:50:36.919  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 19:50:36.919  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 19:50:36.919  3848  3897 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 19:50:36.919  3848  3897 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 19:50:36.919  3848  3897 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 19:50:36.920  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 19:50:36.920  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:36.920  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 19:50:36.921  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:36.921  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.921  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.921  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 19:50:36.923  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:36.923  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.923  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.923  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:36.923  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.923  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.923  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.923  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.924  3848  3938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
09-09 19:50:36.925  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:50:36.926  3848  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
09-09 19:50:36.927  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:50:36.927  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.927  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.928  3848  3897 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 19:50:36.928  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 19:50:36.928  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:36.929  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 19:50:36.929  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:36.929  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.929  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.929  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:36.929  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.929  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.929  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:36.929  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.929  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.929  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.930  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.932  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:50:36.932  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:50:36.932  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.932  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.933  3848  3897 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 19:50:36.933  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 19:50:36.933  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:36.933  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 19:50:36.933  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:36.933  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.934  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.934  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:36.934  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.934  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.934  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:36.934  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.934  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.934  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.934  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.934  3848  3938 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 19:50:36.938  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:50:36.938  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:50:36.938  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.938  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.939  3848  3897 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 19:50:36.939  3848  3897 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 19:50:36.939  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 19:50:36.939  3848  3897 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 19:50:36.939  3848  3897 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 19:50:36.939  3848  3897 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 19:50:36.939  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 19:50:36.939  3848  3897 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 19:50:36.939  3848  3897 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 19:50:36.939  3848  3897 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 19:50:36.940  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 19:50:36.940  3848  3897 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 19:50:36.940  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 19:50:36.940  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:36.940  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 19:50:36.940  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:36.940  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.940  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.940  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:36.940  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 19:50:36.940  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.940  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:36.940  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.941  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.941  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.941  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.941  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:50:36.941  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:50:36.941  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.941  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.942  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:36.942  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.942  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:36.942  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:36.942  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:36.942  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:36.942  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:36.942  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:36.943  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:50:37.605  1504  3930 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-09 19:50:37.606  1504  3930 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-09 19:50:37.606  1504  3930 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 19:50:37.606  1504  3930 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:50:37.624  1504  3930 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 19:50:37.624  1504  3930 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 19:50:37.624  1504  3930 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 19:50:37.624  1504  3930 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 19:50:37.624  1504  3930 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 19:50:37.624  1504  3930 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 19:50:37.624  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 19:50:37.624  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 19:50:37.624  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 19:50:37.624  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 19:50:37.624  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 19:50:37.624  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 19:50:37.624  1504  3930 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 19:50:41.943  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 19:50:41.944  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:41.944  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:41.944  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 19:50:41.944  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:50:41.946  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:41.946  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 19:50:41.947  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 19:50:41.947  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 19:50:41.948  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:41.948  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 19:50:41.948  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:41.949  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:41.949  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 19:50:41.949  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:41.949  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:41.950  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 19:50:41.950  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:41.950  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 19:50:41.951  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:41.953  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:50:41.953  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 19:50:41.953  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:41.954  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:41.958  3848  3897 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 19:50:41.959  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 19:50:41.960  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 19:50:41.962  3848  3897 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-09 19:50:41.963  3848  3897 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 19:50:41.964  3848  3848 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 19:50:41.964  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 19:50:41.964  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 19:50:41.965  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 19:50:41.966  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 19:50:41.966  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 19:50:41.966  3848  3946 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 19:50:41.966  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 19:50:41.967  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:50:41.967  3848  3897 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 19:50:41.967  3848  3848 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 19:50:41.968  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:41.968  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:41.969  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 19:50:41.969  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 19:50:41.969  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 19:50:41.969  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:41.969  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:50:41.971  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 19:50:41.971  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:41.971  3848  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 19:50:41.971  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 19:50:41.971  3848  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 19:50:41.971  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 19:50:41.971  3848  3848 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 19:50:41.971  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 19:50:41.972  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:41.972  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:41.972  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:41.972  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:41.972  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:41.972  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:41.972  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 19:50:41.973  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:41.973  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:41.973  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:41.973  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:41.973  3848  3946 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 19:50:41.973  3848  3946 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 19:50:41.974  3848  3946 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 19:50:41.974  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:50:41.974  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:50:41.974  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:41.975  3848  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 19:50:41.975  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
,09-09 19:50:41.978  3848  3897 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-09 19:50:41.978  3848  3897 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-09 19:50:41.978  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 19:50:41.979  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 19:50:41.979  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 19:50:41.979  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 19:50:41.980  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:41.980  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 19:50:41.980  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:41.980  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:41.980  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:41.980  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:41.980  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:41.980  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:41.980  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:41.980  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 19:50:41.980  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:41.981  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:41.981  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:50:41.982  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:50:41.982  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:50:41.982  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:41.983  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
,09-09 19:50:41.989  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 19:50:41.989  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 19:50:41.989  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 19:50:41.989  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:41.990  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:41.990  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:41.990  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:41.990  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:41.990  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
,09-09 19:50:41.990  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:41.990  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:41.990  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:41.990  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:41.991  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:41.992  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:50:41.992  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:50:41.992  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:41.992  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
,09-09 19:50:41.993  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 19:50:41.994  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 19:50:41.994  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 19:50:41.994  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:50:41.994  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:41.994  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:41.994  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc1e746 not in the list
09-09 19:50:41.994  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 19:50:41.994  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
09-09 19:50:41.994  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:41.995  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:41.995  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:41.995  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:41.995  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:50:41.996  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:50:41.996  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:50:41.996  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:41.996  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62afd07 not in the list
,09-09 19:50:41.998  3848  3897 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 19:50:41.998  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 19:50:41.998  3848  3897 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 19:50:41.998  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-09 19:50:41.998  3848  3897 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 19:50:41.998  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-09 19:50:42.001  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-09 19:50:42.001  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 19:50:42.002  3848  3897 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 19:50:42.002  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 19:50:42.003  3848  3897 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-09 19:50:42.003  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 19:50:42.003  3848  3897 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 19:50:42.003  3848  3897 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 19:50:42.003  3848  3897 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 19:50:42.004  3848  3897 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-09 19:50:42.004  3848  3897 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 19:50:42.004  3848  3897 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 19:50:42.004  3848  3897 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 19:50:42.005  3848  3897 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-09 19:50:42.006  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 19:50:42.006  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@78adf6 added. We now have 3 listener(s)
09-09 19:50:42.006  3848  3897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 19:50:42.008  3848  3897 D BluetoothAdapter: enable(): BT is already enabled..!
09-09 19:50:42.008   875   885 D WifiService: setWifiEnabled: true pid=3848, uid=10000
,09-09 19:50:42.008   875   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 19:50:42.063  2720  2892 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-09 19:50:42.066  2720  2914 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-09 19:50:42.067  3848  3938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
,09-09 19:50:42.473  3848  3848 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 19:50:42.744  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:50:42.747  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:50:42.789  1504  3930 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-09 19:50:42.789  1504  3930 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-09 19:50:42.789  1504  3930 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 19:50:42.789  1504  3930 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:50:42.811  1504  3930 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 19:50:42.811  1504  3930 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 19:50:42.811  1504  3930 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 19:50:42.811  1504  3930 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 19:50:42.811  1504  3930 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 19:50:42.811  1504  3930 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 19:50:42.811  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 19:50:42.811  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 19:50:42.811  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 19:50:42.811  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 19:50:42.811  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 19:50:42.811  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 19:50:42.811  1504  3930 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 19:50:42.988  1504  3930 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-09 19:50:42.988  1504  3930 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-09 19:50:42.988  1504  3930 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 19:50:42.988  1504  3930 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:50:43.010  1504  3930 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 19:50:43.010  1504  3930 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 19:50:43.010  1504  3930 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 19:50:43.010  1504  3930 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 19:50:43.010  1504  3930 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 19:50:43.010  1504  3930 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 19:50:43.010  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 19:50:43.010  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 19:50:43.010  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 19:50:43.010  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 19:50:43.010  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 19:50:43.010  1504  3930 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 19:50:43.010  1504  3930 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 19:50:47.017  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 19:50:47.018  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aa735f7 added. We now have 4 listener(s)
09-09 19:50:47.018  3848  3897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 19:50:47.034  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 19:50:47.035  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aa735f7 removed from the list
,09-09 19:50:47.035  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 19:50:47.036  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:47.036  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:47.038  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 19:50:47.039  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fad6c64 added. We now have 4 listener(s)
09-09 19:50:47.039  3848  3897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 19:50:47.043  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:50:47.043  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fad6c64 removed from the list
09-09 19:50:47.044  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:50:47.044  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:50:47.044  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:50:47.047  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 19:50:47.047  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d35cecd added. We now have 4 listener(s)
09-09 19:50:47.048  3848  3897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 19:50:47.056   875  2047 D WifiService: setWifiEnabled: false pid=3848, uid=10000
09-09 19:50:47.056   875  2047 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 19:50:47.068  2720  2768 D BluetoothAdapterState: Current state: ON, message: 23
09-09 19:50:47.068  2720  2768 D BluetoothAdapterProperties: Setting state to 13
,09-09 19:50:47.069  2720  2768 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 19:50:47.070  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 19:50:47.071  2720  2768 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 19:50:47.074  2720  2768 I BluetoothAdapterState: Entering PendingCommandState
,09-09 19:50:47.077  2720  2772 D BluetoothAdapterProperties: Scan Mode:20
09-09 19:50:47.078  2720  2768 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-09 19:50:47.082  2720  2720 D HeadsetService: Received stop request...Stopping profile...
,09-09 19:50:47.084  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 19:50:47.084  3848  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 19:50:47.084  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:47.084  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:47.084  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:47.084  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:47.084  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:50:47.084  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:50:47.084  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 19:50:47.087  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 19:50:47.087  3848  3897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 19:50:47.087  1369  2064 D BluetoothHeadset: Proxy object disconnected
09-09 19:50:47.087  3848  3897 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 19:50:47.088  1369  1369 D HeadsetProfile: Bluetooth service disconnected
,09-09 19:50:47.088   875   875 D BluetoothHeadset: Proxy object disconnected
,09-09 19:50:47.088   875   875 D BluetoothHeadset: Proxy object disconnected
,09-09 19:50:47.088   875   875 D BluetoothHeadset: Proxy object disconnected
09-09 19:50:47.089  1990  2296 D BluetoothHeadset: Proxy object disconnected
09-09 19:50:47.092  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:50:47.094  2720  2720 D A2dpService: Received stop request...Stopping profile...
,09-09 19:50:47.096  2720  2922 D A2dpStateMachine: Exit Disconnected: -1
09-09 19:50:47.097  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 19:50:47.097  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:50:47.099   875  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 19:50:47.099   875  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-09 19:50:47.099   875  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
09-09 19:50:47.099   875  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 19:50:47.100   875   875 D BluetoothA2dp: Proxy object disconnected
09-09 19:50:47.100  1369  1369 D BluetoothA2dp: Proxy object disconnected
09-09 19:50:47.101  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-09 19:50:47.101  2720  2720 V BluetoothAdapterState: isTurningOff()=true
09-09 19:50:47.101  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:47.101  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:47.101  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:47.101  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:47.101  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:47.101  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:50:47.101  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:50:47.101  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 19:50:47.101  2720  2720 V BluetoothAdapterState: isTurningOn()=false
09-09 19:50:47.101  2720  2720 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:50:47.101  2720  2720 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:50:47.102  2720  2720 D HidService: Received stop request...Stopping profile...
,09-09 19:50:47.102  2720  2720 D HidService: Stopping Bluetooth HidService
09-09 19:50:47.102  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:47.102  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 19:50:47.103  1369  1369 D BluetoothInputDevice: Proxy object disconnected
09-09 19:50:47.103  1369  1369 D HidProfile: Bluetooth service disconnected
,09-09 19:50:47.105  2720  2720 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-09 19:50:47.106  2720  2720 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 19:50:47.106  2720  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 19:50:47.106  2720  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 19:50:47.106  2720  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 19:50:47.106  2720  2772 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 19:50:47.106  2720  2720 D HealthService: Received stop request...Stopping profile...
,09-09 19:50:47.106  2720  2772 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 19:50:47.107  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:47.107  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:47.107  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:47.107  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:47.107  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:47.107  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:47.107  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:50:47.107  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:50:47.107  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 19:50:47.108  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:47.108  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 19:50:47.111  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:50:47.112  2720  2720 D PanService: Received stop request...Stopping profile...
09-09 19:50:47.114  1369  1369 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 19:50:47.114  1369  1369 D PanProfile: Bluetooth service disconnected
09-09 19:50:47.114   875  1310 E native  : do suspend true
09-09 19:50:47.115  2720  2720 D BluetoothMapService: Received stop request...Stopping profile...
09-09 19:50:47.115  2720  2720 D BluetoothMapService: stop()
,09-09 19:50:47.116  2720  2720 D BluetoothMapAppObserver: deinitObservers()
,09-09 19:50:47.116  2720  2720 D BluetoothMapAppObserver: removeReceiver()
09-09 19:50:47.117  1369  1369 D BluetoothMap: Proxy object disconnected
09-09 19:50:47.117  1369  1369 D MapProfile: Bluetooth service disconnected
09-09 19:50:47.118  2720  2720 V BluetoothAdapterState: isTurningOff()=true
,09-09 19:50:47.118  2720  2720 V BluetoothAdapterState: isTurningOn()=false
09-09 19:50:47.118  2720  2720 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:50:47.118  2720  2720 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:50:47.119  2720  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 19:50:47.119  2720  2720 V BluetoothAdapterState: isTurningOff()=true
09-09 19:50:47.119  2720  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 19:50:47.119  2720  2720 V BluetoothAdapterState: isTurningOn()=false
09-09 19:50:47.119  2720  2720 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:50:47.119  2720  2720 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:50:47.119  2720  2892 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 19:50:47.119  2720  2892 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 19:50:47.119  2720  2892 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 19:50:47.119  2720  2892 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 19:50:47.119  2720  2720 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 19:50:47.119  2720  2772 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-09 19:50:47.119  2720  2720 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 19:50:47.120  2720  2772 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 19:50:47.123  2720  2720 V BluetoothAdapterState: isTurningOff()=true
09-09 19:50:47.123  2720  2720 V BluetoothAdapterState: isTurningOn()=false
09-09 19:50:47.123  2720  2720 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:50:47.123  2720  2720 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:50:47.124  2720  2720 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 19:50:47.124  2720  2772 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 19:50:47.124  2720  2720 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 19:50:47.124  2720  2720 V BluetoothAdapterState: isTurningOff()=true
09-09 19:50:47.124  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:50:47.124  2720  2720 V BluetoothAdapterState: isTurningOn()=false
09-09 19:50:47.124  2720  2720 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:50:47.125  2720  2720 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:50:47.125  2720  2720 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 19:50:47.125  2720  2720 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 19:50:47.126  2720  2720 D BluetoothMapService: MAP Service closeService in
09-09 19:50:47.126  2720  2720 D BluetoothMapMasInstance0: MAP Service shutdown
09-09 19:50:47.126  2720  2720 D ObexServerSockets0: shutdown(block = true)
09-09 19:50:47.126  2720  2938 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 19:50:47.126  2720  2720 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 19:50:47.126  2720  2939 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 19:50:47.127  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:50:47.127  2720  2914 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-09 19:50:47.127  2720  2720 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 19:50:47.127  2720  2720 V BluetoothAdapterState: isTurningOff()=true
09-09 19:50:47.127  2720  2720 V BluetoothAdapterState: isTurningOn()=false
09-09 19:50:47.127  2720  2720 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:50:47.127  2720  2720 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:50:47.127  2720  2720 D BluetoothMapService: clean,up()
09-09 19:50:47.128  2720  2720 D BluetoothMapService: MAP Service closeService in
09-09 19:50:47.128  2720  2720 I BtOppRfcommListener: stopping Accept Thread
09-09 19:50:47.128  2720  3498 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 19:50:47.128  2720  2768 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 19:50:47.128  2720  2768 D BluetoothAdapterProperties: Setting state to 15
09-09 19:50:47.128  2720  2768 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 19:50:47.129  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:50:47.129  2720  2768 I BluetoothAdapterState: Entering BleOnState
09-09 19:50:47.129  2720  3498 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 19:50:47.132   372   873 D CommandListener: Clearing all IP addresses on wlan0
09-09 19:50:47.132   875  2095 D DhcpClient: Clearing IP address
09-09 19:50:47.135   372   873 D CommandListener: Setting iface cfg
09-09 19:50:47.136   875  2103 D DhcpClient: Receive thread stopped
09-09 19:50:47.137  1504  2550 V NativeCrypto: Read error: ssl=0x9aea5800: I/O error during system call, Connection timed out
09-09 19:50:47.137   875   888 I ActivityManager: Start proc 3953:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-09 19:50:47.137   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 19:50:47.138   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 19:50:47.138  1369  2064 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 19:50:47.138  1504  2550 V NativeCrypto: SSL shutdown failed: ssl=0x9aea5800: I/O error during system call, Broken pipe
09-09 19:50:47.140  1369  2091 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 19:50:47.141  1369  1381 D BluetoothMap: onBluetoothStateChange: up=false
09-09 19:50:47.141   875  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 19:50:47.142   875  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-09 19:50:47.143   875  1310 D WifiStateMachine: Start Disconnecting Watchdog 1
09-09 19:50:47.144   875  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 19:50:47.144   875  1310 E native  : do suspend true
09-09 19:50:47.146  1369  2064 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 19:50:47.147   396   396 E Parcel  : Reading a NULL string not supported here.
09-09 19:50:47.148   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 19:50:47.148  1369  1381 D BluetoothPan: onBluetoothStateChange on: false
09-09 19:50:47.149   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 19:50:47.149  1369  2064 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 19:50:47.150  1990  2296 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 19:50:47.150  2720  2768 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 19:50:47.150  2720  2768 D BluetoothAdapterProperties: Setting state to 16
09-09 19:50:47.150  2720  2768 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 19:50:47.151  2720  2768 D BluetoothAdapterProperties: onBleDisable
09-09 19:50:47.151  2720  2768 I BluetoothAdapterState: Entering PendingCommandState
09-09 19:50:47.151  2720  2769 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 19:50:47.151  2720  2772 D BluetoothAdapterProperties: Scan Mode:20
09-09 19:50:47.152  2720  2892 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 19:50:47.152  2720  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 19:50:47.152   875  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-09 19:50:47.155  3848  3848 W org.thaliproject.p2p.btconnectorlib,.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:47.155  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:47.155  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:47.155  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:47.155  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:47.155  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:47.155  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:50:47.155  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:50:47.155  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 19:50:47.155  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:47.156  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:50:47.157  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:47.157  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:47.157  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:47.157  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:47.157  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:47.157  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:47.157  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:50:47.157  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:50:47.157  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:50:47.158  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:47.158  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:50:47.160  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:47.160  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:47.160  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:47.160  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:47.160  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:47.160  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:47.160  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:50:47.160  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:50:47.160  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:50:47.161  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:47.161  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:50:47.163  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:47.163  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:47.163  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:47.163  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:47.163  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:47.163  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:47.163  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:50:47.163  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:50:47.163  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:50:47.165  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:50:47.166  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:50:47.191  3953  3953 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-09 19:50:47.195   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-09 19:50:47.202  3953  3953 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 19:50:47.214   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-09 19:50:47.214  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 19:50:47.214   372   873 D CommandListener: Clearing all IP addresses on wlan0
09-09 19:50:47.216   875  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-09 19:50:47.216   875  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 19:50:47.219   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aba865d:true
09-09 19:50:47.229   875  2048 I ActivityManager: Start proc 3969:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-09 19:50:47.236   875  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 19:50:47.236  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:50:47.237  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:50:47.235   875   892 D Tethering: MasterInitialState.processMessage what=3
09-09 19:50:47.238  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:50:47.242  3484  3484 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@7d7f966 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-09 19:50:47.244  2067  2067 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-09 19:50:47.253   875  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 19:50:47.255   875  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 19:50:47.256  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:47.256  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:47.256  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:47.256  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:47.256  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 19:50:47.256  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:47.256  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:50:47.256  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:50:47.256  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:50:47.257  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 19:50:47.257  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 19:50:47.258  1865  2231 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 19:50:47.258  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 19:50:47.259  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:47.259  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:47.259  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:47.259  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 19:50:47.259  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:47.259  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:50:47.259  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:50:47.259  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:50:47.259  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:47.259  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:50:47.261  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:47.261  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:47.261  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:47.261  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:47.261  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 19:50:47.261  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:47.261  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:50:47.261  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:50:47.261  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:50:47.262  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:47.262  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 19:50:47.270  3953  3953 D LocalBluetoothProfileManager: Adding local MAP profile
,09-09 19:50:47.273  3953  3953 D BluetoothMap: Create BluetoothMap proxy object
,09-09 19:50:47.278  3969  3969 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-09 19:50:47.281  3953  3953 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-09 19:50:47.288   372   873 E Netd    : netlink response contains error (No such file or directory)
,09-09 19:50:47.300  3953  3953 D DockEventReceiver: finishStartingService: stopping service
,09-09 19:50:47.303   875  1380 I ActivityManager: Killing 3006:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-09 19:50:47.352  2720  2772 I bt_hci  : shut_down
,09-09 19:50:47.358  2720  2778 D bt_hwcfg: hw_epilog_process
,09-09 19:50:47.358  2720  2778 I bt_vendor: low_power_mode_cb
,09-09 19:50:47.381  2720  2778 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 19:50:47.382  2720  2778 I bt_vendor: epilog_cb
09-09 19:50:47.382  2720  2778 I bt_hci  : epilog_finished_callback
,09-09 19:50:47.385  2720  2772 I bt_hci_h4: hal_close
,09-09 19:50:47.386  2720  2772 I bt_userial_vendor: device fd = 51 close
,09-09 19:50:47.453  3969  3969 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 19:50:47.453  3969  3969 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 19:50:47.453  3969  3969 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 19:50:47.453  3969  3969 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 19:50:47.453  3969  3969 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.r.k.d(PG:583)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 19:50:47.453  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 19:50:47.454  3969  3969 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 19:50:47.454  3969  3969 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 19:50:47.454  3969  3969 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 19:50:47.454  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 19:50:47.459  3953  3953 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 19:50:47.469  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 19:50:47.486  3953  3953 D DockEventReceiver: finishStartingService: stopping service
,09-09 19:50:47.493   875  1380 I ActivityManager: Killing 3484:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-09 19:50:47.627  2720  2769 D bt_stack_manager: event_shut_down_stack finished.
,09-09 19:50:47.628  2720  2768 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 19:50:47.635  2720  2768 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 19:50:47.635  2720  2720 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 19:50:47.637  3969  3994 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-09 19:50:47.637  2720  2720 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 19:50:47.637  2720  2720 D BtGatt.GattService: stop()
09-09 19:50:47.638  2720  2720 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 19:50:47.647  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-09 19:50:47.648  2720  2720 V BluetoothAdapterState: isTurningOff()=false
09-09 19:50:47.648  2720  2720 V BluetoothAdapterState: isTurningOn()=false
09-09 19:50:47.648  2720  2720 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:50:47.648  2720  2720 V BluetoothAdapterState: isBleTurningOff()=true
09-09 19:50:47.648  2720  2768 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-09 19:50:47.649  2720  2768 D BluetoothAdapterProperties: Setting state to 10
09-09 19:50:47.649  2720  2768 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-09 19:50:47.650  2720  2768 I BluetoothAdapterState: Entering OffState
09-09 19:50:47.650   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-09 19:50:47.657  1715  1715 D SystemUpdateService: onCreate
,09-09 19:50:47.667  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-09 19:50:47.668  2720  2720 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-09 19:50:47.668  2720  2720 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 19:50:47.668  2720  2769 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 19:50:47.672  2720  2769 D bt_stack_manager: event_clean_up_stack finished.
,09-09 19:50:47.672  2720  2720 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 19:50:47.675  1715  4006 I SystemUpdateService: active receiver: enabled
,09-09 19:50:47.678  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 19:50:47.680  2720  2720 I art     : System.exit called, status: 0
09-09 19:50:47.680  2720  2720 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 19:50:47.684  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 19:50:47.685  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-09 19:50:47.684  1715  2528 I iu.UploadsManager: num queued entries: 0
09-09 19:50:47.686  1715  2528 I iu.UploadsManager: num updated entries: 0
09-09 19:50:47.686  1715  4006 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 19:50:47.687  1715  2528 I iu.SyncManager: NEXT; no task
,09-09 19:50:47.690  1715  4006 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 19:50:47.690  1715  4006 I SystemUpdateService: now status is 0 (complete)
09-09 19:50:47.690  1715  4006 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 19:50:47.690  1715  4006 I SystemUpdateService: file has been verified
09-09 19:50:47.690  1715  4006 I SystemUpdateService: OTA package size = 12249756
,09-09 19:50:47.695  1715  4006 I SystemUpdateService: showing system update notification
,09-09 19:50:47.701   875  2048 I ActivityManager: Start proc 4009:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-09 19:50:47.714   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d404a39:true
,09-09 19:50:47.730   875  2048 I ActivityManager: Process com.android.bluetooth (pid 2720) has died
,09-09 19:50:47.736  1715  1715 D SystemUpdateService: onDestroy
,09-09 19:50:47.739  4009  4009 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-09 19:50:47.749  4009  4009 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 19:50:47.755  4009  4009 D SprintDMHelper: simOperator: 
09-09 19:50:47.755  4009  4009 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 19:50:47.776   875  2048 I ActivityManager: Start proc 4021:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-09 19:50:47.926   875  2047 I ActivityManager: Start proc 4036:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-09 19:50:47.929  3142  4035 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-09 19:50:47.934   875   885 I ActivityManager: Killing 3544:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-09 19:50:48.002  4036  4036 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-09 19:50:48.063  4036  4036 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 19:50:48.063  4036  4036 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 19:50:48.063  4036  4036 I GAv4    :   adb logcat -s GAv4
,09-09 19:50:48.076  4036  4036 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 19:50:48.082  4036  4036 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 19:50:48.112  4036  4053 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 19:50:48.226  4036  4036 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-09 19:50:48.273  4036  4036 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-09 19:50:48.283  4036  4036 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5424-5428)
09-09 19:50:48.283  4036  4036 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 19:50:48.296  4036  4036 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b59f3f0}
,09-09 19:50:48.297  4036  4036 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 19:50:48.297  4036  4036 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 19:50:48.306  4036  4036 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 19:50:48.308  4036  4036 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 19:50:48.325  4036  4036 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 19:50:48.339  4036  4036 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 19:50:48.339  4036  4036 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 19:50:48.339  4036  4036 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 19:50:48.339  4036  4036 I Adreno  : Build Date                       : 10/20/15
09-09 19:50:48.339  4036  4036 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 19:50:48.339  4036  4036 I Adreno  : Local Branch                     : M14
09-09 19:50:48.339  4036  4036 I Adreno  : Remote Branch                    : 
09-09 19:50:48.339  4036  4036 I Adreno  : Remote Branch                    : 
09-09 19:50:48.339  4036  4036 I Adreno  : Reconstruct Branch               : 
,09-09 19:50:48.402  4036  4036 I NSApplication: Starting up...
,09-09 19:50:48.401  4036  4082 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 19:50:48.449   875  2025 I ActivityManager: Start proc 4087:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-09 19:50:48.450   875  2025 I ActivityManager: Killing 1700:android.process.acore/u0a5 (adj 15): empty #17
,09-09 19:50:48.544  4087  4087 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-09 19:50:48.761   875  1693 I ActivityManager: Killing 3701:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-09 19:50:48.845   875  1693 I ActivityManager: Start proc 4101:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-09 19:50:48.903  4101  4101 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-09 19:50:48.953  4101  4101 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-09 19:50:48.968   875  1694 I ActivityManager: Killing 3718:com.android.musicfx/u0a18 (adj 15): empty #17
,09-09 19:50:52.094   875  1380 D WifiService: setWifiEnabled: true pid=3848, uid=10000
,09-09 19:50:52.094   875  1380 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 19:50:52.109   875  1310 D WifiConfigStore: Loading config and enabling all networks 
,09-09 19:50:52.118  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:52.118  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:52.118  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:52.118  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:52.118  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:52.118  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:52.118  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:50:52.118  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:50:52.118  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:50:52.119  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:52.119  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 19:50:52.122  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 19:50:52.122  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:52.122  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:52.122  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:52.122  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:52.122  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:52.122  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:50:52.122  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:50:52.122  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:50:52.122  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:52.123  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:50:52.125  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 19:50:52.125  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:52.125  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:52.125  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:52.125  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:52.125  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:52.125  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:50:52.125  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:50:52.125  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:50:52.126  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:52.126  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 19:50:52.148   875  1310 D WifiConfigStore: loaded 0 passpoint configs
,09-09 19:50:52.150   875  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-09 19:50:52.151   875  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-09 19:50:52.153   875  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-09 19:50:52.153   875  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-09 19:50:52.153   875  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 19:50:52.154   875  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 19:50:52.168   372   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 19:50:52.169   875  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-09 19:50:52.170   372   873 D CommandListener: Setting iface cfg
,09-09 19:50:52.181   875  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-09 19:50:52.182   875  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 19:50:52.182   875  1310 E native  : do suspend true
,09-09 19:50:52.200   875  1309 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 19:50:52.201   875  1310 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 19:50:52.201   875  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62,
,09-09 19:50:52.792   875  2048 I ActivityManager: Killing 3525:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-09 19:50:53.502   875  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 19:50:53.547   875  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.69 rxSuccessRate=10.12 delta 1000 -> 994
,09-09 19:50:53.549   875  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 19:50:53.549   875  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 19:50:53.571   875  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 19:50:53.655   875  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 19:50:53.656  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 19:50:54.080  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 19:50:54.125  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 19:50:54.125  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 19:50:54.131   875  1310 D WifiConfigStore: Retrieve network priorities after PNO.,
,09-09 19:50:54.142   875  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 19:50:54.144   875  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 19:50:54.145   875  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 19:50:54.169   875  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 19:50:54.186   372   873 D CommandListener: Setting iface cfg
,09-09 19:50:54.192   875  1310 D WifiStateMachine: Start Dhcp Watchdog 2
,09-09 19:50:54.198   875  4136 D DhcpClient: Receive thread started
,09-09 19:50:54.201   875  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 19:50:54.290   875  1310 E native  : do suspend false
,09-09 19:50:54.310   875  2095 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 19:50:54.339   875  4136 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172642, domain null
,09-09 19:50:54.340   875  2095 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172642 seconds
,09-09 19:50:54.343   875  2095 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 19:50:54.368   875  4136 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 19:50:54.369   875  2095 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 19:50:54.374   372   873 D CommandListener: Setting iface cfg
,09-09 19:50:54.386   875  2095 D DhcpClient: Scheduling renewal in 86399s
,09-09 19:50:54.387   875  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 19:50:54.391   875  1310 E native  : do suspend true
,09-09 19:50:54.418   875  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 19:50:54.421   875  1310 D WifiConfigStore: No blacklist allowed without epno enabled
09-09 19:50:54.422   875  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 19:50:54.426   875  1312 D ConnectivityService: Adding iface wlan0 to network 101
,09-09 19:50:54.438   875  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 19:50:54.483   875  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 19:50:54.483   875  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-09 19:50:54.485   875  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-09 19:50:54.486   875  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-09 19:50:54.487   875  1312 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-09 19:50:54.498   875  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 19:50:54.505   875  1312 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-09 19:50:54.505   875  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-09 19:50:54.505   875  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-09 19:50:54.505   875  1312 D ConnectivityService:    accepting network in place of null
09-09 19:50:54.505   875  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 19:50:54.506   875  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 19:50:54.508   875  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 19:50:54.519   875  4135 D NetlinkSocketObserver: NeighborEvent{elapsedMs=181663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 19:50:54.542   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 19:50:54.593   875  4134 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-09 19:50:54.603   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 19:50:54.612   875  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-09 19:50:54.613   875  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 19:50:54.619   875   892 D Tethering: MasterInitialState.processMessage what=3
,09-09 19:50:54.617   875  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-09 19:50:54.635  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:54.636  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:54.636  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:54.636  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:54.636  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:54.636  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:54.636  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:50:54.636  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:50:54.636  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 19:50:54.636  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:54.636  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 19:50:54.645  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:54.645  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:54.645  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:54.645  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:54.645  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:54.645  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:54.645  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:50:54.645  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:50:54.645  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 19:50:54.645  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:54.646  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 19:50:54.649  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:54.649  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:54.649  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:54.649  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:54.649  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:54.649  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:54.649  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:50:54.649  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:50:54.649  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 19:50:54.650  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:54.650  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 19:50:54.656  2067  2067 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-09 19:50:54.663  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-09 19:50:54.666   875  4134 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 17:50:54 GMT], X-Android-Received-Millis=[1473443454665], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473443454642]}
09-09 19:50:54.669   875  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 19:50:54.669   875  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-09 19:50:54.670   875  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 19:50:54.671   875  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 19:50:54.673  1715  1715 D SystemUpdateService: onCreate
09-09 19:50:54.677  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 19:50:54.690  3799  4148 I BooksSync: Starting books sync for 61035162, extras: ade
09-09 19:50:54.699  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-09 19:50:54.701  1715  2528 I iu.UploadsManager: num queued entries: 0
09-09 19:50:54.702  1715  2528 I iu.UploadsManager: num updated entries: 0
09-09 19:50:54.703  1715  4150 I SystemUpdateService: active receiver: enabled
09-09 19:50:54.712  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-09 19:50:54.713  1715  4150 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-09 19:50:54.713  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-09 19:50:54.715  4009  4009 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-09 19:50:54.719  1715  4153 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-09 19:50:54.720  1715  4153 W BaseAppContext: Using Auth Proxy for data requests.
09-09 19:50:54.722  1715  4153 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
09-09 19:50:54.722  4009  4009 D SprintDMHelper: simOperator: 
09-09 19:50:54.722  4009  4009 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 19:50:54.726  1715  2528 I iu.SyncManager: NEXT; no task
,09-09 19:50:54.731  1715  4150 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 19:50:54.731  1715  4150 I SystemUpdateService: now status is 0 (complete)
09-09 19:50:54.731  1715  4150 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 19:50:54.731  1715  4150 I SystemUpdateService: file has been verified
09-09 19:50:54.732  1715  4150 I SystemUpdateService: OTA package size = 12249756
,09-09 19:50:54.735  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:50:54.741  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:50:54.783  1715  4150 I SystemUpdateService: showing system update notification
,09-09 19:50:54.810  3799  4160 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 19:50:54.844  1504  2259 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 19:50:54.844  1504  2259 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 19:50:54.844  1504  2259 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 19:50:54.844  1504  2259 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:50:54.854  1504  2257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 19:50:54.854  1504  2257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-09 19:50:54.854  1504  2257 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:50:54.854  1504  2257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:50:54.866  1715  1715 D SystemUpdateService: onDestroy
,09-09 19:50:54.887  1504  2259 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 19:50:54.887  1504  2259 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 19:50:54.887  1504  2259 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:50:54.887  1504  2259 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:50:54.904  3142  4155 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 19:50:54.907  3799  4160 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 19:50:54.908  3799  4148 E BooksSync: Soft error
09-09 19:50:54.908  3799  4148 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 19:50:54.908  3799  4148 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 19:50:54.908  3799  4148 E BooksSync: Sync error
09-09 19:50:54.908  3799  4148 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 19:50:54.908  3799  4148 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 19:50:54.908  3799  4148 I BooksSync: Finished books sync
,09-09 19:50:54.914   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 160564, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 19:50:54.916  1715  4153 E MDM     : [178] SitrepService.a: Error sending sitrep.
,09-09 19:50:55.611   875  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 19:50:57.100   875  1396 D WifiService: setWifiEnabled: false pid=3848, uid=10000
,09-09 19:50:57.101   875  1396 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 19:50:57.121  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:50:57.129  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 19:50:57.135   875  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 19:50:57.136   875  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-09 19:50:57.136   875  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 19:50:57.136   875  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 19:50:57.158   875  1310 E native  : do suspend true
,09-09 19:50:57.173   875  2095 D DhcpClient: Clearing IP address
,09-09 19:50:57.174   372   873 D CommandListener: Clearing all IP addresses on wlan0
09-09 19:50:57.177   372   873 D CommandListener: Setting iface cfg
09-09 19:50:57.183  1504  4163 V NativeCrypto: Read error: ssl=0x9aea5800: I/O error during system call, Connection timed out
,09-09 19:50:57.183  1504  2259 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-09 19:50:57.185  1504  2259 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 19:50:57.185  1504  4163 V NativeCrypto: SSL shutdown failed: ssl=0x9aea5800: I/O error during system call, Broken pipe
,09-09 19:50:57.187   875  4136 D DhcpClient: Receive thread stopped
,09-09 19:50:57.185  1504  2259 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:50:57.188  1504  2259 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-09 19:50:57.193   875  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 19:50:57.193   875  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-09 19:50:57.199   396   396 E Parcel  : Reading a NULL string not supported here.
,09-09 19:50:57.208   875  1310 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-09 19:50:57.209   875  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 19:50:57.209   875  1310 E native  : do suspend true
09-09 19:50:57.210   875  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-09 19:50:57.229  3586  3586 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 19:50:57.229  3586  3586 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 19:50:57.229  3586  3586 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-09 19:50:57.251   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 19:50:57.278   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 19:50:57.278   372   873 D CommandListener: Clearing all IP addresses on wlan0
09-09 19:50:57.279   875  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 19:50:57.279   875  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 19:50:57.283   875   892 D Tethering: MasterInitialState.processMessage what=3
09-09 19:50:57.287  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 19:50:57.287  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:57.287  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:57.287  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:57.287  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:57.287  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:57.287  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:50:57.287  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:50:57.287  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:50:57.288  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:57.288  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:50:57.291  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:57.291  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:57.291  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:57.291  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:57.291  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:57.291  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:57.291  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:50:57.291  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:50:57.291  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:50:57.291   875  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-09 19:50:57.291  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:57.292  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:50:57.295  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:57.295  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:57.295  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:57.295  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:57.295  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:50:57.295  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:57.295  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:50:57.295  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:50:57.295  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 19:50:57.295  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:57.296  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:50:57.300  2067  2067 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-09 19:50:57.305  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-09 19:50:57.311  1715  1715 D SystemUpdateService: onCreate
09-09 19:50:57.312   875  1310 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 19:50:57.315  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:57.315  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:57.315  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:57.315  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:57.315  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 19:50:57.315  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:57.315  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:50:57.315  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:50:57.315  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:50:57.315  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:57.315  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:50:57.316  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:57.316  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:57.316  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:57.316  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:57.316  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 19:50:57.316  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:57.316  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:50:57.316  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:50:57.316  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:50:57.316  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:57.316  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:50:57.317  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:57.317  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:50:57.317  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:50:57.317  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:50:57.317  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 19:50:57.317  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:50:57.317  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:50:57.317  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:50:57.317  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:50:57.317  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:50:57.318  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:50:57.318  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-09 19:50:57.319  1865  2231 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 19:50:57.324   875  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 19:50:57.335  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-09 19:50:57.342  1715  4171 I SystemUpdateService: active receiver: enabled
09-09 19:50:57.344  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-09 19:50:57.345  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-09 19:50:57.348  4009  4009 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-09 19:50:57.352  4009  4009 D SprintDMHelper: simOperator: 
09-09 19:50:57.352  4009  4009 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-09 19:50:57.360  1715  2528 I iu.UploadsManager: num queued entries: 0
,09-09 19:50:57.364  1715  4171 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-09 19:50:57.367  3142  4174 I Babel   : connection state changed from CONNECTED to DISCONNECTED
09-09 19:50:57.376   372   873 E Netd    : netlink response contains error (No such file or directory)
09-09 19:50:57.377   875  1312 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-09 19:50:57.363  1715  2528 I iu.UploadsManager: num updated entries: 0
09-09 19:50:57.390  1715  2528 I iu.SyncManager: NEXT; no task
09-09 19:50:57.391  1715  4171 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-09 19:50:57.391  1715  4171 I SystemUpdateService: now status is 0 (complete)
09-09 19:50:57.391  1715  4171 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 19:50:57.391  1715  4171 I SystemUpdateService: file has been verified
09-09 19:50:57.391  1715  4171 I SystemUpdateService: OTA package size = 12249756
,09-09 19:50:57.405  1715  4171 I SystemUpdateService: showing system update notification
,09-09 19:50:57.414  1715  1715 D SystemUpdateService: onDestroy
,09-09 19:51:02.155   875   892 I ActivityManager: Start proc 4181:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 19:51:02.287  4181  4181 D AdapterServiceConfig: Adding HeadsetService
,09-09 19:51:02.288  4181  4181 D AdapterServiceConfig: Adding A2dpService
09-09 19:51:02.288  4181  4181 D AdapterServiceConfig: Adding HidService
09-09 19:51:02.288  4181  4181 D AdapterServiceConfig: Adding HealthService
,09-09 19:51:02.289  4181  4181 D AdapterServiceConfig: Adding PanService
09-09 19:51:02.289  4181  4181 D AdapterServiceConfig: Adding GattService
09-09 19:51:02.289  4181  4181 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 19:51:02.304  4181  4181 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 19:51:02.304   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8d9c467:true
,09-09 19:51:02.309  4181  4181 I bt_bluedroid: init
,09-09 19:51:02.310  4181  4193 I BluetoothAdapterState: Entering OffState
,09-09 19:51:02.315  4181  4194 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 19:51:02.316  4181  4194 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-09 19:51:02.316  4181  4194 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-09 19:51:02.317  4181  4194 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 19:51:02.318  4181  4181 I bt_bluedroid: get_profile_interface socket
09-09 19:51:02.320  4181  4181 I bt_bluedroid: get_profile_interface sdp
,09-09 19:51:02.323  4181  4192 I bt_bluedroid: config_hci_snoop_log
09-09 19:51:02.323  4181  4197 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 19:51:02.324   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-09 19:51:02.324  4181  4197 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 19:51:02.346  4181  4193 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 19:51:02.347  4181  4193 D BluetoothAdapterProperties: Setting state to 14
09-09 19:51:02.347  4181  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 19:51:02.352  4181  4193 D BluetoothBondStateMachine: make
,09-09 19:51:02.357  4181  4198 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 19:51:02.363  4181  4193 I BluetoothAdapterState: Entering PendingCommandState
,09-09 19:51:02.366  4181  4181 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 19:51:02.373  4181  4181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
,09-09 19:51:02.374  4181  4181 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 19:51:02.376  4181  4181 D BtGatt.GattService: Received start request. Starting profile...
,09-09 19:51:02.376  4181  4181 D BtGatt.GattService: start()
,09-09 19:51:02.376  4181  4181 I bt_bluedroid: get_profile_interface gatt
,09-09 19:51:02.378  4181  4181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
,09-09 19:51:02.379  4181  4181 D BtGatt.AdvertiseManager: advertise manager created
,09-09 19:51:02.391  4181  4181 V BluetoothAdapterState: isTurningOff()=false
09-09 19:51:02.391  4181  4181 V BluetoothAdapterState: isTurningOn()=false
,09-09 19:51:02.391  4181  4181 V BluetoothAdapterState: isBleTurningOn()=true
09-09 19:51:02.391  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:51:02.391  4181  4193 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-09 19:51:02.392  4181  4193 I bt_bluedroid: enable
,09-09 19:51:02.392  4181  4194 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-09 19:51:02.393  4181  4194 I bt_hci  : start_up
,09-09 19:51:02.412  4181  4194 I bt_vendor: alloc value 0xb3a1c189
,09-09 19:51:02.412  4181  4194 I bt_vendor: init
,09-09 19:51:02.413  4181  4194 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 19:51:02.413  4181  4194 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 19:51:02.510   875  1312 D ConnectivityService: handlePromptUnvalidated 101
,09-09 19:51:02.519  4181  4194 D bt_hci  : start_up starting async portion
,09-09 19:51:02.520  4181  4201 I bt_hci  : event_finish_startup
,09-09 19:51:02.520  4181  4201 I bt_hci_h4: hal_open
,09-09 19:51:02.520  4181  4201 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 19:51:02.531  4181  4201 I bt_userial_vendor: device fd = 51 open
,09-09 19:51:02.562  4181  4201 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 19:51:02.594  4181  4201 D bt_hwcfg: Chipset BCM4354A2
,09-09 19:51:02.595  4181  4201 D bt_hwcfg: Target name = [BCM4354A2]
,09-09 19:51:02.596  4181  4201 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 19:51:03.258  4181  4201 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 19:51:03.260  4181  4201 D bt_hwcfg: Settlement delay -- 100 ms
09-09 19:51:03.260  4181  4201 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 19:51:03.377  4181  4201 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 19:51:03.378  4181  4201 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 19:51:03.406  4181  4201 I bt_hwcfg: vendor lib fwcfg completed
,09-09 19:51:03.406  4181  4201 I bt_vendor: firmware callback
09-09 19:51:03.407  4181  4201 I bt_hci  : firmware_config_callback
,09-09 19:51:03.418  4181  4203 I bt_btu  : btu_task pending for preload complete event
,09-09 19:51:03.418  4181  4203 I bt_btu_task: Bluetooth chip preload is complete
,09-09 19:51:03.419  4181  4203 I bt_btu  : btu_task received preload complete event
,09-09 19:51:03.428  4181  4203 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 19:51:03.429  4181  4203 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-09 19:51:03.429  4181  4203 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-09 19:51:03.430  4181  4203 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-09 19:51:03.430  4181  4203 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-09 19:51:03.430  4181  4203 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 19:51:03.431  4181  4203 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 19:51:03.432  4181  4203 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 19:51:03.432  4181  4203 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 19:51:03.432  4181  4203 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 19:51:03.433  4181  4203 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 19:51:03.433  4181  4203 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 19:51:03.433  4181  4203 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 19:51:03.434  4181  4203 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 19:51:03.434  4181  4203 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 19:51:03.566  4181  4203 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3999d9d
,09-09 19:51:03.567  4181  4203 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3999d9d 
,09-09 19:51:03.579  4181  4197 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 19:51:03.580  4181  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 19:51:03.581  4181  4197 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 19:51:03.584  4181  4197 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 19:51:03.588  4181  4197 D BluetoothAdapterProperties: Scan Mode:20
09-09 19:51:03.588  4181  4197 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 19:51:03.589  4181  4197 D bt_hci  : do_postload posting postload work item
,09-09 19:51:03.589  4181  4201 I bt_hci  : event_postload
,09-09 19:51:03.589  4181  4201 I bt_vendor: sco_config_cb
09-09 19:51:03.589  4181  4201 I bt_hci  : sco_config_callback postload finished.
09-09 19:51:03.594  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:03.596  4181  4197 D bt_bte_conf: Device ID record 1 : primary
,09-09 19:51:03.596  4181  4197 D bt_bte_conf:   vendorId            = 000f
,09-09 19:51:03.596  4181  4197 D bt_bte_conf:   vendorIdSource      = 0001
09-09 19:51:03.596  4181  4197 D bt_bte_conf:   product             = 1200
,09-09 19:51:03.596  4181  4197 D bt_bte_conf:   version             = 1436
09-09 19:51:03.596  4181  4197 D bt_bte_conf:   clientExecutableURL = 
09-09 19:51:03.597  4181  4197 D bt_bte_conf:   serviceDescription  = 
,09-09 19:51:03.597  4181  4197 D bt_bte_conf:   documentationURL    = 
,09-09 19:51:03.597  4181  4197 D bt_bte_conf: bte_load_did_conf no section named DID2.,
09-09 19:51:03.597  4181  4194 D bt_stack_manager: event_start_up_stack finished
,09-09 19:51:03.597  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:03.602  4181  4201 I bt_vendor: low_power_mode_cb
09-09 19:51:03.602  4181  4193 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 19:51:03.602  4181  4193 D BluetoothAdapterProperties: Setting state to 15
,09-09 19:51:03.603  4181  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-09 19:51:03.603  4181  4193 I BluetoothAdapterState: Entering BleOnState
09-09 19:51:03.603  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:51:03.606  4181  4193 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-09 19:51:03.606  4181  4193 D BluetoothAdapterProperties: Setting state to 11
09-09 19:51:03.606  4181  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-09 19:51:03.611  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:51:03.614  4181  4181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
09-09 19:51:03.615  4181  4181 D HeadsetService: Received start request. Starting profile...
,09-09 19:51:03.617  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:51:03.619  4181  4181 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-09 19:51:03.619  4181  4181 D HeadsetStateMachine: make
09-09 19:51:03.621  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:51:03.625  4181  4193 I BluetoothAdapterState: Entering PendingCommandState
,09-09 19:51:03.629  4181  4181 D HeadsetStateMachine: max_hf_connections = 1
,09-09 19:51:03.629  4181  4181 I bt_bluedroid: get_profile_interface handsfree
,09-09 19:51:03.629  4181  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 19:51:03.632  4181  4197 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-09 19:51:03.634  4181  4181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
,09-09 19:51:03.635  4181  4181 D A2dpService: Received start request. Starting profile...
,09-09 19:51:03.636  4181  4181 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 19:51:03.636  4181  4181 I bt_bluedroid: get_profile_interface avrcp
,09-09 19:51:03.643  4181  4181 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 19:51:03.644  4181  4181 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 19:51:03.644  4181  4181 D A2dpStateMachine: make
,09-09 19:51:03.646  4181  4181 I bt_bluedroid: get_profile_interface a2dp
,09-09 19:51:03.647  4181  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 19:51:03.648  4181  4212 D A2dpStateMachine: Enter Disconnected: -2,
09-09 19:51:03.648  4181  4181 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 19:51:03.649  4181  4181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
,09-09 19:51:03.650  3953  3953 D BluetoothInputDevice: Proxy object connected
,09-09 19:51:03.651  3953  3953 D HidProfile: Bluetooth service connected
,09-09 19:51:03.652  4181  4181 D HidService: Received start request. Starting profile...
09-09 19:51:03.652  4181  4181 I bt_bluedroid: get_profile_interface hidhost
09-09 19:51:03.652  4181  4181 D HidService: setHidService(): set to: null
09-09 19:51:03.652  4181  4197 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb397b3e5
,09-09 19:51:03.652  4181  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 19:51:03.652  4181  4181 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 19:51:03.653  4181  4181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
09-09 19:51:03.654  4181  4181 D HealthService: Received start request. Starting profile...
,09-09 19:51:03.656  4181  4181 I bt_bluedroid: get_profile_interface health
,09-09 19:51:03.656  4181  4181 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-09 19:51:03.657  4181  4181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
,09-09 19:51:03.658  3953  3953 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 19:51:03.658  4181  4181 D PanService: Received start request. Starting profile...
09-09 19:51:03.658  4181  4181 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 19:51:03.659  3953  3953 D PanProfile: Bluetooth service connected
09-09 19:51:03.659  4181  4181 I bt_bluedroid: get_profile_interface pan
,09-09 19:51:03.659  4181  4197 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 19:51:03.665  4181  4181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
,09-09 19:51:03.667  3953  3953 D BluetoothMap: Proxy object connected
09-09 19:51:03.667  3953  3953 D MapProfile: Bluetooth service connected
09-09 19:51:03.667  3953  3953 D BluetoothMap: getConnectedDevices(),
09-09 19:51:03.667  4181  4181 D BluetoothMapService: Received start request. Starting profile...
09-09 19:51:03.668  4181  4181 D BluetoothMapService: start()
,09-09 19:51:03.668  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 19:51:03.670  3953  3953 D BluetoothMap: Bluetooth is Not enabled
,09-09 19:51:03.672  4181  4181 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 19:51:03.673  4181  4181 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-09 19:51:03.673  4181  4181 D BluetoothMapAppObserver: createReceiver()
,09-09 19:51:03.675  4181  4181 D BluetoothMapAppObserver: initObservers()
,09-09 19:51:03.675  4181  4181 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 19:51:03.682  4181  4181 V BluetoothAdapterState: isTurningOff()=false
,09-09 19:51:03.683  4181  4181 V BluetoothAdapterState: isTurningOn()=true
09-09 19:51:03.683  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:03.683  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 19:51:03.685  4181  4210 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-09 19:51:03.686  4181  4181 V BluetoothAdapterState: isTurningOff()=false
,09-09 19:51:03.686  4181  4181 V BluetoothAdapterState: isTurningOn()=true
09-09 19:51:03.686  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:03.686  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:51:03.686  4181  4181 V BluetoothAdapterState: isTurningOff()=false
09-09 19:51:03.686  4181  4181 V BluetoothAdapterState: isTurningOn()=true
,09-09 19:51:03.686  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:03.686  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:51:03.687  4181  4181 V BluetoothAdapterState: isTurningOff()=false
09-09 19:51:03.687  4181  4181 V BluetoothAdapterState: isTurningOn()=true
09-09 19:51:03.687  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 19:51:03.687  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:51:03.687  4181  4181 V BluetoothAdapterState: isTurningOff()=false
,09-09 19:51:03.687  4181  4181 V BluetoothAdapterState: isTurningOn()=true
,09-09 19:51:03.687  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:03.687  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 19:51:03.689  4181  4181 V BluetoothAdapterState: isTurningOff()=false
,09-09 19:51:03.690  4181  4181 V BluetoothAdapterState: isTurningOn()=true
09-09 19:51:03.690  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:03.690  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 19:51:03.691  4181  4193 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 19:51:03.691  4181  4193 D BluetoothAdapterProperties: ScanMode =  20
,09-09 19:51:03.691  4181  4193 D BluetoothAdapterProperties: State =  11
09-09 19:51:03.694  4181  4197 D BluetoothAdapterProperties: Scan Mode:21
09-09 19:51:03.694  4181  4197 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 19:51:03.695  4181  4193 D BluetoothAdapterProperties: Setting state to 12
09-09 19:51:03.695  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:03.695  4181  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 19:51:03.696  4181  4193 I BluetoothAdapterState: Entering OnState
,09-09 19:51:03.697   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 19:51:03.697   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 19:51:03.699  3953  3964 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 19:51:03.700  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:51:03.700  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:03.700  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:03.700  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 19:51:03.700  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:51:03.700  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:51:03.700  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:51:03.700  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 19:51:03.700  1369  2091 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 19:51:03.702   875   875 D BluetoothA2dp: Proxy object connected
09-09 19:51:03.702  1369  1369 D BluetoothA2dp: Proxy object connected
,09-09 19:51:03.702  3953  3965 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 19:51:03.704  1369  2064 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 19:51:03.705  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 19:51:03.706  4181  4181 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 19:51:03.706  1369  1386 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 19:51:03.708  1369  1369 D BluetoothInputDevice: Proxy object connected
09-09 19:51:03.708  1369  1369 D HidProfile: Bluetooth service connected
09-09 19:51:03.708  1369  2091 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 19:51:03.709  4181  4181 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-09 19:51:03.710  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:51:03.710  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:03.710  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:03.710  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 19:51:03.710  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:51:03.710  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:51:03.710  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:51:03.710  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:51:03.711  4181  4181 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 19:51:03.711  1369  1369 D BluetoothMap: Proxy object connected
09-09 19:51:03.711  1369  1369 D MapProfile: Bluetooth service connected
09-09 19:51:03.711  3953  3964 D BluetoothMap: onBluetoothStateChange: up=true
09-09 19:51:03.711  1369  1369 D BluetoothMap: getConnectedDevices()
,09-09 19:51:03.711   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 19:51:03.712  3953  3965 D BluetoothPan: onBluetoothStateChange on: true
09-09 19:51:03.712  1369  2064 D BluetoothPan: onBluetoothStateChange on: true
09-09 19:51:03.714  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:51:03.714   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 19:51:03.714  1369  1369 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 19:51:03.715  1369  1386 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 19:51:03.715  1369  1369 D PanProfile: Bluetooth service connected
09-09 19:51:03.715  4181  4181 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 19:51:03.715  1990  2076 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 19:51:03.716  4181  4181 D ObexServerSockets: Succeed to create listening sockets 
,09-09 19:51:03.716  4181  4181 D ObexServerSockets0: startAccept()
09-09 19:51:03.716  4181  4181 D ObexServerSockets0: prepareForNewConnect()
09-09 19:51:03.718   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 19:51:03.719  4181  4181 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 19:51:03.720  4181  4181 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 19:51:03.721  4181  4181 D BluetoothMapService: onReceive
,09-09 19:51:03.721  4181  4181 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 19:51:03.721  4181  4181 D BluetoothMapService: STATE_ON
09-09 19:51:03.722  4181  4220 D ObexServerSockets0: Accepting socket connection...
,09-09 19:51:03.723  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:51:03.723  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:03.723  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:03.723  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 19:51:03.723  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:51:03.723  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:51:03.723  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:51:03.723  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:51:03.724  3953  3953 D LocalBluetoothProfileManager: Adding local A2DP profile
09-09 19:51:03.724  4181  4219 D ObexServerSockets0: Accepting socket connection...
09-09 19:51:03.728  3953  3953 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-09 19:51:03.728  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 19:51:03.735  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:51:03.738  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:51:03.739  3953  3953 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 19:51:03.742  4181  4181 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 19:51:03.742  4181  4181 D ObexServerSockets0: prepareForNewConnect()
09-09 19:51:03.742  3953  3953 D BluetoothA2dp: Proxy object connected
,09-09 19:51:03.746  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 19:51:03.749  3953  3953 D DockEventReceiver: finishStartingService: stopping service
,09-09 19:51:03.759  3953  3953 D BluetoothPbap: Proxy object connected
,09-09 19:51:03.759  3953  3953 D PbapServerProfile: Bluetooth service connected
,09-09 19:51:03.761  1369  1369 D BluetoothPbap: Proxy object connected
,09-09 19:51:03.761  1369  1369 D PbapServerProfile: Bluetooth service connected
,09-09 19:51:03.767  4181  4225 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 19:51:03.787  4181  4229 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 19:51:03.788  4181  4229 I BtOppRfcommListener: Accept thread started.
,09-09 19:51:03.798  1369  1381 D BluetoothHeadset: Proxy object connected
,09-09 19:51:03.798  1369  1369 D HeadsetProfile: Bluetooth service connected
,09-09 19:51:03.799   875   875 D BluetoothHeadset: Proxy object connected
09-09 19:51:03.799   875   875 D BluetoothHeadset: Proxy object connected
09-09 19:51:03.799   875   875 D BluetoothHeadset: Proxy object connected
09-09 19:51:03.799  1990  2296 D BluetoothHeadset: Proxy object connected
,09-09 19:51:03.812   875   892 D BluetoothHeadset: Proxy object connected
,09-09 19:51:03.814   875   892 D BluetoothHeadset: Proxy object connected
,09-09 19:51:03.815  1369  2091 D BluetoothHeadset: Proxy object connected
09-09 19:51:03.815  1369  1369 D HeadsetProfile: Bluetooth service connected
,09-09 19:51:03.816  1990  2005 D BluetoothHeadset: Proxy object connected
,09-09 19:51:03.831  3953  3964 D BluetoothHeadset: Proxy object connected
,09-09 19:51:03.832  3953  3953 D HeadsetProfile: Bluetooth service connected
,09-09 19:51:07.121  4181  4193 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 19:51:07.122  4181  4193 D BluetoothAdapterProperties: Setting state to 13
,09-09 19:51:07.122  4181  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-09 19:51:07.124  4181  4193 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 19:51:07.126  4181  4193 I BluetoothAdapterState: Entering PendingCommandState
,09-09 19:51:07.132  4181  4181 D BluetoothMapService: onReceive
,09-09 19:51:07.132  4181  4181 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 19:51:07.134  4181  4181 D BluetoothMapService: STATE_TURNING_OFF
,09-09 19:51:07.135  4181  4181 D BluetoothMapService: MAP Service closeService in
09-09 19:51:07.135  4181  4181 D BluetoothMapMasInstance0: MAP Service shutdown
,09-09 19:51:07.137  4181  4181 D ObexServerSockets0: shutdown(block = true)
,09-09 19:51:07.139  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 19:51:07.139  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:51:07.139  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:07.139  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:07.139  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 19:51:07.139  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:51:07.139  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:51:07.139  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:51:07.139  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:51:07.139  4181  4219 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-09 19:51:07.141  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:51:07.141  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:51:07.145  4181  4197 D BluetoothAdapterProperties: Scan Mode:20
,09-09 19:51:07.146  4181  4193 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-09 19:51:07.146  4181  4181 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 19:51:07.147  4181  4220 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 19:51:07.147  4181  4206 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-09 19:51:07.148  4181  4181 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 19:51:07.148  4181  4181 I BtOppRfcommListener: stopping Accept Thread
09-09 19:51:07.148  4181  4229 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-09 19:51:07.149  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 19:51:07.152  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:51:07.152  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:07.152  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:07.152  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 19:51:07.152  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:51:07.152  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:51:07.152  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:51:07.152  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:51:07.149  4181  4229 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-09 19:51:07.154  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:51:07.154  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:51:07.155  4181  4181 D HeadsetService: Received stop request...Stopping profile...
09-09 19:51:07.158  1369  2091 D BluetoothHeadset: Proxy object disconnected
,09-09 19:51:07.158  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 19:51:07.158  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:51:07.158  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:07.158  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:07.158  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 19:51:07.158  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 19:51:07.158  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:51:07.158  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:51:07.158  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 19:51:07.160  4181  4181 D A2dpService: Received stop request...Stopping profile...
09-09 19:51:07.160  4181  4212 D A2dpStateMachine: Exit Disconnected: -1
,09-09 19:51:07.160  1369  1369 D HeadsetProfile: Bluetooth service disconnected
09-09 19:51:07.160  3848  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 19:51:07.160  3953  3965 D BluetoothHeadset: Proxy object disconnected
,09-09 19:51:07.160  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:51:07.161   875   875 D BluetoothHeadset: Proxy object disconnected
09-09 19:51:07.161   875   875 D BluetoothHeadset: Proxy object disconnected
09-09 19:51:07.161   875   875 D BluetoothHeadset: Proxy object disconnected
09-09 19:51:07.162  1990  2000 D BluetoothHeadset: Proxy object disconnected
,09-09 19:51:07.163  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:07.164   875   875 D BluetoothA2dp: Proxy object disconnected
09-09 19:51:07.166  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:07.166  1369  1369 D BluetoothA2dp: Proxy object disconnected
09-09 19:51:07.162  3953  3953 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 19:51:07.171  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:07.173  4181  4181 D HidService: Received stop request...Stopping profile...
09-09 19:51:07.174  4181  4181 D HidService: Stopping Bluetooth HidService
09-09 19:51:07.175  3953  3953 D HeadsetProfile: Bluetooth service disconnected
09-09 19:51:07.175  3953  3953 D BluetoothA2dp: Proxy object disconnected
09-09 19:51:07.176  4181  4181 V BluetoothAdapterState: isTurningOff()=true
,09-09 19:51:07.176  4181  4181 V BluetoothAdapterState: isTurningOn()=false
09-09 19:51:07.176  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:07.176  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:51:07.176  1369  1369 D BluetoothInputDevice: Proxy object disconnected
,09-09 19:51:07.176  1369  1369 D HidProfile: Bluetooth service disconnected
09-09 19:51:07.178  4181  4181 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 19:51:07.178  4181  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 19:51:07.178  4181  4181 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 19:51:07.178  4181  4203 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 19:51:07.178  4181  4203 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 19:51:07.178  4181  4203 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 19:51:07.179  4181  4197 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 19:51:07.179  3953  3953 D DockEventReceiver: finishStartingService: stopping service
09-09 19:51:07.180  4181  4181 D HealthService: Received stop request...Stopping profile...
09-09 19:51:07.181  3953  3953 D BluetoothInputDevice: Proxy object disconnected
09-09 19:51:07.181  3953  3953 D HidProfile: Bluetooth service disconnected
09-09 19:51:07.184  4181  4181 D PanService: Received stop request...Stopping profile...
,09-09 19:51:07.185  1369  1369 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 19:51:07.185  1369  1369 D PanProfile: Bluetooth service disconnected
09-09 19:51:07.186  4181  4181 D BluetoothMapService: Received stop request...Stopping profile...
09-09 19:51:07.186  4181  4181 D BluetoothMapService: stop()
09-09 19:51:07.187  4181  4181 D BluetoothMapAppObserver: deinitObservers()
09-09 19:51:07.187  4181  4181 D BluetoothMapAppObserver: removeReceiver()
09-09 19:51:07.188  1369  1369 D BluetoothMap: Proxy object disconnected
09-09 19:51:07.188  1369  1369 D MapProfile: Bluetooth service disconnected
09-09 19:51:07.189  4181  4181 V BluetoothAdapterState: isTurningOff()=true
09-09 19:51:07.189  4181  4181 V BluetoothAdapterState: isTurningOn()=false
09-09 19:51:07.189  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:07.189  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:51:07.189  3953  3953 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 19:51:07.189  3953  3953 D PanProfile: Bluetooth service disconnected
09-09 19:51:07.189  3953  3953 D BluetoothMap: Proxy object disconnected
09-09 19:51:07.189  3953  3953 D MapProfile: Bluetooth service disconnected
09-09 19:51:07.190  4181  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-09 19:51:07.190  4181  4203 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 19:51:07.190  4181  4203 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 19:51:07.190  4181  4203 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 19:51:07.190  4181  4203 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 19:51:07.190  4181  4181 V BluetoothAdapterState: isTurningOff()=true
09-09 19:51:07.190  4181  4203 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 19:51:07.190  4181  4203 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 19:51:07.190  4181  4181 V BluetoothAdapterState: isTurningOn()=false
09-09 19:51:07.191  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:07.191  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:51:07.193  4181  4181 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 19:51:07.193  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 19:51:07.194  4181  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 19:51:07.194  4181  4181 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 19:51:07.194  4181  4181 V BluetoothAdapterState: isTurningOff()=true
09-09 19:51:07.194  4181  4181 V BluetoothAdapterState: isTurningOn()=false
09-09 19:51:07.194  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:07.194  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:51:07.194  4181  4181 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 19:51:07.194  4181  4197 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 19:51:07.195  4181  4181 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 19:51:07.196  4181  4181 V BluetoothAdapterState: isTurningOff()=true
09-09 19:51:07.196  4181  4181 V BluetoothAdapterState: isTurningOn()=false
09-09 19:51:07.196  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:07.196  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:51:07.196  4181  4181 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 19:51:07.196  4181  4181 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 19:51:07.197  4181  4181 D BluetoothMapService: MAP Service closeService in
09-09 19:51:07.197  4181  4181 V BluetoothAdapterState: isTurningOff()=true
09-09 19:51:07.197  4181  4181 V BluetoothAdapterState: isTurningOn()=false
09-09 19:51:07.198  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:07.198  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:51:07.198  4181  4193 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 19:51:07.198  4181  4193 D BluetoothAdapterProperties: Setting state to 15
09-09 19:51:07.198  4181  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 19:51:07.199   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 19:51:07.199   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 19:51:07.199  4181  4193 I BluetoothAdapterState: Entering BleOnState
09-09 19:51:07.199  3953  3964 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 19:51:07.199  4181  4181 D BluetoothMapService: cleanup()
09-09 19:51:07.199  4181  4181 D BluetoothMapService: MAP Service closeService in
09-09 19:51:07.200  1369  2064 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 19:51:07.200  3953  3965 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 19:51:07.201  1369  1369 D BluetoothPbap: Proxy object disconnected
09-09 19:51:07.201  3953  3964 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 19:51:07.201  1369  1369 D PbapServerProfile: Bluetooth service disconnected
09-09 19:51:07.202  3953  3965 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 19:51:07.203  1369  2091 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 19:51:07.204  1369  2064 D BluetoothMap: onBluetoothStateChange: up=false
09-09 19:51:07.207  1369  1386 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 19:51:07.207  3953  3964 D BluetoothMap: onBluetoothStateChange: up=false
09-09 19:51:07.208   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 19:51:07.208  3953  3965 D BluetoothPan: onBluetoothStateChange on: false
09-09 19:51:07.208  1369  1381 D BluetoothPan: onBluetoothStateChange on: false
09-09 19:51:07.209   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 19:51:07.209  1369  2091 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 19:51:07.209  1990  2076 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 19:51:07.210  4181  4193 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 19:51:07.210  4181  4193 D BluetoothAdapterProperties: Setting state to 16
09-09 19:51:07.210  4181  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 19:51:07.211  4181  4193 D BluetoothAdapterProperties: onBleDisable
09-09 19:51:07.212  4181  4193 I BluetoothAdapterState: Entering PendingCommandState
09-09 19:51:07.212  4181  4194 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 19:51:07.214  4181  4203 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 19:51:07.214  4181  4203 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 19:51:07.214  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:07.214  4181  4197 D BluetoothAdapterProperties: Scan Mode:20
09-09 19:51:07.215  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:07.216  3953  3953 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 19:51:07.217  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:07.220  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:07.221  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:07.222  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:07.224  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 19:51:07.229  3953  3953 D DockEventReceiver: finishStartingService: stopping service
,09-09 19:51:07.419  4181  4197 I bt_hci  : shut_down
,09-09 19:51:07.437  4181  4201 D bt_hwcfg: hw_epilog_process
,09-09 19:51:07.438  4181  4201 I bt_vendor: low_power_mode_cb
,09-09 19:51:07.462  4181  4201 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-09 19:51:07.463  4181  4201 I bt_vendor: epilog_cb
,09-09 19:51:07.463  4181  4201 I bt_hci  : epilog_finished_callback
,09-09 19:51:07.470  4181  4197 I bt_hci_h4: hal_close
,09-09 19:51:07.471  4181  4197 I bt_userial_vendor: device fd = 51 close
,09-09 19:51:07.600  4181  4194 D bt_stack_manager: event_shut_down_stack finished.
,09-09 19:51:07.601  4181  4193 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 19:51:07.607  4181  4193 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 19:51:07.607  4181  4181 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 19:51:07.610  4181  4181 D BtGatt.GattService: Received stop request...Stopping profile...
,09-09 19:51:07.610  4181  4181 D BtGatt.GattService: stop()
09-09 19:51:07.611  4181  4181 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 19:51:07.617  4181  4181 V BluetoothAdapterState: isTurningOff()=false
,09-09 19:51:07.617  4181  4181 V BluetoothAdapterState: isTurningOn()=false
,09-09 19:51:07.618  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:07.618  4181  4181 V BluetoothAdapterState: isBleTurningOff()=true
09-09 19:51:07.619  4181  4193 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-09 19:51:07.619  4181  4193 D BluetoothAdapterProperties: Setting state to 10
09-09 19:51:07.620  4181  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-09 19:51:07.622  4181  4193 I BluetoothAdapterState: Entering OffState
09-09 19:51:07.623   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-09 19:51:07.642  4181  4181 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 19:51:07.643  4181  4181 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 19:51:07.643  4181  4194 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 19:51:07.646  4181  4194 D bt_stack_manager: event_clean_up_stack finished.
,09-09 19:51:07.646  4181  4181 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 19:51:07.648  4181  4181 I art     : System.exit called, status: 0
09-09 19:51:07.648  4181  4181 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 19:51:07.691   875  1693 I ActivityManager: Process com.android.bluetooth (pid 4181) has died
,09-09 19:51:12.118  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:51:12.119  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:51:12.123  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 19:51:12.124  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d35cecd removed from the list
09-09 19:51:12.124  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:51:12.124  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 19:51:12.124  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:51:12.127  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 19:51:12.128  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@50f3a93 added. We now have 4 listener(s)
09-09 19:51:12.128  3848  3897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 19:51:12.130  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 19:51:12.130  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@50f3a93 removed from the list
09-09 19:51:12.131  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:51:12.131  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 19:51:12.131  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:51:12.133  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 19:51:12.134  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c06ead0 added. We now have 4 listener(s)
,09-09 19:51:12.134  3848  3897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 19:51:17.148  3848  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:51:17.196   875   892 I ActivityManager: Start proc 4240:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 19:51:17.357  4240  4240 D AdapterServiceConfig: Adding HeadsetService
,09-09 19:51:17.358  4240  4240 D AdapterServiceConfig: Adding A2dpService
09-09 19:51:17.358  4240  4240 D AdapterServiceConfig: Adding HidService
09-09 19:51:17.358  4240  4240 D AdapterServiceConfig: Adding HealthService
09-09 19:51:17.358  4240  4240 D AdapterServiceConfig: Adding PanService
,09-09 19:51:17.359  4240  4240 D AdapterServiceConfig: Adding GattService
09-09 19:51:17.359  4240  4240 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 19:51:17.374   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f775c28:true
,09-09 19:51:17.375  4240  4240 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 19:51:17.380  4240  4240 I bt_bluedroid: init
,09-09 19:51:17.381  4240  4252 I BluetoothAdapterState: Entering OffState
,09-09 19:51:17.386  4240  4253 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 19:51:17.387  4240  4253 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-09 19:51:17.387  4240  4253 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 19:51:17.388  4240  4253 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 19:51:17.391  4240  4240 I bt_bluedroid: get_profile_interface socket
,09-09 19:51:17.394  4240  4240 I bt_bluedroid: get_profile_interface sdp
,09-09 19:51:17.396  4240  4256 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 19:51:17.399  4240  4251 I bt_bluedroid: config_hci_snoop_log
09-09 19:51:17.399  4240  4256 D BluetoothAdapterProperties: Name is: Nexus 6
09-09 19:51:17.400   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 19:51:17.409  4240  4252 D BluetoothAdapterState: Current state: OFF, message: 0
09-09 19:51:17.409  4240  4252 D BluetoothAdapterProperties: Setting state to 14
,09-09 19:51:17.410  4240  4252 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 19:51:17.414  4240  4252 D BluetoothBondStateMachine: make
,09-09 19:51:17.420  4240  4257 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 19:51:17.428  4240  4252 I BluetoothAdapterState: Entering PendingCommandState
,09-09 19:51:17.431  4240  4240 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 19:51:17.441  4240  4240 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
,09-09 19:51:17.443  4240  4240 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 19:51:17.445  4240  4240 D BtGatt.GattService: Received start request. Starting profile...
09-09 19:51:17.446  4240  4240 D BtGatt.GattService: start()
09-09 19:51:17.446  4240  4240 I bt_bluedroid: get_profile_interface gatt
,09-09 19:51:17.449  4240  4240 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
09-09 19:51:17.450  4240  4240 D BtGatt.AdvertiseManager: advertise manager created
,09-09 19:51:17.467  4240  4240 V BluetoothAdapterState: isTurningOff()=false
,09-09 19:51:17.467  4240  4240 V BluetoothAdapterState: isTurningOn()=false
09-09 19:51:17.467  4240  4240 V BluetoothAdapterState: isBleTurningOn()=true
09-09 19:51:17.468  4240  4240 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:51:17.469  4240  4252 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-09 19:51:17.470  4240  4252 I bt_bluedroid: enable
09-09 19:51:17.470  4240  4253 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-09 19:51:17.472  4240  4253 I bt_hci  : start_up
,09-09 19:51:17.493  4240  4253 I bt_vendor: alloc value 0xb3a1c189
,09-09 19:51:17.494  4240  4253 I bt_vendor: init
09-09 19:51:17.494  4240  4253 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 19:51:17.494  4240  4253 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 19:51:17.604  4240  4253 D bt_hci  : start_up starting async portion
,09-09 19:51:17.604  4240  4260 I bt_hci  : event_finish_startup
09-09 19:51:17.605  4240  4260 I bt_hci_h4: hal_open
,09-09 19:51:17.605  4240  4260 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 19:51:17.615  4240  4260 I bt_userial_vendor: device fd = 51 open
,09-09 19:51:17.646  4240  4260 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 19:51:17.678  4240  4260 D bt_hwcfg: Chipset BCM4354A2
,09-09 19:51:17.678  4240  4260 D bt_hwcfg: Target name = [BCM4354A2]
,09-09 19:51:17.679  4240  4260 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 19:51:18.336  4240  4260 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 19:51:18.338  4240  4260 D bt_hwcfg: Settlement delay -- 100 ms
09-09 19:51:18.338  4240  4260 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 19:51:18.455  4240  4260 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 19:51:18.456  4240  4260 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 19:51:18.486  4240  4260 I bt_hwcfg: vendor lib fwcfg completed
,09-09 19:51:18.486  4240  4260 I bt_vendor: firmware callback
,09-09 19:51:18.486  4240  4260 I bt_hci  : firmware_config_callback
,09-09 19:51:18.499  4240  4262 I bt_btu  : btu_task pending for preload complete event
,09-09 19:51:18.499  4240  4262 I bt_btu_task: Bluetooth chip preload is complete
09-09 19:51:18.499  4240  4262 I bt_btu  : btu_task received preload complete event
,09-09 19:51:18.509  4240  4262 I         : BTE_InitTraceLevels -- TRC_HCI
09-09 19:51:18.509  4240  4262 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 19:51:18.510  4240  4262 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 19:51:18.510  4240  4262 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 19:51:18.510  4240  4262 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 19:51:18.510  4240  4262 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 19:51:18.511  4240  4262 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-09 19:51:18.511  4240  4262 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 19:51:18.511  4240  4262 I         : BTE_InitTraceLevels -- TRC_GAP
,09-09 19:51:18.511  4240  4262 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 19:51:18.512  4240  4262 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 19:51:18.512  4240  4262 I         : BTE_InitTraceLevels -- TRC_GATT
,09-09 19:51:18.512  4240  4262 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 19:51:18.513  4240  4262 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 19:51:18.513  4240  4262 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 19:51:18.647  4240  4262 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3999d9d
,09-09 19:51:18.647  4240  4262 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3999d9d 
,09-09 19:51:18.658  4240  4256 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 19:51:18.660  4240  4256 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 19:51:18.661  4240  4256 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-09 19:51:18.663  4240  4256 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 19:51:18.667  4240  4256 D BluetoothAdapterProperties: Scan Mode:20
,09-09 19:51:18.667  4240  4256 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 19:51:18.668  4240  4256 D bt_hci  : do_postload posting postload work item
,09-09 19:51:18.668  4240  4260 I bt_hci  : event_postload
,09-09 19:51:18.668  4240  4260 I bt_vendor: sco_config_cb
,09-09 19:51:18.669  4240  4260 I bt_hci  : sco_config_callback postload finished.
,09-09 19:51:18.671  4240  4256 D bt_bte_conf: Device ID record 1 : primary
,09-09 19:51:18.672  4240  4256 D bt_bte_conf:   vendorId            = 000f
09-09 19:51:18.672  4240  4256 D bt_bte_conf:   vendorIdSource      = 0001
,09-09 19:51:18.672  4240  4256 D bt_bte_conf:   product             = 1200
09-09 19:51:18.672  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:51:18.673  4240  4256 D bt_bte_conf:   version             = 1436
,09-09 19:51:18.673  4240  4256 D bt_bte_conf:   clientExecutableURL = 
09-09 19:51:18.673  4240  4256 D bt_bte_conf:   serviceDescription  = 
09-09 19:51:18.673  4240  4256 D bt_bte_conf:   documentationURL    = 
,09-09 19:51:18.674  4240  4256 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-09 19:51:18.674  4240  4253 D bt_stack_manager: event_start_up_stack finished
,09-09 19:51:18.676  4240  4260 I bt_vendor: low_power_mode_cb
09-09 19:51:18.676  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:18.676  4240  4252 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 19:51:18.677  4240  4252 D BluetoothAdapterProperties: Setting state to 15
09-09 19:51:18.677  4240  4252 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15,
09-09 19:51:18.678  4240  4252 I BluetoothAdapterState: Entering BleOnState
09-09 19:51:18.684  4240  4252 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-09 19:51:18.684  4240  4252 D BluetoothAdapterProperties: Setting state to 11
09-09 19:51:18.684  4240  4252 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-09 19:51:18.693  4240  4240 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
,09-09 19:51:18.694  4240  4240 D HeadsetService: Received start request. Starting profile...
09-09 19:51:18.697  4240  4240 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 19:51:18.697  4240  4240 D HeadsetStateMachine: make
09-09 19:51:18.706  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:18.709  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:51:18.715  4240  4240 D HeadsetStateMachine: max_hf_connections = 1
,09-09 19:51:18.715  4240  4240 I bt_bluedroid: get_profile_interface handsfree
,09-09 19:51:18.715  4240  4256 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 19:51:18.715  4240  4256 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-09 19:51:18.716  4240  4252 I BluetoothAdapterState: Entering PendingCommandState
,09-09 19:51:18.720  4240  4240 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
,09-09 19:51:18.721  4240  4240 D A2dpService: Received start request. Starting profile...
09-09 19:51:18.721  4240  4240 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 19:51:18.721  4240  4240 I bt_bluedroid: get_profile_interface avrcp
,09-09 19:51:18.727  4240  4240 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 19:51:18.727  4240  4240 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 19:51:18.727  4240  4240 D A2dpStateMachine: make
,09-09 19:51:18.728  4240  4240 I bt_bluedroid: get_profile_interface a2dp
,09-09 19:51:18.728  4240  4256 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-09 19:51:18.730  4240  4271 D A2dpStateMachine: Enter Disconnected: -2
,09-09 19:51:18.733  4240  4240 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 19:51:18.733  4240  4240 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
,09-09 19:51:18.734  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 19:51:18.734  4240  4240 D HidService: Received start request. Starting profile...
09-09 19:51:18.734  4240  4240 I bt_bluedroid: get_profile_interface hidhost
09-09 19:51:18.734  4240  4256 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb397b3e5
09-09 19:51:18.734  4240  4240 D HidService: setHidService(): set to: null
09-09 19:51:18.735  4240  4256 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-09 19:51:18.736  4240  4240 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 19:51:18.737  4240  4240 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
09-09 19:51:18.737  4240  4240 D HealthService: Received start request. Starting profile...
,09-09 19:51:18.738  4240  4240 I bt_bluedroid: get_profile_interface health
,09-09 19:51:18.739  4240  4240 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-09 19:51:18.740  4240  4240 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
,09-09 19:51:18.740  4240  4240 D PanService: Received start request. Starting profile...
09-09 19:51:18.740  4240  4240 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 19:51:18.741  4240  4240 I bt_bluedroid: get_profile_interface pan
09-09 19:51:18.741  4240  4256 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 19:51:18.744  4240  4240 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
,09-09 19:51:18.745  4240  4240 D BluetoothMapService: Received start request. Starting profile...
09-09 19:51:18.745  4240  4240 D BluetoothMapService: start()
,09-09 19:51:18.748  4240  4240 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 19:51:18.748  4240  4240 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-09 19:51:18.748  4240  4240 D BluetoothMapAppObserver: createReceiver()
,09-09 19:51:18.750  4240  4240 D BluetoothMapAppObserver: initObservers()
09-09 19:51:18.750  4240  4240 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 19:51:18.756  4240  4240 V BluetoothAdapterState: isTurningOff()=false
,09-09 19:51:18.756  4240  4240 V BluetoothAdapterState: isTurningOn()=true
09-09 19:51:18.756  4240  4240 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:18.756  4240  4240 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 19:51:18.758  4240  4240 V BluetoothAdapterState: isTurningOff()=false
09-09 19:51:18.758  4240  4240 V BluetoothAdapterState: isTurningOn()=true
09-09 19:51:18.758  4240  4268 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-09 19:51:18.758  4240  4240 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:18.758  4240  4240 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:51:18.758  4240  4240 V BluetoothAdapterState: isTurningOff()=false
09-09 19:51:18.758  4240  4240 V BluetoothAdapterState: isTurningOn()=true
,09-09 19:51:18.758  4240  4240 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:18.758  4240  4240 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:51:18.760  4240  4240 V BluetoothAdapterState: isTurningOff()=false
09-09 19:51:18.760  4240  4240 V BluetoothAdapterState: isTurningOn()=true,
09-09 19:51:18.760  4240  4240 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:18.760  4240  4240 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:51:18.761  4240  4240 V BluetoothAdapterState: isTurningOff()=false
09-09 19:51:18.761  4240  4240 V BluetoothAdapterState: isTurningOn()=true
09-09 19:51:18.761  4240  4240 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:18.761  4240  4240 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 19:51:18.761  4240  4240 V BluetoothAdapterState: isTurningOff()=false
09-09 19:51:18.761  4240  4240 V BluetoothAdapterState: isTurningOn()=true
09-09 19:51:18.761  4240  4240 V BluetoothAdapterState: isBleTurningOn()=false
09-09 19:51:18.761  4240  4240 V BluetoothAdapterState: isBleTurningOff()=false
09-09 19:51:18.761  4240  4252 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 19:51:18.762  4240  4252 D BluetoothAdapterProperties: ScanMode =  20
09-09 19:51:18.762  4240  4252 D BluetoothAdapterProperties: State =  11
09-09 19:51:18.763  4240  4256 D BluetoothAdapterProperties: Scan Mode:21
09-09 19:51:18.763  4240  4252 D BluetoothAdapterProperties: Setting state to 12
09-09 19:51:18.764  4240  4252 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 19:51:18.764   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 19:51:18.764  4240  4256 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 19:51:18.764   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 19:51:18.765  4240  4252 I BluetoothAdapterState: Entering OnState
,09-09 19:51:18.765  3953  4233 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 19:51:18.767   875   875 D BluetoothA2dp: Proxy object connected
09-09 19:51:18.767  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:51:18.767  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:18.767  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:18.767  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 19:51:18.767  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:51:18.767  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:51:18.767  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:51:18.767  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 19:51:18.768  1369  2064 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 19:51:18.769  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:51:18.770  1369  1369 D BluetoothA2dp: Proxy object connected
,09-09 19:51:18.771  3953  3965 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 19:51:18.771  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:51:18.771  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:18.771  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:18.771  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 19:51:18.771  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:51:18.771  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:51:18.771  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:51:18.771  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 19:51:18.773  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:51:18.773  3953  3964 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 19:51:18.775  3953  4233 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 19:51:18.776  4240  4240 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 19:51:18.776  1369  1381 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 19:51:18.776  3953  3953 D BluetoothInputDevice: Proxy object connected
09-09 19:51:18.776  3953  3953 D HidProfile: Bluetooth service connected
09-09 19:51:18.776  4240  4240 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-09 19:51:18.777  1369  1369 D BluetoothInputDevice: Proxy object connected
09-09 19:51:18.777  1369  1369 D HidProfile: Bluetooth service connected
09-09 19:51:18.778  1369  1386 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 19:51:18.778  4240  4240 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 19:51:18.779  3953  3953 D BluetoothA2dp: Proxy object connected
09-09 19:51:18.780  1369  2064 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 19:51:18.780  4240  4240 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 19:51:18.781  4240  4240 D ObexServerSockets: Succeed to create listening sockets 
09-09 19:51:18.781  4240  4240 D ObexServerSockets0: startAccept()
09-09 19:51:18.781  4240  4240 D ObexServerSockets0: prepareForNewConnect()
,09-09 19:51:18.781  3953  3965 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 19:51:18.783  4240  4240 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-09 19:51:18.783  4240  4240 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 19:51:18.783   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 19:51:18.784  3953  3964 D BluetoothPan: onBluetoothStateChange on: true
09-09 19:51:18.784  1369  1369 D BluetoothMap: Proxy object connected
09-09 19:51:18.784  1369  1369 D MapProfile: Bluetooth service connected
09-09 19:51:18.784  4240  4278 D ObexServerSockets0: Accepting socket connection...
,09-09 19:51:18.784  1369  1369 D BluetoothMap: getConnectedDevices()
,09-09 19:51:18.784  4240  4277 D ObexServerSockets0: Accepting socket connection...
,09-09 19:51:18.784  3953  3953 D BluetoothMap: Proxy object connected
09-09 19:51:18.784  3953  3953 D MapProfile: Bluetooth service connected
09-09 19:51:18.785  3953  3953 D BluetoothMap: getConnectedDevices()
09-09 19:51:18.786  1369  1381 D BluetoothPan: onBluetoothStateChange on: true
,09-09 19:51:18.787  1369  1369 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 19:51:18.787   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 19:51:18.787  1369  1369 D PanProfile: Bluetooth service connected
09-09 19:51:18.787  1369  2064 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 19:51:18.787  3953  3953 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 19:51:18.787  3953  3953 D PanProfile: Bluetooth service connected
09-09 19:51:18.787  1990  2076 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 19:51:18.789   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 19:51:18.790  4240  4240 D BluetoothMapService: onReceive
09-09 19:51:18.790  4240  4240 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 19:51:18.790  4240  4240 D BluetoothMapService: STATE_ON
09-09 19:51:18.790  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:18.791  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:18.795  3953  3953 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 19:51:18.800  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 19:51:18.807  3953  3953 D DockEventReceiver: finishStartingService: stopping service
,09-09 19:51:18.808  3953  3953 D BluetoothPbap: Proxy object connected
,09-09 19:51:18.808  3953  3953 D PbapServerProfile: Bluetooth service connected
,09-09 19:51:18.812  4240  4283 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 19:51:18.812  1369  1369 D BluetoothPbap: Proxy object connected
09-09 19:51:18.812  1369  1369 D PbapServerProfile: Bluetooth service connected
,09-09 19:51:18.819  4240  4240 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 19:51:18.819  4240  4240 D ObexServerSockets0: prepareForNewConnect()
,09-09 19:51:18.822  4240  4287 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 19:51:18.823  4240  4287 I BtOppRfcommListener: Accept thread started.
,09-09 19:51:18.864  1369  2091 D BluetoothHeadset: Proxy object connected
,09-09 19:51:18.864  1369  1369 D HeadsetProfile: Bluetooth service connected
,09-09 19:51:18.865  3953  3964 D BluetoothHeadset: Proxy object connected
09-09 19:51:18.865   875   875 D BluetoothHeadset: Proxy object connected
09-09 19:51:18.865   875   875 D BluetoothHeadset: Proxy object connected
,09-09 19:51:18.865  3953  3953 D HeadsetProfile: Bluetooth service connected
09-09 19:51:18.865   875   875 D BluetoothHeadset: Proxy object connected
09-09 19:51:18.865  1990  2296 D BluetoothHeadset: Proxy object connected
,09-09 19:51:18.876  3953  4233 D BluetoothHeadset: Proxy object connected
,09-09 19:51:18.876  3953  3953 D HeadsetProfile: Bluetooth service connected
,09-09 19:51:18.883   875   892 D BluetoothHeadset: Proxy object connected
,09-09 19:51:18.886   875   892 D BluetoothHeadset: Proxy object connected
,09-09 19:51:18.888  1369  1386 D BluetoothHeadset: Proxy object connected
09-09 19:51:18.888  1369  1369 D HeadsetProfile: Bluetooth service connected
,09-09 19:51:18.890  1990  2005 D BluetoothHeadset: Proxy object connected
,09-09 19:51:22.168  3848  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:51:22.168  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:22.168  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:22.168  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 19:51:22.168  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:51:22.168  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:51:22.168  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:51:22.168  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 19:51:22.176  3848  3897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 19:51:22.177  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-09 19:51:22.178  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c06ead0 removed from the list
,09-09 19:51:22.178  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 19:51:22.178  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:22.179  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:51:22.182  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 19:51:22.183  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@75d8ac9 added. We now have 4 listener(s)
09-09 19:51:22.183  3848  3897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 19:51:22.189   875   886 D WifiService: setWifiEnabled: false pid=3848, uid=10000
,09-09 19:51:22.190   875   886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 19:51:25.792  1899  1966 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-09 19:51:25.792  1899  1966 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-09 19:51:25.841  1504  1504 I ConfigService: onCreate
,09-09 19:51:27.205  3848  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:51:27.206   875  2046 D WifiService: setWifiEnabled: true pid=3848, uid=10000
,09-09 19:51:27.206   875  2046 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 19:51:27.218   875  1310 D WifiConfigStore: Loading config and enabling all networks 
,09-09 19:51:27.236  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:51:27.236  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:27.236  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:27.236  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:51:27.236  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:51:27.236  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:51:27.236  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:51:27.236  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 19:51:27.242   875  1310 D WifiConfigStore: loaded 0 passpoint configs
,09-09 19:51:27.243   875  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-09 19:51:27.244   875  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 19:51:27.244  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 19:51:27.245   875  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-09 19:51:27.245   875  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 19:51:27.246   875  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 19:51:27.246   875  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 19:51:27.252  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:51:27.252  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:27.252  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:27.252  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:51:27.252  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:51:27.252  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 19:51:27.252  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 19:51:27.252  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 19:51:27.258  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 19:51:27.263   372   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 19:51:27.264   372   873 D CommandListener: Setting iface cfg
,09-09 19:51:27.264   875  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-09 19:51:27.265   875  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-09 19:51:27.265   875  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 19:51:27.317   875  1310 E native  : do suspend true
,09-09 19:51:27.317   875  1309 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 19:51:27.326   875  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 19:51:27.334   875  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 19:51:28.609   875  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 19:51:28.758   875  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.44 rxSuccessRate=11.75 delta 1000 -> 994
,09-09 19:51:28.760   875  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 19:51:28.760   875  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 19:51:28.785   875  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 19:51:28.858   875  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 19:51:28.860  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 19:51:29.329  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 19:51:29.430  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 19:51:29.431  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 19:51:29.443   875  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 19:51:29.457   875  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 19:51:29.458   875  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 19:51:29.458   875  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 19:51:29.480   875  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 19:51:29.494   372   873 D CommandListener: Setting iface cfg
,09-09 19:51:29.495   875  1310 D WifiStateMachine: Start Dhcp Watchdog 3
,09-09 19:51:29.503   875  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 19:51:29.536   875  4299 D DhcpClient: Receive thread started
,09-09 19:51:29.632   875  1310 E native  : do suspend false
,09-09 19:51:29.657   875  2095 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 19:51:29.677   875  4299 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null,
09-09 19:51:29.679   875  2095 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
09-09 19:51:29.683   875  2095 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 19:51:29.705   875  4299 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 19:51:29.706   875  2095 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 19:51:29.713   372   873 D CommandListener: Setting iface cfg
,09-09 19:51:29.725   875  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 19:51:29.726   875  2095 D DhcpClient: Scheduling renewal in 86399s
,09-09 19:51:29.728   875  1310 E native  : do suspend true
,09-09 19:51:29.766   875  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 19:51:29.770   875  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 19:51:29.771   875  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 19:51:29.776   875  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 19:51:29.777   875  1312 D ConnectivityService: Adding iface wlan0 to network 102
,09-09 19:51:29.817   875  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 19:51:29.818   875  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-09 19:51:29.823   875  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-09 19:51:29.825   875  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-09 19:51:29.830   875  1312 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-09 19:51:29.837   875  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 19:51:29.841   875  1312 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-09 19:51:29.842   875  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-09 19:51:29.842   875  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-09 19:51:29.842   875  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 19:51:29.842   875  1312 D ConnectivityService:    accepting network in place of null
09-09 19:51:29.842   875  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 19:51:29.843   875  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 19:51:29.867   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=217011, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 19:51:29.893   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 19:51:29.924   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 19:51:29.934   875  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-09 19:51:29.934   875  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 19:51:29.943   875  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-09 19:51:29.944   875   892 D Tethering: MasterInitialState.processMessage what=3
,09-09 19:51:29.965  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:51:29.965  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:29.965  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:29.965  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:51:29.965  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:51:29.965  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:51:29.965  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:51:29.965  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 19:51:29.965   875  4297 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-09 19:51:29.968  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 19:51:29.974  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:51:29.974  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:29.974  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:29.974  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:51:29.974  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:51:29.974  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:51:29.974  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:51:29.974  3848  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 19:51:29.977  3848  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 19:51:29.980  2067  2067 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-09 19:51:29.986  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 19:51:29.992  1715  1715 D SystemUpdateService: onCreate
,09-09 19:51:29.998  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 19:51:30.019  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-09 19:51:30.021  1715  2528 I iu.UploadsManager: num queued entries: 0
09-09 19:51:30.022  1715  2528 I iu.UploadsManager: num updated entries: 0
,09-09 19:51:30.026  1715  4308 I SystemUpdateService: active receiver: enabled
,09-09 19:51:30.028  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 19:51:30.030  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 19:51:30.036  1715  2528 I iu.SyncManager: NEXT; no task
09-09 19:51:30.036  1715  4308 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 19:51:30.038  4009  4009 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 19:51:30.042  1715  4308 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 19:51:30.042  1715  4308 I SystemUpdateService: now status is 0 (complete)
,09-09 19:51:30.044  1715  4308 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 19:51:30.044  1715  4308 I SystemUpdateService: file has been verified
,09-09 19:51:30.045  1715  4310 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-09 19:51:30.045  1715  4310 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 19:51:30.045  1715  4308 I SystemUpdateService: OTA package size = 12249756
,09-09 19:51:30.047  1715  4310 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 19:51:30.049  4009  4009 D SprintDMHelper: simOperator: 
09-09 19:51:30.049  4009  4009 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 19:51:30.066  1715  4308 I SystemUpdateService: showing system update notification
,09-09 19:51:30.070  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:51:30.072  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:51:30.099  3799  4315 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 19:51:30.101   875  4297 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 17:51:30 GMT], X-Android-Received-Millis=[1473443490101], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473443490057]}
09-09 19:51:30.102   875  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 19:51:30.102   875  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-09 19:51:30.103   875  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 19:51:30.104   875  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 19:51:30.163  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-09 19:51:30.164  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-09 19:51:30.164  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:51:30.164  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:51:30.168  1715  1715 D SystemUpdateService: onDestroy
,09-09 19:51:30.186  1715  4310 E MDM     : [184] SitrepService.a: Error sending sitrep.
,09-09 19:51:30.191  3142  4313 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 19:51:30.200  3799  4320 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 19:51:30.219  1504  1956 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 19:51:30.219  1504  1956 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 19:51:30.219  1504  1956 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:51:30.220  1504  1956 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:51:30.248  1504  2259 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 19:51:30.249  1504  2259 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 19:51:30.249  1504  2259 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 19:51:30.249  1504  2259 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:51:30.259  3799  4320 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 19:51:30.260  3799  4315 E BooksSync: Soft error
09-09 19:51:30.260  3799  4315 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 19:51:30.260  3799  4315 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 19:51:30.260  3799  4315 E BooksSync: Sync error
09-09 19:51:30.260  3799  4315 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 19:51:30.260  3799  4315 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 19:51:30.260  3799  4315 I BooksSync: Finished books sync
,09-09 19:51:30.269   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 213304, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 19:51:30.931  1504  1504 I ConfigService: onDestroy
,09-09 19:51:30.933   875  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-09 19:51:32.233  3848  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 19:51:32.233  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:32.233  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:32.233  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:51:32.233  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:51:32.233  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:51:32.233  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:51:32.233  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 19:51:32.240  3848  3897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 19:51:32.241  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:51:32.242  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@75d8ac9 removed from the list
,09-09 19:51:32.242  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:51:32.242  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:32.243  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:51:32.257  3848  4322 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-09 19:51:32.257  3848  4322 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 19:51:35.263  3848  4323 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-09 19:51:35.265  3848  4322 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-09 19:51:35.265  3848  4323 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-09 19:51:35.265  3848  4322 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-09 19:51:35.266  3848  4323 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 19:51:35.266  3848  4322 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 19:51:35.267  3848  4322 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 19:51:35.268  3848  4323 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 19:51:35.269  3848  4322 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-09 19:51:35.269  3848  4323 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-09 19:51:35.274  3848  4325 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: OutgoingSocketThread/Sender)
,09-09 19:51:35.277  3848  4326 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 424, name: IncomingSocketThread/Sender)
,09-09 19:51:35.279  3848  4327 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: OutgoingSocketThread/Receiver)
,09-09 19:51:35.281  3848  4327 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 426, thread name: OutgoingSocketThread/Receiver)
,09-09 19:51:35.281  3848  4327 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-09 19:51:35.281  3848  4327 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 426, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-09 19:51:35.283  3848  4328 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: IncomingSocketThread/Receiver)
09-09 19:51:35.284  3848  4328 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: IncomingSocketThread/Receiver)
09-09 19:51:35.284  3848  4328 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 19:51:35.284  3848  4328 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 19:51:37.849   875  1312 D ConnectivityService: handlePromptUnvalidated 102
,09-09 19:51:38.263  3848  3897 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-09 19:51:38.266  3848  3897 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 19:51:38.275  3848  3897 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5211732 Bundle[{}]
,09-09 19:51:38.276  3848  3897 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 19:51:38.276  3848  3897 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 19:51:38.277  3848  3897 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 19:51:38.278  3848  3897 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 19:51:38.278  3848  3897 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-09 19:51:38.279  3848  3897 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 19:51:38.284  3848  3897 I System.out: Running OutgoingSocketThread
,09-09 19:51:38.288  3848  4329 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-09 19:51:38.288  3848  4329 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 19:51:41.297  3848  4330 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-09 19:51:41.298  3848  4330 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-09 19:51:41.298  3848  4329 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-09 19:51:41.298  3848  4330 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 19:51:41.299  3848  4329 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 19:51:41.299  3848  4329 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 19:51:41.299  3848  4330 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 19:51:41.301  3848  4329 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 19:51:41.301  3848  4330 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-09 19:51:41.309  3848  4332 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: IncomingSocketThread/Sender)
,09-09 19:51:41.309  3848  4329 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 19:51:41.314  3848  4333 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: OutgoingSocketThread/Sender)
,09-09 19:51:41.317  3848  4334 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: IncomingSocketThread/Receiver)
09-09 19:51:41.318  3848  4334 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: IncomingSocketThread/Receiver)
09-09 19:51:41.318  3848  4334 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 19:51:41.319  3848  4334 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-09 19:51:41.319  3848  4335 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: OutgoingSocketThread/Receiver)
09-09 19:51:41.321  3848  4335 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: OutgoingSocketThread/Receiver)
09-09 19:51:41.321  3848  4335 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-09 19:51:41.322  3848  4335 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 19:51:44.300  3848  3897 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 448)
,09-09 19:51:44.303  3848  3897 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-09 19:51:44.303  3848  3897 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 449),
,09-09 19:51:44.309  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 19:51:44.310  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39385ce added. We now have 3 listener(s)
,09-09 19:51:44.312  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
09-09 19:51:44.312  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 19:51:44.312  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 19:51:44.313  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 19:51:44.313  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e8ecef added. We now have 4 listener(s)
09-09 19:51:44.313  3848  3897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
09-09 19:51:44.314  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 19:51:44.321  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 19:51:44.335  3848  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 19:51:44.335  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:44.335  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:44.335  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:51:44.335  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:51:44.335  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:51:44.335  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:51:44.335  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 19:51:44.342  3848  3897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 19:51:44.342  3848  3897 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 19:51:44.343  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 19:51:44.344  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 19:51:44.344  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 19:51:44.344  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:51:44.344  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:44.345  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 19:51:44.345  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 19:51:44.345  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39385ce removed from the list
09-09 19:51:44.345  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:51:44.346  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e8ecef removed from the list
,09-09 19:51:44.349  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:51:44.357  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:51:44.357  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:51:44.358  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:51:44.359  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:44.359  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:51:44.362  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 19:51:44.362  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:51:44.362  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:51:44.363  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e8ecef not in the list
09-09 19:51:44.363  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 19:51:44.363  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:51:44.366  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:51:44.366  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:51:44.367  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:51:44.367  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e8ecef not in the list
09-09 19:51:44.367  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 19:51:44.367  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:44.368  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:51:44.368  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39385ce not in the list
09-09 19:51:44.370  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 19:51:44.370  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2b0a85 added. We now have 3 listener(s)
,09-09 19:51:44.377  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 19:51:44.377  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 19:51:44.377  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 19:51:44.378  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 19:51:44.378  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96630da added. We now have 4 listener(s)
09-09 19:51:44.379  3848  3897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 19:51:44.381  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 19:51:44.388  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 19:51:44.401  3848  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 19:51:44.401  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:44.401  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:44.401  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:51:44.401  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:51:44.401  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:51:44.401  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:51:44.401  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 19:51:44.408  3848  3897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 19:51:44.408  3848  3897 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 19:51:44.409  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 19:51:44.409  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 19:51:44.410  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 19:51:44.410  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 19:51:44.410  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 19:51:44.417  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:51:44.421  3848  3897 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 19:51:44.421  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 19:51:44.426  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:51:44.433  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 19:51:44.436  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 19:51:44.436  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 19:51:44.448  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 19:51:44.448  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 19:51:44.449  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 19:51:44.451  3848  3897 D BluetoothAdapter: STATE_ON
,09-09 19:51:44.460  4240  4269 D BtGatt.GattService: registerClient() - UUID=c9ce4e18-15d0-421b-b474-246ed2cf102a
,09-09 19:51:44.462  4240  4256 D BtGatt.GattService: onClientRegistered() - UUID=c9ce4e18-15d0-421b-b474-246ed2cf102a, clientIf=5
,09-09 19:51:44.463  3848  3860 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 19:51:44.466  4240  4251 D BtGatt.GattService: start scan with filters
,09-09 19:51:44.477  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 19:51:44.477  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 19:51:44.477  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 19:51:44.477  4240  4259 D BtGatt.ScanManager: handling starting scan
09-09 19:51:44.478  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 19:51:44.483  4240  4259 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3836a6
,09-09 19:51:44.487  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 19:51:44.487  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 19:51:44.488  3848  3848 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 19:51:44.493  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 19:51:44.500  4240  4256 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 19:51:44.501  4240  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:51:44.502  4240  4259 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 19:51:44.503  3848  3897 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 19:51:44.503  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 19:51:44.503  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 19:51:44.504  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:44.504  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 19:51:44.504  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 19:51:44.504  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 19:51:44.504  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 19:51:44.504  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 19:51:44.504  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 19:51:44.504  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 19:51:44.506  3848  3897 D BluetoothAdapter: STATE_ON
09-09 19:51:44.508  4240  4269 D BtGatt.GattService: stopScan() - queue size =1
,09-09 19:51:44.511  4240  4251 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 19:51:44.513  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 19:51:44.513  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 19:51:44.513  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 19:51:44.514  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 19:51:44.514  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 19:51:44.516  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 19:51:44.516  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 19:51:44.516  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 19:51:44.517  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 19:51:44.517  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 19:51:44.518  3848  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 19:51:44.519  3848  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 19:51:44.519  3848  3848 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 19:51:44.522  4240  4256 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 19:51:44.522  4240  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,09-09 19:51:44.524  4240  4259 D BtGatt.ScanManager: Starting BLE batch scan
09-09 19:51:44.524  4240  4259 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 19:51:44.559  4240  4256 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 19:51:44.559  4240  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:51:44.580  4240  4256 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 19:51:44.581  4240  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:51:44.610  4240  4256 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 19:51:44.611  4240  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:51:44.611  4240  4259 D BtGatt.ScanManager: stopping BLe Batch
,09-09 19:51:44.635  4240  4256 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 19:51:44.636  4240  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:51:44.637  4240  4259 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 19:51:44.660  4240  4256 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 19:51:44.660  4240  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:51:45.021  3848  3848 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 19:51:45.021  3848  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 19:51:45.021  3848  3848 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 19:51:47.519  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 19:51:47.520  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 19:51:47.520  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 19:51:47.520  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 19:51:47.521  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:47.521  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 19:51:47.521  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 19:51:47.522  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2b0a85 removed from the list
,09-09 19:51:47.522  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:51:47.522  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96630da removed from the list
09-09 19:51:47.522  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 19:51:47.523  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:51:47.524  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:47.525  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:51:47.531  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:51:47.533  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 19:51:47.534  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 19:51:47.536  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96630da not in the list
,09-09 19:51:47.538  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:47.538  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:51:47.541  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:51:47.542  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 19:51:47.542  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 19:51:47.542  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96630da not in the list
09-09 19:51:47.543  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:51:47.543  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:47.543  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:51:47.544  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2b0a85 not in the list
,09-09 19:51:47.546  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 19:51:47.546  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fdb8ae7 added. We now have 3 listener(s)
,09-09 19:51:47.553  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 19:51:47.553  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 19:51:47.553  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 19:51:47.554  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 19:51:47.554  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a76b694 added. We now have 4 listener(s)
09-09 19:51:47.555  3848  3897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 19:51:47.556  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 19:51:47.562  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 19:51:47.568  3848  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 19:51:47.568  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:47.568  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:47.568  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:51:47.568  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:51:47.568  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:51:47.568  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:51:47.568  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 19:51:47.572  3848  3897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 19:51:47.572  3848  3897 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 19:51:47.573  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 19:51:47.574  3848  3897 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-09 19:51:47.574  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-09 19:51:47.575  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 19:51:47.575  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 19:51:47.575  3848  3897 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 19:51:47.575  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 19:51:47.576  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 19:51:47.577  3848  3897 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 19:51:47.577  3848  3897 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 19:51:47.577  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-09 19:51:47.577  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 19:51:47.577  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 19:51:47.577  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 19:51:47.578  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:51:47.582  3848  3897 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 19:51:47.583  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 19:51:47.583  3848  4336 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 19:51:47.584  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:47.584  3848  3848 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 19:51:47.588  3848  4336 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 19:51:47.592  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 19:51:47.593  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 19:51:47.594  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 19:51:47.598  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 19:51:47.599  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 19:51:47.600  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-09 19:51:47.603  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 19:51:47.604  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 19:51:47.604  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 19:51:47.606  3848  3897 D BluetoothAdapter: STATE_ON
,09-09 19:51:47.611  4240  4250 D BtGatt.GattService: registerClient() - UUID=612efc12-dadd-41bd-aaed-6bc5f317cb7a
,09-09 19:51:47.612  4240  4256 D BtGatt.GattService: onClientRegistered() - UUID=612efc12-dadd-41bd-aaed-6bc5f317cb7a, clientIf=5
,09-09 19:51:47.613  3848  3860 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-09 19:51:47.617  4240  4258 D BtGatt.AdvertiseManager: message : 0
,09-09 19:51:47.623  4240  4258 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 19:51:47.648  4240  4256 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 19:51:47.664  4240  4256 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 19:51:47.666  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 19:51:47.667  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 19:51:47.671  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 19:51:47.674  3848  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 19:51:47.675  3848  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 19:51:47.675  3848  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING,
09-09 19:51:47.675  3848  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 19:51:47.676  3848  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-09 19:51:47.676  3848  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 19:51:47.680  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 19:51:47.686  3848  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 19:51:47.687  3848  3848 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 19:51:48.188  3848  3848 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 19:51:48.189  3848  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 19:51:48.189  3848  3848 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 19:51:50.682  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 19:51:50.682  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-09 19:51:50.683  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 19:51:50.683  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 19:51:50.683  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 19:51:50.684  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-09 19:51:50.684  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 19:51:50.685  3848  3897 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 19:51:50.685  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 19:51:50.685  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 19:51:50.685  3848  3848 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 19:51:50.686  3848  4336 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 19:51:50.686  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 19:51:50.686  3848  4336 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 19:51:50.686  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 19:51:50.686  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 19:51:50.686  3848  4336 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 19:51:50.689  3848  3897 D BluetoothAdapter: STATE_ON
09-09 19:51:50.689  3848  3897 D BluetoothLeScanner: could not find callback wrapper
09-09 19:51:50.689  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 19:51:50.690  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 19:51:50.693  4240  4258 D BtGatt.AdvertiseManager: message : 1
,09-09 19:51:50.695  4240  4258 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-09 19:51:50.704  4240  4256 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-09 19:51:50.704  4240  4256 D BtGatt.GattService: Client app is not null!
,09-09 19:51:50.705  4240  4251 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 19:51:50.706  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 19:51:50.706  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 19:51:50.706  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 19:51:50.706  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 19:51:50.706  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-09 19:51:50.708  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 19:51:50.708  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 19:51:50.708  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 19:51:50.710  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 19:51:50.712  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 19:51:50.712  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:50.713  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 19:51:50.713  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 19:51:50.713  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fdb8ae7 removed from the list
09-09 19:51:50.713  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 19:51:50.714  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a76b694 removed from the list
09-09 19:51:50.714  3848  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 19:51:50.714  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:51:50.714  3848  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 19:51:50.714  3848  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 19:51:50.714  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:51:50.714  3848  3848 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 19:51:50.715  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:50.716  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:51:50.718  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:51:50.718  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 19:51:50.719  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:51:50.719  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a76b694 not in the list
09-09 19:51:50.719  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:50.720  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:51:50.722  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 19:51:50.722  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 19:51:50.723  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 19:51:50.723  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a76b694 not in the list
09-09 19:51:50.723  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:51:50.723  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:50.723  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:51:50.723  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fdb8ae7 not in the list
,09-09 19:51:50.724  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 19:51:50.724  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e61b839 added. We now have 3 listener(s)
09-09 19:51:50.726  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 19:51:50.726  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 19:51:50.726  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 19:51:50.726  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 19:51:50.726  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad2fe7e added. We now have 4 listener(s)
09-09 19:51:50.726  3848  3897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 19:51:50.727  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 19:51:50.730  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 19:51:50.737  3848  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 19:51:50.737  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:50.737  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:50.737  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:51:50.737  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:51:50.737  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:51:50.737  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:51:50.737  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 19:51:50.739  3848  3897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 19:51:50.740  3848  3897 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 19:51:50.740  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 19:51:50.740  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 19:51:50.740  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 19:51:50.740  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 19:51:50.740  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 19:51:50.742  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:51:50.745  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 19:51:50.747  3848  3897 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 19:51:50.747  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 19:51:50.755  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 19:51:50.757  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 19:51:50.757  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 19:51:50.763  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 19:51:50.763  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 19:51:50.763  3848  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 19:51:50.765  3848  3897 D BluetoothAdapter: STATE_ON
,09-09 19:51:50.769  4240  4276 D BtGatt.GattService: registerClient() - UUID=7329d1e6-5519-4ac3-a1f8-c9f03e75cf0a
,09-09 19:51:50.770  4240  4256 D BtGatt.GattService: onClientRegistered() - UUID=7329d1e6-5519-4ac3-a1f8-c9f03e75cf0a, clientIf=5
,09-09 19:51:50.770  3848  3859 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 19:51:50.771  4240  4251 D BtGatt.GattService: start scan with filters
,09-09 19:51:50.776  4240  4259 D BtGatt.ScanManager: handling starting scan
,09-09 19:51:50.776  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 19:51:50.776  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 19:51:50.776  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 19:51:50.777  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 19:51:50.783  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 19:51:50.784  3848  3848 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 19:51:50.784  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 19:51:50.788  4240  4256 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
,09-09 19:51:50.788  4240  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:51:50.788  4240  4259 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 19:51:50.789  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 19:51:50.799  4240  4256 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 19:51:50.799  4240  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:51:50.800  4240  4259 D BtGatt.ScanManager: Starting BLE batch scan
09-09 19:51:50.800  4240  4259 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 19:51:50.828  4240  4256 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 19:51:50.828  4240  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:51:50.839  4240  4256 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 19:51:50.839  4240  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:51:51.215  3848  3848 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 19:51:51.284  3848  3848 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 19:51:51.285  3848  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 19:51:51.285  3848  3848 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 19:51:52.346  4240  4240 D BtGatt.ScanManager: awakened up at time 239490
,09-09 19:51:52.349  4240  4259 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 19:51:52.379  4240  4256 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
09-09 19:51:52.379  4240  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 19:51:52.380  4240  4256 D BtGatt.GattService: current time is 239524854607
09-09 19:51:52.381  4240  4256 D BtGatt.GattService: Batch record : [87, 45, 110, 28, -13, -4, 1, -128, -72, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85, 0, 35, 97, 126, -92, 22, -56, 1, -128, -85, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -79, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
,09-09 19:51:52.385  4240  4256 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85]
,09-09 19:51:52.388  4240  4256 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 19:51:52.389  4240  4256 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-09 19:51:52.390  4240  4256 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,09-09 19:51:52.396  3848  3848 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 1], added - the peer count is 1
,09-09 19:51:52.397  3848  3848 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
,09-09 19:51:53.803  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 19:51:53.804  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 19:51:53.804  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 19:51:53.805  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:53.805  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 19:51:53.805  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 19:51:53.806  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 19:51:53.806  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 19:51:53.806  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 19:51:53.807  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 19:51:53.808  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 19:51:53.810  3848  3897 D BluetoothAdapter: STATE_ON
09-09 19:51:53.812  4240  4279 D BtGatt.GattService: stopScan() - queue size =1
,09-09 19:51:53.815  4240  4276 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 19:51:53.816  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 19:51:53.816  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 19:51:53.817  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 19:51:53.817  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 19:51:53.818  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 19:51:53.823  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 19:51:53.825  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 19:51:53.825  4240  4240 D BtGatt.ScanManager: awakened up at time 240970
,09-09 19:51:53.826  3848  3897 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 19:51:53.826  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 19:51:53.833  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 19:51:53.833  3848  3897 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,09-09 19:51:53.839  4240  4256 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 19:51:53.839  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 19:51:53.839  4240  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 19:51:53.839  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:53.840  3848  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 19:51:53.840  3848  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 19:51:53.840  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 19:51:53.840  4240  4259 D BtGatt.ScanManager: stopping BLe Batch
09-09 19:51:53.840  3848  3848 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 19:51:53.840  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 19:51:53.841  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e61b839 removed from the list
,09-09 19:51:53.842  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:51:53.842  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad2fe7e removed from the list
09-09 19:51:53.842  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:51:53.842  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:51:53.844  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:53.844  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:51:53.847  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 19:51:53.847  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:51:53.847  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:51:53.847  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad2fe7e not in the list
09-09 19:51:53.848  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:53.848  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 19:51:53.850  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:51:53.851  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 19:51:53.851  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:51:53.851  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad2fe7e not in the list
09-09 19:51:53.851  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:51:53.852  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 19:51:53.852  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:51:53.852  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e61b839 not in the list
,09-09 19:51:53.854  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 19:51:53.855  4240  4256 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 19:51:53.855  4240  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 19:51:53.855  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1d7718 added. We now have 3 listener(s)
09-09 19:51:53.856  4240  4259 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 19:51:53.860  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 19:51:53.860  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 19:51:53.861  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 19:51:53.861  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 19:51:53.861  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7653571 added. We now have 4 listener(s)
,09-09 19:51:53.862  3848  3897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 19:51:53.863  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 19:51:53.868  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 19:51:53.875  3848  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 19:51:53.875  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 19:51:53.875  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 19:51:53.875  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 19:51:53.875  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 19:51:53.875  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 19:51:53.875  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 19:51:53.875  3848  3897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 19:51:53.879  3848  3897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 19:51:53.879  3848  3897 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 19:51:53.879  4240  4256 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-09 19:51:53.879  4240  4256 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 19:51:53.880  4240  4256 D BtGatt.GattService: current time is 241024568445
,09-09 19:51:53.880  3848  3897 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 19:51:53.880  4240  4256 D BtGatt.GattService: Batch record : [-13, -12, 98, -123, 83, 73, 1, -128, -39, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 116, -43, -111, -91, -20, -29, 1, -128, -87, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
09-09 19:51:53.880  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-09 19:51:53.880  3848  3897 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 19:51:53.880  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 19:51:53.880  4240  4256 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
,09-09 19:51:53.880  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 19:51:53.880  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 19:51:53.880  4240  4256 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,09-09 19:51:53.880  3848  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 19:51:53.881  3848  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1d7718 removed from the list
,09-09 19:51:53.881  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:51:53.881  3848  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7653571 removed from the list
,09-09 19:51:53.884  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:53.885  3848  3897 D io.jxcore.node.ConnectivityMonitor: stop
09-09 19:51:53.885  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:51:53.886  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:53.886  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:51:53.887  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:51:53.887  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:51:53.887  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:51:53.887  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7653571 not in the list
09-09 19:51:53.887  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:53.887  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:51:53.889  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 19:51:53.889  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 19:51:53.889  3848  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 19:51:53.889  3848  3897 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7653571 not in the list
09-09 19:51:53.889  3848  3897 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 19:51:53.889  3848  3897 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 19:51:53.889  3848  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 19:51:53.889  3848  3897 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1d7718 not in the list
09-09 19:51:53.891  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 19:51:53.891  3848  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 19:51:53.891  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 19:51:53.891  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 19:51:53.891  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 19:51:53.891  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 19:51:53.891  3848  3897 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everythin,g
,09-09 19:51:54.341  3848  3848 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 19:51:55.908  3848  4338 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: My test thread name)
,09-09 19:51:57.906  3848  3897 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 458
,09-09 19:51:57.907  3848  3897 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 458, name: My test thread name)
,09-09 19:51:57.914  3848  4339 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: My test thread name)
,09-09 19:51:57.914  3848  4339 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 459, thread name: My test thread name)
09-09 19:51:57.914  3848  4339 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-09 19:51:57.922  3848  3897 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes,
,09-09 19:51:57.931  3848  4340 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 463, name: My test thread name),
09-09 19:51:57.932  3848  4340 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 463, thread name: My test thread name): Test exception.
09-09 19:51:57.932  3848  4340 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 463, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-09 19:51:57.938  3848  3897 I jxcore-log: Total number of executed tests:  82
,09-09 19:51:57.938  3848  3897 I jxcore-log: 
,09-09 19:51:57.938  3848  3897 I jxcore-log: Number of passed tests:  82,
09-09 19:51:57.938  3848  3897 I jxcore-log: 
09-09 19:51:57.939  3848  3897 I jxcore-log: Number of failed tests:  0
09-09 19:51:57.939  3848  3897 I jxcore-log: 
09-09 19:51:57.939  3848  3897 I jxcore-log: Number of ignored tests:  0
09-09 19:51:57.939  3848  3897 I jxcore-log: 
,09-09 19:51:57.940  3848  3897 I jxcore-log: Total duration:  101422
09-09 19:51:57.940  3848  3897 I jxcore-log: 
,09-09 19:51:57.949  3848  3897 I jxcore-log: Unit Test app is loaded
,09-09 19:51:57.949  3848  3897 I jxcore-log: 
,09-09 19:51:57.965  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,09-09 19:51:57.965  3848  3897 I jxcore-log: 
09-09 19:51:57.965  3848  3848 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-09 19:51:57.972  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-09 19:51:57.972  3848  3897 I jxcore-log: 
09-09 19:51:57.973  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:57.973  3848  3897 I jxcore-log: 
,09-09 19:51:57.974  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:57.974  3848  3897 I jxcore-log: 
09-09 19:51:57.975  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 19:51:57.975  3848  3897 I jxcore-log: 
,09-09 19:51:57.976  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 19:51:57.976  3848  3897 I jxcore-log: 
,09-09 19:51:57.980  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:57.980  3848  3897 I jxcore-log: 
,09-09 19:51:57.981  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:57.981  3848  3897 I jxcore-log: 
,09-09 19:51:57.982  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 19:51:57.982  3848  3897 I jxcore-log: 
,09-09 19:51:57.983  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 19:51:57.983  3848  3897 I jxcore-log: 
09-09 19:51:57.984  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 19:51:57.984  3848  3897 I jxcore-log: 
09-09 19:51:57.985  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:57.985  3848  3897 I jxcore-log: 
,09-09 19:51:57.986  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:57.986  3848  3897 I jxcore-log: 
,09-09 19:51:57.986  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:57.986  3848  3897 I jxcore-log: 
09-09 19:51:57.987  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 19:51:57.987  3848  3897 I jxcore-log: 
09-09 19:51:57.988  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 19:51:57.988  3848  3897 I jxcore-log: 
09-09 19:51:57.989  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 19:51:57.989  3848  3897 I jxcore-log: 
09-09 19:51:57.990  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 19:51:57.990  3848  3897 I jxcore-log: 
,09-09 19:51:57.990  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 19:51:57.990  3848  3897 I jxcore-log: 
09-09 19:51:57.991  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 19:51:57.991  3848  3897 I jxcore-log: 
09-09 19:51:57.992  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 19:51:57.992  3848  3897 I jxcore-log: 
09-09 19:51:57.993  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 19:51:57.993  3848  3897 I jxcore-log: 
,09-09 19:51:57.994  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 19:51:57.994  3848  3897 I jxcore-log: 
,09-09 19:51:57.995  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:57.995  3848  3897 I jxcore-log: 
,09-09 19:51:57.995  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:57.995  3848  3897 I jxcore-log: 
09-09 19:51:57.996  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:57.996  3848  3897 I jxcore-log: 
09-09 19:51:57.997  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 19:51:57.997  3848  3897 I jxcore-log: 
09-09 19:51:57.998  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 19:51:57.998  3848  3897 I jxcore-log: 
09-09 19:51:57.998  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 19:51:57.998  3848  3897 I jxcore-log: 
,09-09 19:51:57.999  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 19:51:57.999  3848  3897 I jxcore-log: 
,09-09 19:51:58.000  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 19:51:58.000  3848  3897 I jxcore-log: 
09-09 19:51:58.001  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 19:51:58.001  3848  3897 I jxcore-log: 
09-09 19:51:58.001  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 19:51:58.001  3848  3897 I jxcore-log: 
,09-09 19:51:58.002  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 19:51:58.002  3848  3897 I jxcore-log: 
,09-09 19:51:58.003  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 19:51:58.003  3848  3897 I jxcore-log: 
09-09 19:51:58.004  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 19:51:58.004  3848  3897 I jxcore-log: 
09-09 19:51:58.004  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 19:51:58.004  3848  3897 I jxcore-log: 
09-09 19:51:58.005  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 19:51:58.005  3848  3897 I jxcore-log: 
,09-09 19:51:58.006  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 19:51:58.006  3848  3897 I jxcore-log: 
09-09 19:51:58.006  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 19:51:58.006  3848  3897 I jxcore-log: 
09-09 19:51:58.007  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 19:51:58.007  3848  3897 I jxcore-log: 
,09-09 19:51:58.008  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 19:51:58.008  3848  3897 I jxcore-log: 
,09-09 19:51:58.009  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 19:51:58.009  3848  3897 I jxcore-log: 
,09-09 19:51:58.010  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:58.010  3848  3897 I jxcore-log: 
09-09 19:51:58.010  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:58.010  3848  3897 I jxcore-log: 
09-09 19:51:58.011  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:58.011  3848  3897 I jxcore-log: 
09-09 19:51:58.011  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:58.011  3848  3897 I jxcore-log: 
09-09 19:51:58.012  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:58.012  3848  3897 I jxcore-log: 
09-09 19:51:58.012  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 19:51:58.012  3848  3897 I jxcore-log: 
,09-09 19:51:58.013  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:58.013  3848  3897 I jxcore-log: 
09-09 19:51:58.013  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 19:51:58.013  3848  3897 I jxcore-log: 
09-09 19:51:58.014  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:58.014  3848  3897 I jxcore-log: 
09-09 19:51:58.014  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 19:51:58.014  3848  3897 I jxcore-log: 
09-09 19:51:58.015  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 19:51:58.015  3848  3897 I jxcore-log: 
,09-09 19:51:58.016  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-09 19:51:58.016  3848  3897 I jxcore-log: 
,09-09 19:51:58.017  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 19:51:58.017  3848  3897 I jxcore-log: 
09-09 19:51:58.017  3848  3897 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 19:51:58.017  3848  3897 I jxcore-log: 
09-09 19:51:58.020  3848  4338 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 458, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-09 19:51:58.023  3848  3897 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-09 19:51:58.023  3848  3897 I jxcore-log:   bluetooth: 'on',
09-09 19:51:58.023  3848  3897 I jxcore-log:   wifi: 'on',
09-09 19:51:58.023  3848  3897 I jxcore-log:   cellular: 'doNotCare',
09-09 19:51:58.023  3848  3897 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-09 19:51:58.023  3848  3897 I jxcore-log: 
,09-09 19:51:58.028  3848  3897 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-09 19:51:58.028  3848  3897 I jxcore-log:   bluetooth: 'on',
09-09 19:51:58.028  3848  3897 I jxcore-log:   wifi: 'on',
09-09 19:51:58.028  3848  3897 I jxcore-log:   cellular: 'doNotCare',
09-09 19:51:58.028  3848  3897 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-09 19:51:58.028  3848  3897 I jxcore-log: 
09-09 19:51:58.030  3848  3897 I jxcore-log: My device name is: motorola-Nexus 6
09-09 19:51:58.030  3848  3897 I jxcore-log: 
09-09 19:51:58.030  3848  3897 I jxcore-log: Running for WIFI network type
09-09 19:51:58.030  3848  3897 I jxcore-log: 
09-09 19:51:58.031  3848  3897 I jxcore-log: [TTR] ::  Looking for tests in bv_tests
09-09 19:51:58.031  3848  3897 I jxcore-log: 
,09-09 19:51:58.040  3848  3897 I jxcore-log: [TTR] ::  Going to execute 32 test file(s)
09-09 19:51:58.040  3848  3897 I jxcore-log: 
,09-09 19:51:58.045  3848  3897 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-09 19:51:58.046  3848  3897 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-09 19:51:58.046  3848  3897 I jxcore-log: 
,09-09 19:52:00.559  3799  4342 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 19:52:00.579  3799  4343 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 19:52:00.589  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:52:00.595  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:52:00.627  1504  2259 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 19:52:00.627  1504  2259 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 19:52:00.627  1504  2259 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:52:00.627  1504  2259 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:52:00.653  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:52:00.655  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:52:00.677  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 19:52:00.677  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 19:52:00.677  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 19:52:00.677  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:52:00.690  3799  4343 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 19:52:00.690  3799  4342 E BooksSync: Soft error
09-09 19:52:00.690  3799  4342 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 19:52:00.690  3799  4342 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 19:52:00.691  3799  4342 E BooksSync: Sync error
09-09 19:52:00.691  3799  4342 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 19:52:00.691  3799  4342 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 19:52:00.691  3799  4342 I BooksSync: Finished books sync
,09-09 19:52:00.707   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 247536, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 19:52:01.590  1504  2156 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 19:52:02.180  3848  3897 I jxcore-log: ThaliTape :: Started ThaliTape
09-09 19:52:02.180  3848  3897 I jxcore-log: 
,09-09 19:52:02.184  3848  3897 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-09 19:52:02.184  3848  3897 I jxcore-log: 
,09-09 19:52:02.532  3848  3897 I jxcore-log: ThaliTape :: Connected to the test server
09-09 19:52:02.532  3848  3897 I jxcore-log: 
,09-09 19:52:31.112  3079  4353 V KeepSync: Connecting to GoogleApiClient
,09-09 19:52:31.112   875  2046 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 19:52:31.172  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:52:31.174  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:52:31.225  1504  1956 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 19:52:31.225  1504  1956 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 19:52:31.226  1504  1956 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 19:52:31.226  1504  1956 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:52:31.251  1715  4354 V BaseAuthAsyncOperation: access token request failed
,09-09 19:52:31.252  3079  4353 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 19:52:31.305  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 19:52:31.305  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-09 19:52:31.305  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:52:31.305  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:52:31.320  3079  4353 E KeepSync: IOException
09-09 19:52:31.320  3079  4353 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 19:52:31.320  3079  4353 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 19:52:31.320  3079  4353 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 19:52:31.320  3079  4353 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 19:52:31.320  3079  4353 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 19:52:31.320  3079  4353 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 19:52:31.320  3079  4353 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 19:52:31.320  3079  4353 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 19:52:31.320  3079  4353 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 19:52:31.320  3079  4353 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 19:52:31.320  3079  4353 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 19:52:31.320  3079  4353 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 19:52:31.320  3079  4353 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 19:52:31.320  3079  4353 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 19:52:31.320  3079  4353 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 19:52:31.320  3079  4353 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 19:52:31.320  3079  4353 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 19:52:31.320  3079  4353 E KeepSync: 	... 10 more
09-09 19:52:31.320  3079  4353 W KeepSync: Sync result 2
,09-09 19:52:31.331   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 251274, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 19:53:01.473  3799  4362 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 19:53:01.565  3799  4364 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 19:53:01.577  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:53:01.579  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:53:01.618  1504  2259 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 19:53:01.618  1504  2259 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 19:53:01.618  1504  2259 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:53:01.618  1504  2259 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:53:01.641  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:53:01.643  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,09-09 19:53:01.669  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 19:53:01.669  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 19:53:01.669  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:53:01.669  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:53:01.730  3799  4364 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 19:53:01.730  3799  4362 E BooksSync: Soft error
09-09 19:53:01.730  3799  4362 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 19:53:01.730  3799  4362 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 19:53:01.731  3799  4362 E BooksSync: Sync error
09-09 19:53:01.731  3799  4362 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 19:53:01.731  3799  4362 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 19:53:01.731  3799  4362 I BooksSync: Finished books sync
,09-09 19:53:01.757   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 308096, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 19:53:01.764  1504  2257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 19:53:01.764  1504  2257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 19:53:01.764  1504  2257 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:53:01.764  1504  2257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:53:01.787  3029  4363 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 19:53:01.787  3029  4363 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at jdm.a(PG:82)
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at jcs.o(PG:406)
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at jcn.a(PG:1379)
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at jcs.i(PG:143)
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at blb.a(PG:3937)
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at czp.a(PG:18188)
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at czp.a(PG:9081)
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at czq.run(PG:1686)
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 19:53:01.787  3029  4363 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at jdj.a(PG:4091)
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at jdj.a(PG:1125)
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at jdm.a(PG:77)
09-09 19:53:01.787  3029  4363 E HttpOperation: 	... 12 more
09-09 19:53:01.787  3029  4363 E HttpOperation: Caused by: faj: BadAuthentication
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at fal.a(PG:38)
09-09 19:53:01.787  3029  4363 E HttpOperation: 	at jdj.a(PG:4089)
09-09 19:53:01.787  3029  4363 E HttpOperation: 	... 14 more
,09-09 19:53:01.854  1504  1956 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 19:53:01.854  1504  1956 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 19:53:01.854  1504  1956 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 19:53:01.854  1504  1956 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:53:01.891  3029  4363 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 19:53:01.891  3029  4363 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at jdm.a(PG:82)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at jcs.o(PG:406)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at jcn.a(PG:1379)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at jcs.i(PG:143)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at hec.a(PG:42)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at hee.a(PG:102)
,09-09 19:53:01.891  3029  4363 E HttpOperation: 	at czr.a(PG:65)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at kka.a(PG:108)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at czp.a(PG:19176)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at czp.a(PG:9081)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at czq.run(PG:1686)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 19:53:01.891  3029  4363 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at jdj.a(PG:4091)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at jdj.a(PG:1125)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at jdm.a(PG:77)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	... 15 more
,09-09 19:53:01.891  3029  4363 E HttpOperation: Caused by: faj: BadAuthentication
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at fal.a(PG:38)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	at jdj.a(PG:4089)
09-09 19:53:01.891  3029  4363 E HttpOperation: 	... 17 more
09-09 19:53:01.891  3029  4363 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 19:53:01.891  3029  4363 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at hec.a(PG:42)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	,at hee.a(PG:102)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at czr.a(PG:65)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at kka.a(PG:108)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	... 15 more
09-09 19:53:01.891  3029  4363 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at fal.a(PG:38)
09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	at jdj.a(PG:4089)
,09-09 19:53:01.891  3029  4363 E ExperimentLoader: 	... 17 more
,09-09 19:53:02.020   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 284903, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-09 19:53:32.167  3079  4367 V KeepSync: Connecting to GoogleApiClient
09-09 19:53:32.167   875  2047 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 19:53:32.211  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:53:32.212  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:53:32.238  1504  1956 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-09 19:53:32.238  1504  1956 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 19:53:32.238  1504  1956 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:53:32.238  1504  1956 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:53:32.255  1715  4368 V BaseAuthAsyncOperation: access token request failed
,09-09 19:53:32.256  3079  4367 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 19:53:32.307  1504  2259 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 19:53:32.307  1504  2259 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-09 19:53:32.307  1504  2259 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 19:53:32.307  1504  2259 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:53:32.325  3079  4367 E KeepSync: IOException
09-09 19:53:32.325  3079  4367 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 19:53:32.325  3079  4367 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 19:53:32.325  3079  4367 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 19:53:32.325  3079  4367 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 19:53:32.325  3079  4367 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 19:53:32.325  3079  4367 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 19:53:32.325  3079  4367 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 19:53:32.325  3079  4367 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 19:53:32.325  3079  4367 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 19:53:32.325  3079  4367 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 19:53:32.325  3079  4367 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 19:53:32.325  3079  4367 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 19:53:32.325  3079  4367 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 19:53:32.325  3079  4367 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 19:53:32.325  3079  4367 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 19:53:32.325  3079  4367 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 19:53:32.325  3079  4367 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 19:53:32.325  3079  4367 E KeepSync: 	... 10 more
,09-09 19:53:32.325  3079  4367 W KeepSync: Sync result 2
,09-09 19:53:32.339   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 309855, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 19:53:37.278  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:53:37.338  1504  2259 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-09 19:53:37.338  1504  2259 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-09 19:53:37.339  1504  2259 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 19:53:37.340  1504  2259 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:53:37.376  1504  2259 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 19:53:37.376  1504  2259 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 19:53:37.376  1504  2259 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 19:53:37.376  1504  2259 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-09 19:53:37.376  1504  2259 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-09 19:53:37.376  1504  2259 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-09 19:53:37.376  1504  2259 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 19:53:37.390  3586  3618 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 19:53:37.390  3586  3618 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-09 19:53:37.390  3586  3618 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-09 19:53:37.390  3586  3618 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-09 19:53:37.390  3586  3618 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-09 19:53:37.390  3586  3618 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-09 19:53:37.390  3586  3618 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 19:54:02.718  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:54:02.720  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:54:02.755  1504  1956 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 19:54:02.755  1504  1956 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 19:54:02.755  1504  1956 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:54:02.756  1504  1956 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:54:02.773  3029  4374 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 19:54:02.773  3029  4374 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at jdm.a(PG:82)
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at jcs.o(PG:406)
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at jcn.a(PG:1379)
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at jcs.i(PG:143)
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at blb.a(PG:3937)
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at czp.a(PG:18188)
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at czp.a(PG:9081)
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at czq.run(PG:1686)
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 19:54:02.773  3029  4374 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at jdj.a(PG:4091)
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at jdj.a(PG:1125)
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at jdm.a(PG:77)
09-09 19:54:02.773  3029  4374 E HttpOperation: 	... 12 more
09-09 19:54:02.773  3029  4374 E HttpOperation: Caused by: faj: BadAuthentication
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at fal.a(PG:38)
09-09 19:54:02.773  3029  4374 E HttpOperation: 	at jdj.a(PG:4089)
09-09 19:54:02.773  3029  4374 E HttpOperation: 	... 14 more
,09-09 19:54:02.819  1504  2259 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 19:54:02.819  1504  2259 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 19:54:02.819  1504  2259 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 19:54:02.819  1504  2259 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:54:02.835  3029  4374 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 19:54:02.835  3029  4374 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at jdm.a(PG:82)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at jcs.o(PG:406)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at jcn.a(PG:1379)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at jcs.i(PG:143)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at hec.a(PG:42)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at hee.a(PG:102)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at czr.a(PG:65)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at kka.a(PG:108)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at czp.a(PG:19176)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at czp.a(PG:9081)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at czq.run(PG:1686),
09-09 19:54:02.835  3029  4374 E HttpOperation: ,	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 19:54:02.835  3029  4374 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at jdj.a(PG:4091)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at jdj.a(PG:1125)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at jdm.a(PG:77)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	... 15 more
09-09 19:54:02.835  3029  4374 E HttpOperation: Caused by: faj: BadAuthentication
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at fal.a(PG:38)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	at jdj.a(PG:4089)
09-09 19:54:02.835  3029  4374 E HttpOperation: 	... 17 more
09-09 19:54:02.835  3029  4374 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 19:54:02.835  3029  4374 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at hec.a(PG:42)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at hee.a(PG:102)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at czr.a(PG:65)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at kka.a(PG:108)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	... 15 more
09-09 19:54:02.835  3029  4374 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at fal.a(PG:38)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 19:54:02.835  3029  4374 E ExperimentLoader: 	... 17 more
,09-09 19:54:02.987   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 340243, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-09 19:54:35.344  3079  4378 V KeepSync: Connecting to GoogleApiClient
,09-09 19:54:35.345   875  2048 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 19:54:35.404  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:54:35.406  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:54:35.444  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-09 19:54:35.444  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-09 19:54:35.445  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:54:35.445  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:54:35.467  1715  4379 V BaseAuthAsyncOperation: access token request failed
,09-09 19:54:35.469  3079  4378 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 19:54:35.530  1504  2257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 19:54:35.530  1504  2257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 19:54:35.531  1504  2257 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:54:35.531  1504  2257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:54:35.560  3079  4378 E KeepSync: IOException
09-09 19:54:35.560  3079  4378 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 19:54:35.560  3079  4378 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 19:54:35.560  3079  4378 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 19:54:35.560  3079  4378 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 19:54:35.560  3079  4378 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 19:54:35.560  3079  4378 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 19:54:35.560  3079  4378 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 19:54:35.560  3079  4378 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 19:54:35.560  3079  4378 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 19:54:35.560  3079  4378 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 19:54:35.560  3079  4378 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 19:54:35.560  3079  4378 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 19:54:35.560  3079  4378 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 19:54:35.560  3079  4378 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 19:54:35.560  3079  4378 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 19:54:35.560  3079  4378 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 19:54:35.560  3079  4378 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 19:54:35.560  3079  4378 E KeepSync: 	... 10 more
09-09 19:54:35.560  3079  4378 W KeepSync: Sync result 2
,09-09 19:54:35.579   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 402241, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 19:55:05.704  3799  4381 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 19:55:05.792  3799  4384 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 19:55:05.807  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:55:05.809  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:55:05.838  1504  2259 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 19:55:05.839  1504  2259 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 19:55:05.839  1504  2259 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:55:05.839  1504  2259 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:55:05.862  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:55:05.867  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:55:05.928  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 19:55:05.928  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 19:55:05.928  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:55:05.929  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:55:05.932  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 19:55:05.932  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 19:55:05.932  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:55:05.932  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:55:05.973  3029  4383 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 19:55:05.973  3029  4383 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at jdm.a(PG:82)
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at jcs.o(PG:406)
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at jcn.a(PG:1379)
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at jcs.i(PG:143)
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at blb.a(PG:3937)
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at czp.a(PG:18188)
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at czp.a(PG:9081)
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at czq.run(PG:1686)
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 19:55:05.973  3029  4383 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at jdj.a(PG:4091)
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at jdj.a(PG:1125)
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at jdm.a(PG:77)
09-09 19:55:05.973  3029  4383 E HttpOperation: 	... 12 more
09-09 19:55:05.973  3029  4383 E HttpOperation: Caused by: faj: BadAuthentication
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at fal.a(PG:38)
09-09 19:55:05.973  3029  4383 E HttpOperation: 	at jdj.a(PG:4089)
09-09 19:55:05.973  3029  4383 E HttpOperation: 	... 14 more
,09-09 19:55:05.985  3799  4384 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 19:55:05.986  3799  4381 E BooksSync: Soft error
09-09 19:55:05.986  3799  4381 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 19:55:05.986  3799  4381 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 19:55:05.986  3799  4381 E BooksSync: Sync error
09-09 19:55:05.986  3799  4381 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 19:55:05.986  3799  4381 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 19:55:05.990  3799  4381 I BooksSync: Finished books sync
,09-09 19:55:06.013   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 429389, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 19:55:06.043  1504  2257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 19:55:06.043  1504  2257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 19:55:06.043  1504  2257 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:55:06.043  1504  2257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:55:06.068  3029  4383 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 19:55:06.068  3029  4383 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at jdm.a(PG:82)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at jcs.o(PG:406)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at jcn.a(PG:1379)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at jcs.i(PG:143)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at hec.a(PG:42)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at hee.a(PG:102)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at czr.a(PG:65)
,09-09 19:55:06.068  3029  4383 E HttpOperation: 	at kka.a(PG:108)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at czp.a(PG:19176)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at czp.a(PG:9081)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at czq.run(PG:1686)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 19:55:06.068  3029  4383 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at jdj.a(PG:4091)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at jdj.a(PG:1125)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at jdm.a(PG:77)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	... 15 more
09-09 19:55:06.068  3029  4383 E HttpOperation: Caused by: faj: BadAuthentication
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at fal.a(PG:38)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	at jdj.a(PG:4089)
09-09 19:55:06.068  3029  4383 E HttpOperation: 	... 17 more
09-09 19:55:06.068  3029  4383 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 19:55:06.068  3029  4383 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at hec.a(PG:42)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at hee.a(PG:102)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at czr.a(PG:65)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at kka.a(PG:108)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	... 15 more
09-09 19:55:06.068  3029  4383 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at fal.a(PG:38)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 19:55:06.068  3029  4383 E ExperimentLoader: 	... 17 more
,09-09 19:55:06.198   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 432288, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-09 19:56:41.196  3079  4389 V KeepSync: Connecting to GoogleApiClient
,09-09 19:56:41.198   875  1692 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 19:56:41.268  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:56:41.273  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:56:41.317  1504  1956 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 19:56:41.318  1504  1956 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 19:56:41.318  1504  1956 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:56:41.318  1504  1956 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:56:41.346  1715  4390 V BaseAuthAsyncOperation: access token request failed
09-09 19:56:41.348  3079  4389 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 19:56:41.412  1504  2259 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-09 19:56:41.413  1504  2259 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 19:56:41.413  1504  2259 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:56:41.413  1504  2259 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:56:41.433  3079  4389 E KeepSync: IOException
09-09 19:56:41.433  3079  4389 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 19:56:41.433  3079  4389 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 19:56:41.433  3079  4389 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 19:56:41.433  3079  4389 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 19:56:41.433  3079  4389 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 19:56:41.433  3079  4389 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 19:56:41.433  3079  4389 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 19:56:41.433  3079  4389 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 19:56:41.433  3079  4389 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 19:56:41.433  3079  4389 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 19:56:41.433  3079  4389 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 19:56:41.433  3079  4389 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 19:56:41.433  3079  4389 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 19:56:41.433  3079  4389 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 19:56:41.433  3079  4389 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 19:56:41.433  3079  4389 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 19:56:41.433  3079  4389 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 19:56:41.433  3079  4389 E KeepSync: 	... 10 more
09-09 19:56:41.433  3079  4389 W KeepSync: Sync result 2
,09-09 19:56:41.446   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 528240, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 19:57:11.891  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:57:11.893  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 19:57:11.941  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 19:57:11.941  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 19:57:11.941  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 19:57:11.941  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:57:11.964  3029  4393 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 19:57:11.964  3029  4393 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at jdm.a(PG:82)
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at jcs.o(PG:406)
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at jcn.a(PG:1379)
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at jcs.i(PG:143)
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at blb.a(PG:3937)
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at czp.a(PG:18188)
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at czp.a(PG:9081)
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at czq.run(PG:1686)
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 19:57:11.964  3029  4393 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at jdj.a(PG:4091)
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at jdj.a(PG:1125)
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at jdm.a(PG:77)
09-09 19:57:11.964  3029  4393 E HttpOperation: 	... 12 more
09-09 19:57:11.964  3029  4393 E HttpOperation: Caused by: faj: BadAuthentication
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at fal.a(PG:38)
09-09 19:57:11.964  3029  4393 E HttpOperation: 	at jdj.a(PG:4089)
09-09 19:57:11.964  3029  4393 E HttpOperation: 	... 14 more
,09-09 19:57:12.051  1504  2257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 19:57:12.051  1504  2257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 19:57:12.051  1504  2257 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 19:57:12.051  1504  2257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 19:57:12.065  3029  4393 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 19:57:12.065  3029  4393 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at jdm.a(PG:82)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at jcs.o(PG:406)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at jcn.a(PG:1379)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at jcs.i(PG:143)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at hec.a(PG:42)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at hee.a(PG:102)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at czr.a(PG:65)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at kka.a(PG:108)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at czp.a(PG:19176)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at czp.a(PG:9081)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at czq.run(PG:1686)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 19:57:12.065  3029  4393 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at jdj.a(PG:4091)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at jdj.a(PG:1125)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at jdm.a(PG:77)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	... 15 more
09-09 19:57:12.065  3029  4393 E HttpOperation: Caused by: faj: BadAuthentication
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at fal.a(PG:38)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	at jdj.a(PG:4089)
09-09 19:57:12.065  3029  4393 E HttpOperation: 	... 17 more
09-09 19:57:12.066  3029  4393 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 19:57:12.066  3029  4393 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at hec.a(PG:42)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at hee.a(PG:102)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at czr.a(PG:65)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at kka.a(PG:108)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	... 15 more
09-09 19:57:12.066  3029  4393 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at fal.a(PG:38)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 19:57:12.066  3029  4393 E ExperimentLoader: 	... 17 more
,09-09 19:57:12.224   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 557655, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-09 19:59:12.002  1504  2156 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 20:02:51.213   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=898357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:02:59.466   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=906610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:03:16.320   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=923464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:03:24.519   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=931663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:03:41.333   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=948477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:03:49.586   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=956730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:04:06.400   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=973544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:04:14.639   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=981783, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:04:31.466   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=998610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:04:39.706   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1006850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:04:56.533   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1023677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:05:04.760   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1031904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:05:21.600   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1048744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:05:29.813   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1056957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:05:46.666   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1073810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:05:54.879   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1082023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:06:11.680   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1098824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:06:19.946   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1107090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:06:30.488  1715  4422 I EventLogService: Opted in for usage reporting
,09-09 20:06:30.488  1715  4422 I EventLogService: Aggregate from 1473442523077 (log), 1473442523077 (data)
,09-09 20:06:30.541  1715  4422 W EventLogAggregator: Unknown tag: snet_gcore
,09-09 20:06:30.541  1715  4422 W EventLogAggregator: Unknown tag: snet_launch_service
,09-09 20:06:30.650   875  2048 I ActivityManager: Start proc 4427:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,09-09 20:06:30.661  1715  4422 I ServiceDumpSys: dumping service [account]
,09-09 20:06:30.727  4427  4427 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,09-09 20:06:30.794  4427  4439 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-09 20:06:30.921  4427  4439 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-09 20:06:30.975  4427  4439 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-09 20:06:31.008  4427  4427 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,09-09 20:06:31.227  4427  4427 W InstanceID/Rpc: Found 10011
,09-09 20:06:31.246  4427  4478 W YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1035 Unknown task tag innertube_config_fetch_charging; aborting...
,09-09 20:06:31.346  4467  4467 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-796703701.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-796703701.dex
,09-09 20:06:31.400  4467  4467 I dex2oat : dex2oat took 55.594ms (threads: 4) arena alloc=170KB java alloc=29KB native alloc=1386KB free=1685KB
,09-09 20:06:31.432   875  2025 I ActivityManager: Killing 3745:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-09 20:07:01.840   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1148984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:07:10.080   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1157224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:07:26.933   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1174077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:07:35.146   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1182290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:07:42.293   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1189437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:08:00.213   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1207357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:08:07.360   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1214504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:08:11.741   875   887 I UsageStatsService: User[0] Flushing usage stats to disk
,09-09 20:08:25.280   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1232424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:08:32.426   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1239570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:08:50.333   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1257477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:08:57.493   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1264637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:09:15.400   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1282544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:09:22.533   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1289677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:09:40.453   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1307597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:09:47.599   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1314743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:10:05.520   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1332664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:10:12.667   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1339811, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:10:30.586   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1357730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:10:37.733   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1364877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:10:55.653   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1382797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:11:02.826   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1389970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:11:20.746   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1407890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:11:27.893   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1415037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:11:45.813   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1432957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:11:52.960   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1440104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:12:10.880   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1458024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:12:18.026   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1465170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:12:35.960   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1483104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:12:46.133   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1493277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:13:01.013   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1508157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 20:13:11.200   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1518344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 20:13:26.080   875  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1533224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,TIME-OUT KILL (timeout was 1400000ms),09-09 20:13:27.034  4524  4524 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 20:13:27.039  4524  4524 D AndroidRuntime: CheckJNI is OFF
09-09 20:13:27.075  4524  4524 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 20:13:27.116  4524  4524 I Radio-JNI: register_android_hardware_Radio DONE
09-09 20:13:27.139  4524  4524 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-09 20:13:27.152   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-09 20:13:27.153   875   888 I ActivityManager: Killing 3848:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-09 20:13:27.239   875  1380 D GraphicsStats: Buffer count: 2
09-09 20:13:27.239   875   885 I WindowState: WIN DEATH: Window{e0bbeea u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 20:13:27.241   875  1311 D WifiService: Client connection lost with reason: 4
09-09 20:13:27.282   875   898 W PackageSettings: Skipping PackageSetting{85f539b com.example.hello/10273} due to missing metadata
09-09 20:13:27.305   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-09 20:13:27.305   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-09 20:13:27.306   875   888 E ActivityManager: Failure starting process com.test.thalitest
09-09 20:13:27.306   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-09 20:13:27.306   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-09 20:13:27.306   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-09 20:13:27.306   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-09 20:13:27.306   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-09 20:13:27.306   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-09 20:13:27.306   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-09 20:13:27.306   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-09 20:13:27.306   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-09 20:13:27.306   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-09 20:13:27.306   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-09 20:13:27.306   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-09 20:13:27.306   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-09 20:13:27.306   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-09 20:13:27.306   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-09 20:13:27.306   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 20:13:27.306   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 20:13:27.306   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 20:13:27.306   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 20:13:27.307   875   888 I ActivityManager:   Force finishing activity ActivityRecord{10b9183 u0 com.test.thalitest/.MainActivity t4}
09-09 20:13:27.307   875   898 I art     : Starting a blocking GC Explicit
09-09 20:13:27.317   875  1692 W ActivityManager: Spurious death for ProcessRecord{ead4098 0:com.test.thalitest/u0a0}, curProc for 3848: null
09-09 20:13:27.363   875   898 I art     : Explicit concurrent mark sweep GC freed 22686(1823KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 788us total 54.487ms
09-09 20:13:27.383   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-09 20:13:27.385  4524  4524 I art     : System.exit called, status: 0
09-09 20:13:27.385  4524  4524 I AndroidRuntime: VM exiting with result code 0.
09-09 20:13:27.392   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-09 20:13:27.407   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-09 20:13:27.412  4240  4240 D BluetoothMapAppObserver: onReceive
09-09 20:13:27.412  4240  4240 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-09 20:13:27.413   875  1302 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 20:13:27.413  1865  2150 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 20:13:27.415  3687  3687 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-09 20:13:27.416  1899  1899 I Keyboard.Facilitator: resetDictionaries() : en_US
09-09 20:13:27.434  1899  4538 I Keyboard.Facilitator.DecoderInitializer: run()
09-09 20:13:27.437  1899  4538 I Decoder : createOrResetDecoder
09-09 20:13:27.454   875  2050 I ActivityManager: Start proc 4541:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-09 20:13:27.470  1990  1990 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-09 20:13:27.477  1504  1504 I ConfigService: onCreate
09-09 20:13:27.491   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 20:13:27.514  4541  4541 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-09 20:13:27.516  1504  4553 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
09-09 20:13:27.520  2003  2092 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-09 20:13:27.520   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-09 20:13:27.521   875   887 E PackageManager: Failed to write settings, restoring backup
09-09 20:13:27.521   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-09 20:13:27.521   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-09 20:13:27.521   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-09 20:13:27.521   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-09 20:13:27.521   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-09 20:13:27.521   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 20:13:27.521   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 20:13:27.521   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 20:13:27.526   875   888 E DropBoxManagerService: Can't write: system_server_wtf
09-09 20:13:27.526   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 20:13:27.526   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 20:13:27.526   875   888 E DropBoxManagerService: 	... 13 more
09-09 20:13:27.527   875  1396 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3848 uid 10000
09-09 20:13:27.532  1899  1899 I Keyboard.Facilitator: onFinishInput()
09-09 20:13:27.534   875  1693 I ActivityManager: Start proc 4554:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-09 20:13:27.535  2003  2092 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-09 20:13:27.535  2003  2092 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2003
09-09 20:13:27.535  2003  2092 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 20:13:27.535  2003  2092 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 20:13:27.535  2003  2092 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 20:13:27.535  2003  2092 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 20:13:27.535  2003  2092 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 20:13:27.535  2003  2092 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 20:13:27.535  2003  2092 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-09 20:13:27.535  2003  2092 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-09 20:13:27.535  2003  2092 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 20:13:27.535  2003  2092 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 20:13:27.535  2003  2092 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 20:13:27.535  2003  2092 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 20:13:27.537   875  2048 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 20:13:27.538   875  4560 E DropBoxManagerService: Can't write: system_app_crash
09-09 20:13:27.538   875  4560 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-09 20:13:27.538   875  4560 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 20:13:27.538   875  4560 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 20:13:27.538   875  4560 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 20:13:27.538   875  4560 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 20:13:27.538   875  4560 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 20:13:27.538   875  4560 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 20:13:27.538   875  4560 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 20:13:27.538   875  4560 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 20:13:27.538   875  4560 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 20:13:27.538   875  4560 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 20:13:27.538   875  4560 E DropBoxManagerService: 	... 5 more
09-09 20:13:27.539  2003  2092 I Process : Sending signal. PID: 2003 SIG: 9
09-09 20:13:27.566  1899  4538 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-09 20:13:27.590  1899  4538 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-09 20:13:27.592  1899  4538 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-09 20:13:27.592  1899  4538 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-09 20:13:27.604  1899  4538 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-09 20:13:27.604  1899  4538 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-09 20:13:27.606   875  2037 D GraphicsStats: Buffer count: 1
09-09 20:13:27.606   875  1692 I WindowState: WIN DEATH: Window{c05d0d8 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-09 20:13:27.612   875  2047 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2003) has died
09-09 20:13:27.613  1899  4538 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-09 20:13:27.613  1899  4538 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-09 20:13:27.614   875  2047 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-09 20:13:27.615  1899  4538 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-09 20:13:27.615  1899  4538 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-09 20:13:27.615  1899  4538 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-09 20:13:27.615  1899  4538 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-09 20:13:27.615  1899  4538 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-09 20:13:27.615  1899  4538 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-09 20:13:27.617   875  2047 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 20:13:27.644  4541  4569 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-09 20:13:27.645  4541  4569 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 20:13:27.647   875   888 I ActivityManager: Start proc 4572:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 20:13:27.653  4541  4541 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-09 20:13:27.666  4541  4584 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-09 20:13:27.674   875  2047 I ActivityManager: Start proc 4586:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-09 20:13:27.712  4586  4586 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 20:13:27.720  4572  4572 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 20:13:27.721  4572  4572 D AndroidRuntime: Shutting down VM
09-09 20:13:27.731  1715  4598 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-09 20:13:27.736  4572  4572 E AndroidRuntime: FATAL EXCEPTION: main
09-09 20:13:27.736  4572  4572 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4572
09-09 20:13:27.736  4572  4572 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 20:13:27.736  4572  4572 E AndroidRuntime: 	... 10 more
09-09 20:13:27.737   875  2025 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 20:13:27.739  4572  4572 I Process : Sending signal. PID: 4572 SIG: 9
09-09 20:13:27.739   875  4601 E DropBoxManagerService: Can't write: system_app_crash
09-09 20:13:27.739   875  4601 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-09 20:13:27.739   875  4601 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 20:13:27.739   875  4601 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 20:13:27.739   875  4601 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 20:13:27.739   875  4601 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 20:13:27.739   875  4601 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 20:13:27.739   875  4601 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 20:13:27.739   875  4601 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 20:13:27.739   875  4601 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 20:13:27.739   875  4601 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 20:13:27.739   875  4601 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 20:13:27.739   875  4601 E DropBoxManagerService: 	... 5 more
09-09 20:13:27.741  1715  4598 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-09 20:13:27.749  1715  4598 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-09 20:13:27.750  1715  4598 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-09 20:13:27.755   875  1396 I ActivityManager: Killing 2067:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
09-09 20:13:27.769  1504  1504 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-09 20:13:27.770  1504  1504 D AndroidRuntime: Shutting down VM
09-09 20:13:27.771  1504  1504 E AndroidRuntime: FATAL EXCEPTION: main
09-09 20:13:27.771  1504  1504 E AndroidRuntime: Process: com.google.process.gapps, PID: 1504
09-09 20:13:27.771  1504  1504 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-09 20:13:27.771  1504  1504 E AndroidRuntime: 	... 8 more
09-09 20:13:27.792  4541  4569 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-09 20:13:27.796   875  1311 D WifiService: Client connection lost with reason: 4
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 20:13:27.799  4541  4584 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-09 20:13:27.799  4541  4584 E AndroidRuntime: Process: android.process.acore, PID: 4541
09-09 20:13:27.799  4541  4584 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 20:13:27.799  4541  4584 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 20:13:27.800  4541  4569 I Process : Sending signal. PID: 4541 SIG: 9
09-09 20:13:27.806   875   886 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4572) has died
09-09 20:13:27.807   875   886 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-09 20:13:27.809   875  4603 E DropBoxManagerService: Can't write: system_app_crash
09-09 20:13:27.809   875  4603 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-09 20:13:27.809   875  4603 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 20:13:27.809   875  4603 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 20:13:27.809   875  4603 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 20:13:27.809   875  4603 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 20:13:27.809   875  4603 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 20:13:27.809   875  4603 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 20:13:27.809   875  4603 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 20:13:27.809   875  4603 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 20:13:27.809   875  4603 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 20:13:27.809   875  4603 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 20:13:27.809   875  4603 E DropBoxManagerService: 	... 5 more
09-09 20:13:27.816   875  4604 E DropBoxManagerService: Can't write: system_app_crash
09-09 20:13:27.816   875  4604 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-09 20:13:27.816   875  4604 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 20:13:27.816   875  4604 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 20:13:27.816   875  4604 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 20:13:27.816   875  4604 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 20:13:27.816   875  4604 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 20:13:27.816   875  4604 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 20:13:27.816   875  4604 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 20:13:27.816   875  4604 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 20:13:27.816   875  4604 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 20:13:27.816   875  4604 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 20:13:27.816   875  4604 E DropBoxManagerService: 	... 5 more
09-09 20:13:27.868   875   888 I ActivityManager: Start proc 4606:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 20:13:27.873   875  2047 I ActivityManager: Process android.process.acore (pid 4541) has died
09-09 20:13:27.873   875  2047 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
09-09 20:13:27.874  1504  1504 I Process : Sending signal. PID: 1504 SIG: 9

```
