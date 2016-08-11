#### Test 8091287736177d0_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-11 09:33:42.255  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 09:33:42.276  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 09:33:42.283  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 09:33:42.368  1526  1545 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-11 09:33:42.368  1526  1545 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-11 09:33:42.368  1526  1545 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 09:33:42.368  1526  1545 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-11 09:33:42.402  3360  3360 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-11 09:33:42.403  3360  3360 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-11 09:33:42.403  3360  3360 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-11 09:33:42.936  3627  3627 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-11 09:33:42.940  3627  3627 D AndroidRuntime: CheckJNI is OFF
08-11 09:33:42.978  3627  3627 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-11 09:33:43.021  3627  3627 I Radio-JNI: register_android_hardware_Radio DONE
08-11 09:33:43.041  3627  3627 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 09:33:43.045   872   883 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 09:33:43.088  1789  1802 W SearchService: Abort, client detached.
08-11 09:33:43.092  1789  2135 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d0fa877
08-11 09:33:43.092  1789  2154 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-11 09:33:43.092  1789  1789 I HotwordDetector: Closing mic
08-11 09:33:43.097  3627  3627 D AndroidRuntime: Shutting down VM
08-11 09:33:43.117   872  1411 I ActivityManager: Start proc 3637:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-11 09:33:43.151   376  2156 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-11 09:33:43.153   376  2156 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-11 09:33:43.161   376  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-11 09:33:43.165  1789  2138 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-11 09:33:43.162  1789  2153 I MicroRecognitionRnrImpl: Detection finished
08-11 09:33:43.201  3637  3637 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-11 09:33:43.232  3637  3637 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-11 09:33:43.243  3637  3637 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 9461-9466)
08-11 09:33:43.243  3637  3637 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 09:33:43.274  3637  3637 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3db2087}
08-11 09:33:43.276  3637  3637 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 09:33:43.277  3637  3637 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 09:33:43.295  3637  3637 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-11 09:33:43.298  3637  3637 E SysUtils: ApplicationContext is null in ApplicationStatus
08-11 09:33:43.329  3637  3637 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-11 09:33:43.371  3637  3637 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-11 09:33:43.371  3637  3637 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 09:33:43.371  3637  3637 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 09:33:43.371  3637  3637 I Adreno  : Build Date                       : 10/20/15
08-11 09:33:43.371  3637  3637 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 09:33:43.371  3637  3637 I Adreno  : Local Branch                     : M14
08-11 09:33:43.371  3637  3637 I Adreno  : Remote Branch                    : 
08-11 09:33:43.371  3637  3637 I Adreno  : Remote Branch                    : 
08-11 09:33:43.371  3637  3637 I Adreno  : Reconstruct Branch               : 
,08-11 09:33:43.474   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@63b49ec:true
,08-11 09:33:43.538  3637  3637 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-11 09:33:43.557  3637  3637 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-11 09:33:43.615  3637  3676 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 09:33:43.629  3637  3662 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-11 09:33:43.667  3637  3676 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 09:33:43.764   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +665ms
,08-11 09:33:43.783  1643  1643 I Keyboard.Facilitator: onFinishInput()
,08-11 09:33:43.890  3637  3637 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3637
,08-11 09:33:43.946   872  1758 I ActivityManager: Killing 3048:com.google.android.gm/u0a78 (adj 15): empty #17
,08-11 09:33:43.995  3637  3637 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 09:33:44.010   872  1758 I ActivityManager: Killing 2919:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-11 09:33:44.163  3637  3678 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1682769616
,08-11 09:33:44.171  3637  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 09:33:44.171  3637  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 09:33:44.171  3637  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 09:33:44.171  3637  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 09:33:44.171  3637  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-11 09:33:44.171  3637  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70b596a added. We now have 1 listener(s)
,08-11 09:33:44.174  3637  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-11 09:33:44.175  3637  3678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-11 09:33:44.175  3637  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 09:33:44.175  3637  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-11 09:33:44.182  3637  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 09:33:44.182  3637  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 09:33:44.182  3637  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 09:33:44.182  3637  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-11 09:33:44.182  3637  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 09:33:44.182  3637  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 09:33:44.182  3637  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 09:33:44.182  3637  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 09:33:44.182  3637  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 09:33:44.182  3637  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 09:33:44.182  3637  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 09:33:44.182  3637  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 09:33:44.182  3637  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 09:33:44.182  3637  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 09:33:44.182  3637  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7637d1 added. We now have 1 listener(s)
08-11 09:33:44.182  3637  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 09:33:44.185   872  1307 D WifiService: New client listening to asynchronous messages
,08-11 09:33:44.186  3637  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 09:33:44.186  3637  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-11 09:33:44.186  3637  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-11 09:33:44.187  3637  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-11 09:33:44.187  3637  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-11 09:33:44.190  3637  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 09:33:44.190  3637  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-11 09:33:44.196  3637  3678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-11 09:33:44.197  3637  3678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 09:33:44.197  3637  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 09:33:44.197  3637  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 09:33:44.197  3637  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 09:33:44.197  3637  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 09:33:44.197  3637  3678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 09:33:44.197  3637  3678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 09:33:44.197  3637  3678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 09:33:44.197  3637  3678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 09:33:44.197  3637  3678 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 09:33:44.200  3637  3637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 09:33:44.202  3637  3637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 09:33:44.202  3637  3678 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-11 09:33:44.229  3637  3637 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 09:33:45.484  3637  3688 W jxcore-log: Initializing JXcore engine
,08-11 09:33:45.484  3637  3688 W jxcore-log: JXcore engine is ready
,08-11 09:33:45.532  3688  3688 W Thread-326: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8980 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-11 09:33:45.532  3688  3688 W Thread-326: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11464]" dev="sockfs" ino=11464 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
08-11 09:33:45.532  3688  3688 W Thread-326: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-11 09:33:45.532  3688  3688 W Thread-326: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24863]" dev="sockfs" ino=24863 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-11 09:33:45.545  3637  3688 W jxcore-log: Starting JXcore engine
,08-11 09:33:45.623  3637  3688 W jxcore-log: Platform android
08-11 09:33:45.623  3637  3688 W jxcore-log: 
,08-11 09:33:45.623  3637  3688 W jxcore-log: Process ARCH arm
08-11 09:33:45.623  3637  3688 W jxcore-log: 
,08-11 09:33:45.789  3637  3688 I jxcore-log: JXcore Cordova bridge is ready!
08-11 09:33:45.789  3637  3688 I jxcore-log: 
,08-11 09:33:45.790  3637  3688 W jxcore-log: JXcore engine is started
,08-11 09:33:45.802  3637  3678 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-11 09:33:45.809  3637  3637 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-11 09:33:46.348   872  1306 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-11 09:33:49.249  2899  3694 V KeepSync: Connecting to GoogleApiClient
,08-11 09:33:49.249   872   883 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 09:33:49.284  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 09:33:49.285  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 09:33:49.317  1526  1862 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-11 09:33:49.317  1526  1862 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-11 09:33:49.317  1526  1862 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 09:33:49.317  1526  1862 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 09:33:49.337  1978  3695 V BaseAuthAsyncOperation: access token request failed
,08-11 09:33:49.338  2899  3694 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 09:33:49.383  1526  1868 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-11 09:33:49.383  1526  1868 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-11 09:33:49.383  1526  1868 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 09:33:49.383  1526  1868 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 09:33:49.404  2899  3694 E KeepSync: IOException
08-11 09:33:49.404  2899  3694 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 09:33:49.404  2899  3694 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 09:33:49.404  2899  3694 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 09:33:49.404  2899  3694 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 09:33:49.404  2899  3694 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 09:33:49.404  2899  3694 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 09:33:49.404  2899  3694 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 09:33:49.404  2899  3694 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 09:33:49.404  2899  3694 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 09:33:49.404  2899  3694 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 09:33:49.404  2899  3694 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 09:33:49.404  2899  3694 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 09:33:49.404  2899  3694 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 09:33:49.404  2899  3694 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 09:33:49.404  2899  3694 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 09:33:49.404  2899  3694 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 09:33:49.404  2899  3694 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 09:33:49.404  2899  3694 E KeepSync: 	... 10 more
,08-11 09:33:49.404  2899  3694 W KeepSync: Sync result 2
,08-11 09:33:49.413   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 124982, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 09:33:56.056  3637  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 09:33:56.056  3637  3688 I jxcore-log: 
,08-11 09:33:56.059  3637  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 09:33:56.059  3637  3688 I jxcore-log: 
,08-11 09:33:56.070  3637  3688 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 09:33:56.070  3637  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 09:33:56.070  3637  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 09:33:56.070  3637  3688 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 09:33:56.070  3637  3688 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 09:33:56.070  3637  3688 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 09:33:56.070  3637  3688 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 09:33:56.070  3637  3688 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 09:33:56.074  3637  3688 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 09:33:56.077  3637  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 09:33:56.077  3637  3688 I jxcore-log: 
,08-11 09:33:56.079  3637  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 09:33:56.079  3637  3688 I jxcore-log: 
,08-11 09:33:56.421  3637  3688 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-11 09:33:56.422  3637  3688 I jxcore-log: Failed to execute UT.
08-11 09:33:56.422  3637  3688 I jxcore-log: 
,08-11 09:33:56.422  3637  3688 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 09:33:56.422  3637  3688 I jxcore-log: 
08-11 09:33:56.425  3637  3688 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 09:33:56.425  3637  3688 I jxcore-log: 
,08-11 09:33:56.442  3637  3637 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-11 09:33:57.062  3705  3705 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-11 09:33:57.066  3705  3705 D AndroidRuntime: CheckJNI is OFF
,08-11 09:33:57.103  3705  3705 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-11 09:33:57.151  3705  3705 I Radio-JNI: register_android_hardware_Radio DONE
,08-11 09:33:57.171  3705  3705 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 09:33:57.194   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-11 09:33:57.195   872   885 I ActivityManager: Killing 3637:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-11 09:33:57.279   872   895 W PackageSettings: Skipping PackageSetting{ba4f222 com.example.hello/10273} due to missing metadata
,08-11 09:33:57.306   872  1750 I WindowState: WIN DEATH: Window{89b061c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 09:33:57.306   872   883 D GraphicsStats: Buffer count: 2
08-11 09:33:57.306   872  1307 D WifiService: Client connection lost with reason: 4
,08-11 09:33:57.312   872   895 I art     : Starting a blocking GC Explicit
,08-11 09:33:57.340   872   885 W ActivityManager: Force removing ActivityRecord{9acf98d u0 com.test.thalitest/.MainActivity t8}: app died, no saved state
,08-11 09:33:57.356   872  2989 W ActivityManager: Spurious death for ProcessRecord{db1670a 0:com.test.thalitest/u0a0}, curProc for 3637: null
,08-11 09:33:57.373   872   895 I art     : Explicit concurrent mark sweep GC freed 40635(2MB) AllocSpace objects, 11(212KB) LOS objects, 33% free, 28MB/43MB, paused 883us total 59.530ms
,08-11 09:33:57.401   872  1411 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3637 uid 10000
08-11 09:33:57.403  1643  1643 I Keyboard.Facilitator: onFinishInput()
,08-11 09:33:57.403   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-11 09:33:57.406  3705  3705 I art     : System.exit called, status: 0
08-11 09:33:57.406  3705  3705 I AndroidRuntime: VM exiting with result code 0.
,08-11 09:33:57.414   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-11 09:33:57.428  2543  2543 D BluetoothMapAppObserver: onReceive
,08-11 09:33:57.428  2543  2543 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-11 09:33:57.433  1902  2031 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-11 09:33:57.451  3472  3472 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-11 09:33:57.455   872  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 09:33:57.458  1643  1643 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-11 09:33:57.471  1643  3718 I Keyboard.Facilitator.DecoderInitializer: run()
,08-11 09:33:57.473  1643  3718 I Decoder : createOrResetDecoder
,08-11 09:33:57.499  1709  1709 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-11 09:33:57.514  1526  1526 I ConfigService: onCreate
,08-11 09:33:57.547  1789  3724 I MicroRecognitionRnrImpl: Starting detection.
,08-11 09:33:57.548  1789  3725 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@235936d
,08-11 09:33:57.550   376  3727 I AudioFlinger: AudioFlinger's thread 0xb1e00000 ready to run
08-11 09:33:57.557   376  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-11 09:33:57.558  1789  3725 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@235936d
08-11 09:33:57.563   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-11 09:33:57.568   376  3727 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-11 09:33:57.568   376  3727 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-11 09:33:57.568   376  3727 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-11 09:33:57.576   376  3727 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-11 09:33:57.577  1643  3718 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-11 09:33:57.582  1774  1815 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-11 09:33:57.582  1526  1526 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-11 09:33:57.582  1526  1526 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-11 09:33:57.583  1774  1815 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-11 09:33:57.583  1774  1815 E AndroidRuntime: Process: android.process.acore, PID: 1774
08-11 09:33:57.583  1774  1815 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 09:33:57.583  1774  1815 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-11 09:33:57.583  1774  1815 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-11 09:33:57.583  1774  1815 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-11 09:33:57.583  1774  1815 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-11 09:33:57.583  1774  1815 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-11 09:33:57.583  1774  1815 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-11 09:33:57.583  1774  1815 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
08-11 09:33:57.583  1774  1815 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
08-11 09:33:57.583  1774  1815 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
08-11 09:33:57.583  1774  1815 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-11 09:33:57.583  1774  1815 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 09:33:57.583  1774  1815 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 09:33:57.583  1774  1815 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 09:33:57.583  1526  1526 E AndroidRuntime: FATAL EXCEPTION: main
08-11 09:33:57.583  1526  1526 E AndroidRuntime: Process: com.google.process.gapps, PID: 1526
,08-11 09:33:57.583  1526  1526 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499),
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-11 09:33:57.583  1526  1526 E AndroidRuntime: 	... 8 more
,08-11 09:33:57.590   872  3732 E DropBoxManagerService: Can't write: system_app_crash
08-11 09:33:57.590   872  3732 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
08-11 09:33:57.590   872  3732 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 09:33:57.590   872  3732 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 09:33:57.590   872  3732 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 09:33:57.590   872  3732 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 09:33:57.590   872  3732 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 09:33:57.590   872  3732 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 09:33:57.590   872  3732 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 09:33:57.590   872  3732 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 09:33:57.590   872  3732 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 09:33:57.590   872  3732 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 09:33:57.590   872  3732 E DropBoxManagerService: 	... 5 more
,08-11 09:33:57.597  1774  3730 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-11 09:33:57.604   872  3733 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 09:33:57.621  1643  3718 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-11 09:33:57.624  1643  3718 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-11 09:33:57.624  1643  3718 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-11 09:33:57.627  1643  3718 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-11 09:33:57.627  1643  3718 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-11 09:33:57.628  1774  3730 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-11 09:33:57.629  1774  3730 I Process : Sending signal. PID: 1774 SIG: 9
08-11 09:33:57.629  1725  1821 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-11 09:33:57.631  1643  3718 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-11 09:33:57.631  1643  3718 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-11 09:33:57.632  1643  3718 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-11 09:33:57.632  1643  3718 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-11 09:33:57.633  1643  3718 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-11 09:33:57.633  1643  3718 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-11 09:33:57.633  1643  3718 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-11 09:33:57.634  1643  3718 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-11 09:33:57.637   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-11 09:33:57.638   872  3733 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 09:33:57.638   872  3733 I Adreno  : Build Date                       : 10/20/15
08-11 09:33:57.638   872  3733 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 09:33:57.638   872  3733 I Adreno  : Local Branch                     : M14
08-11 09:33:57.638   872  3733 I Adreno  : Remote Branch                    : 
08-11 09:33:57.638   872  3733 I Adreno  : Remote Branch                    : 
08-11 09:33:57.638   872  3733 I Adreno  : Reconstruct Branch               : 
,08-11 09:33:57.640   872   884 E PackageManager: Failed to write settings, restoring backup
08-11 09:33:57.640   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-11 09:33:57.640   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-11 09:33:57.640   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-11 09:33:57.640   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-11 09:33:57.640   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-11 09:33:57.640   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 09:33:57.640   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-11 09:33:57.640   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 09:33:57.642   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-11 09:33:57.642   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-11 09:33:57.642   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 09:33:57.642   872   885 E DropBoxManagerService: 	... 13 more
,08-11 09:33:57.644   872  3733 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 09:33:57.648   872  1371 I ActivityManager: Start proc 3735:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-11 09:33:57.648  1725  1821 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-11 09:33:57.648  1725  1821 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1725
08-11 09:33:57.648  1725  1821 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 09:33:57.648  1725  1821 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 09:33:57.648  1725  1821 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 09:33:57.648  1725  1821 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 09:33:57.648  1725  1821 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 09:33:57.648  1725  1821 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 09:33:57.648  1725  1821 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-11 09:33:57.648  1725  1821 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-11 09:33:57.648  1725  1821 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 09:33:57.648  1725  1821 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 09:33:57.648  1725  1821 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 09:33:57.648  1725  1821 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 09:33:57.650   872  1758 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-11 09:33:57.651  1789  1789 I HotwordWorkerImpl: onReady
08-11 09:33:57.652  1789  1801 W SearchService: Abort, client detached.
08-11 09:33:57.659   872  3740 E DropBoxManagerService: Can't write: system_app_crash
08-11 09:33:57.659   872  3740 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-11 09:33:57.659   872  3740 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 09:33:57.659   872  3740 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 09:33:57.659   872  3740 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 09:33:57.659   872  3740 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 09:33:57.659   872  3740 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 09:33:57.659   872  3740 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 09:33:57.659   872  3740 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 09:33:57.659   872  3740 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 09:33:57.659   872  3740 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 09:33:57.659   872  3740 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 09:33:57.659   872  3740 E DropBoxManagerService: 	... 5 more
08-11 09:33:57.669  1789  1789 I HotwordDetector: Closing mic
08-11 09:33:57.670  1789  2135 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@235936d
08-11 09:33:57.674  1789  3725 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-11 09:33:57.676  1789  3752 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-11 09:33:57.709   872  1371 I ActivityManager: Process android.process.acore (pid 1774) has died
08-11 09:33:57.710   872  1371 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-11 09:33:57.739   376  3727 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-11 09:33:57.740   376  3727 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,08-11 09:33:57.745   376  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-11 09:33:57.746  1789  3724 I MicroRecognitionRnrImpl: Detection finished
,08-11 09:33:57.746  1789  2138 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-11 09:33:57.782  1978  3756 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-11 09:33:57.782  1978  3756 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-11 09:33:57.923   280   280 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,08-11 09:33:57.923   280   280 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-11 09:33:57.923   280   280 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-11 09:33:57.923   280   280 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
,08-11 09:33:57.924   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-11 09:33:57.924   280   280 E qdoverlay: MdpCtrl close error in unset
,08-11 09:33:58.187   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-11 09:33:58.189   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted

```
