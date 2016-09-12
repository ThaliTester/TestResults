#### Test 846186379f428f5_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,09-12 18:30:11.370  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 18:30:11.387  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 18:30:11.392  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 18:30:11.467  1513  1952 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 18:30:11.467  1513  1952 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 18:30:11.468  1513  1952 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:30:11.468  1513  1952 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 18:30:11.512  3604  3604 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 18:30:11.513  3604  3604 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 18:30:11.513  3604  3604 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-12 18:30:12.086  3870  3870 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 18:30:12.091  3870  3870 D AndroidRuntime: CheckJNI is OFF
09-12 18:30:12.135  3870  3870 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 18:30:12.188  3870  3870 I Radio-JNI: register_android_hardware_Radio DONE
09-12 18:30:12.210  3870  3870 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-12 18:30:12.216   872  1942 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-12 18:30:12.248  3870  3870 D AndroidRuntime: Shutting down VM
09-12 18:30:12.250  2080  2218 W SearchService: Abort, client detached.
09-12 18:30:12.256  2080  2302 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@6ff5b91
09-12 18:30:12.256  2080  2080 I HotwordDetector: Closing mic
09-12 18:30:12.256  2080  2314 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-12 18:30:12.279   872  2014 I ActivityManager: Start proc 3881:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-12 18:30:12.313   376  2316 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-12 18:30:12.313   376  2316 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-12 18:30:12.319   376  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-12 18:30:12.321  2080  2309 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-12 18:30:12.321  2080  2312 I MicroRecognitionRnrImpl: Detection finished
09-12 18:30:12.357  3881  3881 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-12 18:30:12.392  3881  3881 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-12 18:30:12.402  3881  3881 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9015-9019)
09-12 18:30:12.402  3881  3881 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 18:30:12.420  3881  3881 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5c79fed}
09-12 18:30:12.420  3881  3881 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 18:30:12.420  3881  3881 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 18:30:12.429  3881  3881 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-12 18:30:12.430  3881  3881 E SysUtils: ApplicationContext is null in ApplicationStatus
09-12 18:30:12.454  3881  3881 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 18:30:12.473  3881  3881 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 18:30:12.474  3881  3881 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 18:30:12.474  3881  3881 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 18:30:12.474  3881  3881 I Adreno  : Build Date                       : 10/20/15
09-12 18:30:12.474  3881  3881 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 18:30:12.474  3881  3881 I Adreno  : Local Branch                     : M14
09-12 18:30:12.474  3881  3881 I Adreno  : Remote Branch                    : 
09-12 18:30:12.474  3881  3881 I Adreno  : Remote Branch                    : 
09-12 18:30:12.474  3881  3881 I Adreno  : Reconstruct Branch               : 
,09-12 18:30:12.549   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16ae5c3:true
,09-12 18:30:12.586  3881  3881 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 18:30:12.601  3881  3881 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-12 18:30:12.664  3881  3920 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-12 18:30:12.671  3881  3906 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-12 18:30:12.711  3881  3920 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 18:30:12.809   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +554ms
,09-12 18:30:12.824  1901  1901 I Keyboard.Facilitator: onFinishInput()
,09-12 18:30:12.876  3881  3881 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3881
,09-12 18:30:12.996  3881  3881 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 18:30:13.078   872   883 I ActivityManager: Killing 3225:com.google.android.gm/u0a78 (adj 15): empty #17
,09-12 18:30:13.135   872   883 I ActivityManager: Killing 3455:com.android.cellbroadcastreceiver/u0a4 (adj 15): empty #18
,09-12 18:30:13.238  3881  3922 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1713112784
,09-12 18:30:13.244  3881  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 18:30:13.244  3881  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 18:30:13.244  3881  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 18:30:13.244  3881  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 18:30:13.244  3881  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 18:30:13.244  3881  3922 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91206e1 added. We now have 1 listener(s)
,09-12 18:30:13.247  3881  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-12 18:30:13.249  3881  3922 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 18:30:13.250  3881  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 18:30:13.250  3881  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 18:30:13.253  3881  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 18:30:13.253  3881  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 18:30:13.253  3881  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 18:30:13.253  3881  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-12 18:30:13.253  3881  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 18:30:13.253  3881  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 18:30:13.253  3881  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 18:30:13.253  3881  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 18:30:13.253  3881  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 18:30:13.253  3881  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 18:30:13.253  3881  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 18:30:13.253  3881  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 18:30:13.253  3881  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 18:30:13.253  3881  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-12 18:30:13.253  3881  3922 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ad40f4 added. We now have 1 listener(s)
,09-12 18:30:13.254  3881  3922 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:30:13.256   872  1318 D WifiService: New client listening to asynchronous messages
,09-12 18:30:13.258  3881  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
09-12 18:30:13.258  3881  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-12 18:30:13.258  3881  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-12 18:30:13.258  3881  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-12 18:30:13.258  3881  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-12 18:30:13.260  3881  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:30:13.261  3881  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-12 18:30:13.267  3881  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-12 18:30:13.268  3881  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:30:13.268  3881  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:30:13.268  3881  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:30:13.268  3881  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:30:13.268  3881  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:30:13.268  3881  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:30:13.268  3881  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:30:13.268  3881  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:30:13.268  3881  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-12 18:30:13.268  3881  3922 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:30:13.268  3881  3922 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 18:30:13.393  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:30:13.395  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:30:13.396  3881  3881 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 18:30:14.187  3881  3932 W jxcore-log: Initializing JXcore engine
09-12 18:30:14.187  3881  3932 W jxcore-log: JXcore engine is ready
,09-12 18:30:14.225  3932  3932 W Thread-346: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8844 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-12 18:30:14.225  3932  3932 W Thread-346: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10796]" dev="sockfs" ino=10796 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-12 18:30:14.225  3932  3932 W Thread-346: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-12 18:30:14.239  3881  3932 W jxcore-log: Starting JXcore engine
,09-12 18:30:14.225  3932  3932 W Thread-346: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26268]" dev="sockfs" ino=26268 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-12 18:30:14.319  3881  3932 W jxcore-log: Platform android
09-12 18:30:14.319  3881  3932 W jxcore-log: 
09-12 18:30:14.319  3881  3932 W jxcore-log: Process ARCH arm
09-12 18:30:14.319  3881  3932 W jxcore-log: 
,09-12 18:30:14.629  3881  3932 I jxcore-log: JXcore Cordova bridge is ready!
09-12 18:30:14.629  3881  3932 I jxcore-log: 
,09-12 18:30:14.629  3881  3932 W jxcore-log: JXcore engine is started
,09-12 18:30:14.639  3881  3922 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 18:30:14.645  3881  3881 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 18:30:16.151   872  1317 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-12 18:30:22.015  3037  3940 V KeepSync: Connecting to GoogleApiClient
09-12 18:30:22.015   872  2034 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 18:30:22.096  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:30:22.101  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:30:22.136  1513  1952 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 18:30:22.136  1513  1952 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-12 18:30:22.136  1513  1952 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 18:30:22.136  1513  1952 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:30:22.159  1712  3941 V BaseAuthAsyncOperation: access token request failed
09-12 18:30:22.160  3037  3940 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 18:30:22.207  1513  1952 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-12 18:30:22.207  1513  1952 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 18:30:22.207  1513  1952 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 18:30:22.207  1513  1952 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:30:22.229  3037  3940 E KeepSync: IOException
09-12 18:30:22.229  3037  3940 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 18:30:22.229  3037  3940 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 18:30:22.229  3037  3940 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 18:30:22.229  3037  3940 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 18:30:22.229  3037  3940 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 18:30:22.229  3037  3940 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 18:30:22.229  3037  3940 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 18:30:22.229  3037  3940 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 18:30:22.229  3037  3940 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 18:30:22.229  3037  3940 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 18:30:22.229  3037  3940 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 18:30:22.229  3037  3940 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 18:30:22.229  3037  3940 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 18:30:22.229  3037  3940 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 18:30:22.229  3037  3940 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 18:30:22.229  3037  3940 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 18:30:22.229  3037  3940 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 18:30:22.229  3037  3940 E KeepSync: 	... 10 more
,09-12 18:30:22.229  3037  3940 W KeepSync: Sync result 2
,09-12 18:30:22.242   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 128550, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:30:27.980   872  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 18:30:29.170  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 18:30:29.170  3881  3932 I jxcore-log: 
,09-12 18:30:29.173  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 18:30:29.173  3881  3932 I jxcore-log: 
,09-12 18:30:29.185  3881  3932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:30:29.185  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:30:29.185  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:30:29.185  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:30:29.185  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:30:29.185  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:30:29.185  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:30:29.185  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:30:29.191  3881  3932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:30:29.193  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 18:30:29.193  3881  3932 I jxcore-log: 
,09-12 18:30:29.195  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 18:30:29.195  3881  3932 I jxcore-log: 
,09-12 18:30:29.557  3881  3932 I jxcore-log: Running unit tests
09-12 18:30:29.557  3881  3932 I jxcore-log: 
,09-12 18:30:29.558  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:30:29.558  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed38d61 added. We now have 2 listener(s)
,09-12 18:30:29.559  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 18:30:29.559  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 18:30:29.559  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:30:29.559  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:30:29.559  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2cf086 added. We now have 2 listener(s)
09-12 18:30:29.559  3881  3932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:30:29.560  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:30:29.562  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:30:29.582  3881  3932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:30:29.582  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:30:29.582  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:30:29.582  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:30:29.582  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:30:29.582  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:30:29.582  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:30:29.582  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:30:29.588  3881  3932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:30:29.589  3881  3932 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:30:29.590  3881  3932 D executeNativeTests: Running unit tests
,09-12 18:30:29.591  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:30:29.595  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:30:29.684  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 18:30:29.684  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 added. We now have 3 listener(s)
09-12 18:30:29.685  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 18:30:29.685  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:30:29.685  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:30:29.685  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:30:29.685  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d added. We now have 3 listener(s)
09-12 18:30:29.685  3881  3932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:30:29.686  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:30:29.696  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:30:29.702  3881  3932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:30:29.702  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:30:29.702  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:30:29.702  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:30:29.702  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:30:29.702  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:30:29.702  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:30:29.702  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:30:29.707  3881  3932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:30:29.707  3881  3932 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:30:29.709  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 18:30:29.710  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:30:29.711  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 18:30:29.711  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 18:30:29.711  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 18:30:29.713  3881  3932 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-12 18:30:29.713  3881  3932 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 18:30:29.713  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-12 18:30:29.713  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 18:30:29.713  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:30:29.713  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:30:29.713  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:30:29.714  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:30:29.714  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:30:29.714  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:30:29.715  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:30:29.715  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:29.715  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:30:29.715  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:30:29.715  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 removed from the list
09-12 18:30:29.715  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:29.715  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d removed from the list
09-12 18:30:29.715  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:29.715  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:29.717  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:29.717  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:29.719  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:30:29.719  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:29.721  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:29.721  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:29.722  3881  3932 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-12 18:30:29.723  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:30:29.723  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:30:29.723  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:30:29.724  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:30:29.724  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:29.724  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.B,luetoothManager: release: 2 listener(s) left
09-12 18:30:29.724  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:29.724  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:29.724  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:29.724  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:29.724  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:29.724  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:29.724  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:29.724  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:29.726  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:30:29.726  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:29.726  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:29.726  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:29.731  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 18:30:29.731  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 18:30:29.732  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 18:30:29.732  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 18:30:29.732  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 18:30:29.732  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 18:30:29.732  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 18:30:29.732  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 18:30:29.732  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 18:30:29.732  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 18:30:29.732  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 18:30:29.732  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 18:30:29.732  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 18:30:29.732  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 18:30:29.733  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 18:30:29.733  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 18:30:29.733  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 18:30:29.733  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 18:30:29.733  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 18:30:29.733  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 18:30:29.733  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 18:30:29.733  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 18:30:29.733  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 18:30:29.733  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 18:30:29.733  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 18:30:29.734  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 18:30:29.734  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 18:30:29.734  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 18:30:29.734  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 18:30:29.734  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 18:30:29.734  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 18:30:29.734  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:30:29.734  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:30:29.734  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:30:29.735  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:30:29.735  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:29.735  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:29.735  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:29.735  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:29.735  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:29.735  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:29.735  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:29.735  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:29.735  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:29.735  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:29.737  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:30:29.737  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:29.737  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:29.737  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:29.738  3881  3932 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 18:30:29.739  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:30:29.747  3881  3932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:30:29.747  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:30:29.747  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:30:29.747  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:30:29.747  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:30:29.747  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:30:29.747  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:30:29.747  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:30:29.748  3881  3932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:30:29.748  3881  3932 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:30:29.750  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:30:29.750  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:30:29.750  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:30:29.751  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:30:29.751  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:30:29.752  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 18:30:29.759  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:30:29.761  3881  3932 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 18:30:29.761  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 18:30:29.768  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 18:30:29.770  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 18:30:29.770  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 18:30:29.773  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-12 18:30:29.776  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-12 18:30:29.776  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 18:30:29.776  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 18:30:29.777  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 18:30:29.778  3881  3932 D BluetoothAdapter: STATE_ON
09-12 18:30:29.782  2636  2859 D BtGatt.GattService: registerClient() - UUID=079db437-0b26-4442-8552-936fc5081fb7
09-12 18:30:29.783  2636  2687 D BtGatt.GattService: onClientRegistered() - UUID=079db437-0b26-4442-8552-936fc5081fb7, clientIf=5
09-12 18:30:29.784  3881  3892 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 18:30:29.785  2636  2649 D BtGatt.GattService: start scan with filters
09-12 18:30:29.788  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 18:30:29.789  2636  2691 D BtGatt.ScanManager: handling starting scan
09-12 18:30:29.789  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:30:29.789  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 18:30:29.789  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 18:30:29.790  2636  2691 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
09-12 18:30:29.792  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 18:30:29.792  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 18:30:29.793  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 18:30:29.794  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-12 18:30:29.798  3881  3932 I io.jxcore.node.ConnectionHelper: start: OK
09-12 18:30:29.801  2636  2687 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 18:30:29.801  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:30:29.801  2636  2691 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 18:30:29.808  2636  2687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 18:30:29.808  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:30:29.808  2636  2691 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 18:30:29.808  2636  2691 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 18:30:29.819  2636  2687 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 18:30:29.819  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:29.822  2636  2687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 18:30:29.822  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:30.295  3881  3881 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 18:30:30.295  3881  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 18:30:30.296  3881  3881 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 18:30:31.011   872  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 18:30:31.333  2636  2636 D BtGatt.ScanManager: awakened up at time 137950
,09-12 18:30:31.337  2636  2691 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 18:30:31.379  2636  2687 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,09-12 18:30:31.379  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:30:31.380  2636  2687 D BtGatt.GattService: current time is 137997616308
09-12 18:30:31.381  2636  2687 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -97, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -87, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -85, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 18:30:31.389  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 18:30:31.391  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 18:30:31.392  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-12 18:30:31.393  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 18:30:32.898  2636  2636 D BtGatt.ScanManager: awakened up at time 139515
,09-12 18:30:32.900  2636  2691 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 18:30:32.930  2636  2687 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 18:30:32.930  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:33.293  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:30:33.310  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:30:33.316  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:30:33.379  1513  2976 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 18:30:33.379  1513  2976 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 18:30:33.380  1513  2976 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:30:33.380  1513  2976 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:30:33.426  3604  3604 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 18:30:33.426  3604  3604 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 18:30:33.427  3604  3604 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-12 18:30:34.042   872  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 18:30:34.432  2636  2636 D BtGatt.ScanManager: awakened up at time 141049
,09-12 18:30:34.435  2636  2691 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 18:30:34.488  2636  2687 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,09-12 18:30:34.488  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:34.489  2636  2687 D BtGatt.GattService: current time is 141106859951
09-12 18:30:34.490  2636  2687 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -92, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -92, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -87, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-12 18:30:34.491  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-12 18:30:34.492  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 18:30:34.493  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-12 18:30:34.494  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 18:30:34.807  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:30:34.808  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:30:34.810  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 18:30:34.810  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:34.811  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 18:30:34.812  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 18:30:34.812  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:30:34.812  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:30:34.813  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 18:30:34.815  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 18:30:34.815  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 18:30:34.819  3881  3932 D BluetoothAdapter: STATE_ON
,09-12 18:30:34.820  2636  2871 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:30:34.826  2636  2859 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 18:30:34.826  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:30:34.826  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 18:30:34.826  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:30:34.826  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 18:30:34.826  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 18:30:34.828  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:30:34.828  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 18:30:34.828  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:30:34.829  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 18:30:34.829  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 18:30:34.831  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 18:30:34.831  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:30:34.831  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:30:34.831  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:30:34.831  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:34.831  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:30:34.832  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:34.832  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:34.832  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
,09-12 18:30:34.832  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:34.832  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:30:34.845  2636  2687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 18:30:34.845  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:30:34.845  2636  2691 D BtGatt.ScanManager: stopping BLe Batch
,09-12 18:30:34.858  2636  2687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 18:30:34.858  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:30:34.859  2636  2691 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 18:30:34.889  2636  2687 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-12 18:30:34.889  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:34.890  2636  2687 D BtGatt.GattService: current time is 141507505824
,09-12 18:30:34.891  2636  2687 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -90, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -96, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-12 18:30:34.893  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 18:30:34.893  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 18:30:35.331  3881  3881 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 18:30:37.068   872  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 18:30:39.833  3881  3932 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 18:30:39.839  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:30:39.853  3881  3932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:30:39.853  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:30:39.853  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:30:39.853  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:30:39.853  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:30:39.853  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:30:39.853  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:30:39.853  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:30:39.860  3881  3932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:30:39.861  3881  3932 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:30:39.861  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 18:30:39.861  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:30:39.862  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:30:39.862  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:30:39.863  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 18:30:39.869  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:30:39.874  3881  3932 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 18:30:39.874  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 18:30:39.877  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:30:39.886  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:30:39.888  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 18:30:39.888  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:30:39.898  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 18:30:39.898  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 18:30:39.899  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:30:39.900  3881  3932 D BluetoothAdapter: STATE_ON
,09-12 18:30:39.907  2636  2650 D BtGatt.GattService: registerClient() - UUID=07f7e7bb-3e2e-4aed-9c51-0ce6969c523d
,09-12 18:30:39.908  2636  2687 D BtGatt.GattService: onClientRegistered() - UUID=07f7e7bb-3e2e-4aed-9c51-0ce6969c523d, clientIf=5
09-12 18:30:39.909  3881  3928 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 18:30:39.910  2636  2871 D BtGatt.GattService: start scan with filters
,09-12 18:30:39.917  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 18:30:39.918  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:30:39.918  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 18:30:39.918  2636  2691 D BtGatt.ScanManager: handling starting scan
09-12 18:30:39.919  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 18:30:39.928  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:30:39.929  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:30:39.930  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 18:30:39.937  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:30:39.937  2636  2687 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 18:30:39.938  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:39.939  2636  2691 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 18:30:39.950  3881  3932 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 18:30:39.955  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:30:39.955  3881  3932 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 18:30:39.955  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:30:39.956  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 18:30:39.955  2636  2687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 18:30:39.956  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:30:39.956  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 18:30:39.956  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:39.956  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 18:30:39.956  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:30:39.956  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 18:30:39.956  2636  2691 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 18:30:39.957  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:30:39.957  2636  2691 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 18:30:39.957  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 18:30:39.957  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 18:30:39.959  3881  3932 D BluetoothAdapter: STATE_ON
,09-12 18:30:39.960  2636  2650 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:30:39.962  2636  2871 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 18:30:39.962  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 18:30:39.963  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 18:30:39.970  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 18:30:39.970  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 18:30:39.970  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 18:30:39.972  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:30:39.973  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 18:30:39.973  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:30:39.973  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 18:30:39.974  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 18:30:39.977  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 18:30:39.977  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:30:39.977  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:30:39.977  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:39.977  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:30:39.977  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:30:39.978  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
,09-12 18:30:39.978  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:30:39.978  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
,09-12 18:30:39.978  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:39.979  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:30:39.980  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:30:39.980  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:30:39.984  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:30:39.984  2636  2687 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 18:30:39.985  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:39.984  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 18:30:39.986  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:30:39.986  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
,09-12 18:30:39.988  3881  3932 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 18:30:39.991  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:30:39.995  2636  2687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 18:30:39.996  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:39.999  3881  3932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:30:39.999  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:30:39.999  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:30:39.999  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:30:39.999  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:30:39.999  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:30:39.999  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:30:39.999  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:30:40.001  3881  3932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:30:40.001  3881  3932 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:30:40.002  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:30:40.002  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:30:40.002  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 18:30:40.002  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:30:40.002  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 18:30:40.006  3881  3932 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 18:30:40.006  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 18:30:40.007  2636  2687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 18:30:40.007  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:30:40.008  2636  2691 D BtGatt.ScanManager: stopping BLe Batch
,09-12 18:30:40.008  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:30:40.011  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 18:30:40.012  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 18:30:40.012  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:30:40.013  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:30:40.016  2636  2687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 18:30:40.016  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:30:40.016  2636  2691 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 18:30:40.019  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 18:30:40.019  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 18:30:40.020  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:30:40.021  3881  3932 D BluetoothAdapter: STATE_ON
,09-12 18:30:40.022  2636  2687 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 18:30:40.022  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:40.025  2636  2871 D BtGatt.GattService: registerClient() - UUID=180fa272-09e3-46dd-aff8-5b70afd6c33b
,09-12 18:30:40.025  2636  2687 D BtGatt.GattService: onClientRegistered() - UUID=180fa272-09e3-46dd-aff8-5b70afd6c33b, clientIf=5
09-12 18:30:40.025  3881  3893 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 18:30:40.026  2636  2650 D BtGatt.GattService: start scan with filters
,09-12 18:30:40.029  2636  2691 D BtGatt.ScanManager: handling starting scan
,09-12 18:30:40.029  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 18:30:40.030  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:30:40.030  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 18:30:40.030  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 18:30:40.033  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:30:40.033  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 18:30:40.033  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:30:40.035  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:30:40.038  3881  3932 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 18:30:40.040  2636  2687 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 18:30:40.040  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:40.040  2636  2691 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 18:30:40.047  2636  2687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 18:30:40.047  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:30:40.047  2636  2691 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:30:40.047  2636  2691 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 18:30:40.061  2636  2687 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 18:30:40.062  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:40.070  2636  2687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 18:30:40.070  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:40.534  3881  3881 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 18:30:40.535  3881  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:30:40.535  3881  3881 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 18:30:41.577  2636  2636 D BtGatt.ScanManager: awakened up at time 148194
,09-12 18:30:41.580  2636  2691 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 18:30:41.626  2636  2687 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-12 18:30:41.627  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:30:41.627  2636  2687 D BtGatt.GattService: current time is 148244864571
09-12 18:30:41.628  2636  2687 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -83, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -78, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -86, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -85, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -96, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -91, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-12 18:30:41.629  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 18:30:41.630  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-12 18:30:41.631  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 18:30:41.631  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-12 18:30:41.632  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-12 18:30:41.633  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-12 18:30:43.131  2636  2636 D BtGatt.ScanManager: awakened up at time 149748
,09-12 18:30:43.133  2636  2691 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 18:30:43.145  2636  2687 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 18:30:43.146  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:43.365   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-12 18:30:43.374  1901  1901 I Keyboard.Facilitator: onFinishInput()
,09-12 18:30:43.390   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 18:30:43.390   872   892 I Adreno  : Build Date                       : 10/20/15
09-12 18:30:43.390   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 18:30:43.390   872   892 I Adreno  : Local Branch                     : M14
09-12 18:30:43.390   872   892 I Adreno  : Remote Branch                    : 
09-12 18:30:43.390   872   892 I Adreno  : Remote Branch                    : 
09-12 18:30:43.390   872   892 I Adreno  : Reconstruct Branch               : 
,09-12 18:30:43.436   281  1306 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (196 us)
,09-12 18:30:44.065  3881  3881 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 18:30:44.065  3881  3881 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 18:30:44.114   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-12 18:30:44.120  3881  3881 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@654132b Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@6af29e6, 16908290=android.view.AbsSavedState$1@6af29e6}, android:focusedViewId=100}]}]
,09-12 18:30:44.121  3881  3881 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-12 18:30:44.121  3881  3881 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 18:30:44.121  3881  3881 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-12 18:30:44.127   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-12 18:30:44.134   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-12 18:30:44.134   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
09-12 18:30:44.134   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-12 18:30:44.391   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-12 18:30:44.395   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-12 18:30:44.401   872  1341 D SurfaceControl: Excessive delay in setPowerMode(): 267ms
,09-12 18:30:44.407   872   892 I DreamManagerService: Entering dreamland.
,09-12 18:30:44.408   872   892 I PowerManagerService: Dozing...
,09-12 18:30:44.411   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-12 18:30:44.480   376  1288 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-12 18:30:44.481   376  1288 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-12 18:30:44.487  2636  2636 D BtGatt.ScanManager: awakened up at time 151104
,09-12 18:30:44.489  2636  2691 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 18:30:44.502   872  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 18:30:44.510  2006  3951 D NfcService: Discovery configuration equal, not updating.
,09-12 18:30:44.517   872  1317 E native  : do suspend false
,09-12 18:30:44.536  2636  2687 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-12 18:30:44.537  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:44.537  2636  2687 D BtGatt.GattService: current time is 151155103400
,09-12 18:30:44.541  2636  2687 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -91, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -85, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -91, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -86, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -84, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 18:30:44.543   872  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 18:30:44.543  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-12 18:30:44.550  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 18:30:44.550  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-12 18:30:44.551  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-12 18:30:44.551  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 18:30:44.551  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 18:30:44.558   872  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 18:30:44.562   872  1317 E native  : do suspend true
,09-12 18:30:44.615   376  1325 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-12 18:30:44.615   376  1325 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-12 18:30:45.010   872  1317 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-12 18:30:45.038  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:30:45.039  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 18:30:45.039  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 18:30:45.039  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:30:45.040  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 18:30:45.040  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:30:45.040  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:30:45.041  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 18:30:45.041  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:30:45.042  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 18:30:45.042  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 18:30:45.046  3881  3932 D BluetoothAdapter: STATE_ON
,09-12 18:30:45.047  2636  2650 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:30:45.051  2636  2859 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 18:30:45.053  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:30:45.053  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 18:30:45.054  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:30:45.054  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 18:30:45.054  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 18:30:45.058  2636  2636 D BtGatt.ScanManager: awakened up at time 151675
,09-12 18:30:45.063  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:30:45.063  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 18:30:45.064  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 18:30:45.064  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 18:30:45.066  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 18:30:45.069  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 18:30:45.070  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:30:45.070  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:30:45.071  2636  2687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 18:30:45.071  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:45.072  2636  2691 D BtGatt.ScanManager: stopping BLe Batch
,09-12 18:30:45.088  2636  2687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 18:30:45.089  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:45.089  2636  2691 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 18:30:45.119  2636  2687 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-12 18:30:45.119  2636  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:30:45.119  2636  2687 D BtGatt.GattService: current time is 151737284291
09-12 18:30:45.120  2636  2687 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -92, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-12 18:30:45.120  2636  2687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 18:30:45.571  3881  3881 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 18:30:45.572  3881  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:30:45.572  3881  3881 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 18:30:49.769  1869  2577 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 18:30:50.072  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:30:50.072  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:30:50.073  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:30:50.074  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:30:50.074  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.074  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:30:50.075  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:50.075  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:50.075  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:50.076  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:50.076  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:30:50.078  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.078  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.082  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:30:50.083  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:50.083  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:50.083  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:50.086  3881  3932 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-12 18:30:50.088  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:30:50.088  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:30:50.088  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:30:50.089  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:30:50.089  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.089  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.090  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:50.090  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:50.090  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:50.091  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:50.091  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.091  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.091  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.091  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:30:50.094  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:30:50.094  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:50.095  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:50.095  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
,09-12 18:30:50.097  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-12 18:30:50.097  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:30:50.097  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:30:50.097  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:30:50.097  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:30:50.097  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.097  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.098  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:50.098  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:30:50.098  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:50.098  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:50.098  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.098  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.098  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.098  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:30:50.100  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:30:50.100  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:50.100  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:30:50.101  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
,09-12 18:30:50.102  3881  3932 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-12 18:30:50.103  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:30:50.103  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:30:50.103  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:30:50.104  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:30:50.104  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:30:50.104  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.105  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:50.105  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:30:50.105  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:50.105  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:50.105  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.106  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.106  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:30:50.106  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:30:50.108  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:30:50.108  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:50.109  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:50.109  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
,09-12 18:30:50.111  3881  3932 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-12 18:30:50.111  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:30:50.111  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:30:50.111  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:30:50.112  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:30:50.112  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:30:50.112  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.113  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:50.113  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:50.113  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
,09-12 18:30:50.113  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:50.114  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.114  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.114  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:30:50.114  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:30:50.116  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:30:50.116  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:50.116  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:50.117  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
,09-12 18:30:50.118  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 18:30:50.119  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 18:30:50.119  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 18:30:50.120  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-12 18:30:50.120  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:30:50.120  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:30:50.120  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 18:30:50.121  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 18:30:50.121  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 18:30:50.121  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:30:50.122  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:30:50.122  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:30:50.122  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:30:50.123  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.123  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.123  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:50.123  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:50.124  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:50.124  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:50.124  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:30:50.124  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.125  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.125  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:30:50.129  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:30:50.129  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:50.129  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:30:50.130  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
,09-12 18:30:50.131  3881  3932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:30:50.131  3881  3932 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 18:30:50.131  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-12 18:30:50.136  3881  3932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 18:30:50.136  3881  3932 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 18:30:50.136  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 18:30:50.137  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 18:30:50.137  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-12 18:30:50.137  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 18:30:50.137  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 18:30:50.137  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 18:30:50.137  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 18:30:50.137  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-12 18:30:50.137  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 18:30:50.137  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 18:30:50.137  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 18:30:50.137  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 18:30:50.138  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-12 18:30:50.138  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 18:30:50.138  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 18:30:50.138  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 18:30:50.138  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-12 18:30:50.138  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 18:30:50.138  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 18:30:50.138  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 18:30:50.138  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-12 18:30:50.138  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 18:30:50.139  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 18:30:50.139  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 18:30:50.139  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 18:30:50.139  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 18:30:50.139  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 18:30:50.139  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 18:30:50.139  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 18:30:50.139  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 18:30:50.139  3881  3932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 18:30:50.140  3881  3932 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 18:30:50.140  3881  3932 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 18:30:50.140  3881  3932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:30:50.140  3881  3932 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 18:30:50.140  3881  3932 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 18:30:50.140  3881  3932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:30:50.141  3881  3932 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 18:30:50.141  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 18:30:50.144  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-12 18:30:50.146  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-12 18:30:50.146  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-12 18:30:50.147  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 18:30:50.147  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 18:30:50.147  3881  3932 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 18:30:50.147  3881  3932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:30:50.148  3881  3932 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 18:30:50.149  3881  3956 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 410)
09-12 18:30:50.149  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:30:50.149  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:30:50.149  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:30:50.150  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:30:50.150  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.150  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.151  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 18:30:50.152  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:50.152  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:50.152  3881  3956 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:30:50.152  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:50.152  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:50.152  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.153  3881  3957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 410
09-12 18:30:50.153  3881  3957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 410)
09-12 18:30:50.152  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.153  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.153  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.153  3881  3957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 410)
09-12 18:30:50.155  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:30:50.155  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:50.155  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:50.155  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:50.156  3881  3956 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 410)
09-12 18:30:50.157  3881  3932 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 18:30:50.158  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:30:50.158  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:30:50.158  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:30:50.159  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:30:50.159  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.159  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.159  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:50.159  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:50.160  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:50.160  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:50.160  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.160  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.160  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.160  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.162  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:30:50.162  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:50.162  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:50.162  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:50.163  3881  3932 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 18:30:50.164  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:30:50.164  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:30:50.164  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:30:50.164  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:30:50.165  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.165  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.165  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:50.165  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:50.165  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:50.165  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:50.165  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.165  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.166  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.166  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.167  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:30:50.167  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:50.167  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:50.167  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:50.168  3881  3932 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 18:30:50.169  3881  3932 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 18:30:50.169  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 18:30:50.169  3881  3932 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 18:30:50.169  3881  3932 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 18:30:50.169  3881  3932 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 18:30:50.169  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 18:30:50.170  3881  3932 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 18:30:50.170  3881  3932 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 18:30:50.170  3881  3932 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 18:30:50.170  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 18:30:50.170  3881  3932 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 18:30:50.170  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:30:50.170  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:30:50.171  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:30:50.171  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:30:50.171  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.171  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.171  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:50.172  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:50.172  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:50.172  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:50.172  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.172  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.172  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.172  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.174  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:30:50.174  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:50.174  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:50.174  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
,09-12 18:30:50.175  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:30:50.175  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.175  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:50.175  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:50.176  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:50.176  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:50.176  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:50.176  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:50.176  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:30:52.464  3689  3958 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 18:30:52.494  3689  3961 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 18:30:52.515  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:30:52.519  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:30:52.537  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 18:30:52.537  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 18:30:52.537  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:30:52.537  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:30:52.557  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:30:52.559  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:30:52.577  1513  1952 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 18:30:52.577  1513  1952 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 18:30:52.577  1513  1952 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:30:52.577  1513  1952 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:30:52.592  3689  3961 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 18:30:52.594  3689  3958 E BooksSync: Soft error
09-12 18:30:52.594  3689  3958 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 18:30:52.594  3689  3958 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 18:30:52.594  3689  3958 E BooksSync: Sync error
09-12 18:30:52.594  3689  3958 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 18:30:52.594  3689  3958 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 18:30:52.594  3689  3958 I BooksSync: Finished books sync
,09-12 18:30:52.602   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 129912, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:30:52.617  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:30:52.619  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:30:52.659  1513  3942 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 18:30:52.660  1513  3942 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 18:30:52.660  1513  3942 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 18:30:52.661  1513  3942 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:30:52.683  3645  3960 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 18:30:52.683  3645  3960 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at jdm.a(PG:82)
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at jcs.o(PG:406)
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at jcn.a(PG:1379)
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at jcs.i(PG:143)
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at blb.a(PG:3937)
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at czp.a(PG:18188)
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at czp.a(PG:9081)
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at czq.run(PG:1686)
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:30:52.683  3645  3960 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at jdj.a(PG:4091)
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at jdj.a(PG:1125)
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at jdm.a(PG:77)
09-12 18:30:52.683  3645  3960 E HttpOperation: 	... 12 more
09-12 18:30:52.683  3645  3960 E HttpOperation: Caused by: faj: BadAuthentication
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at fal.a(PG:38)
09-12 18:30:52.683  3645  3960 E HttpOperation: 	at jdj.a(PG:4089)
09-12 18:30:52.683  3645  3960 E HttpOperation: 	... 14 more
,09-12 18:30:52.738  1513  2252 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 18:30:52.738  1513  2252 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 18:30:52.738  1513  2252 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:30:52.738  1513  2252 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:30:52.760  3645  3960 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 18:30:52.760  3645  3960 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at jdm.a(PG:82)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at jcs.o(PG:406)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at jcn.a(PG:1379)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at jcs.i(PG:143)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at hec.a(PG:42)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at hee.a(PG:102)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at czr.a(PG:65)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at kka.a(PG:108)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at czp.a(PG:19176)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at czp.a(PG:9081)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at czq.run(PG:1686)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:30:52.760  3645  3960 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at jdj.a(PG:4091)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at jdj.a(PG:1125)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at jdm.a(PG:77)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	... 15 more
09-12 18:30:52.760  3645  3960 E HttpOperation: Caused by: faj: BadAuthentication
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at fal.a(PG:38)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	at jdj.a(PG:4089)
09-12 18:30:52.760  3645  3960 E HttpOperation: 	... 17 more
,09-12 18:30:52.760  3645  3960 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 18:30:52.760  3645  3960 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at hec.a(PG:42)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at hee.a(PG:102)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at czr.a(PG:65)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at kka.a(PG:108)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	... 15 more
09-12 18:30:52.760  3645  3960 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at fal.a(PG:38)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 18:30:52.760  3645  3960 E ExperimentLoader: 	... 17 more
,09-12 18:30:52.864   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 130339, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:30:53.594  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:30:53.806  1513  3964 I VacuumService: Vacuum at: now=1473697853806 tag=VacuumService
,09-12 18:30:53.810  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:30:53.831  1513  1513 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-12 18:30:53.904  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure,
09-12 18:30:53.904  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 18:30:53.904  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:30:53.905  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:30:53.918  3604  3604 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 18:30:53.919  3604  3604 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 18:30:53.919  3604  3604 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-12 18:30:55.177  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:30:55.177  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
,09-12 18:30:55.178  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:30:55.178  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:55.178  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:30:55.179  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:55.179  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:30:55.180  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:30:55.180  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:30:55.181  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:30:55.182  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:30:55.182  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:55.182  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
,09-12 18:30:55.183  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:55.183  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:55.183  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:55.184  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:55.184  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:55.184  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:55.184  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:55.188  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:30:55.188  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:55.189  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:55.189  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
,09-12 18:30:55.194  3881  3932 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-12 18:30:55.195  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:30:55.197  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 18:30:55.199  3881  3932 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-12 18:30:55.199  3881  3932 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-12 18:30:55.200  3881  3881 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 18:30:55.201  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 18:30:55.201  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:30:55.202  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:30:55.202  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 18:30:55.202  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 18:30:55.203  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-12 18:30:55.203  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:30:55.203  3881  3932 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-12 18:30:55.204  3881  3881 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-12 18:30:55.204  3881  3970 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:30:55.204  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:55.204  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:30:55.205  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:30:55.205  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:30:55.205  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 18:30:55.206  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:55.206  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:55.209  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:30:55.210  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:30:55.210  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:30:55.210  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:30:55.210  3881  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 18:30:55.211  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:55.211  3881  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-12 18:30:55.211  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:30:55.211  3881  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-12 18:30:55.211  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:30:55.211  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:30:55.213  3881  3881 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 18:30:55.213  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:30:55.213  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:30:55.213  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:55.213  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:55.213  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:55.213  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:55.214  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:55.214  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:55.214  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:55.214  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:55.214  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:30:55.215  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:30:55.215  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:55.215  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:55.215  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:55.217  3881  3932 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-12 18:30:55.217  3881  3932 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 18:30:55.217  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 18:30:55.218  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:30:55.218  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:30:55.218  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:30:55.218  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:30:55.218  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:30:55.218  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:30:55.218  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:30:55.218  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:55.219  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
,09-12 18:30:55.219  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:30:55.219  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:55.219  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:30:55.219  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:30:55.219  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:55.219  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:30:55.219  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:55.220  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:30:55.220  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:55.220  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:30:55.221  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:55.224  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:30:55.224  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:30:55.224  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 18:30:55.225  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:30:55.225  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:55.225  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:55.225  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:55.225  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:30:55.225  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:55.225  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:30:55.225  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:55.225  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:55.226  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:55.226  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:55.227  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:30:55.227  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:55.227  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:55.227  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:55.228  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:30:55.228  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:30:55.228  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 18:30:55.228  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:30:55.228  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:55.228  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:55.229  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae07a4 not in the list
09-12 18:30:55.229  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:30:55.229  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:55.229  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:30:55.229  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:55.229  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:55.229  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:30:55.229  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:30:55.230  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:30:55.230  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:30:55.230  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:30:55.231  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@645690d not in the list
09-12 18:30:55.232  3881  3932 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 18:30:55.232  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 18:30:55.232  3881  3932 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 18:30:55.232  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 18:30:55.232  3881  3932 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-12 18:30:55.232  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 18:30:55.236  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 18:30:55.236  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-12 18:30:55.236  3881  3932 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 18:30:55.237  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 18:30:55.237  3881  3932 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-12 18:30:55.237  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 18:30:55.237  3881  3932 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 18:30:55.237  3881  3932 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 18:30:55.238  3881  3932 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 18:30:55.238  3881  3932 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-12 18:30:55.238  3881  3932 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-12 18:30:55.238  3881  3932 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 18:30:55.239  3881  3932 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 18:30:55.239  3881  3932 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-12 18:30:55.240  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:30:55.240  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@74a1d4 added. We now have 3 listener(s)
09-12 18:30:55.240  3881  3932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:30:55.243  3881  3932 D BluetoothAdapter: enable(): BT is already enabled..!
,09-12 18:30:55.243   872   883 D WifiService: setWifiEnabled: true pid=3881, uid=10000
09-12 18:30:55.244   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 18:30:55.285  2636  2824 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-12 18:30:55.285  2636  2856 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-12 18:30:55.686  1513  3965 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,09-12 18:30:55.709  1513  3976 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-12 18:30:55.711  3881  3881 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-12 18:30:55.714  1513  3976 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-12 18:30:55.767  1513  3976 W Uploader:  no longer exists, so no auth token.
,09-12 18:30:56.167   872  1317 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-12 18:30:58.689  1513  3976 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-12 18:30:58.689  1513  3976 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-12 18:30:58.689  1513  3976 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 18:30:58.689  1513  3976 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:30:58.705  1513  3976 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 18:30:58.705  1513  3976 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 18:30:58.705  1513  3976 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 18:30:58.705  1513  3976 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 18:30:58.705  1513  3976 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 18:30:58.705  1513  3976 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 18:30:58.705  1513  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 18:30:58.705  1513  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 18:30:58.705  1513  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 18:30:58.705  1513  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 18:30:58.705  1513  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 18:30:58.705  1513  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 18:30:58.705  1513  3976 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 18:30:58.940   872  2092 D NetlinkSocketObserver: NeighborEvent{elapsedMs=165557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:31:00.251  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:31:00.251  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8efaf7d added. We now have 4 listener(s)
09-12 18:31:00.252  3881  3932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:31:00.268  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:31:00.268  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8efaf7d removed from the list
09-12 18:31:00.268  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:31:00.269  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:31:00.269  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:31:00.271  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:31:00.272  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d33fe72 added. We now have 4 listener(s)
09-12 18:31:00.272  3881  3932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:31:00.276  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:31:00.276  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d33fe72 removed from the list
09-12 18:31:00.277  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:31:00.277  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:31:00.277  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:31:00.280  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:31:00.280  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d642c3 added. We now have 4 listener(s)
,09-12 18:31:00.280  3881  3932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:31:00.288   872   882 D WifiService: setWifiEnabled: false pid=3881, uid=10000
,09-12 18:31:00.288   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 18:31:00.298  2636  2683 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 18:31:00.298  2636  2683 D BluetoothAdapterProperties: Setting state to 13
,09-12 18:31:00.298  2636  2683 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-12 18:31:00.303  2636  2683 D BluetoothAdapterProperties: onBluetoothDisable()
,09-12 18:31:00.303  2636  2683 I BluetoothAdapterState: Entering PendingCommandState,
09-12 18:31:00.304  2636  2687 D BluetoothAdapterProperties: Scan Mode:20
,09-12 18:31:00.305  2636  2683 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-12 18:31:00.305  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:31:00.310  2636  2636 D HeadsetService: Received stop request...Stopping profile...
,09-12 18:31:00.312   872   872 D BluetoothHeadset: Proxy object disconnected
,09-12 18:31:00.312   872   872 D BluetoothHeadset: Proxy object disconnected,
,09-12 18:31:00.312  2636  2636 V BluetoothAdapterState: isTurningOff()=true
,09-12 18:31:00.313  2636  2636 V BluetoothAdapterState: isTurningOn()=false
,09-12 18:31:00.313  2636  2636 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 18:31:00.313  2636  2636 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:31:00.313  1360  1379 D BluetoothHeadset: Proxy object disconnected
09-12 18:31:00.313  1360  1360 D HeadsetProfile: Bluetooth service disconnected
09-12 18:31:00.313  2636  2636 D A2dpService: Received stop request...Stopping profile...
,09-12 18:31:00.314  2636  2862 D A2dpStateMachine: Exit Disconnected: -1
09-12 18:31:00.314   872   872 D BluetoothHeadset: Proxy object disconnected
09-12 18:31:00.315  2020  2032 D BluetoothHeadset: Proxy object disconnected
09-12 18:31:00.317  1360  1360 D BluetoothA2dp: Proxy object disconnected
09-12 18:31:00.318   872   872 D BluetoothA2dp: Proxy object disconnected
09-12 18:31:00.322  2636  2636 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-12 18:31:00.322  2636  2824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 18:31:00.322  2636  2824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 18:31:00.322  2636  2824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 18:31:00.322  2636  2687 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 18:31:00.323  2636  2687 E bt_btif : btif_hf_upstreams_evt: Invalid index 46824
09-12 18:31:00.323  2636  2636 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-12 18:31:00.323  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:00.323  3881  3932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:31:00.323  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:00.323  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:00.323  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:00.323  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:00.323  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:31:00.323  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:31:00.323  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:31:00.324  2636  2636 D HidService: Received stop request...Stopping profile...
09-12 18:31:00.324  2636  2636 D HidService: Stopping Bluetooth HidService
09-12 18:31:00.324  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:00.324  3881  3932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:31:00.324  3881  3932 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:31:00.325  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 18:31:00.326  1360  1360 D BluetoothInputDevice: Proxy object disconnected
,09-12 18:31:00.326  1360  1360 D HidProfile: Bluetooth service disconnected
,09-12 18:31:00.328  2636  2636 V BluetoothAdapterState: isTurningOff()=true
09-12 18:31:00.328  2636  2636 V BluetoothAdapterState: isTurningOn()=false
,09-12 18:31:00.328  2636  2636 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:31:00.328   872  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 18:31:00.328  2636  2636 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:31:00.328   872  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-12 18:31:00.329  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:00.329   872  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 18:31:00.330   872  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 18:31:00.331  2636  2824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
,09-12 18:31:00.331  2636  2687 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-12 18:31:00.331  2636  2824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 18:31:00.331  2636  2824 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:31:00.331  2636  2824 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:31:00.331  2636  2824 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 18:31:00.331  2636  2824 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:31:00.332  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:00.334  2636  2636 D HealthService: Received stop request...Stopping profile...
,09-12 18:31:00.338  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:00.339  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:00.339  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:00.339  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:00.339  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:00.339  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:00.339  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:31:00.339  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:31:00.339  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:31:00.339  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:00.340  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:31:00.340  2636  2636 D PanService: Received stop request...Stopping profile...
,09-12 18:31:00.341  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 18:31:00.341  1360  1360 D PanProfile: Bluetooth service disconnected,
09-12 18:31:00.343  2636  2636 V BluetoothAdapterState: isTurningOff()=true
09-12 18:31:00.343   872  1317 E native  : do suspend true
,09-12 18:31:00.343  2636  2636 V BluetoothAdapterState: isTurningOn()=false
,09-12 18:31:00.343  2636  2636 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 18:31:00.343  2636  2636 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:31:00.343  2636  2636 D BluetoothMapService: Received stop request...Stopping profile...
09-12 18:31:00.343  2636  2636 D BluetoothMapService: stop()
09-12 18:31:00.344  2636  2636 D BluetoothMapAppObserver: deinitObservers()
09-12 18:31:00.344  2636  2636 D BluetoothMapAppObserver: removeReceiver(),
09-12 18:31:00.345  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:00.345  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:00.345  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:00.345  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:00.345  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:00.345  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:00.345  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:31:00.345  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:31:00.345  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:31:00.347  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:00.347  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:31:00.347  1360  1360 D BluetoothMap: Proxy object disconnected
09-12 18:31:00.347  1360  1360 D MapProfile: Bluetooth service disconnected
09-12 18:31:00.347  2636  2636 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 18:31:00.347  2636  2687 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 18:31:00.348  2636  2636 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 18:31:00.348  2636  2636 V BluetoothAdapterState: isTurningOff()=true
,09-12 18:31:00.348  2636  2636 V BluetoothAdapterState: isTurningOn()=false
09-12 18:31:00.348  2636  2636 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:31:00.348  2636  2636 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:31:00.349  2636  2636 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-12 18:31:00.349  2636  2687 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 18:31:00.349  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:00.349  2636  2636 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 18:31:00.350  2636  2636 V BluetoothAdapterState: isTurningOff()=true
09-12 18:31:00.350  2636  2636 V BluetoothAdapterState: isTurningOn()=false
09-12 18:31:00.350  2636  2636 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:31:00.350  2636  2636 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:31:00.350  2636  2636 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 18:31:00.350  2636  2636 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 18:31:00.351  2636  2636 D BluetoothMapService: MAP Service closeService in
,09-12 18:31:00.351  2636  2636 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 18:31:00.351  2636  2636 D ObexServerSockets0: shutdown(block = true)
09-12 18:31:00.351  2636  2873 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-12 18:31:00.352  2636  2636 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 18:31:00.352  2636  2874 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 18:31:00.352  2636  2856 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-12 18:31:00.353  2636  2636 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 18:31:00.353  2636  2636 V BluetoothAdapterState: isTurningOff()=true
09-12 18:31:00.353  2636  2636 V BluetoothAdapterState: isTurningOn()=false
09-12 18:31:00.353  2636  2636 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:31:00.353  2636  2636 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:31:00.353  2636  2683 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 18:31:00.354  2636  2683 D BluetoothAdapterProperties: Setting state to 15
,09-12 18:31:00.354  2636  2683 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 18:31:00.354  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:00.355  2636  2683 I BluetoothAdapterState: Entering BleOnState
09-12 18:31:00.355  2636  2636 D BluetoothMapService: cleanup()
09-12 18:31:00.355  2636  2636 D BluetoothMapService: MAP Service closeService in
09-12 18:31:00.356  2636  2636 I BtOppRfcommListener: stopping Accept Thread
09-12 18:31:00.356  2636  3483 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 18:31:00.356  2636  3483 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 18:31:00.357  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:00.358  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:00.359   872  2094 D DhcpClient: Clearing IP address
09-12 18:31:00.359   372   870 D CommandListener: Clearing all IP addresses on wlan0
09-12 18:31:00.362   372   870 D CommandListener: Setting iface cfg
09-12 18:31:00.364  1513  2477 V NativeCrypto: Read error: ssl=0x9ae47a00: I/O error during system call, Connection timed out
09-12 18:31:00.365  1513  3976 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
09-12 18:31:00.366   872   885 I ActivityManager: Start proc 3986:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-12 18:31:00.367  1360  1379 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 18:31:00.367  1513  2477 V NativeCrypto: SSL shutdown failed: ssl=0x9ae47a00: I/O error during system call, Broken pipe
09-12 18:31:00.367   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 18:31:00.368  1360  1372 D BluetoothMap: onBluetoothStateChange: up=false
09-12 18:31:00.368  1360  2103 D BluetoothPan: onBluetoothStateChange on: false
09-12 18:31:00.369   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:31:00.369  1360  1379 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:31:00.369   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 18:31:00.370  2020  2031 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:31:00.370   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:31:00.370   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 18:31:00.370   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-12 18:31:00.370  1360  1372 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 18:31:00.373  1360  2103 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 18:31:00.374  2636  2683 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 18:31:00.374   872  1317 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-12 18:31:00.374  2636  2683 D BluetoothAdapterProperties: Setting state to 16
09-12 18:31:00.374  2636  2683 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 18:31:00.375   872  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 18:31:00.375   872  1317 E native  : do suspend true
09-12 18:31:00.375  2636  2683 D BluetoothAdapterProperties: onBleDisable
09-12 18:31:00.376  2636  2683 I BluetoothAdapterState: Entering PendingCommandState
09-12 18:31:00.376  2636  2684 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-12 18:31:00.377  2636  2687 D BluetoothAdapterProperties: Scan Mode:20
09-12 18:31:00.378  2636  2824 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 18:31:00.378  2636  2824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 18:31:00.380   401   401 E Parcel  : Reading a NULL string not supported here.
09-12 18:31:00.380   872  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-12 18:31:00.386  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:00.386  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:00.386  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:00.386  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:00.386  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:00.386  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:00.386  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:00.386  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:00.386  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:31:00.387  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:00.387  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:31:00.390  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:00.390  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:00.390  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:00.390  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:00.390  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:00.390  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:00.390  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:00.390  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:00.390  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:31:00.391  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:00.391  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:31:00.392  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:00.392  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:00.392  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:00.392  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:00.392  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:00.392  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:00.392  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:00.392  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:00.392  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:31:00.393  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:00.393  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:31:00.394   872  2096 D DhcpClient: Receive thread stopped
09-12 18:31:00.395  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:00.395  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:00.395  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:00.395  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:00.395  3881  3,881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:00.395  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:00.395  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:00.395  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:00.395  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:31:00.396  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:00.398  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:00.412   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 18:31:00.429   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 18:31:00.429   372   870 D CommandListener: Clearing all IP addresses on wlan0
,09-12 18:31:00.429   872  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-12 18:31:00.430   872  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:31:00.430  3986  3986 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-12 18:31:00.433   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-12 18:31:00.434  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:00.434  3476  3476 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f4808cf and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-12 18:31:00.435  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:00.436  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:00.450  3986  3986 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:31:00.455  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:31:00.458   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@82e422d:true
,09-12 18:31:00.467   872  2034 I ActivityManager: Start proc 4007:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-12 18:31:00.479   372   870 E Netd    : netlink response contains error (No such file or directory)
,09-12 18:31:00.481   872  1319 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-12 18:31:00.482   872  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 18:31:00.498   872  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 18:31:00.500  1869  2245 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 18:31:00.502   872  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 18:31:00.502  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:00.502  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:00.502  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:00.502  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:00.502  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:31:00.502  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:00.502  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:00.502  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:00.502  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:31:00.503  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:31:00.503  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:31:00.504  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:31:00.504  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:00.504  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:00.504  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:00.504  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:31:00.504  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:00.504  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:00.504  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:00.504  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:31:00.505  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:00.505  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:31:00.507  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:31:00.507  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:00.507  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:00.507  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:00.507  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:31:00.507  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:00.507  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:00.507  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:00.507  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:31:00.507  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:00.507  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:31:00.506  3986  3986 D LocalBluetoothProfileManager: Adding local MAP profile
,09-12 18:31:00.513  4007  4007 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-12 18:31:00.518  3986  3986 D BluetoothMap: Create BluetoothMap proxy object
,09-12 18:31:00.522  3986  3986 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-12 18:31:00.534  3986  3986 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:31:00.579  2636  2687 I bt_hci  : shut_down
,09-12 18:31:00.580  2636  2692 D bt_hwcfg: hw_epilog_process
,09-12 18:31:00.585  2636  2692 I bt_vendor: low_power_mode_cb
,09-12 18:31:00.613  2636  2692 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 18:31:00.613  2636  2692 I bt_vendor: epilog_cb
09-12 18:31:00.613  2636  2692 I bt_hci  : epilog_finished_callback
,09-12 18:31:00.618  2636  2687 I bt_hci_h4: hal_close
,09-12 18:31:00.619  2636  2687 I bt_userial_vendor: device fd = 51 close
,09-12 18:31:00.658  4007  4007 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 18:31:00.658  4007  4007 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:31:00.658  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 18:31:00.659  4007  4007 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 18:31:00.659  4007  4007 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 18:31:00.659  4007  4007 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 18:31:00.659  4007  4007 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.r.k.d(PG:583)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 18:31:00.659  4007  4007 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 18:31:00.659  4007  4007 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 18:31:00.659  4007  4007 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:31:00.659  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 18:31:00.671  3986  3986 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:31:00.683  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:31:00.695  3986  3986 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:31:00.709   872  1391 I ActivityManager: Killing 2979:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-12 18:31:00.786  1712  1712 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 18:31:00.790  2636  2684 D bt_stack_manager: event_shut_down_stack finished.
,09-12 18:31:00.790  2636  2683 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-12 18:31:00.793  1712  1712 D SystemUpdateService: onCreate
,09-12 18:31:00.797  2636  2683 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-12 18:31:00.798  2636  2636 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 18:31:00.799  2636  2636 D BtGatt.GattService: Received stop request...Stopping profile...
,09-12 18:31:00.799  2636  2636 D BtGatt.GattService: stop()
,09-12 18:31:00.800  2636  2636 D BtGatt.AdvertiseManager: advertise clients cleared,
,09-12 18:31:00.801  1712  1712 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-12 18:31:00.804  2636  2636 V BluetoothAdapterState: isTurningOff()=false
09-12 18:31:00.805  2636  2636 V BluetoothAdapterState: isTurningOn()=false
09-12 18:31:00.805  2636  2636 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 18:31:00.805  2636  2636 V BluetoothAdapterState: isBleTurningOff()=true
09-12 18:31:00.805  2636  2683 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-12 18:31:00.806  2636  2683 D BluetoothAdapterProperties: Setting state to 10
09-12 18:31:00.806  2636  2683 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 18:31:00.806  2636  2683 I BluetoothAdapterState: Entering OffState
,09-12 18:31:00.810   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-12 18:31:00.810  1712  4038 I SystemUpdateService: active receiver: enabled
,09-12 18:31:00.816  1712  1712 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 18:31:00.816  1712  4038 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 18:31:00.818  2636  2636 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-12 18:31:00.818  2636  2636 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 18:31:00.819  2636  2636 I BluetoothServiceJni: cleanupNative: return from cleanup
09-12 18:31:00.819  2636  2684 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-12 18:31:00.819  1712  2442 I iu.UploadsManager: num queued entries: 0
09-12 18:31:00.821  1712  1712 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-12 18:31:00.821  1712  2442 I iu.UploadsManager: num updated entries: 0
09-12 18:31:00.822  1712  2442 I iu.SyncManager: NEXT; no task
,09-12 18:31:00.822  1712  4038 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-12 18:31:00.822  1712  1712 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-12 18:31:00.822  1712  4038 I SystemUpdateService: now status is 0 (complete)
09-12 18:31:00.822  1712  4038 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 18:31:00.822  1712  4038 I SystemUpdateService: file has been verified
09-12 18:31:00.822  1712  4038 I SystemUpdateService: OTA package size = 12249756
09-12 18:31:00.824  2636  2684 D bt_stack_manager: event_clean_up_stack finished.
,09-12 18:31:00.826  2636  2636 I art     : System.exit called, status: 0
,09-12 18:31:00.826  2636  2636 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-12 18:31:00.828  1712  4038 I SystemUpdateService: showing system update notification
,09-12 18:31:00.837   872  1704 I ActivityManager: Start proc 4041:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-12 18:31:00.849  1712  1712 D SystemUpdateService: onDestroy
,09-12 18:31:00.859   872  1391 I ActivityManager: Process com.android.bluetooth (pid 2636) has died
,09-12 18:31:00.878  4041  4041 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-12 18:31:00.884  4041  4041 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:31:00.911  4041  4041 D SprintDMHelper: simOperator: 
,09-12 18:31:00.911  4041  4041 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 18:31:00.937   872  2019 I ActivityManager: Start proc 4055:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-12 18:31:00.939   872  2019 I ActivityManager: Killing 3476:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-12 18:31:00.969  4007  4030 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 18:31:00.999   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f609b09:true
,09-12 18:31:01.119   872  1704 I ActivityManager: Start proc 4070:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-12 18:31:01.122  3542  4069 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-12 18:31:01.125   872   882 I ActivityManager: Killing 3524:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-12 18:31:01.194  4070  4070 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-12 18:31:01.274  4070  4070 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-12 18:31:01.274  4070  4070 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 18:31:01.274  4070  4070 I GAv4    :   adb logcat -s GAv4
,09-12 18:31:01.290  4070  4070 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 18:31:01.296  4070  4070 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 18:31:01.330  4070  4087 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 18:31:01.435  4070  4070 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-12 18:31:01.484  4070  4070 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-12 18:31:01.492  4070  4070 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8106-8109)
,09-12 18:31:01.492  4070  4070 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 18:31:01.504  4070  4070 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7196a51}
,09-12 18:31:01.504  4070  4070 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 18:31:01.505  4070  4070 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 18:31:01.513  4070  4070 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 18:31:01.515  4070  4070 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 18:31:01.534  4070  4070 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 18:31:01.547  4070  4070 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 18:31:01.547  4070  4070 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 18:31:01.547  4070  4070 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 18:31:01.547  4070  4070 I Adreno  : Build Date                       : 10/20/15
09-12 18:31:01.547  4070  4070 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 18:31:01.547  4070  4070 I Adreno  : Local Branch                     : M14
09-12 18:31:01.547  4070  4070 I Adreno  : Remote Branch                    : 
09-12 18:31:01.547  4070  4070 I Adreno  : Remote Branch                    : 
09-12 18:31:01.547  4070  4070 I Adreno  : Reconstruct Branch               : 
,09-12 18:31:01.603  4070  4070 I NSApplication: Starting up...
,09-12 18:31:01.617  4070  4116 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-12 18:31:01.650   872  2034 I ActivityManager: Start proc 4121:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-12 18:31:01.651   872  2034 I ActivityManager: Killing 1727:android.process.acore/u0a5 (adj 15): empty #17
,09-12 18:31:01.749  4121  4121 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-12 18:31:02.001   872  2005 I ActivityManager: Killing 3764:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-12 18:31:02.068   872   882 I ActivityManager: Start proc 4135:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-12 18:31:02.146  4135  4135 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-12 18:31:02.196  4135  4135 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-12 18:31:02.259   872  2005 I ActivityManager: Killing 3779:com.android.musicfx/u0a18 (adj 15): empty #17
,09-12 18:31:05.327   872  2005 D WifiService: setWifiEnabled: true pid=3881, uid=10000
09-12 18:31:05.327   872  2005 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 18:31:05.340   872  1317 D WifiConfigStore: Loading config and enabling all networks 
,09-12 18:31:05.348  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:31:05.348  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:05.348  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:05.348  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:05.348  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:05.348  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:05.348  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:05.348  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:05.348  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:31:05.348  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:31:05.349  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:31:05.351  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:31:05.351  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:05.351  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:05.351  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:05.351  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:05.351  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:05.351  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:05.351  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:05.351  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:31:05.352  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:31:05.352  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:31:05.354  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:05.355  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:05.355  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:05.355  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:05.355  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:05.355  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:05.355  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:05.355  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:05.355  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:31:05.355  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:31:05.355  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:31:05.367   872  1317 D WifiConfigStore: loaded 0 passpoint configs
,09-12 18:31:05.369   872  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 18:31:05.371   872  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-12 18:31:05.374   872  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 18:31:05.375   872  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-12 18:31:05.375   872  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-12 18:31:05.376   872  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 18:31:05.399   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-12 18:31:05.399   872  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-12 18:31:05.400   372   870 D CommandListener: Setting iface cfg
09-12 18:31:05.400   872  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-12 18:31:05.400   872  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 18:31:05.410   872  1316 D WifiNative-HAL: p2pGetDeviceAddress
09-12 18:31:05.410   872  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 18:31:05.415   872  1317 E native  : do suspend true
,09-12 18:31:05.436   872  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 18:31:06.141   872  1942 I ActivityManager: Killing 3568:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-12 18:31:06.617   872  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 18:31:06.719   872  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.31 rxSuccessRate=7.81 delta 1000 -> 994
,09-12 18:31:06.721   872  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-12 18:31:06.721   872  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:31:06.742   872  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 18:31:06.805   872  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 18:31:06.807  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 18:31:07.251  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 18:31:07.314  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 18:31:07.315  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 18:31:07.323   872  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 18:31:07.336   872  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-12 18:31:07.337   872  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:31:07.337   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 18:31:07.354   872  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:31:07.368   372   870 D CommandListener: Setting iface cfg
,09-12 18:31:07.369   872  1317 D WifiStateMachine: Start Dhcp Watchdog 2
,09-12 18:31:07.376   872  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 18:31:07.404   872  4170 D DhcpClient: Receive thread started
,09-12 18:31:07.491   872  1317 E native  : do suspend false
,09-12 18:31:07.515   872  2094 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 18:31:07.531   872  4170 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172648, domain null
,09-12 18:31:07.533   872  2094 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172648 seconds
,09-12 18:31:07.536   872  2094 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 18:31:07.549   872  4170 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 18:31:07.550   872  2094 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 18:31:07.555   372   870 D CommandListener: Setting iface cfg
,09-12 18:31:07.567   872  2094 D DhcpClient: Scheduling renewal in 86399s
,09-12 18:31:07.571   872  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 18:31:07.574   872  1317 E native  : do suspend true
,09-12 18:31:07.597   872  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 18:31:07.601   872  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 18:31:07.603   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 18:31:07.607   872  1319 D ConnectivityService: Adding iface wlan0 to network 101
,09-12 18:31:07.608   872  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 18:31:07.665   872  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 18:31:07.666   872  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-12 18:31:07.671   872  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-12 18:31:07.674   872  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-12 18:31:07.676   872  1319 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-12 18:31:07.684   872  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 18:31:07.691   872  1319 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-12 18:31:07.691   872  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-12 18:31:07.691   872  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-12 18:31:07.691   872  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-12 18:31:07.691   872  1319 D ConnectivityService:    accepting network in place of null
,09-12 18:31:07.692   872  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 18:31:07.692   872  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 18:31:07.738   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 18:31:07.741   872  4169 D NetlinkSocketObserver: NeighborEvent{elapsedMs=174358, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:31:07.777   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 18:31:07.785   872  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-12 18:31:07.786   872  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:31:07.796   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-12 18:31:07.812  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:07.813  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:07.813  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:07.813  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:07.813  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:07.813  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:07.813  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:31:07.813  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:31:07.813  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:31:07.813  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:07.813  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:31:07.816   872  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-12 18:31:07.816  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:07.816  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:07.816  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:07.816  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
09-12 18:31:07.816  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:07.816  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:07.816  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:31:07.816  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:31:07.816  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:31:07.816  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:07.816  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:31:07.820  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:31:07.821  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:07.821  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:07.821  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:07.821  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:07.821  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:07.821  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:31:07.821  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:31:07.821  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:31:07.821  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:07.821  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:31:07.830  1712  1712 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 18:31:07.837  1712  1712 D SystemUpdateService: onCreate
,09-12 18:31:07.840  1712  1712 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 18:31:07.859   872  4168 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-12 18:31:07.865  1712  4180 I SystemUpdateService: active receiver: enabled
,09-12 18:31:07.869  1712  1712 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-12 18:31:07.872  1712  2442 I iu.UploadsManager: num queued entries: 0
,09-12 18:31:07.880  1712  4180 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 18:31:07.881  1712  2442 I iu.UploadsManager: num updated entries: 0
,09-12 18:31:07.885  1712  1712 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 18:31:07.885  1712  4180 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 18:31:07.885  1712  4180 I SystemUpdateService: now status is 0 (complete)
09-12 18:31:07.885  1712  4180 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 18:31:07.885  1712  4180 I SystemUpdateService: file has been verified
09-12 18:31:07.886  1712  4180 I SystemUpdateService: OTA package size = 12249756
09-12 18:31:07.887  1712  1712 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-12 18:31:07.890  4041  4041 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:31:07.896  1712  4182 I MDM     : [174] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-12 18:31:07.896  1712  4182 W BaseAppContext: Using Auth Proxy for data requests.
09-12 18:31:07.897  1712  4182 V GoogleAuthProtoRequest: [174] a.<init>: mAccountName set to: thalitester@gmail.com
09-12 18:31:07.899  4041  4041 D SprintDMHelper: simOperator: 
09-12 18:31:07.900  4041  4041 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 18:31:07.882  1712  2442 I iu.SyncManager: NEXT; no task
,09-12 18:31:07.910  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 18:31:07.911  1712  4180 I SystemUpdateService: showing system update notification
,09-12 18:31:07.915  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:31:07.925   872  4168 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 16:31:07 GMT], X-Android-Received-Millis=[1473697867925], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473697867901]}
,09-12 18:31:07.929   872  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 18:31:07.929   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-12 18:31:07.930   872  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 18:31:07.935   872  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 18:31:07.968  1712  1712 D SystemUpdateService: onDestroy
,09-12 18:31:07.999  1513  1952 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 18:31:07.999  1513  1952 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-12 18:31:07.999  1513  1952 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 18:31:07.999  1513  1952 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:31:08.012  1712  4182 E MDM     : [174] SitrepService.a: Error sending sitrep.
,09-12 18:31:08.047  3542  4187 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 18:31:08.785   872  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-12 18:31:10.334   872  2019 D WifiService: setWifiEnabled: false pid=3881, uid=10000
09-12 18:31:10.334   872  2019 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 18:31:10.373  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 18:31:10.384   872  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 18:31:10.384   872  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 18:31:10.385   872  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 18:31:10.385   872  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:31:10.416   872  1317 E native  : do suspend true
,09-12 18:31:10.427   872  2094 D DhcpClient: Clearing IP address
09-12 18:31:10.427   372   870 D CommandListener: Clearing all IP addresses on wlan0
,09-12 18:31:10.432   372   870 D CommandListener: Setting iface cfg
,09-12 18:31:10.439  1513  4194 V NativeCrypto: Read error: ssl=0x99cf9200: I/O error during system call, Connection timed out
,09-12 18:31:10.441  1513  4194 V NativeCrypto: SSL shutdown failed: ssl=0x99cf9200: I/O error during system call, Broken pipe
,09-12 18:31:10.448   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-12 18:31:10.448   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-12 18:31:10.452   872  1317 D WifiStateMachine: Start Disconnecting Watchdog 2
09-12 18:31:10.454   872  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 18:31:10.454   872  1317 E native  : do suspend true
,09-12 18:31:10.456   401   401 E Parcel  : Reading a NULL string not supported here.
09-12 18:31:10.463   872  4170 D DhcpClient: Receive thread stopped
09-12 18:31:10.468   872  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-12 18:31:10.472   372   870 D CommandListener: Clearing all IP addresses on wlan0
,09-12 18:31:10.474   872  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 18:31:10.493   872  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 18:31:10.493  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:10.493  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:10.493  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:10.493  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:10.493  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:31:10.493  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:10.493  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:10.493  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:10.493  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:31:10.493  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:10.493  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:31:10.494  1869  2245 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:31:10.496   872  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 18:31:10.496  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:31:10.496  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:10.496  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:10.496  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:10.496  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:31:10.496  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:10.496  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:10.496  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:10.496  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:31:10.496  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:10.496  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:31:10.497  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:10.497  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:10.497  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:10.497  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:10.497  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:31:10.497  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:10.497  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:10.497  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:10.497  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:31:10.497  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:10.498  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:31:10.505   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 18:31:10.534   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 18:31:10.535   872  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-12 18:31:10.535   872  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:31:10.539   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-12 18:31:10.543  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:10.544  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:10.545  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:10.553  1712  1712 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 18:31:10.558  1712  1712 D SystemUpdateService: onCreate
,09-12 18:31:10.564  1712  1712 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 18:31:10.579  1712  1712 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 18:31:10.590  1712  2442 I iu.UploadsManager: num queued entries: 0
,09-12 18:31:10.592  1712  1712 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 18:31:10.594  1712  1712 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 18:31:10.598  4041  4041 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:31:10.603  4041  4041 D SprintDMHelper: simOperator: 
,09-12 18:31:10.603  4041  4041 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 18:31:10.609   372   870 E Netd    : netlink response contains error (No such file or directory)
,09-12 18:31:10.611   872  1319 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-12 18:31:10.639  1712  4204 I SystemUpdateService: active receiver: enabled
,09-12 18:31:10.640  3542  4208 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-12 18:31:10.648  1712  2442 I iu.UploadsManager: num updated entries: 0
,09-12 18:31:10.650  1712  4204 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 18:31:10.651  1712  2442 I iu.SyncManager: NEXT; no task
,09-12 18:31:10.652  1712  4204 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-12 18:31:10.652  1712  4204 I SystemUpdateService: now status is 0 (complete)
09-12 18:31:10.652  1712  4204 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 18:31:10.652  1712  4204 I SystemUpdateService: file has been verified
09-12 18:31:10.653  1712  4204 I SystemUpdateService: OTA package size = 12249756
,09-12 18:31:10.657  1712  4204 I SystemUpdateService: showing system update notification
,09-12 18:31:10.667  1712  1712 D SystemUpdateService: onDestroy
,09-12 18:31:15.393   872   889 I ActivityManager: Start proc 4212:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 18:31:15.527  4212  4212 D AdapterServiceConfig: Adding HeadsetService
09-12 18:31:15.528  4212  4212 D AdapterServiceConfig: Adding A2dpService
09-12 18:31:15.528  4212  4212 D AdapterServiceConfig: Adding HidService
,09-12 18:31:15.529  4212  4212 D AdapterServiceConfig: Adding HealthService
09-12 18:31:15.530  4212  4212 D AdapterServiceConfig: Adding PanService
09-12 18:31:15.531  4212  4212 D AdapterServiceConfig: Adding GattService
09-12 18:31:15.531  4212  4212 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 18:31:15.548  4212  4212 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 18:31:15.548   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3eff2c4:true
,09-12 18:31:15.553  4212  4212 I bt_bluedroid: init
,09-12 18:31:15.553  4212  4224 I BluetoothAdapterState: Entering OffState
,09-12 18:31:15.558  4212  4225 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 18:31:15.559  4212  4225 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-12 18:31:15.559  4212  4225 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 18:31:15.559  4212  4225 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 18:31:15.561  4212  4212 I bt_bluedroid: get_profile_interface socket
,09-12 18:31:15.563  4212  4212 I bt_bluedroid: get_profile_interface sdp
,09-12 18:31:15.564  4212  4228 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 18:31:15.566  4212  4228 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 18:31:15.567  4212  4223 I bt_bluedroid: config_hci_snoop_log
,09-12 18:31:15.570   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 18:31:15.580  4212  4224 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 18:31:15.580  4212  4224 D BluetoothAdapterProperties: Setting state to 14
,09-12 18:31:15.581  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 18:31:15.585  4212  4224 D BluetoothBondStateMachine: make
,09-12 18:31:15.590  4212  4229 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 18:31:15.596  4212  4224 I BluetoothAdapterState: Entering PendingCommandState
,09-12 18:31:15.598  4212  4212 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 18:31:15.601  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
,09-12 18:31:15.602  4212  4212 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 18:31:15.603  4212  4212 D BtGatt.GattService: Received start request. Starting profile...
,09-12 18:31:15.603  4212  4212 D BtGatt.GattService: start()
,09-12 18:31:15.604  4212  4212 I bt_bluedroid: get_profile_interface gatt
,09-12 18:31:15.606  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
09-12 18:31:15.606  4212  4212 D BtGatt.AdvertiseManager: advertise manager created
,09-12 18:31:15.617  4212  4212 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:31:15.617  4212  4212 V BluetoothAdapterState: isTurningOn()=false
09-12 18:31:15.617  4212  4212 V BluetoothAdapterState: isBleTurningOn()=true
,09-12 18:31:15.617  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:31:15.618  4212  4224 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 18:31:15.619  4212  4224 I bt_bluedroid: enable
,09-12 18:31:15.619  4212  4225 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-12 18:31:15.620  4212  4225 I bt_hci  : start_up
,09-12 18:31:15.640  4212  4225 I bt_vendor: alloc value 0xb3994189
,09-12 18:31:15.641  4212  4225 I bt_vendor: init
09-12 18:31:15.641  4212  4225 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-12 18:31:15.641  4212  4225 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 18:31:15.696   872  1319 D ConnectivityService: handlePromptUnvalidated 101
,09-12 18:31:15.754  4212  4225 D bt_hci  : start_up starting async portion
,09-12 18:31:15.755  4212  4232 I bt_hci  : event_finish_startup
09-12 18:31:15.755  4212  4232 I bt_hci_h4: hal_open
09-12 18:31:15.756  4212  4232 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 18:31:15.767  4212  4232 I bt_userial_vendor: device fd = 51 open
,09-12 18:31:15.793  4212  4232 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 18:31:15.825  4212  4232 D bt_hwcfg: Chipset BCM4354A2
09-12 18:31:15.826  4212  4232 D bt_hwcfg: Target name = [BCM4354A2]
,09-12 18:31:15.827  4212  4232 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 18:31:16.484  4212  4232 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 18:31:16.486  4212  4232 D bt_hwcfg: Settlement delay -- 100 ms
09-12 18:31:16.486  4212  4232 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 18:31:16.603  4212  4232 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 18:31:16.604  4212  4232 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 18:31:16.633  4212  4232 I bt_hwcfg: vendor lib fwcfg completed
,09-12 18:31:16.634  4212  4232 I bt_vendor: firmware callback
09-12 18:31:16.634  4212  4232 I bt_hci  : firmware_config_callback
,09-12 18:31:16.645  4212  4234 I bt_btu  : btu_task pending for preload complete event
,09-12 18:31:16.645  4212  4234 I bt_btu_task: Bluetooth chip preload is complete
09-12 18:31:16.645  4212  4234 I bt_btu  : btu_task received preload complete event
,09-12 18:31:16.658  4212  4234 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 18:31:16.659  4212  4234 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 18:31:16.659  4212  4234 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-12 18:31:16.659  4212  4234 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 18:31:16.660  4212  4234 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-12 18:31:16.660  4212  4234 I         : BTE_InitTraceLevels -- TRC_A2D
,09-12 18:31:16.660  4212  4234 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 18:31:16.660  4212  4234 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 18:31:16.662  4212  4234 I         : BTE_InitTraceLevels -- TRC_GAP
,09-12 18:31:16.662  4212  4234 I         : BTE_InitTraceLevels -- TRC_PAN
,09-12 18:31:16.664  4212  4234 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 18:31:16.664  4212  4234 I         : BTE_InitTraceLevels -- TRC_GATT
,09-12 18:31:16.665  4212  4234 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 18:31:16.666  4212  4234 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 18:31:16.667  4212  4234 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 18:31:16.804  4212  4234 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3911d9d
,09-12 18:31:16.805  4212  4234 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3911d9d 
,09-12 18:31:16.815  4212  4228 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 18:31:16.816  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 18:31:16.817  4212  4228 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 18:31:16.822  4212  4228 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 18:31:16.825  4212  4228 D BluetoothAdapterProperties: Scan Mode:20
,09-12 18:31:16.825  4212  4228 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 18:31:16.825  4212  4228 D bt_hci  : do_postload posting postload work item
,09-12 18:31:16.826  4212  4232 I bt_hci  : event_postload
,09-12 18:31:16.826  4212  4232 I bt_vendor: sco_config_cb
,09-12 18:31:16.826  4212  4232 I bt_hci  : sco_config_callback postload finished.
,09-12 18:31:16.829  4212  4228 D bt_bte_conf: Device ID record 1 : primary
,09-12 18:31:16.829  4212  4228 D bt_bte_conf:   vendorId            = 000f
,09-12 18:31:16.829  4212  4228 D bt_bte_conf:   vendorIdSource      = 0001
09-12 18:31:16.830  4212  4228 D bt_bte_conf:   product             = 1200
09-12 18:31:16.830  4212  4228 D bt_bte_conf:   version             = 1436
09-12 18:31:16.830  4212  4228 D bt_bte_conf:   clientExecutableURL = 
,09-12 18:31:16.831  4212  4228 D bt_bte_conf:   serviceDescription  = 
,09-12 18:31:16.831  4212  4228 D bt_bte_conf:   documentationURL    = 
,09-12 18:31:16.831  4212  4228 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 18:31:16.831  4212  4225 D bt_stack_manager: event_start_up_stack finished
09-12 18:31:16.832  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:16.833  4212  4232 I bt_vendor: low_power_mode_cb
09-12 18:31:16.834  4212  4224 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-12 18:31:16.835  4212  4224 D BluetoothAdapterProperties: Setting state to 15
,09-12 18:31:16.835  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 18:31:16.835  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:16.838  4212  4224 I BluetoothAdapterState: Entering BleOnState
09-12 18:31:16.840  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:16.842  4212  4224 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-12 18:31:16.842  4212  4224 D BluetoothAdapterProperties: Setting state to 11
09-12 18:31:16.842  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-12 18:31:16.849  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
09-12 18:31:16.849  4212  4212 D HeadsetService: Received start request. Starting profile...
09-12 18:31:16.854  4212  4212 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 18:31:16.854  4212  4212 D HeadsetStateMachine: make
09-12 18:31:16.862  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:16.864  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:16.867  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:16.870  4212  4212 D HeadsetStateMachine: max_hf_connections = 1
,09-12 18:31:16.871  4212  4212 I bt_bluedroid: get_profile_interface handsfree
,09-12 18:31:16.871  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-12 18:31:16.872  4212  4228 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 18:31:16.873  4212  4224 I BluetoothAdapterState: Entering PendingCommandState
,09-12 18:31:16.876  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
,09-12 18:31:16.876  4212  4212 D A2dpService: Received start request. Starting profile...
,09-12 18:31:16.877  4212  4212 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-12 18:31:16.877  4212  4212 I bt_bluedroid: get_profile_interface avrcp
,09-12 18:31:16.884  4212  4212 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-12 18:31:16.884  4212  4212 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 18:31:16.884  4212  4212 D A2dpStateMachine: make
,09-12 18:31:16.886  4212  4212 I bt_bluedroid: get_profile_interface a2dp
,09-12 18:31:16.886  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 18:31:16.887  4212  4245 D A2dpStateMachine: Enter Disconnected: -2
09-12 18:31:16.888  4212  4212 I BluetoothHidServiceJni: classInitNative: succeeds
09-12 18:31:16.889  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
09-12 18:31:16.890  4212  4212 D HidService: Received start request. Starting profile...
09-12 18:31:16.890  4212  4212 I bt_bluedroid: get_profile_interface hidhost
09-12 18:31:16.890  4212  4212 D HidService: setHidService(): set to: null
09-12 18:31:16.890  4212  4228 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38f33e5
09-12 18:31:16.890  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-12 18:31:16.890  3986  3986 D BluetoothInputDevice: Proxy object connected
09-12 18:31:16.891  4212  4212 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 18:31:16.892  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
09-12 18:31:16.892  3986  3986 D HidProfile: Bluetooth service connected
09-12 18:31:16.892  4212  4212 D HealthService: Received start request. Starting profile...
,09-12 18:31:16.894  4212  4212 I bt_bluedroid: get_profile_interface health
,09-12 18:31:16.896  4212  4212 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 18:31:16.897  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
,09-12 18:31:16.898  4212  4212 D PanService: Received start request. Starting profile...
,09-12 18:31:16.898  3986  3986 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 18:31:16.898  4212  4212 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-12 18:31:16.898  4212  4212 I bt_bluedroid: get_profile_interface pan
09-12 18:31:16.899  4212  4228 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 18:31:16.900  3986  3986 D PanProfile: Bluetooth service connected
,09-12 18:31:16.903  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
,09-12 18:31:16.904  4212  4212 D BluetoothMapService: Received start request. Starting profile...
09-12 18:31:16.904  4212  4212 D BluetoothMapService: start()
,09-12 18:31:16.904  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 18:31:16.907  3986  3986 D BluetoothMap: Proxy object connected
09-12 18:31:16.907  3986  3986 D MapProfile: Bluetooth service connected
,09-12 18:31:16.907  3986  3986 D BluetoothMap: getConnectedDevices()
,09-12 18:31:16.913  3986  3986 D BluetoothMap: Bluetooth is Not enabled
,09-12 18:31:16.913  4212  4212 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-12 18:31:16.915  4212  4212 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-12 18:31:16.915  4212  4212 D BluetoothMapAppObserver: createReceiver()
,09-12 18:31:16.919  4212  4212 D BluetoothMapAppObserver: initObservers()
,09-12 18:31:16.919  4212  4212 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 18:31:16.930  4212  4212 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:31:16.930  4212  4212 V BluetoothAdapterState: isTurningOn()=true
09-12 18:31:16.930  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 18:31:16.930  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:31:16.932  4212  4212 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:31:16.932  4212  4212 V BluetoothAdapterState: isTurningOn()=true
,09-12 18:31:16.932  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 18:31:16.933  4212  4241 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-12 18:31:16.933  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:31:16.933  4212  4212 V BluetoothAdapterState: isTurningOff()=false
09-12 18:31:16.933  4212  4212 V BluetoothAdapterState: isTurningOn()=true
09-12 18:31:16.933  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:31:16.933  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:31:16.933  4212  4212 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:31:16.933  4212  4212 V BluetoothAdapterState: isTurningOn()=true
,09-12 18:31:16.933  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 18:31:16.933  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:31:16.934  4212  4212 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:31:16.934  4212  4212 V BluetoothAdapterState: isTurningOn()=true
09-12 18:31:16.934  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 18:31:16.934  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:31:16.934  4212  4212 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:31:16.934  4212  4212 V BluetoothAdapterState: isTurningOn()=true
,09-12 18:31:16.934  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 18:31:16.935  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:31:16.935  4212  4224 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-12 18:31:16.935  4212  4224 D BluetoothAdapterProperties: ScanMode =  20
,09-12 18:31:16.935  4212  4224 D BluetoothAdapterProperties: State =  11
,09-12 18:31:16.936  4212  4224 D BluetoothAdapterProperties: Setting state to 12
,09-12 18:31:16.936  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 18:31:16.937  1360  2103 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 18:31:16.937  4212  4228 D BluetoothAdapterProperties: Scan Mode:21
09-12 18:31:16.937  4212  4228 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 18:31:16.939   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 18:31:16.939  1360  1360 D BluetoothInputDevice: Proxy object connected
,09-12 18:31:16.939  1360  1360 D HidProfile: Bluetooth service connected
09-12 18:31:16.940  4212  4224 I BluetoothAdapterState: Entering OnState
09-12 18:31:16.941  3986  4000 D BluetoothMap: onBluetoothStateChange: up=true
09-12 18:31:16.942   872   872 D BluetoothA2dp: Proxy object connected
,09-12 18:31:16.942  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:16.942  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:16.942  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:16.942  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:31:16.942  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:31:16.942  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:16.942  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:16.942  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:31:16.943  1360  1372 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 18:31:16.946  1360  1360 D BluetoothMap: Proxy object connected
,09-12 18:31:16.946  1360  1360 D MapProfile: Bluetooth service connected
,09-12 18:31:16.946  1360  1360 D BluetoothMap: getConnectedDevices()
,09-12 18:31:16.946  1360  2103 D BluetoothPan: onBluetoothStateChange on: true
,09-12 18:31:16.949  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:31:16.952  4212  4212 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 18:31:16.953  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 18:31:16.953   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:31:16.953  1360  1360 D PanProfile: Bluetooth service connected
,09-12 18:31:16.953  4212  4212 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 18:31:16.953  1360  1372 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:31:16.954   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:31:16.954  3986  3998 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 18:31:16.954  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:16.954  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:16.954  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:16.954  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:31:16.954  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:31:16.954  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:16.954  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:16.954  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:31:16.955  4212  4212 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:31:16.956  3986  4000 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 18:31:16.957  3986  3998 D BluetoothPan: onBluetoothStateChange on: true
,09-12 18:31:16.957  2020  2031 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:31:16.957  4212  4212 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:31:16.957  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:31:16.958   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:31:16.958  1360  1379 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 18:31:16.959  4212  4212 D ObexServerSockets: Succeed to create listening sockets 
,09-12 18:31:16.959  4212  4212 D ObexServerSockets0: startAccept()
,09-12 18:31:16.959  4212  4212 D ObexServerSockets0: prepareForNewConnect()
09-12 18:31:16.961  1360  1360 D BluetoothA2dp: Proxy object connected
09-12 18:31:16.962  4212  4212 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 18:31:16.962  4212  4212 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 18:31:16.962  1360  1372 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 18:31:16.962  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:16.962  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:16.962  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:16.962  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:31:16.962  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:31:16.962  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:16.962  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:16.962  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:31:16.963  4212  4250 D ObexServerSockets0: Accepting socket connection...
09-12 18:31:16.964  4212  4251 D ObexServerSockets0: Accepting socket connection...
09-12 18:31:16.966  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:31:16.967   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 18:31:16.968  4212  4212 D BluetoothMapService: onReceive
09-12 18:31:16.968  4212  4212 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:31:16.968  4212  4212 D BluetoothMapService: STATE_ON
09-12 18:31:16.969  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:16.971  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:16.972  3986  3986 D LocalBluetoothProfileManager: Adding local A2DP profile
09-12 18:31:16.972  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:16.976  3986  3986 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-12 18:31:16.984  3986  3986 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 18:31:16.987  3986  3986 D BluetoothA2dp: Proxy object connected
09-12 18:31:16.988  4212  4212 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 18:31:16.989  4212  4212 D ObexServerSockets0: prepareForNewConnect()
09-12 18:31:16.992  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 18:31:17.000  3986  3986 D DockEventReceiver: finishStartingService: stopping service
09-12 18:31:17.003  1360  1360 D BluetoothPbap: Proxy object connected
09-12 18:31:17.003  1360  1360 D PbapServerProfile: Bluetooth service connected
09-12 18:31:17.003  3986  3986 D BluetoothPbap: Proxy object connected
,09-12 18:31:17.004  3986  3986 D PbapServerProfile: Bluetooth service connected
09-12 18:31:17.011  4212  4256 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:31:17.024  4212  4260 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:31:17.025  4212  4260 I BtOppRfcommListener: Accept thread started.
,09-12 18:31:17.054   872   872 D BluetoothHeadset: Proxy object connected
,09-12 18:31:17.054   872   872 D BluetoothHeadset: Proxy object connected
,09-12 18:31:17.054  1360  2103 D BluetoothHeadset: Proxy object connected
,09-12 18:31:17.055   872   872 D BluetoothHeadset: Proxy object connected
09-12 18:31:17.055  1360  1360 D HeadsetProfile: Bluetooth service connected
09-12 18:31:17.055  2020  2100 D BluetoothHeadset: Proxy object connected
,09-12 18:31:17.058  2020  2916 D BluetoothHeadset: Proxy object connected
,09-12 18:31:17.058   872   889 D BluetoothHeadset: Proxy object connected
,09-12 18:31:17.079  3986  3998 D BluetoothHeadset: Proxy object connected
,09-12 18:31:17.080  3986  3986 D HeadsetProfile: Bluetooth service connected
,09-12 18:31:20.352  4212  4224 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 18:31:20.352  4212  4224 D BluetoothAdapterProperties: Setting state to 13
09-12 18:31:20.353  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 18:31:20.354  4212  4224 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 18:31:20.356  4212  4224 I BluetoothAdapterState: Entering PendingCommandState
09-12 18:31:20.364  4212  4212 D BluetoothMapService: onReceive
,09-12 18:31:20.365  4212  4212 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:31:20.365  4212  4212 D BluetoothMapService: STATE_TURNING_OFF
,09-12 18:31:20.366  4212  4212 D BluetoothMapService: MAP Service closeService in
09-12 18:31:20.367  4212  4212 D BluetoothMapMasInstance0: MAP Service shutdown
,09-12 18:31:20.367  4212  4212 D ObexServerSockets0: shutdown(block = true)
09-12 18:31:20.368  4212  4250 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-12 18:31:20.369  4212  4212 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 18:31:20.370  4212  4251 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 18:31:20.370  4212  4237 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-12 18:31:20.371  4212  4212 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 18:31:20.372  4212  4212 I BtOppRfcommListener: stopping Accept Thread
09-12 18:31:20.373  4212  4260 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 18:31:20.375  4212  4260 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 18:31:20.378  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:20.378  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:20.378  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:20.378  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:20.378  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:31:20.378  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:20.378  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:20.378  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:20.378  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:31:20.380  4212  4228 D BluetoothAdapterProperties: Scan Mode:20
09-12 18:31:20.381  4212  4224 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-12 18:31:20.384  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:20.384  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:31:20.386  4212  4212 D HeadsetService: Received stop request...Stopping profile...
09-12 18:31:20.387  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:20.388  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:20.388  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:20.388  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:20.388  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:31:20.388  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:20.388  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:20.388  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:20.388  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:31:20.388   872   872 D BluetoothHeadset: Proxy object disconnected
09-12 18:31:20.388  4212  4212 V BluetoothAdapterState: isTurningOff()=true
09-12 18:31:20.388   872   872 D BluetoothHeadset: Proxy object disconnected
09-12 18:31:20.388  4212  4212 V BluetoothAdapterState: isTurningOn()=false
09-12 18:31:20.388  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:31:20.388  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:31:20.389  4212  4212 D A2dpService: Received stop request...Stopping profile...
09-12 18:31:20.389  3986  4000 D BluetoothHeadset: Proxy object disconnected
09-12 18:31:20.389  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:20.389  4212  4245 D A2dpStateMachine: Exit Disconnected: -1
09-12 18:31:20.389  1360  2103 D BluetoothHeadset: Proxy object disconnected
09-12 18:31:20.390  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18,:31:20.390   872   872 D BluetoothHeadset: Proxy object disconnected
09-12 18:31:20.390  2020  2031 D BluetoothHeadset: Proxy object disconnected
09-12 18:31:20.391  3986  3986 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 18:31:20.391   872   872 D BluetoothA2dp: Proxy object disconnected
09-12 18:31:20.393  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:20.393  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:20.393  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:20.393  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:20.393  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:31:20.393  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:31:20.393  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:20.393  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:20.393  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:31:20.394  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:31:20.394  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:31:20.396  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:20.398  4212  4212 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 18:31:20.398  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 18:31:20.398  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:20.399  4212  4212 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 18:31:20.399  4212  4234 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 18:31:20.399  4212  4234 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 18:31:20.399  3986  3986 D HeadsetProfile: Bluetooth service disconnected
09-12 18:31:20.399  4212  4234 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 18:31:20.399  3986  3986 D BluetoothA2dp: Proxy object disconnected
09-12 18:31:20.401  4212  4228 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-12 18:31:20.402  4212  4212 D HidService: Received stop request...Stopping profile...
09-12 18:31:20.402  4212  4212 D HidService: Stopping Bluetooth HidService
09-12 18:31:20.403  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:20.403  4212  4212 V BluetoothAdapterState: isTurningOff()=true
09-12 18:31:20.403  4212  4212 V BluetoothAdapterState: isTurningOn()=false
09-12 18:31:20.404  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:31:20.404  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:31:20.404  4212  4212 D HealthService: Received stop request...Stopping profile...
09-12 18:31:20.406  1360  1360 D HeadsetProfile: Bluetooth service disconnected
09-12 18:31:20.407  1360  1360 D BluetoothA2dp: Proxy object disconnected
09-12 18:31:20.407  1360  1360 D BluetoothInputDevice: Proxy object disconnected
09-12 18:31:20.407  1360  1360 D HidProfile: Bluetooth service disconnected
09-12 18:31:20.408  4212  4234 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 18:31:20.408  4212  4234 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 18:31:20.408  4212  4234 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:31:20.408  4212  4234 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:31:20.408  4212  4234 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:31:20.408  4212  4234 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:31:20.408  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-12 18:31:20.409  3986  3986 D DockEventReceiver: finishStartingService: stopping service
09-12 18:31:20.410  4212  4212 D PanService: Received stop request...Stopping profile...
09-12 18:31:20.411  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 18:31:20.411  3986  3986 D BluetoothInputDevice: Proxy object disconnected
09-12 18:31:20.411  3986  3986 D HidProfile: Bluetooth service disconnected
09-12 18:31:20.411  1360  1360 D PanProfile: Bluetooth service disconnected
09-12 18:31:20.412  4212  4212 D BluetoothMapService: Received stop request...Stopping profile...
09-12 18:31:20.412  4212  4212 D BluetoothMapService: stop()
09-12 18:31:20.413  4212  4212 D BluetoothMapAppObserver: deinitObservers()
09-12 18:31:20.413  3986  3986 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 18:31:20.413  3986  3986 D PanProfile: Bluetooth service disconnected
,09-12 18:31:20.413  4212  4212 D BluetoothMapAppObserver: removeReceiver()
09-12 18:31:20.414  1360  1360 D BluetoothMap: Proxy object disconnected
09-12 18:31:20.414  1360  1360 D MapProfile: Bluetooth service disconnected
09-12 18:31:20.415  3986  3986 D BluetoothMap: Proxy object disconnected
09-12 18:31:20.415  3986  3986 D MapProfile: Bluetooth service disconnected
,09-12 18:31:20.417  4212  4212 V BluetoothAdapterState: isTurningOff()=true
,09-12 18:31:20.418  4212  4212 V BluetoothAdapterState: isTurningOn()=false
09-12 18:31:20.418  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:31:20.418  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:31:20.418  4212  4212 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-12 18:31:20.418  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 18:31:20.418  4212  4212 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-12 18:31:20.419  4212  4212 V BluetoothAdapterState: isTurningOff()=true
09-12 18:31:20.418  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 18:31:20.419  4212  4212 V BluetoothAdapterState: isTurningOn()=false
09-12 18:31:20.419  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:31:20.419  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:31:20.419  4212  4212 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 18:31:20.419  4212  4228 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 18:31:20.420  4212  4212 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 18:31:20.420  4212  4212 V BluetoothAdapterState: isTurningOff()=true
,09-12 18:31:20.420  4212  4212 V BluetoothAdapterState: isTurningOn()=false
09-12 18:31:20.420  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:31:20.420  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:31:20.421  4212  4212 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 18:31:20.421  4212  4212 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-12 18:31:20.422  4212  4212 D BluetoothMapService: MAP Service closeService in
09-12 18:31:20.422  4212  4212 V BluetoothAdapterState: isTurningOff()=true
09-12 18:31:20.422  4212  4212 V BluetoothAdapterState: isTurningOn()=false
09-12 18:31:20.422  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 18:31:20.422  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:31:20.423  4212  4224 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 18:31:20.423  4212  4224 D BluetoothAdapterProperties: Setting state to 15
09-12 18:31:20.423  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-12 18:31:20.424  4212  4224 I BluetoothAdapterState: Entering BleOnState
09-12 18:31:20.424  4212  4212 D BluetoothMapService: cleanup()
09-12 18:31:20.424  1360  2103 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 18:31:20.424  4212  4212 D BluetoothMapService: MAP Service closeService in
09-12 18:31:20.425   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 18:31:20.425  3986  4000 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 18:31:20.426  1360  1360 D BluetoothPbap: Proxy object disconnected
09-12 18:31:20.426  1360  1360 D PbapServerProfile: Bluetooth service disconnected
,09-12 18:31:20.426  1360  2103 D BluetoothMap: onBluetoothStateChange: up=false
09-12 18:31:20.427  1360  1379 D BluetoothPan: onBluetoothStateChange on: false
09-12 18:31:20.427  3986  3986 D BluetoothPbap: Proxy object disconnected
,09-12 18:31:20.428  3986  3986 D PbapServerProfile: Bluetooth service disconnected
09-12 18:31:20.429   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:31:20.430  1360  1372 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 18:31:20.430   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:31:20.430  3986  3998 D BluetoothPbap: onBluetoothStateChange: up=false
,09-12 18:31:20.432  3986  4000 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 18:31:20.433  3986  3998 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 18:31:20.433  3986  4000 D BluetoothPan: onBluetoothStateChange on: false
,09-12 18:31:20.434  2020  2100 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:31:20.434  3986  3998 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:31:20.434   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:31:20.434  1360  2103 D BluetoothA2dp: onBluetoothStateChange: up=false,
,09-12 18:31:20.435  1360  1379 D BluetoothPbap: onBluetoothStateChange: up=false
,09-12 18:31:20.435  4212  4224 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-12 18:31:20.436  4212  4224 D BluetoothAdapterProperties: Setting state to 16
09-12 18:31:20.436  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 18:31:20.439  4212  4224 D BluetoothAdapterProperties: onBleDisable
,09-12 18:31:20.439  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:20.439  4212  4224 I BluetoothAdapterState: Entering PendingCommandState
09-12 18:31:20.440  3986  3986 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:31:20.440  4212  4225 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-12 18:31:20.440  4212  4228 D BluetoothAdapterProperties: Scan Mode:20
09-12 18:31:20.441  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:20.442  4212  4234 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-12 18:31:20.442  4212  4234 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 18:31:20.442  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:20.444  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:20.445  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:20.446  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:20.448  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 18:31:20.448  3986  3986 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:31:20.643  4212  4228 I bt_hci  : shut_down
,09-12 18:31:20.657  4212  4232 D bt_hwcfg: hw_epilog_process
,09-12 18:31:20.658  4212  4232 I bt_vendor: low_power_mode_cb
,09-12 18:31:20.677  4212  4232 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 18:31:20.677  4212  4232 I bt_vendor: epilog_cb
09-12 18:31:20.677  4212  4232 I bt_hci  : epilog_finished_callback
,09-12 18:31:20.685  4212  4228 I bt_hci_h4: hal_close
,09-12 18:31:20.687  4212  4228 I bt_userial_vendor: device fd = 51 close
,09-12 18:31:20.809  4212  4225 D bt_stack_manager: event_shut_down_stack finished.
,09-12 18:31:20.810  4212  4224 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 18:31:20.818  4212  4224 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-12 18:31:20.818  4212  4212 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 18:31:20.821  4212  4212 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 18:31:20.823  4212  4212 D BtGatt.GattService: stop()
09-12 18:31:20.823  4212  4212 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 18:31:20.830  4212  4212 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:31:20.830  4212  4212 V BluetoothAdapterState: isTurningOn()=false
,09-12 18:31:20.830  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:31:20.831  4212  4212 V BluetoothAdapterState: isBleTurningOff()=true
,09-12 18:31:20.833  4212  4224 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25,
09-12 18:31:20.834  4212  4224 D BluetoothAdapterProperties: Setting state to 10
09-12 18:31:20.834  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 18:31:20.835  4212  4224 I BluetoothAdapterState: Entering OffState
09-12 18:31:20.837   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-12 18:31:20.859  4212  4212 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-12 18:31:20.859  4212  4212 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-12 18:31:20.863  4212  4225 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 18:31:20.863  4212  4212 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 18:31:20.873  4212  4225 D bt_stack_manager: event_clean_up_stack finished.
,09-12 18:31:20.879  4212  4212 I art     : System.exit called, status: 0
,09-12 18:31:20.879  4212  4212 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 18:31:20.929   872  1942 I ActivityManager: Process com.android.bluetooth (pid 4212) has died
,09-12 18:31:22.294  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:31:22.306  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:31:22.311  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:31:22.357  1513  3942 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 18:31:22.357  1513  3942 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 18:31:22.358  1513  3942 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:31:22.358  1513  3942 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:31:22.413  3604  3604 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 18:31:22.413  3604  3604 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 18:31:22.413  3604  3604 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-12 18:31:25.349  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:31:25.350  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:31:25.354  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:31:25.354  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d642c3 removed from the list
,09-12 18:31:25.355  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:31:25.355  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:31:25.355  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:31:25.358  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:31:25.358  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@94cc679 added. We now have 4 listener(s)
,09-12 18:31:25.359  3881  3932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:31:25.361  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:31:25.361  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@94cc679 removed from the list
09-12 18:31:25.361  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:31:25.362  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:31:25.362  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:31:25.364  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:31:25.364  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4bf8fbe added. We now have 4 listener(s)
,09-12 18:31:25.365  3881  3932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:31:30.379  3881  3932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:30.429   872   889 I ActivityManager: Start proc 4271:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 18:31:30.579  4271  4271 D AdapterServiceConfig: Adding HeadsetService
,09-12 18:31:30.579  4271  4271 D AdapterServiceConfig: Adding A2dpService
,09-12 18:31:30.580  4271  4271 D AdapterServiceConfig: Adding HidService
,09-12 18:31:30.580  4271  4271 D AdapterServiceConfig: Adding HealthService
,09-12 18:31:30.580  4271  4271 D AdapterServiceConfig: Adding PanService
,09-12 18:31:30.580  4271  4271 D AdapterServiceConfig: Adding GattService
09-12 18:31:30.580  4271  4271 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 18:31:30.593  4271  4271 D BluetoothAdapterState: make() - Creating AdapterState
09-12 18:31:30.593   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@75756ab:true
,09-12 18:31:30.602  4271  4271 I bt_bluedroid: init
09-12 18:31:30.602  4271  4283 I BluetoothAdapterState: Entering OffState
,09-12 18:31:30.608  4271  4284 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-12 18:31:30.608  4271  4284 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-12 18:31:30.608  4271  4284 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 18:31:30.609  4271  4284 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 18:31:30.611  4271  4271 I bt_bluedroid: get_profile_interface socket
,09-12 18:31:30.613  4271  4287 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-12 18:31:30.614  4271  4287 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 18:31:30.615  4271  4271 I bt_bluedroid: get_profile_interface sdp
,09-12 18:31:30.623  4271  4282 I bt_bluedroid: config_hci_snoop_log
,09-12 18:31:30.624   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 18:31:30.632  4271  4283 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 18:31:30.632  4271  4283 D BluetoothAdapterProperties: Setting state to 14
09-12 18:31:30.632  4271  4283 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-12 18:31:30.634  4271  4283 D BluetoothBondStateMachine: make
,09-12 18:31:30.636  4271  4288 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 18:31:30.641  4271  4283 I BluetoothAdapterState: Entering PendingCommandState
,09-12 18:31:30.645  4271  4271 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 18:31:30.654  4271  4271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
,09-12 18:31:30.656  4271  4271 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 18:31:30.658  4271  4271 D BtGatt.GattService: Received start request. Starting profile...
,09-12 18:31:30.659  4271  4271 D BtGatt.GattService: start()
09-12 18:31:30.659  4271  4271 I bt_bluedroid: get_profile_interface gatt
,09-12 18:31:30.661  4271  4271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
09-12 18:31:30.661  4271  4271 D BtGatt.AdvertiseManager: advertise manager created
,09-12 18:31:30.668  4271  4271 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:31:30.668  4271  4271 V BluetoothAdapterState: isTurningOn()=false
09-12 18:31:30.668  4271  4271 V BluetoothAdapterState: isBleTurningOn()=true
09-12 18:31:30.668  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false,
09-12 18:31:30.669  4271  4283 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 18:31:30.669  4271  4283 I bt_bluedroid: enable
,09-12 18:31:30.669  4271  4284 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-12 18:31:30.670  4271  4284 I bt_hci  : start_up
,09-12 18:31:30.677  4271  4284 I bt_vendor: alloc value 0xb3994189
,09-12 18:31:30.677  4271  4284 I bt_vendor: init
09-12 18:31:30.677  4271  4284 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 18:31:30.677  4271  4284 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 18:31:30.785  4271  4284 D bt_hci  : start_up starting async portion
,09-12 18:31:30.786  4271  4291 I bt_hci  : event_finish_startup
09-12 18:31:30.786  4271  4291 I bt_hci_h4: hal_open
,09-12 18:31:30.786  4271  4291 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 18:31:30.799  4271  4291 I bt_userial_vendor: device fd = 51 open
,09-12 18:31:30.828  4271  4291 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 18:31:30.859  4271  4291 D bt_hwcfg: Chipset BCM4354A2
,09-12 18:31:30.860  4271  4291 D bt_hwcfg: Target name = [BCM4354A2]
,09-12 18:31:30.861  4271  4291 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 18:31:31.696  4271  4291 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 18:31:31.698  4271  4291 D bt_hwcfg: Settlement delay -- 100 ms
09-12 18:31:31.698  4271  4291 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 18:31:31.816  4271  4291 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 18:31:31.818  4271  4291 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 18:31:31.846  4271  4291 I bt_hwcfg: vendor lib fwcfg completed
09-12 18:31:31.846  4271  4291 I bt_vendor: firmware callback
09-12 18:31:31.846  4271  4291 I bt_hci  : firmware_config_callback
,09-12 18:31:31.859  4271  4293 I bt_btu  : btu_task pending for preload complete event
,09-12 18:31:31.860  4271  4293 I bt_btu_task: Bluetooth chip preload is complete
09-12 18:31:31.860  4271  4293 I bt_btu  : btu_task received preload complete event
,09-12 18:31:31.871  4271  4293 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 18:31:31.872  4271  4293 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 18:31:31.872  4271  4293 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 18:31:31.872  4271  4293 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-12 18:31:31.873  4271  4293 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 18:31:31.873  4271  4293 I         : BTE_InitTraceLevels -- TRC_A2D
,09-12 18:31:31.873  4271  4293 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-12 18:31:31.873  4271  4293 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 18:31:31.874  4271  4293 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 18:31:31.875  4271  4293 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 18:31:31.875  4271  4293 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 18:31:31.876  4271  4293 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 18:31:31.876  4271  4293 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 18:31:31.877  4271  4293 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 18:31:31.878  4271  4293 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 18:31:32.014  4271  4293 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3911d9d,
09-12 18:31:32.014  4271  4293 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3911d9d 
,09-12 18:31:32.027  4271  4287 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
09-12 18:31:32.029  4271  4287 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 18:31:32.030  4271  4287 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 18:31:32.037  4271  4287 D BluetoothAdapterProperties: Name is: Nexus 6
09-12 18:31:32.044  4271  4287 D BluetoothAdapterProperties: Scan Mode:20
,09-12 18:31:32.044  4271  4287 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 18:31:32.046  4271  4287 D bt_hci  : do_postload posting postload work item
,09-12 18:31:32.046  4271  4291 I bt_hci  : event_postload
,09-12 18:31:32.046  4271  4291 I bt_vendor: sco_config_cb
09-12 18:31:32.046  4271  4291 I bt_hci  : sco_config_callback postload finished.
09-12 18:31:32.047  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:32.048  4271  4287 D bt_bte_conf: Device ID record 1 : primary
09-12 18:31:32.048  4271  4287 D bt_bte_conf:   vendorId            = 000f
09-12 18:31:32.048  4271  4287 D bt_bte_conf:   vendorIdSource      = 0001
,09-12 18:31:32.048  4271  4287 D bt_bte_conf:   product             = 1200
09-12 18:31:32.048  4271  4287 D bt_bte_conf:   version             = 1436
09-12 18:31:32.048  4271  4287 D bt_bte_conf:   clientExecutableURL = 
09-12 18:31:32.048  4271  4287 D bt_bte_conf:   serviceDescription  = 
09-12 18:31:32.048  4271  4287 D bt_bte_conf:   documentationURL    = 
09-12 18:31:32.048  4271  4287 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 18:31:32.049  4271  4284 D bt_stack_manager: event_start_up_stack finished
09-12 18:31:32.050  4271  4283 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-12 18:31:32.050  4271  4283 D BluetoothAdapterProperties: Setting state to 15
09-12 18:31:32.050  4271  4283 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 18:31:32.051  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:32.051  4271  4283 I BluetoothAdapterState: Entering BleOnState
09-12 18:31:32.052  4271  4291 I bt_vendor: low_power_mode_cb
09-12 18:31:32.055  4271  4283 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-12 18:31:32.055  4271  4283 D BluetoothAdapterProperties: Setting state to 11
09-12 18:31:32.056  4271  4283 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 18:31:32.064  4271  4271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
,09-12 18:31:32.065  4271  4271 D HeadsetService: Received start request. Starting profile...
09-12 18:31:32.074  4271  4271 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-12 18:31:32.074  4271  4271 D HeadsetStateMachine: make
09-12 18:31:32.074  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:32.078  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:32.083  4271  4283 I BluetoothAdapterState: Entering PendingCommandState
,09-12 18:31:32.086  4271  4271 D HeadsetStateMachine: max_hf_connections = 1
09-12 18:31:32.086  4271  4271 I bt_bluedroid: get_profile_interface handsfree
,09-12 18:31:32.086  4271  4287 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 18:31:32.086  4271  4287 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-12 18:31:32.089  4271  4271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
09-12 18:31:32.090  4271  4271 D A2dpService: Received start request. Starting profile...
,09-12 18:31:32.091  4271  4271 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 18:31:32.091  4271  4271 I bt_bluedroid: get_profile_interface avrcp
,09-12 18:31:32.097  4271  4271 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 18:31:32.097  4271  4271 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 18:31:32.097  4271  4271 D A2dpStateMachine: make
,09-12 18:31:32.098  4271  4271 I bt_bluedroid: get_profile_interface a2dp
,09-12 18:31:32.100  4271  4287 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 18:31:32.100  4271  4302 D A2dpStateMachine: Enter Disconnected: -2,
09-12 18:31:32.101  4271  4271 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 18:31:32.102  4271  4271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
,09-12 18:31:32.103  4271  4271 D HidService: Received start request. Starting profile...
09-12 18:31:32.103  4271  4271 I bt_bluedroid: get_profile_interface hidhost
,09-12 18:31:32.103  4271  4287 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38f33e5
,09-12 18:31:32.104  4271  4287 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-12 18:31:32.104  4271  4271 D HidService: setHidService(): set to: null
09-12 18:31:32.104  4271  4271 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 18:31:32.105  4271  4271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
09-12 18:31:32.106  4271  4271 D HealthService: Received start request. Starting profile...
,09-12 18:31:32.107  4271  4271 I bt_bluedroid: get_profile_interface health,
,09-12 18:31:32.109  4271  4271 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 18:31:32.110  4271  4271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
,09-12 18:31:32.110  4271  4271 D PanService: Received start request. Starting profile...
09-12 18:31:32.110  4271  4271 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-12 18:31:32.110  4271  4271 I bt_bluedroid: get_profile_interface pan
09-12 18:31:32.111  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 18:31:32.111  4271  4287 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 18:31:32.114  4271  4271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
09-12 18:31:32.115  4271  4271 D BluetoothMapService: Received start request. Starting profile...
,09-12 18:31:32.115  4271  4271 D BluetoothMapService: start()
,09-12 18:31:32.117  4271  4271 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-12 18:31:32.118  4271  4271 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 18:31:32.118  4271  4271 D BluetoothMapAppObserver: createReceiver()
,09-12 18:31:32.119  4271  4271 D BluetoothMapAppObserver: initObservers()
,09-12 18:31:32.119  4271  4271 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 18:31:32.126  4271  4271 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:31:32.126  4271  4271 V BluetoothAdapterState: isTurningOn()=true
09-12 18:31:32.126  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 18:31:32.127  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:31:32.128  4271  4271 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:31:32.128  4271  4271 V BluetoothAdapterState: isTurningOn()=true
09-12 18:31:32.128  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:31:32.128  4271  4299 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 18:31:32.128  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:31:32.128  4271  4271 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:31:32.129  4271  4271 V BluetoothAdapterState: isTurningOn()=true
,09-12 18:31:32.129  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 18:31:32.129  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:31:32.129  4271  4271 V BluetoothAdapterState: isTurningOff()=false
09-12 18:31:32.129  4271  4271 V BluetoothAdapterState: isTurningOn()=true
09-12 18:31:32.129  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 18:31:32.129  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:31:32.130  4271  4271 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:31:32.130  4271  4271 V BluetoothAdapterState: isTurningOn()=true
09-12 18:31:32.130  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:31:32.130  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 18:31:32.130  4271  4271 V BluetoothAdapterState: isTurningOff()=false
,09-12 18:31:32.130  4271  4271 V BluetoothAdapterState: isTurningOn()=true
09-12 18:31:32.130  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
09-12 18:31:32.130  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
09-12 18:31:32.131  4271  4283 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 18:31:32.131  4271  4283 D BluetoothAdapterProperties: ScanMode =  20
09-12 18:31:32.131  4271  4283 D BluetoothAdapterProperties: State =  11
,09-12 18:31:32.131  4271  4283 D BluetoothAdapterProperties: Setting state to 12
09-12 18:31:32.131  4271  4283 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 18:31:32.132  4271  4283 I BluetoothAdapterState: Entering OnState
09-12 18:31:32.132  1360  1379 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 18:31:32.133  4271  4287 D BluetoothAdapterProperties: Scan Mode:21
09-12 18:31:32.133  4271  4287 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 18:31:32.134   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 18:31:32.134  3986  3998 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 18:31:32.135  1360  1360 D BluetoothInputDevice: Proxy object connected
09-12 18:31:32.135  1360  1360 D HidProfile: Bluetooth service connected
09-12 18:31:32.136   872   872 D BluetoothA2dp: Proxy object connected
09-12 18:31:32.136  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:32.136  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:32.136  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:32.136  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:31:32.136  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:31:32.136  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:32.136  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:32.136  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:31:32.138  1360  2103 D BluetoothMap: onBluetoothStateChange: up=true
09-12 18:31:32.139  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:31:32.139  1360  1360 D BluetoothMap: Proxy object connected
09-12 18:31:32.140  1360  1360 D MapProfile: Bluetooth service connected
09-12 18:31:32.140  3986  3986 D BluetoothMap: Proxy object connected
09-12 18:31:32.140  1360  1360 D BluetoothMap: getConnectedDevices()
09-12 18:31:32.140  1360  1372 D BluetoothPan: onBluetoothStateChange on: true
09-12 18:31:32.140  3986  3986 D MapProfile: Bluetooth service connected
,09-12 18:31:32.140  3986  3986 D BluetoothMap: getConnectedDevices()
09-12 18:31:32.141   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:31:32.141  1360  1379 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:31:32.142   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 18:31:32.142  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 18:31:32.142  3986  3998 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 18:31:32.142  1360  1360 D PanProfile: Bluetooth service connected
09-12 18:31:32.144  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:32.144  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:32.144  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:32.144  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:31:32.144  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:31:32.144  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:32.144  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:32.144  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:31:32.144  3986  4000 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 18:31:32.146  4271  4271 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 18:31:32.146  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:31:32.146  4271  4271 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 18:31:32.146  3986  3998 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 18:31:32.148  4271  4271 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:31:32.149  3986  4000 D BluetoothPan: onBluetoothStateChange on: true
,09-12 18:31:32.150  4271  4271 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:31:32.151  2020  2100 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:31:32.151  4271  4271 D ObexServerSockets: Succeed to create listening sockets 
,09-12 18:31:32.151  4271  4271 D ObexServerSockets0: startAccept()
09-12 18:31:32.151  4271  4271 D ObexServerSockets0: prepareForNewConnect()
09-12 18:31:32.151  3986  3998 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:31:32.150  3986  3986 D BluetoothInputDevice: Proxy object connected
09-12 18:31:32.152   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:31:32.152  1360  1372 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 18:31:32.153  3986  3986 D HidProfile: Bluetooth service connected
09-12 18:31:32.154  1360  1379 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 18:31:32.154  1360  1360 D BluetoothA2dp: Proxy object connected
09-12 18:31:32.156   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-12 18:31:32.156  4271  4271 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 18:31:32.157  4271  4271 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-12 18:31:32.157  4271  4309 D ObexServerSockets0: Accepting socket connection...
09-12 18:31:32.158  4271  4310 D ObexServerSockets0: Accepting socket connection...
,09-12 18:31:32.159  4271  4271 D BluetoothMapService: onReceive
,09-12 18:31:32.159  4271  4271 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:31:32.159  4271  4271 D BluetoothMapService: STATE_ON
,09-12 18:31:32.160  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:31:32.161  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:32.155  3986  3986 D BluetoothA2dp: Proxy object connected
,09-12 18:31:32.164  3986  3986 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 18:31:32.164  3986  3986 D PanProfile: Bluetooth service connected
,09-12 18:31:32.169  3986  3986 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:31:32.175  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:31:32.176  3986  3986 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:31:32.185  1360  1360 D BluetoothPbap: Proxy object connected
,09-12 18:31:32.185  1360  1360 D PbapServerProfile: Bluetooth service connected
09-12 18:31:32.186  3986  3986 D BluetoothPbap: Proxy object connected
,09-12 18:31:32.186  3986  3986 D PbapServerProfile: Bluetooth service connected
,09-12 18:31:32.189  4271  4271 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 18:31:32.189  4271  4271 D ObexServerSockets0: prepareForNewConnect()
09-12 18:31:32.192  4271  4315 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:31:32.208  4271  4319 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:31:32.209  4271  4319 I BtOppRfcommListener: Accept thread started.
,09-12 18:31:32.242   872   872 D BluetoothHeadset: Proxy object connected
,09-12 18:31:32.242   872   872 D BluetoothHeadset: Proxy object connected
09-12 18:31:32.242  3986  3998 D BluetoothHeadset: Proxy object connected
09-12 18:31:32.242  1360  1372 D BluetoothHeadset: Proxy object connected
09-12 18:31:32.243  1360  1360 D HeadsetProfile: Bluetooth service connected
09-12 18:31:32.243  1360  2103 D BluetoothHeadset: Proxy object connected
09-12 18:31:32.243   872   872 D BluetoothHeadset: Proxy object connected
09-12 18:31:32.243   872   889 D BluetoothHeadset: Proxy object connected
09-12 18:31:32.243  2020  2031 D BluetoothHeadset: Proxy object connected
,09-12 18:31:32.246  3986  3986 D HeadsetProfile: Bluetooth service connected
,09-12 18:31:32.251  1360  1360 D HeadsetProfile: Bluetooth service connected
09-12 18:31:32.251  2020  2100 D BluetoothHeadset: Proxy object connected
09-12 18:31:32.252  3986  4308 D BluetoothHeadset: Proxy object connected
,09-12 18:31:32.256   872   889 D BluetoothHeadset: Proxy object connected
09-12 18:31:32.258  3986  3986 D HeadsetProfile: Bluetooth service connected
,09-12 18:31:35.398  3881  3932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:35.398  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:35.398  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:35.398  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:31:35.398  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:31:35.398  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:35.398  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:35.398  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:31:35.406  3881  3932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:31:35.407  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:31:35.407  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4bf8fbe removed from the list
09-12 18:31:35.407  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:31:35.408  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:31:35.408  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:31:35.411  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:31:35.412  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e50481f added. We now have 4 listener(s)
,09-12 18:31:35.412  3881  3932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:31:35.417   872  1962 D WifiService: setWifiEnabled: false pid=3881, uid=10000
,09-12 18:31:35.417   872  1962 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 18:31:40.431  3881  3932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:40.433   872   882 D WifiService: setWifiEnabled: true pid=3881, uid=10000
09-12 18:31:40.433   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 18:31:40.449   872  1317 D WifiConfigStore: Loading config and enabling all networks 
,09-12 18:31:40.467  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:40.467  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:40.467  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:40.467  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:40.467  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:31:40.467  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:40.467  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:40.467  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:31:40.471  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:31:40.480  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:40.480  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:40.480  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:40.480  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:40.480  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:31:40.480  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:31:40.480  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:31:40.480  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:31:40.484   872  1317 D WifiConfigStore: loaded 0 passpoint configs
,09-12 18:31:40.485   872  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 18:31:40.486   872  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-12 18:31:40.486  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:31:40.487   872  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-12 18:31:40.487   872  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 18:31:40.487   872  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-12 18:31:40.487   872  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 18:31:40.501   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-12 18:31:40.502   372   870 D CommandListener: Setting iface cfg
,09-12 18:31:40.502   872  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-12 18:31:40.503   872  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 18:31:40.504   872  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-12 18:31:40.506   872  1316 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 18:31:40.507   872  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 18:31:40.569   872  1317 E native  : do suspend true
,09-12 18:31:40.598   872  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 18:31:41.784   872  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 18:31:41.923   872  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.12 rxSuccessRate=9.56 delta 1000 -> 994
,09-12 18:31:41.925   872  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 18:31:41.925   872  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:31:41.939   872  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 18:31:42.017   872  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 18:31:42.019  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 18:31:42.488  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 18:31:42.569  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 18:31:42.572  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 18:31:42.580   872  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 18:31:42.598   872  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 18:31:42.599   872  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 18:31:42.600   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 18:31:42.624   872  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:31:42.640   372   870 D CommandListener: Setting iface cfg
,09-12 18:31:42.644   872  1317 D WifiStateMachine: Start Dhcp Watchdog 3
,09-12 18:31:42.651   872  4330 D DhcpClient: Receive thread started
,09-12 18:31:42.661   872  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 18:31:42.770   872  1317 E native  : do suspend false
,09-12 18:31:42.799   872  2094 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 18:31:42.820   872  4330 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-12 18:31:42.821   872  2094 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-12 18:31:42.825   872  2094 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 18:31:42.841   872  4330 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 18:31:42.843   872  2094 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 18:31:42.848   372   870 D CommandListener: Setting iface cfg
,09-12 18:31:42.859   872  2094 D DhcpClient: Scheduling renewal in 86399s
,09-12 18:31:42.861   872  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 18:31:42.865   872  1317 E native  : do suspend true
,09-12 18:31:42.901   872  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 18:31:42.906   872  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 18:31:42.907   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 18:31:42.910   872  1319 D ConnectivityService: Adding iface wlan0 to network 102
,09-12 18:31:42.921   872  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 18:31:42.967   872  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 18:31:42.967   872  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-12 18:31:42.969   872  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-12 18:31:42.971   872  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-12 18:31:42.972   872  1319 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-12 18:31:42.983   872  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 18:31:42.992   872  1319 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-12 18:31:42.993   872  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-12 18:31:42.993   872  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-12 18:31:42.993   872  1319 D ConnectivityService:    accepting network in place of null
09-12 18:31:42.993   872  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-12 18:31:42.994   872  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-12 18:31:42.994   872  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 18:31:43.007   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=209624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:31:43.036   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 18:31:43.089   872  4328 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-12 18:31:43.102   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 18:31:43.110   872  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-12 18:31:43.110   872  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:31:43.114   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-12 18:31:43.118   872  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-12 18:31:43.140  1712  1712 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-12 18:31:43.143  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:43.143  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:43.143  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:43.143  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:43.143  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:31:43.143  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:31:43.143  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:31:43.143  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:31:43.146  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:31:43.148  1712  1712 D SystemUpdateService: onCreate
,09-12 18:31:43.151  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:43.151  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:43.151  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:43.151  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:43.151  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:31:43.151  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:31:43.151  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:31:43.151  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:31:43.152  1712  1712 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 18:31:43.152   872  4328 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 16:31:43 GMT], X-Android-Received-Millis=[1473697903152], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473697903131]},
,09-12 18:31:43.153   872  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 18:31:43.153   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-12 18:31:43.154   872  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 18:31:43.155   872  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-12 18:31:43.155  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:31:43.182  1712  1712 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 18:31:43.186  1712  4340 I SystemUpdateService: active receiver: enabled
,09-12 18:31:43.190  1712  2442 I iu.UploadsManager: num queued entries: 0
09-12 18:31:43.190  1712  2442 I iu.UploadsManager: num updated entries: 0
09-12 18:31:43.191  1712  2442 I iu.SyncManager: NEXT; no task
,09-12 18:31:43.193  1712  1712 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 18:31:43.194  1712  1712 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 18:31:43.197  4041  4041 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:31:43.201  1712  4342 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-12 18:31:43.201  1712  4342 W BaseAppContext: Using Auth Proxy for data requests.
09-12 18:31:43.202  1712  4342 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
09-12 18:31:43.203  4041  4041 D SprintDMHelper: simOperator: 
09-12 18:31:43.203  4041  4041 D SprintDMReceiver: Not Sprint UICC, don't do anything.,
,09-12 18:31:43.209  1712  4340 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 18:31:43.220  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:31:43.225  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:31:43.258  1712  4340 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 18:31:43.259  1712  4340 I SystemUpdateService: now status is 0 (complete)
,09-12 18:31:43.259  1712  4340 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 18:31:43.267  1712  4340 I SystemUpdateService: file has been verified
,09-12 18:31:43.267  1712  4340 I SystemUpdateService: OTA package size = 12249756
,09-12 18:31:43.281  1712  4340 I SystemUpdateService: showing system update notification
,09-12 18:31:43.304  1712  1712 D SystemUpdateService: onDestroy
,09-12 18:31:43.310  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 18:31:43.310  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-12 18:31:43.311  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 18:31:43.313  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:31:43.332  1712  4342 E MDM     : [179] SitrepService.a: Error sending sitrep.
,09-12 18:31:43.369  3542  4345 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 18:31:43.412  1901  1954 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-12 18:31:43.413  1901  1954 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-12 18:31:43.425  1513  1513 I ConfigService: onCreate
,09-12 18:31:44.110   872  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-12 18:31:45.460  3881  3932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:31:45.460  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:45.460  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:45.460  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:45.460  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:31:45.460  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:31:45.460  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:31:45.460  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:31:45.467  3881  3932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:31:45.468  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:31:45.468  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e50481f removed from the list
,09-12 18:31:45.469  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:31:45.469  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:31:45.469  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:31:45.481  3881  4352 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-12 18:31:45.482  3881  4352 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 18:31:48.490  3881  4352 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-12 18:31:48.491  3881  4352 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-12 18:31:48.493  3881  4352 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 18:31:48.493  3881  4353 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-12 18:31:48.494  3881  4353 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-12 18:31:48.494  3881  4352 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 18:31:48.494  3881  4353 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 18:31:48.495  3881  4352 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-12 18:31:48.498  3881  4356 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: OutgoingSocketThread/Receiver)
09-12 18:31:48.499  3881  4356 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: OutgoingSocketThread/Receiver)
09-12 18:31:48.499  3881  4356 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-12 18:31:48.499  3881  4356 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-12 18:31:48.500  3881  4357 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 443, name: IncomingSocketThread/Sender)
09-12 18:31:48.501  1513  1513 I ConfigService: onDestroy
09-12 18:31:48.501  3881  4353 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 18:31:48.504  3881  4355 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: OutgoingSocketThread/Sender)
09-12 18:31:48.504  3881  4353 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-12 18:31:48.506  3881  4358 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 444, name: IncomingSocketThread/Receiver)
,09-12 18:31:48.508  3881  4358 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 444, thread name: IncomingSocketThread/Receiver)
09-12 18:31:48.508  3881  4358 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-12 18:31:48.509  3881  4358 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 444, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-12 18:31:51.000   872  1319 D ConnectivityService: handlePromptUnvalidated 102
,09-12 18:31:51.488  3881  3932 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-12 18:31:51.490  3881  3932 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 18:31:51.498  3881  3932 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@654132b Bundle[{}]
,09-12 18:31:51.498  3881  3932 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 18:31:51.498  3881  3932 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-12 18:31:51.499  3881  3932 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-12 18:31:51.499  3881  3932 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 18:31:51.500  3881  3932 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-12 18:31:51.500  3881  3932 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 18:31:51.504  3881  3932 I System.out: Running OutgoingSocketThread
,09-12 18:31:51.508  3881  4360 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-12 18:31:51.508  3881  4360 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 18:31:54.517  3881  4361 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-12 18:31:54.518  3881  4361 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-12 18:31:54.518  3881  4361 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 18:31:54.519  3881  4360 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-12 18:31:54.519  3881  4360 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-12 18:31:54.520  3881  4360 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 18:31:54.520  3881  4361 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 18:31:54.522  3881  4363 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 453, name: IncomingSocketThread/Sender)
,09-12 18:31:54.524  3881  4360 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 18:31:54.525  3881  4361 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-12 18:31:54.528  3881  4360 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-12 18:31:54.531  3881  4365 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 454, name: IncomingSocketThread/Receiver)
,09-12 18:31:54.532  3881  4365 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 454, thread name: IncomingSocketThread/Receiver)
09-12 18:31:54.533  3881  4365 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-12 18:31:54.533  3881  4365 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 454, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-12 18:31:54.533  3881  4364 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 455, name: OutgoingSocketThread/Sender)
09-12 18:31:54.537  3881  4366 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 456, name: OutgoingSocketThread/Receiver)
,09-12 18:31:54.538  3881  4366 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 456, thread name: OutgoingSocketThread/Receiver)
09-12 18:31:54.539  3881  4366 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-12 18:31:54.539  3881  4366 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 456, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-12 18:31:57.520  3881  3932 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 465)
,09-12 18:31:57.523  3881  3932 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-12 18:31:57.523  3881  3932 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 466)
,09-12 18:31:57.529  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 18:31:57.529  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@522576c added. We now have 3 listener(s)
09-12 18:31:57.531  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 18:31:57.531  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 18:31:57.531  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:31:57.531  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:31:57.531  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fca5135 added. We now have 4 listener(s)
09-12 18:31:57.531  3881  3932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:31:57.533  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:31:57.538  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:31:57.549  3881  3932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:31:57.549  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:57.549  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:31:57.549  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:57.549  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:31:57.549  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:31:57.549  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:31:57.549  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:31:57.555  3881  3932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:31:57.555  3881  3932 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:31:57.556  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:31:57.556  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:31:57.556  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:31:57.556  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:31:57.556  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:31:57.556  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:31:57.556  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:31:57.556  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@522576c removed from the list
09-12 18:31:57.556  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:31:57.557  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fca5135 removed from the list
09-12 18:31:57.561  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:57.566  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:57.567  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:31:57.567  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:31:57.567  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:31:57.567  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:31:57.569  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:31:57.569  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:31:57.569  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:31:57.569  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fca5135 not in the list
,09-12 18:31:57.569  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:31:57.569  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:31:57.571  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 18:31:57.571  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:31:57.571  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:31:57.571  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fca5135 not in the list
,09-12 18:31:57.571  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:31:57.571  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:31:57.571  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:31:57.571  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@522576c not in the list
09-12 18:31:57.572  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:31:57.572  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b473b added. We now have 3 listener(s)
,09-12 18:31:57.574  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 18:31:57.574  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:31:57.574  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 18:31:57.574  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:31:57.574  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b937e58 added. We now have 4 listener(s)
09-12 18:31:57.575  3881  3932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:31:57.576  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:31:57.579  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:31:57.587  3881  3932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:31:57.587  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:31:57.587  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
09-12 18:31:57.587  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:31:57.587  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:31:57.587  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:31:57.587  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:31:57.587  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:31:57.591  3881  3932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:31:57.592  3881  3932 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:31:57.593  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:31:57.593  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 18:31:57.594  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:31:57.594  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:31:57.594  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 18:31:57.595  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:57.600  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:31:57.602  3881  3932 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 18:31:57.602  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 18:31:57.607  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:31:57.609  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 18:31:57.609  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:31:57.618  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 18:31:57.618  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 18:31:57.618  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:31:57.620  3881  3932 D BluetoothAdapter: STATE_ON
,09-12 18:31:57.625  4271  4307 D BtGatt.GattService: registerClient() - UUID=92b19e20-4e27-4025-85ac-39dde91fb506
,09-12 18:31:57.627  4271  4287 D BtGatt.GattService: onClientRegistered() - UUID=92b19e20-4e27-4025-85ac-39dde91fb506, clientIf=5
09-12 18:31:57.628  3881  3892 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 18:31:57.630  4271  4300 D BtGatt.GattService: start scan with filters
,09-12 18:31:57.639  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 18:31:57.640  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:31:57.640  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
09-12 18:31:57.640  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 18:31:57.640  4271  4290 D BtGatt.ScanManager: handling starting scan
,09-12 18:31:57.645  4271  4290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4f350f
,09-12 18:31:57.649  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:31:57.650  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 18:31:57.650  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:31:57.656  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:31:57.660  4271  4287 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 18:31:57.660  4271  4287 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:31:57.662  4271  4290 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 18:31:57.666  3881  3932 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 18:31:57.667  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:31:57.667  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 18:31:57.667  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:31:57.668  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 18:31:57.668  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 18:31:57.668  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:31:57.668  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:31:57.668  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:31:57.669  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 18:31:57.669  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 18:31:57.671  3881  3932 D BluetoothAdapter: STATE_ON
09-12 18:31:57.672  4271  4307 D BtGatt.GattService: stopScan() - queue size =1
09-12 18:31:57.674  4271  4300 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 18:31:57.675  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:31:57.675  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 18:31:57.675  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:31:57.675  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 18:31:57.676  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 18:31:57.677  4271  4287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 18:31:57.677  4271  4287 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:31:57.678  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:31:57.679  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 18:31:57.679  4271  4290 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:31:57.679  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:31:57.679  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 18:31:57.679  4271  4290 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 18:31:57.680  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 18:31:57.683  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:31:57.683  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:31:57.683  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:31:57.707  4271  4287 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 18:31:57.707  4271  4287 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:31:57.722  4271  4287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 18:31:57.722  4271  4287 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:31:57.742  4271  4287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 18:31:57.742  4271  4287 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:31:57.743  4271  4290 D BtGatt.ScanManager: stopping BLe Batch
,09-12 18:31:57.760  4271  4287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 18:31:57.761  4271  4287 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:31:57.762  4271  4290 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 18:31:57.782  4271  4287 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 18:31:57.783  4271  4287 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:31:58.185  3881  3881 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 18:31:58.186  3881  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:31:58.186  3881  3881 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 18:32:00.685  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:32:00.685  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:32:00.686  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:32:00.687  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:32:00.687  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:32:00.687  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:32:00.688  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:32:00.688  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b473b removed from the list
,09-12 18:32:00.688  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:32:00.689  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b937e58 removed from the list
09-12 18:32:00.689  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:32:00.689  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:32:00.691  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:32:00.691  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:32:00.695  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:32:00.695  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 18:32:00.695  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:32:00.696  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b937e58 not in the list
09-12 18:32:00.696  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:32:00.696  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:32:00.699  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:32:00.700  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:32:00.700  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:32:00.700  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b937e58 not in the list
09-12 18:32:00.701  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:32:00.701  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:32:00.701  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:32:00.702  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b473b not in the list
09-12 18:32:00.704  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:32:00.704  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b071ed added. We now have 3 listener(s)
,09-12 18:32:00.706  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 18:32:00.706  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:32:00.706  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:32:00.707  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:32:00.707  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24e822 added. We now have 4 listener(s)
09-12 18:32:00.707  3881  3932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:32:00.707  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:32:00.710  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:32:00.716  3881  3932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:32:00.716  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:32:00.716  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:32:00.716  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:32:00.716  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:32:00.716  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:32:00.716  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:32:00.716  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:32:00.718  3881  3932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:32:00.719  3881  3932 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:32:00.719  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 18:32:00.720  3881  3932 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-12 18:32:00.720  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-12 18:32:00.722  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 18:32:00.722  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-12 18:32:00.723  3881  3932 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 18:32:00.723  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:32:00.725  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 18:32:00.725  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:32:00.727  3881  3932 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-12 18:32:00.727  3881  3932 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 18:32:00.727  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-12 18:32:00.728  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 18:32:00.728  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:32:00.728  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:32:00.729  3881  3881 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 18:32:00.728  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 18:32:00.730  3881  4367 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:32:00.733  3881  3932 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 18:32:00.733  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 18:32:00.734  3881  4367 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-12 18:32:00.737  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:32:00.738  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 18:32:00.738  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:32:00.740  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-12 18:32:00.741  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 18:32:00.741  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-12 18:32:00.742  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 18:32:00.742  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 18:32:00.743  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-12 18:32:00.743  3881  3932 D BluetoothAdapter: STATE_ON
09-12 18:32:00.746  4271  4311 D BtGatt.GattService: registerClient() - UUID=64da7f25-ea94-43cc-8cca-6b6104e3779c
,09-12 18:32:00.747  4271  4287 D BtGatt.GattService: onClientRegistered() - UUID=64da7f25-ea94-43cc-8cca-6b6104e3779c, clientIf=5
09-12 18:32:00.748  3881  3928 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-12 18:32:00.750  4271  4289 D BtGatt.AdvertiseManager: message : 0
,09-12 18:32:00.753  4271  4289 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 18:32:00.763  4271  4287 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-12 18:32:00.771  4271  4287 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-12 18:32:00.773  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-12 18:32:00.773  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 18:32:00.775  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:32:00.777  3881  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 18:32:00.777  3881  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-12 18:32:00.777  3881  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-12 18:32:00.777  3881  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-12 18:32:00.777  3881  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-12 18:32:00.778  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-12 18:32:00.780  3881  3881 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 18:32:00.780  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-12 18:32:00.782  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 18:32:00.782  3881  3932 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 18:32:01.281  3881  3881 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-12 18:32:03.783  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:32:03.784  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-12 18:32:03.784  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 18:32:03.785  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-12 18:32:03.785  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 18:32:03.785  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 18:32:03.786  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 18:32:03.786  3881  4367 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-12 18:32:03.787  3881  3932 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-12 18:32:03.787  3881  4367 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 18:32:03.787  3881  4367 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 18:32:03.788  3881  3881 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 18:32:03.788  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 18:32:03.788  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 18:32:03.789  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:32:03.789  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 18:32:03.789  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 18:32:03.791  3881  3932 D BluetoothAdapter: STATE_ON
09-12 18:32:03.792  3881  3932 D BluetoothLeScanner: could not find callback wrapper
09-12 18:32:03.792  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:32:03.793  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-12 18:32:03.795  4271  4289 D BtGatt.AdvertiseManager: message : 1
09-12 18:32:03.799  4271  4289 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-12 18:32:03.807  4271  4287 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-12 18:32:03.807  4271  4287 D BtGatt.GattService: Client app is not null!
09-12 18:32:03.808  4271  4311 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 18:32:03.809  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 18:32:03.809  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-12 18:32:03.809  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-12 18:32:03.810  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-12 18:32:03.810  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-12 18:32:03.812  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
09-12 18:32:03.812  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:32:03.813  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 18:32:03.814  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 18:32:03.816  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:32:03.816  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:32:03.816  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:32:03.816  3881  3881 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 18:32:03.816  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 18:32:03.816  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b071ed removed from the list
09-12 18:32:03.817  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:32:03.817  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24e822 removed from the list
09-12 18:32:03.818  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:32:03.817  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:32:03.819  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:32:03.819  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:32:03.819  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
09-12 18:32:03.820  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:32:03.820  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:32:03.822  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:32:03.822  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 18:32:03.822  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:32:03.822  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24e822 not in the list
09-12 18:32:03.823  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:32:03.823  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,09-12 18:32:03.824  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:32:03.824  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:32:03.824  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:32:03.824  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24e822 not in the list
09-12 18:32:03.824  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:32:03.824  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:32:03.824  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-12 18:32:03.825  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b071ed not in the list,
09-12 18:32:03.826  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:32:03.826  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b21770f added. We now have 3 listener(s)
09-12 18:32:03.828  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 18:32:03.828  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:32:03.828  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:32:03.828  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:32:03.828  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@420739c added. We now have 4 listener(s)
,09-12 18:32:03.828  3881  3932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:32:03.829  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 18:32:03.833  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:32:03.841  3881  3932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-12 18:32:03.841  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:32:03.841  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:32:03.841  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:32:03.841  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:32:03.841  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:32:03.841  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:32:03.841  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:32:03.845  3881  3932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:32:03.845  3881  3932 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:32:03.846  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 18:32:03.846  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:32:03.846  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:32:03.847  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:32:03.847  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 18:32:03.850  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:32:03.853  3881  3932 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 18:32:03.853  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 18:32:03.854  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:32:03.859  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:32:03.860  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 18:32:03.860  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:32:03.866  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 18:32:03.866  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 18:32:03.866  3881  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:32:03.867  3881  3932 D BluetoothAdapter: STATE_ON
,09-12 18:32:03.871  4271  4282 D BtGatt.GattService: registerClient() - UUID=35076990-a577-44f9-98ed-d6eb8f8978f5
,09-12 18:32:03.871  4271  4287 D BtGatt.GattService: onClientRegistered() - UUID=35076990-a577-44f9-98ed-d6eb8f8978f5, clientIf=5
,09-12 18:32:03.872  3881  3928 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 18:32:03.873  4271  4311 D BtGatt.GattService: start scan with filters
,09-12 18:32:03.879  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 18:32:03.879  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:32:03.880  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 18:32:03.880  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 18:32:03.880  4271  4290 D BtGatt.ScanManager: handling starting scan
,09-12 18:32:03.888  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:32:03.888  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:32:03.889  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 18:32:03.894  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:32:03.895  4271  4287 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
09-12 18:32:03.895  4271  4287 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:32:03.895  4271  4290 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 18:32:03.911  4271  4287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 18:32:03.912  4271  4287 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:32:03.912  4271  4290 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:32:03.912  4271  4290 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 18:32:03.945  4271  4287 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 18:32:03.946  4271  4287 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:32:03.963  4271  4287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 18:32:03.964  4271  4287 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 18:32:04.321  3881  3881 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 18:32:04.389  3881  3881 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 18:32:04.389  3881  3881 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:32:04.390  3881  3881 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 18:32:05.469  4271  4271 D BtGatt.ScanManager: awakened up at time 232086
,09-12 18:32:05.472  4271  4290 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 18:32:05.533  4271  4287 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,09-12 18:32:05.534  4271  4287 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:32:05.534  4271  4287 D BtGatt.GattService: current time is 232151703656
09-12 18:32:05.535  4271  4287 D BtGatt.GattService: Batch record : [87, 45, 110, 28, -13, -4, 1, -128, -71, 26, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85, 0, 29, -100, -80, -20, -115, 99, 1, -128, -53, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 81, 34, 97, 112, -14, -5, 1, -128, -83, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -86, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -95, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -91, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -86, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -97, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-12 18:32:05.537  4271  4287 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85]
09-12 18:32:05.538  4271  4287 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
,09-12 18:32:05.538  4271  4287 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 18:32:05.538  4271  4287 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 18:32:05.540  4271  4287 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 18:32:05.540  4271  4287 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-12 18:32:05.540  4271  4287 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 18:32:05.540  4271  4287 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-12 18:32:05.544  3881  3881 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 1
09-12 18:32:05.545  3881  3881 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 1], added - the peer count is 2
,09-12 18:32:05.545  3881  3881 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
09-12 18:32:05.546  3881  3881 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
,09-12 18:32:06.908  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:32:06.909  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 18:32:06.909  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 18:32:06.909  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:32:06.910  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 18:32:06.910  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:32:06.910  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:32:06.911  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:32:06.912  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:32:06.912  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 18:32:06.912  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 18:32:06.916  3881  3932 D BluetoothAdapter: STATE_ON
,09-12 18:32:06.919  4271  4282 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:32:06.922  4271  4311 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 18:32:06.923  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 18:32:06.923  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 18:32:06.924  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 18:32:06.924  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 18:32:06.924  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 18:32:06.927  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:32:06.927  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 18:32:06.928  3881  3932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:32:06.928  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 18:32:06.930  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:32:06.931  3881  3932 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-12 18:32:06.931  4271  4271 D BtGatt.ScanManager: awakened up at time 233548
,09-12 18:32:06.933  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:32:06.933  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:32:06.934  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:32:06.934  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:32:06.934  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:32:06.934  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:32:06.934  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:32:06.934  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b21770f removed from the list
09-12 18:32:06.935  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:32:06.935  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@420739c removed from the list
,09-12 18:32:06.935  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:32:06.935  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:32:06.939  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:32:06.939  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:32:06.941  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:32:06.941  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:32:06.941  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:32:06.941  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@420739c not in the list
09-12 18:32:06.941  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:32:06.941  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:32:06.942  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:32:06.943  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:32:06.943  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:32:06.943  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@420739c not in the list
09-12 18:32:06.943  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:32:06.943  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:32:06.943  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:32:06.943  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b21770f not in the list
09-12 18:32:06.944  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:32:06.944  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c173907 added. We now have 3 listener(s)
09-12 18:32:06.945  4271  4287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 18:32:06.945  4271  4287 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:32:06.946  4271  4290 D BtGatt.ScanManager: stopping BLe Batch
09-12 18:32:06.946  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 18:32:06.946  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:32:06.946  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:32:06.946  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:32:06.947  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bad9a34 added. We now have 4 listener(s)
,09-12 18:32:06.947  3881  3932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:32:06.947  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:32:06.950  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:32:06.955  3881  3932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:32:06.955  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:32:06.955  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:32:06.955  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:32:06.955  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:32:06.955  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:32:06.955  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:32:06.955  3881  3932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:32:06.957  3881  3932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:32:06.957  3881  3932 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:32:06.959  3881  3932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:32:06.959  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:32:06.959  3881  3932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:32:06.959  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:32:06.959  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:32:06.960  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 18:32:06.960  3881  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:32:06.960  3881  3932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c173907 removed from the list
09-12 18:32:06.960  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:32:06.960  3881  3932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bad9a34 removed from the list
,09-12 18:32:06.961  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:32:06.963  4271  4287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 18:32:06.963  4271  4287 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:32:06.963  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:32:06.963  4271  4290 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 18:32:06.963  3881  3932 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:32:06.963  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:32:06.964  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:32:06.964  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:32:06.965  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:32:06.965  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 18:32:06.965  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:32:06.965  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bad9a34 not in the list
09-12 18:32:06.965  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:32:06.965  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:32:06.966  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:32:06.967  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:32:06.967  3881  3932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:32:06.967  3881  3932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bad9a34 not in the list
09-12 18:32:06.967  3881  3932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:32:06.967  3881  3932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:32:06.967  3881  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:32:06.967  3881  3932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c173907 not in the list
09-12 18:32:06.968  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 18:32:06.968  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-12 18:32:06.968  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 18:32:06.969  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:32:06.969  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 18:32:06.969  3881  3932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:32:06.975  4271  4287 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
09-12 18:32:06.975  4271  4287 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 18:32:06.975  4271  4287 D BtGatt.GattService: current time is 233593136235
,09-12 18:32:06.975  4271  4287 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -91, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-12 18:32:06.976  4271  4287 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 18:32:07.435  3881  3881 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 18:32:08.984  3881  4369 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 475, name: My test thread name)
,09-12 18:32:10.982  3881  3932 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 475
,09-12 18:32:10.983  3881  3932 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 475, name: My test thread name)
,09-12 18:32:10.989  3881  4370 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 476, name: My test thread name)
,09-12 18:32:10.989  3881  4370 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 476, thread name: My test thread name)
09-12 18:32:10.990  3881  4370 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 476, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-12 18:32:10.994  3881  3932 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 18:32:11.003  3881  4371 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 480, name: My test thread name)
,09-12 18:32:11.004  3881  4371 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 480, thread name: My test thread name): Test exception.
09-12 18:32:11.005  3881  4371 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 480, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-12 18:32:11.012  3881  3932 I jxcore-log: Total number of executed tests:  82
09-12 18:32:11.012  3881  3932 I jxcore-log: 
,09-12 18:32:11.013  3881  3932 I jxcore-log: Number of passed tests:  82
09-12 18:32:11.013  3881  3932 I jxcore-log: 
09-12 18:32:11.014  3881  3932 I jxcore-log: Number of failed tests:  0
09-12 18:32:11.014  3881  3932 I jxcore-log: 
,09-12 18:32:11.015  3881  3932 I jxcore-log: Number of ignored tests:  0
09-12 18:32:11.015  3881  3932 I jxcore-log: 
09-12 18:32:11.015  3881  3932 I jxcore-log: Total duration:  101331
09-12 18:32:11.015  3881  3932 I jxcore-log: 
,09-12 18:32:11.025  3881  3932 I jxcore-log: Unit Test app is loaded
09-12 18:32:11.025  3881  3932 I jxcore-log: 
,09-12 18:32:11.044  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.044  3881  3932 I jxcore-log: 
,09-12 18:32:11.050  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.050  3881  3932 I jxcore-log: 
,09-12 18:32:11.051  3881  3881 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-12 18:32:11.052  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.052  3881  3932 I jxcore-log: 
,09-12 18:32:11.053  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.053  3881  3932 I jxcore-log: 
,09-12 18:32:11.054  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 18:32:11.054  3881  3932 I jxcore-log: 
,09-12 18:32:11.056  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:32:11.056  3881  3932 I jxcore-log: 
,09-12 18:32:11.059  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.059  3881  3932 I jxcore-log: 
,09-12 18:32:11.061  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.061  3881  3932 I jxcore-log: 
,09-12 18:32:11.062  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 18:32:11.062  3881  3932 I jxcore-log: 
09-12 18:32:11.063  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:32:11.063  3881  3932 I jxcore-log: 
,09-12 18:32:11.064  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:32:11.064  3881  3932 I jxcore-log: 
09-12 18:32:11.065  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.065  3881  3932 I jxcore-log: 
,09-12 18:32:11.066  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.066  3881  3932 I jxcore-log: 
09-12 18:32:11.067  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.067  3881  3932 I jxcore-log: 
,09-12 18:32:11.067  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 18:32:11.067  3881  3932 I jxcore-log: 
09-12 18:32:11.069  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 18:32:11.069  3881  3932 I jxcore-log: 
,09-12 18:32:11.070  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 18:32:11.070  3881  3932 I jxcore-log: 
,09-12 18:32:11.070  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:32:11.070  3881  3932 I jxcore-log: 
09-12 18:32:11.071  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:32:11.071  3881  3932 I jxcore-log: 
09-12 18:32:11.072  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:32:11.072  3881  3932 I jxcore-log: 
09-12 18:32:11.073  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 18:32:11.073  3881  3932 I jxcore-log: 
09-12 18:32:11.074  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 18:32:11.074  3881  3932 I jxcore-log: 
,09-12 18:32:11.074  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 18:32:11.074  3881  3932 I jxcore-log: 
09-12 18:32:11.075  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.075  3881  3932 I jxcore-log: 
,09-12 18:32:11.076  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.076  3881  3932 I jxcore-log: 
09-12 18:32:11.077  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.077  3881  3932 I jxcore-log: 
09-12 18:32:11.078  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:32:11.078  3881  3932 I jxcore-log: 
,09-12 18:32:11.078  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:32:11.078  3881  3932 I jxcore-log: 
09-12 18:32:11.080  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:32:11.080  3881  3932 I jxcore-log: 
,09-12 18:32:11.081  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:32:11.081  3881  3932 I jxcore-log: 
09-12 18:32:11.081  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:32:11.081  3881  3932 I jxcore-log: 
09-12 18:32:11.082  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:32:11.082  3881  3932 I jxcore-log: 
,09-12 18:32:11.082  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:32:11.082  3881  3932 I jxcore-log: 
09-12 18:32:11.083  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:32:11.083  3881  3932 I jxcore-log: 
09-12 18:32:11.083  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:32:11.083  3881  3932 I jxcore-log: 
,09-12 18:32:11.084  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:32:11.084  3881  3932 I jxcore-log: 
09-12 18:32:11.084  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:32:11.084  3881  3932 I jxcore-log: 
09-12 18:32:11.085  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:32:11.085  3881  3932 I jxcore-log: 
,09-12 18:32:11.085  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 18:32:11.085  3881  3932 I jxcore-log: 
09-12 18:32:11.086  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 18:32:11.086  3881  3932 I jxcore-log: 
09-12 18:32:11.086  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.086  3881  3932 I jxcore-log: 
09-12 18:32:11.087  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.087  3881  3932 I jxcore-log: 
,09-12 18:32:11.087  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.087  3881  3932 I jxcore-log: 
09-12 18:32:11.088  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.088  3881  3932 I jxcore-log: 
09-12 18:32:11.089  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.089  3881  3932 I jxcore-log: 
,09-12 18:32:11.089  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:32:11.089  3881  3932 I jxcore-log: 
09-12 18:32:11.090  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.090  3881  3932 I jxcore-log: 
09-12 18:32:11.090  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-12 18:32:11.090  3881  3932 I jxcore-log: 
09-12 18:32:11.091  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.091  3881  3932 I jxcore-log: 
,09-12 18:32:11.091  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:32:11.091  3881  3932 I jxcore-log: 
09-12 18:32:11.092  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 18:32:11.092  3881  3932 I jxcore-log: 
09-12 18:32:11.093  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-12 18:32:11.093  3881  3932 I jxcore-log: 
,09-12 18:32:11.093  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-12 18:32:11.093  3881  3932 I jxcore-log: 
09-12 18:32:11.094  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:32:11.094  3881  3932 I jxcore-log: 
09-12 18:32:11.094  3881  3932 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:32:11.094  3881  3932 I jxcore-log: 
,09-12 18:32:11.099  3881  3932 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-12 18:32:11.099  3881  3932 I jxcore-log:   bluetooth: 'on',
09-12 18:32:11.099  3881  3932 I jxcore-log:   wifi: 'on',
09-12 18:32:11.099  3881  3932 I jxcore-log:   cellular: 'doNotCare',
09-12 18:32:11.099  3881  3932 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-12 18:32:11.099  3881  3932 I jxcore-log: 
,09-12 18:32:11.103  3881  4369 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 475, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-12 18:32:11.120  3881  3932 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-12 18:32:11.120  3881  3932 I jxcore-log:   bluetooth: 'on',
09-12 18:32:11.120  3881  3932 I jxcore-log:   wifi: 'on',
09-12 18:32:11.120  3881  3932 I jxcore-log:   cellular: 'doNotCare',
09-12 18:32:11.120  3881  3932 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-12 18:32:11.120  3881  3932 I jxcore-log: 
,09-12 18:32:11.122  3881  3932 I jxcore-log: My device name is: motorola-Nexus 6
09-12 18:32:11.122  3881  3932 I jxcore-log: 
09-12 18:32:11.122  3881  3932 I jxcore-log: Running for WIFI network type
09-12 18:32:11.122  3881  3932 I jxcore-log: 
,09-12 18:32:12.760   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=239377, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:32:13.664  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-12 18:32:13.664  3881  3932 I jxcore-log: 
,09-12 18:32:14.128  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-12 18:32:14.128  3881  3932 I jxcore-log: 
,09-12 18:32:14.162  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-12 18:32:14.162  3881  3932 I jxcore-log: 
,09-12 18:32:15.568  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-12 18:32:15.568  3881  3932 I jxcore-log: 
,09-12 18:32:15.809  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-12 18:32:15.809  3881  3932 I jxcore-log: 
,09-12 18:32:15.815  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-12 18:32:15.815  3881  3932 I jxcore-log: 
,09-12 18:32:15.822  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-12 18:32:15.822  3881  3932 I jxcore-log: 
,09-12 18:32:15.901  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-12 18:32:15.901  3881  3932 I jxcore-log: 
,09-12 18:32:15.922  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-12 18:32:15.922  3881  3932 I jxcore-log: 
,09-12 18:32:15.927  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-12 18:32:15.927  3881  3932 I jxcore-log: 
,09-12 18:32:16.883  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-12 18:32:16.883  3881  3932 I jxcore-log: 
,09-12 18:32:17.056  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-12 18:32:17.056  3881  3932 I jxcore-log: 
,09-12 18:32:17.398  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-12 18:32:17.398  3881  3932 I jxcore-log: 
,09-12 18:32:17.409  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-12 18:32:17.409  3881  3932 I jxcore-log: 
,09-12 18:32:17.417  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-12 18:32:17.417  3881  3932 I jxcore-log: 
,09-12 18:32:17.425  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-12 18:32:17.425  3881  3932 I jxcore-log: 
,09-12 18:32:17.466  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-12 18:32:17.466  3881  3932 I jxcore-log: 
,09-12 18:32:17.516  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-12 18:32:17.516  3881  3932 I jxcore-log: 
,09-12 18:32:17.524  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-12 18:32:17.524  3881  3932 I jxcore-log: 
,09-12 18:32:17.532  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-12 18:32:17.532  3881  3932 I jxcore-log: 
,09-12 18:32:17.553  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-12 18:32:17.553  3881  3932 I jxcore-log: 
,09-12 18:32:17.559  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-12 18:32:17.559  3881  3932 I jxcore-log: 
,09-12 18:32:17.565  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-12 18:32:17.565  3881  3932 I jxcore-log: 
,09-12 18:32:17.583  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-12 18:32:17.583  3881  3932 I jxcore-log: 
,09-12 18:32:17.610  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-12 18:32:17.610  3881  3932 I jxcore-log: 
,09-12 18:32:17.622  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-12 18:32:17.622  3881  3932 I jxcore-log: 
,09-12 18:32:17.636  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-12 18:32:17.636  3881  3932 I jxcore-log: 
,09-12 18:32:17.648  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-12 18:32:17.648  3881  3932 I jxcore-log: 
,09-12 18:32:17.666  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-12 18:32:17.666  3881  3932 I jxcore-log: 
,09-12 18:32:17.678  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-12 18:32:17.678  3881  3932 I jxcore-log: 
,09-12 18:32:17.684  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-12 18:32:17.684  3881  3932 I jxcore-log: 
,09-12 18:32:17.715  3881  3932 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-12 18:32:17.715  3881  3932 I jxcore-log: 
,09-12 18:32:17.727  3881  3932 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-12 18:32:17.729  3881  3932 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-12 18:32:17.729  3881  3932 I jxcore-log: 
,09-12 18:32:17.732  3881  3932 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-12 18:32:17.732  3881  3932 I jxcore-log: 
,09-12 18:32:17.732  3881  3932 I jxcore-log: ThaliTape :: Started ThaliTape
09-12 18:32:17.732  3881  3932 I jxcore-log: 
,09-12 18:32:17.738  3881  3932 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-12 18:32:17.738  3881  3932 I jxcore-log: 
,09-12 18:32:17.804  3881  3932 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 18:32:17.804  3881  3932 I jxcore-log: 
,09-12 18:32:17.805  3881  3932 I jxcore-log: websocket error
09-12 18:32:17.805  3881  3932 I jxcore-log: 
09-12 18:32:17.805  3881  3932 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 18:32:17.805  3881  3932 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 18:32:17.805  3881  3932 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 18:32:17.805  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:17.805  3881  3932 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 18:32:17.805  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:17.805  3881  3932 I jxcore-log: 
,09-12 18:32:18.959  3881  3932 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 18:32:18.959  3881  3932 I jxcore-log: 
,09-12 18:32:18.961  3881  3932 I jxcore-log: websocket error
09-12 18:32:18.961  3881  3932 I jxcore-log: 
09-12 18:32:18.961  3881  3932 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 18:32:18.961  3881  3932 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5,
09-12 18:32:18.961  3881  3932 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 18:32:18.961  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:18.961  3881  3932 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 18:32:18.961  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:18.961  3881  3932 I jxcore-log: 
,09-12 18:32:21.540  3881  3932 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 18:32:21.540  3881  3932 I jxcore-log: 
,09-12 18:32:21.542  3881  3932 I jxcore-log: websocket error
09-12 18:32:21.542  3881  3932 I jxcore-log: 
,09-12 18:32:21.542  3881  3932 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 18:32:21.542  3881  3932 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 18:32:21.542  3881  3932 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 18:32:21.542  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:21.542  3881  3932 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 18:32:21.542  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:21.542  3881  3932 I jxcore-log: 
,09-12 18:32:22.264  1513  2177 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 18:32:22.793   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=249410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 18:32:23.871  3881  3932 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 18:32:23.871  3881  3932 I jxcore-log: 
,09-12 18:32:23.871  3881  3932 I jxcore-log: websocket error
09-12 18:32:23.871  3881  3932 I jxcore-log: 
09-12 18:32:23.871  3881  3932 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 18:32:23.871  3881  3932 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 18:32:23.871  3881  3932 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 18:32:23.871  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:23.871  3881  3932 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 18:32:23.871  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:23.871  3881  3932 I jxcore-log: 
,09-12 18:32:28.021  3037  4373 V KeepSync: Connecting to GoogleApiClient
,09-12 18:32:28.022   872  2005 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 18:32:28.082  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:32:28.086  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:32:28.131  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 18:32:28.131  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 18:32:28.131  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 18:32:28.131  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:32:28.165  1712  4374 V BaseAuthAsyncOperation: access token request failed
,09-12 18:32:28.168  3037  4373 V KeepSync: GoogleApiClient failed to connect with error code: 4,
,09-12 18:32:28.245  1513  1952 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-12 18:32:28.246  1513  1952 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 18:32:28.246  1513  1952 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:32:28.246  1513  1952 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:32:28.276  3037  4373 E KeepSync: IOException
09-12 18:32:28.276  3037  4373 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 18:32:28.276  3037  4373 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 18:32:28.276  3037  4373 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 18:32:28.276  3037  4373 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 18:32:28.276  3037  4373 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 18:32:28.276  3037  4373 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 18:32:28.276  3037  4373 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 18:32:28.276  3037  4373 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 18:32:28.276  3037  4373 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 18:32:28.276  3037  4373 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 18:32:28.276  3037  4373 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 18:32:28.276  3037  4373 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 18:32:28.276  3037  4373 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 18:32:28.276  3037  4373 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 18:32:28.276  3037  4373 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 18:32:28.276  3037  4373 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 18:32:28.276  3037  4373 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 18:32:28.276  3037  4373 E KeepSync: 	... 10 more
09-12 18:32:28.277  3037  4373 W KeepSync: Sync result 2
,09-12 18:32:28.290   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 254491, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:32:28.934  3881  3932 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 18:32:28.934  3881  3932 I jxcore-log: 
,09-12 18:32:28.934  3881  3932 I jxcore-log: websocket error
09-12 18:32:28.934  3881  3932 I jxcore-log: 
09-12 18:32:28.935  3881  3932 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 18:32:28.935  3881  3932 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 18:32:28.935  3881  3932 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 18:32:28.935  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:28.935  3881  3932 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 18:32:28.935  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:28.935  3881  3932 I jxcore-log: 
,09-12 18:32:34.009  3881  3932 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 18:32:34.009  3881  3932 I jxcore-log: 
,09-12 18:32:34.010  3881  3932 I jxcore-log: websocket error
09-12 18:32:34.010  3881  3932 I jxcore-log: 
09-12 18:32:34.010  3881  3932 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 18:32:34.010  3881  3932 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 18:32:34.010  3881  3932 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 18:32:34.010  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:34.010  3881  3932 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 18:32:34.010  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:34.010  3881  3932 I jxcore-log: 
,09-12 18:32:39.077  3881  3932 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 18:32:39.077  3881  3932 I jxcore-log: 
,09-12 18:32:39.077  3881  3932 I jxcore-log: websocket error
09-12 18:32:39.077  3881  3932 I jxcore-log: 
09-12 18:32:39.078  3881  3932 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 18:32:39.078  3881  3932 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 18:32:39.078  3881  3932 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 18:32:39.078  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:39.078  3881  3932 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 18:32:39.078  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:39.078  3881  3932 I jxcore-log: 
,09-12 18:32:44.134  3881  3932 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 18:32:44.134  3881  3932 I jxcore-log: 
09-12 18:32:44.134  3881  3932 I jxcore-log: websocket error
09-12 18:32:44.134  3881  3932 I jxcore-log: 
,09-12 18:32:44.134  3881  3932 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 18:32:44.134  3881  3932 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 18:32:44.134  3881  3932 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 18:32:44.134  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:44.134  3881  3932 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 18:32:44.134  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:44.134  3881  3932 I jxcore-log: 
,09-12 18:32:49.198  3881  3932 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 18:32:49.198  3881  3932 I jxcore-log: 
,09-12 18:32:49.199  3881  3932 I jxcore-log: websocket error
09-12 18:32:49.199  3881  3932 I jxcore-log: 
09-12 18:32:49.199  3881  3932 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 18:32:49.199  3881  3932 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 18:32:49.199  3881  3932 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 18:32:49.199  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:49.199  3881  3932 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 18:32:49.199  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:49.199  3881  3932 I jxcore-log: 
,09-12 18:32:52.047   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=278664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:32:54.269  3881  3932 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 18:32:54.269  3881  3932 I jxcore-log: 
,09-12 18:32:54.269  3881  3932 I jxcore-log: websocket error
09-12 18:32:54.269  3881  3932 I jxcore-log: 
,09-12 18:32:54.270  3881  3932 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 18:32:54.270  3881  3932 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 18:32:54.270  3881  3932 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 18:32:54.270  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:54.270  3881  3932 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 18:32:54.270  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:54.270  3881  3932 I jxcore-log: 
,09-12 18:32:59.247   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=285864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 18:32:59.357  3881  3932 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 18:32:59.357  3881  3932 I jxcore-log: 
09-12 18:32:59.357  3881  3932 I jxcore-log: websocket error
09-12 18:32:59.357  3881  3932 I jxcore-log: 
,09-12 18:32:59.358  3881  3932 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 18:32:59.358  3881  3932 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 18:32:59.358  3881  3932 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 18:32:59.358  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:59.358  3881  3932 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 18:32:59.358  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:32:59.358  3881  3932 I jxcore-log: 
,09-12 18:32:59.547  3689  4376 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 18:32:59.567  3689  4377 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 18:32:59.581  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:32:59.585  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:32:59.626  1513  3942 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 18:32:59.626  1513  3942 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 18:32:59.626  1513  3942 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:32:59.626  1513  3942 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:32:59.651  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:32:59.653  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:32:59.675  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 18:32:59.675  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 18:32:59.675  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:32:59.675  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:32:59.689  3689  4377 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 18:32:59.690  3689  4376 E BooksSync: Soft error
09-12 18:32:59.690  3689  4376 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 18:32:59.690  3689  4376 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 18:32:59.690  3689  4376 E BooksSync: Sync error
09-12 18:32:59.690  3689  4376 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 18:32:59.690  3689  4376 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 18:32:59.690  3689  4376 I BooksSync: Finished books sync
,09-12 18:32:59.697   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 286083, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:33:04.414  3881  3932 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 18:33:04.414  3881  3932 I jxcore-log: 
,09-12 18:33:04.414  3881  3932 I jxcore-log: websocket error
09-12 18:33:04.414  3881  3932 I jxcore-log: 
09-12 18:33:04.414  3881  3932 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 18:33:04.414  3881  3932 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 18:33:04.414  3881  3932 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 18:33:04.414  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:33:04.414  3881  3932 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 18:33:04.414  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:33:04.414  3881  3932 I jxcore-log: 
,09-12 18:33:09.472  3881  3932 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 18:33:09.472  3881  3932 I jxcore-log: 
,09-12 18:33:09.473  3881  3932 I jxcore-log: websocket error
09-12 18:33:09.473  3881  3932 I jxcore-log: 
09-12 18:33:09.474  3881  3932 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 18:33:09.474  3881  3932 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 18:33:09.474  3881  3932 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 18:33:09.474  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:33:09.474  3881  3932 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 18:33:09.474  3881  3932 I jxcore-log: emit@events.js:82:1
09-12 18:33:09.474  3881  3932 I jxcore-log: 
,09-12 18:33:14.604  3881  3932 I jxcore-log: ThaliTape :: Reconnected to the test server
09-12 18:33:14.604  3881  3932 I jxcore-log: 
,09-12 18:33:14.620  3881  3932 I jxcore-log: ThaliTape :: Connected to the test server
09-12 18:33:14.620  3881  3932 I jxcore-log: 
,09-12 18:33:30.186  3037  4391 V KeepSync: Connecting to GoogleApiClient
,09-12 18:33:30.187   872  2019 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 18:33:30.215  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:33:30.217  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:33:30.307  1513  3942 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 18:33:30.307  1513  3942 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 18:33:30.307  1513  3942 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:33:30.307  1513  3942 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:33:30.349  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-12 18:33:30.350  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-12 18:33:30.350  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:33:30.350  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:33:30.368  3645  4393 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 18:33:30.368  3645  4393 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 18:33:30.368  3645  4393 E HttpOperation: 	at jdm.a(PG:82)
09-12 18:33:30.368  3645  4393 E HttpOperation: 	at jcs.o(PG:406)
09-12 18:33:30.368  3645  4393 E HttpOperation: 	at jcn.a(PG:1379)
09-12 18:33:30.368  3645  4393 E HttpOperation: 	at jcs.i(PG:143)
09-12 18:33:30.368  3645  4393 E HttpOperation: 	at blb.a(PG:3937)
09-12 18:33:30.368  3645  4393 E HttpOperation: 	at czp.a(PG:18188)
,09-12 18:33:30.368  3645  4393 E HttpOperation: 	at czp.a(PG:9081)
09-12 18:33:30.368  3645  4393 E HttpOperation: 	at czq.run(PG:1686)
09-12 18:33:30.368  3645  4393 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:33:30.368  3645  4393 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:33:30.368  3645  4393 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:33:30.368  3645  4393 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:33:30.368  3645  4393 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:33:30.368  3645  4393 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:33:30.368  3645  4393 E HttpOperation: 	at jdj.a(PG:4091)
09-12 18:33:30.368  3645  4393 E HttpOperation: 	at jdj.a(PG:1125)
09-12 18:33:30.368  3645  4393 E HttpOperation: 	at jdm.a(PG:77)
09-12 18:33:30.368  3645  4393 E HttpOperation: 	... 12 more
09-12 18:33:30.368  3645  4393 E HttpOperation: Caused by: faj: BadAuthentication
09-12 18:33:30.368  3645  4393 E HttpOperation: 	at fal.a(PG:38)
09-12 18:33:30.368  3645  4393 E HttpOperation: 	at jdj.a(PG:4089)
09-12 18:33:30.368  3645  4393 E HttpOperation: 	... 14 more
,09-12 18:33:30.423  1712  4394 V BaseAuthAsyncOperation: access token request failed
,09-12 18:33:30.424  3037  4391 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 18:33:30.473  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 18:33:30.473  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 18:33:30.473  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:33:30.473  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:33:30.522  3645  4393 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 18:33:30.522  3645  4393 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at jdm.a(PG:82)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at jcs.o(PG:406)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at jcn.a(PG:1379)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at jcs.i(PG:143)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at hec.a(PG:42)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at hee.a(PG:102)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at czr.a(PG:65)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at kka.a(PG:108)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at czp.a(PG:19176)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at czp.a(PG:9081)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at czq.run(PG:1686)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:33:30.522  3645  4393 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at jdj.a(PG:4091)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at jdj.a(PG:1125)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at jdm.a(PG:77)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	... 15 more
09-12 18:33:30.522  3645  4393 E HttpOperation: Caused by: faj: BadAuthentication
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at fal.a(PG:38)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	at jdj.a(PG:4089)
09-12 18:33:30.522  3645  4393 E HttpOperation: 	... 17 more
,09-12 18:33:30.523  3645  4393 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 18:33:30.523  3645  4393 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at hec.a(PG:42)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at hee.a(PG:102)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at czr.a(PG:65)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at kka.a(PG:108)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	... 15 more
09-12 18:33:30.523  3645  4393 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at fal.a(PG:38)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 18:33:30.523  3645  4393 E ExperimentLoader: 	... 17 more
,09-12 18:33:30.619  1513  2976 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-12 18:33:30.619  1513  2976 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 18:33:30.619  1513  2976 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:33:30.619  1513  2976 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:33:30.641  3037  4391 E KeepSync: IOException
09-12 18:33:30.641  3037  4391 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 18:33:30.641  3037  4391 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 18:33:30.641  3037  4391 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 18:33:30.641  3037  4391 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 18:33:30.641  3037  4391 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 18:33:30.641  3037  4391 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 18:33:30.641  3037  4391 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 18:33:30.641  3037  4391 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 18:33:30.641  3037  4391 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 18:33:30.641  3037  4391 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 18:33:30.641  3037  4391 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 18:33:30.641  3037  4391 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 18:33:30.641  3037  4391 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 18:33:30.641  3037  4391 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 18:33:30.641  3037  4391 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 18:33:30.641  3037  4391 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 18:33:30.641  3037  4391 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 18:33:30.641  3037  4391 E KeepSync: 	... 10 more
09-12 18:33:30.641  3037  4391 W KeepSync: Sync result 2
,09-12 18:33:30.644   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 288901, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:33:30.666   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 286841, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:33:55.330  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:33:55.340  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:33:55.344  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:33:55.396  1513  1952 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 18:33:55.396  1513  1952 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-12 18:33:55.397  1513  1952 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:33:55.397  1513  1952 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:33:55.443  1513  1952 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 18:33:55.443  1513  1952 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 18:33:55.443  1513  1952 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 18:33:55.443  1513  1952 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-12 18:33:55.443  1513  1952 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-12 18:33:55.443  1513  1952 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-12 18:33:55.443  1513  1952 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 18:33:55.468  3604  3635 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 18:33:55.468  3604  3635 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-12 18:33:55.468  3604  3635 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-12 18:33:55.468  3604  3635 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-12 18:33:55.468  3604  3635 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-12 18:33:55.468  3604  3635 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-12 18:33:55.468  3604  3635 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 18:34:00.841  3689  4406 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 18:34:00.869  3689  4407 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 18:34:00.882  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:34:00.885  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:34:00.914  1513  2252 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 18:34:00.914  1513  2252 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 18:34:00.914  1513  2252 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:34:00.914  1513  2252 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:34:00.944  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:34:00.947  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:34:00.973  1513  1952 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 18:34:00.974  1513  1952 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 18:34:00.974  1513  1952 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:34:00.974  1513  1952 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:34:00.992  3689  4407 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 18:34:00.993  3689  4406 E BooksSync: Soft error
09-12 18:34:00.993  3689  4406 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 18:34:00.993  3689  4406 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 18:34:00.993  3689  4406 E BooksSync: Sync error
09-12 18:34:00.993  3689  4406 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 18:34:00.993  3689  4406 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 18:34:00.993  3689  4406 I BooksSync: Finished books sync,
,09-12 18:34:01.003   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 318674, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:34:31.353  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:34:31.356  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:34:31.405  1513  2252 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-12 18:34:31.405  1513  2252 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 18:34:31.405  1513  2252 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:34:31.406  1513  2252 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:34:31.429  3645  4410 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 18:34:31.429  3645  4410 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at jdm.a(PG:82)
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at jcs.o(PG:406)
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at jcn.a(PG:1379)
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at jcs.i(PG:143)
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at blb.a(PG:3937)
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at czp.a(PG:18188)
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at czp.a(PG:9081)
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at czq.run(PG:1686)
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:34:31.429  3645  4410 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at jdj.a(PG:4091)
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at jdj.a(PG:1125)
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at jdm.a(PG:77)
09-12 18:34:31.429  3645  4410 E HttpOperation: 	... 12 more
09-12 18:34:31.429  3645  4410 E HttpOperation: Caused by: faj: BadAuthentication
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at fal.a(PG:38)
09-12 18:34:31.429  3645  4410 E HttpOperation: 	at jdj.a(PG:4089)
09-12 18:34:31.429  3645  4410 E HttpOperation: 	... 14 more
,09-12 18:34:31.483  1513  2252 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 18:34:31.483  1513  2252 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 18:34:31.483  1513  2252 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 18:34:31.483  1513  2252 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:34:31.506  3645  4410 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 18:34:31.506  3645  4410 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at jdm.a(PG:82)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at jcs.o(PG:406)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at jcn.a(PG:1379)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at jcs.i(PG:143)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at hec.a(PG:42)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at hee.a(PG:102)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at czr.a(PG:65)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at kka.a(PG:108)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at czp.a(PG:19176)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at czp.a(PG:9081)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at czq.run(PG:1686)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:34:31.506  3645  4410 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at jdj.a(PG:4091)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at jdj.a(PG:1125)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at jdm.a(PG:77)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	... 15 more
09-12 18:34:31.506  3645  4410 E HttpOperation: Caused by: faj: BadAuthentication
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at fal.a(PG:38)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	at jdj.a(PG:4089)
09-12 18:34:31.506  3645  4410 E HttpOperation: 	... 17 more
,09-12 18:34:31.506  3645  4410 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 18:34:31.506  3645  4410 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at hec.a(PG:42)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at hee.a(PG:102)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at czr.a(PG:65)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at kka.a(PG:108)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at jdj.a(PG:4091)
,09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	... 15 more
09-12 18:34:31.506  3645  4410 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at fal.a(PG:38)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 18:34:31.506  3645  4410 E ExperimentLoader: 	... 17 more
,09-12 18:34:31.643   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 348057, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:35:01.815  3037  4413 V KeepSync: Connecting to GoogleApiClient
09-12 18:35:01.816   872  1430 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 18:35:01.868  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:35:01.871  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:35:01.914  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-12 18:35:01.914  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 18:35:01.914  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:35:01.914  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:35:01.940  1712  4414 V BaseAuthAsyncOperation: access token request failed
,09-12 18:35:01.941  3037  4413 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 18:35:02.015  1513  3942 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-12 18:35:02.015  1513  3942 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-12 18:35:02.015  1513  3942 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:35:02.015  1513  3942 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:35:02.042  3037  4413 E KeepSync: IOException
09-12 18:35:02.042  3037  4413 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 18:35:02.042  3037  4413 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 18:35:02.042  3037  4413 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 18:35:02.042  3037  4413 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 18:35:02.042  3037  4413 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 18:35:02.042  3037  4413 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 18:35:02.042  3037  4413 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 18:35:02.042  3037  4413 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 18:35:02.042  3037  4413 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 18:35:02.042  3037  4413 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 18:35:02.042  3037  4413 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 18:35:02.042  3037  4413 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 18:35:02.042  3037  4413 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 18:35:02.042  3037  4413 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 18:35:02.042  3037  4413 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 18:35:02.042  3037  4413 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 18:35:02.042  3037  4413 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 18:35:02.042  3037  4413 E KeepSync: 	... 10 more
09-12 18:35:02.042  3037  4413 W KeepSync: Sync result 2
,09-12 18:35:02.057   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 381150, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:35:32.234  3689  4416 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 18:35:32.256  3689  4417 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 18:35:32.270  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:35:32.272  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:35:32.302  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 18:35:32.302  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 18:35:32.302  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 18:35:32.303  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:35:32.338  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:35:32.341  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:35:32.373  1513  1952 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 18:35:32.373  1513  1952 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 18:35:32.373  1513  1952 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 18:35:32.374  1513  1952 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:35:32.395  3689  4417 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 18:35:32.396  3689  4416 E BooksSync: Soft error
09-12 18:35:32.396  3689  4416 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 18:35:32.396  3689  4416 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 18:35:32.396  3689  4416 E BooksSync: Sync error
09-12 18:35:32.396  3689  4416 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 18:35:32.396  3689  4416 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 18:35:32.397  3689  4416 I BooksSync: Finished books sync
,09-12 18:35:32.405   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 412340, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:35:55.482  1513  2177 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 18:36:02.829  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:36:02.831  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:36:02.881  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 18:36:02.881  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 18:36:02.881  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:36:02.881  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:36:02.901  3645  4420 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 18:36:02.901  3645  4420 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at jdm.a(PG:82)
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at jcs.o(PG:406)
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at jcn.a(PG:1379)
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at jcs.i(PG:143)
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at blb.a(PG:3937)
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at czp.a(PG:18188)
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at czp.a(PG:9081)
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at czq.run(PG:1686)
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:36:02.901  3645  4420 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at jdj.a(PG:4091)
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at jdj.a(PG:1125)
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at jdm.a(PG:77)
09-12 18:36:02.901  3645  4420 E HttpOperation: 	... 12 more
09-12 18:36:02.901  3645  4420 E HttpOperation: Caused by: faj: BadAuthentication
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at fal.a(PG:38)
09-12 18:36:02.901  3645  4420 E HttpOperation: 	at jdj.a(PG:4089)
09-12 18:36:02.901  3645  4420 E HttpOperation: 	... 14 more
,09-12 18:36:02.966  1513  2976 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-12 18:36:02.966  1513  2976 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 18:36:02.966  1513  2976 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:36:02.966  1513  2976 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:36:03.004  3645  4420 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 18:36:03.004  3645  4420 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at jdm.a(PG:82)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at jcs.o(PG:406)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at jcn.a(PG:1379)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at jcs.i(PG:143)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at hec.a(PG:42)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at hee.a(PG:102)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at czr.a(PG:65)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at kka.a(PG:108)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at czp.a(PG:19176)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at czp.a(PG:9081)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at czq.run(PG:1686)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:36:03.004  3645  4420 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at jdj.a(PG:4091)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at jdj.a(PG:1125)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at jdm.a(PG:77)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	... 15 more
09-12 18:36:03.004  3645  4420 E HttpOperation: Caused by: faj: BadAuthentication
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at fal.a(PG:38)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	at jdj.a(PG:4089)
09-12 18:36:03.004  3645  4420 E HttpOperation: 	... 17 more
,09-12 18:36:03.005  3645  4420 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 18:36:03.005  3645  4420 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at hec.a(PG:42)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at hee.a(PG:102)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at czr.a(PG:65)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at kka.a(PG:108)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	... 15 more
09-12 18:36:03.005  3645  4420 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at fal.a(PG:38)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 18:36:03.005  3645  4420 E ExperimentLoader: 	... 17 more
,09-12 18:36:03.147   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 439851, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:37:09.909  3037  4424 V KeepSync: Connecting to GoogleApiClient
,09-12 18:37:09.909   872  2034 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 18:37:09.962  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:37:09.965  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:37:09.985  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 18:37:09.985  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 18:37:09.985  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:37:09.985  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:37:10.008  1712  4425 V BaseAuthAsyncOperation: access token request failed
09-12 18:37:10.009  3037  4424 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 18:37:10.060  1513  2976 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-12 18:37:10.060  1513  2976 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 18:37:10.060  1513  2976 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:37:10.061  1513  2976 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:37:10.084  3037  4424 E KeepSync: IOException
09-12 18:37:10.084  3037  4424 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 18:37:10.084  3037  4424 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 18:37:10.084  3037  4424 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 18:37:10.084  3037  4424 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 18:37:10.084  3037  4424 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 18:37:10.084  3037  4424 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 18:37:10.084  3037  4424 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 18:37:10.084  3037  4424 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 18:37:10.084  3037  4424 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 18:37:10.084  3037  4424 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 18:37:10.084  3037  4424 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 18:37:10.084  3037  4424 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 18:37:10.084  3037  4424 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 18:37:10.084  3037  4424 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 18:37:10.084  3037  4424 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 18:37:10.084  3037  4424 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 18:37:10.084  3037  4424 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 18:37:10.084  3037  4424 E KeepSync: 	... 10 more
09-12 18:37:10.084  3037  4424 W KeepSync: Sync result 2
,09-12 18:37:10.100   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 536406, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:37:41.888  3689  4427 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 18:37:41.936  3689  4428 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 18:37:41.957  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:37:41.962  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:37:42.017  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 18:37:42.018  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 18:37:42.018  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:37:42.018  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:37:42.074  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:37:42.080  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:37:42.134  1513  3942 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 18:37:42.134  1513  3942 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 18:37:42.135  1513  3942 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 18:37:42.135  1513  3942 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:37:42.169  3689  4428 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 18:37:42.170  3689  4427 E BooksSync: Soft error
09-12 18:37:42.170  3689  4427 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 18:37:42.170  3689  4427 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 18:37:42.170  3689  4427 E BooksSync: Sync error
09-12 18:37:42.170  3689  4427 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 18:37:42.170  3689  4427 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 18:37:42.170  3689  4427 I BooksSync: Finished books sync
,09-12 18:37:42.178   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 568463, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:38:12.573  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:38:12.575  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 18:38:12.610  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-12 18:38:12.610  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 18:38:12.610  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 18:38:12.611  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:38:12.629  3645  4431 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 18:38:12.629  3645  4431 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at jdm.a(PG:82)
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at jcs.o(PG:406)
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at jcn.a(PG:1379)
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at jcs.i(PG:143)
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at blb.a(PG:3937)
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at czp.a(PG:18188)
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at czp.a(PG:9081)
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at czq.run(PG:1686)
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:38:12.629  3645  4431 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at jdj.a(PG:4091)
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at jdj.a(PG:1125)
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at jdm.a(PG:77)
09-12 18:38:12.629  3645  4431 E HttpOperation: 	... 12 more
09-12 18:38:12.629  3645  4431 E HttpOperation: Caused by: faj: BadAuthentication
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at fal.a(PG:38)
09-12 18:38:12.629  3645  4431 E HttpOperation: 	at jdj.a(PG:4089)
09-12 18:38:12.629  3645  4431 E HttpOperation: 	... 14 more
,09-12 18:38:12.732  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 18:38:12.732  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 18:38:12.733  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 18:38:12.733  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 18:38:12.773  3645  4431 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 18:38:12.773  3645  4431 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at jdm.a(PG:82)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at jcs.o(PG:406)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at jcn.a(PG:1379)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at jcs.i(PG:143)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at hec.a(PG:42)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at hee.a(PG:102)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at czr.a(PG:65)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at kka.a(PG:108)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at czp.a(PG:19176)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at czp.a(PG:9081)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at czq.run(PG:1686)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:38:12.773  3645  4431 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at jdj.a(PG:4091)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at jdj.a(PG:1125)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at jdm.a(PG:77)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	... 15 more
09-12 18:38:12.773  3645  4431 E HttpOperation: Caused by: faj: BadAuthentication
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at fal.a(PG:38)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	at jdj.a(PG:4089)
09-12 18:38:12.773  3645  4431 E HttpOperation: 	... 17 more
,09-12 18:38:12.773  3645  4431 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 18:38:12.773  3645  4431 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at hec.a(PG:42)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at hee.a(PG:102)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at czr.a(PG:65)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at kka.a(PG:108)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	... 15 more
09-12 18:38:12.773  3645  4431 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at fal.a(PG:38)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 18:38:12.773  3645  4431 E ExperimentLoader: 	... 17 more
,09-12 18:38:12.911   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 592945, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 18:40:12.667  1513  2177 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 18:43:10.447   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=897063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:43:21.127   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=907744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:43:35.514   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=922130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:43:46.180   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=932797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:44:00.580   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=947197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:44:11.247   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=957864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:44:25.647   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=972263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:44:36.300   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=982917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:44:50.660   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=997277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:45:01.367   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1007984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:45:15.780   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1022397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:45:26.434   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1033050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:45:40.794   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1047410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:45:51.487   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1058104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:46:05.860   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1072477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:46:16.540   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1083157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:46:30.927   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1097544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:46:41.620   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1108237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:46:43.556  1712  4458 I EventLogService: Opted in for usage reporting
09-12 18:46:43.557  1712  4458 I EventLogService: Aggregate from 1473696730047 (log), 1473696730047 (data)
,09-12 18:46:43.625  1712  4458 W EventLogAggregator: Unknown tag: snet_gcore
09-12 18:46:43.625  1712  4458 W EventLogAggregator: Unknown tag: snet_launch_service
,09-12 18:46:43.834  1712  4458 I ServiceDumpSys: dumping service [account]
,09-12 18:47:21.060   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1147677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:47:31.740   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1158357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:47:46.127   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1172744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:47:56.794   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1183410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:48:10.020   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1196637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:48:21.861   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1208477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:48:31.769   872   884 I UsageStatsService: User[0] Flushing usage stats to disk
,09-12 18:48:35.086   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1221703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:48:46.914   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1233531, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:49:00.206   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1246823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:49:12.033   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1258650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:49:25.273   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1271890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:49:37.087   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1283703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:49:50.340   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1296957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:50:02.180   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1308797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:50:15.407   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1322024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:50:27.234   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1333851, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:50:40.473   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1347090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:50:52.286   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1358903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:51:05.540   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1372157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:51:17.353   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1383970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:51:30.607   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1397224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:51:42.420   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1409037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:51:55.673   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1422290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:52:07.473   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1434090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:52:20.713   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1447330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:52:32.526   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1459143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:52:45.807   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1472424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:52:57.620   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1484237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:53:09.647   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1496263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 18:53:22.673   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1509290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 18:53:34.686   872  4329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1521303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),09-12 18:53:43.120  4487  4487 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 18:53:43.124  4487  4487 D AndroidRuntime: CheckJNI is OFF
09-12 18:53:43.160  4487  4487 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 18:53:43.201  4487  4487 I Radio-JNI: register_android_hardware_Radio DONE
09-12 18:53:43.221  4487  4487 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-12 18:53:43.237   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-12 18:53:43.238   872   885 I ActivityManager: Killing 3881:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-12 18:53:43.353   872   883 D GraphicsStats: Buffer count: 2
09-12 18:53:43.354   872  1430 I WindowState: WIN DEATH: Window{340c5b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-12 18:53:43.355   872  1318 D WifiService: Client connection lost with reason: 4
09-12 18:53:43.362   872   895 W PackageSettings: Skipping PackageSetting{2533dc0 com.example.hello/10273} due to missing metadata
09-12 18:53:43.406   872   895 I art     : Starting a blocking GC Explicit
09-12 18:53:43.417   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-12 18:53:43.417   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-12 18:53:43.418   872   885 E ActivityManager: Failure starting process com.test.thalitest
09-12 18:53:43.418   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-12 18:53:43.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-12 18:53:43.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-12 18:53:43.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-12 18:53:43.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-12 18:53:43.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-12 18:53:43.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-12 18:53:43.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-12 18:53:43.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-12 18:53:43.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-12 18:53:43.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-12 18:53:43.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-12 18:53:43.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-12 18:53:43.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-12 18:53:43.418   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-12 18:53:43.418   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:53:43.418   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:53:43.418   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 18:53:43.418   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 18:53:43.418   872   885 I ActivityManager:   Force finishing activity ActivityRecord{5606af8 u0 com.test.thalitest/.MainActivity t4}
09-12 18:53:43.423   872   883 W ActivityManager: Spurious death for ProcessRecord{bc837d7 0:com.test.thalitest/u0a0}, curProc for 3881: null
09-12 18:53:43.456   872   895 I art     : Explicit concurrent mark sweep GC freed 49589(3MB) AllocSpace objects, 10(200KB) LOS objects, 33% free, 29MB/43MB, paused 728us total 45.559ms
09-12 18:53:43.476   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-12 18:53:43.482  4487  4487 I art     : System.exit called, status: 0
09-12 18:53:43.482  4487  4487 I AndroidRuntime: VM exiting with result code 0.
09-12 18:53:43.496   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-12 18:53:43.515   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-12 18:53:43.518  1901  1901 I Keyboard.Facilitator: resetDictionaries() : en_US
09-12 18:53:43.519  4271  4271 D BluetoothMapAppObserver: onReceive
09-12 18:53:43.520  4271  4271 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-12 18:53:43.525  1869  2179 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-12 18:53:43.528   872  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-12 18:53:43.536  3750  3750 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-12 18:53:43.567  2020  2020 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-12 18:53:43.578   872  2033 I ActivityManager: Start proc 4504:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-12 18:53:43.589  1901  4503 I Keyboard.Facilitator.DecoderInitializer: run()
09-12 18:53:43.592  1901  4503 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
09-12 18:53:43.592  1901  4503 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
09-12 18:53:43.593  1901  4503 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
09-12 18:53:43.600  1901  4503 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
09-12 18:53:43.603  1901  4503 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
09-12 18:53:43.603  1901  4503 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
09-12 18:53:43.604  1901  4503 I Decoder : createOrResetDecoder
09-12 18:53:43.611  4504  4504 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-12 18:53:43.615   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-12 18:53:43.623  1513  1513 I ConfigService: onCreate
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-12 18:53:43.631  1513  4516 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-12 18:53:43.633  1513  4516 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-12 18:53:43.634   872  2019 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3881 uid 10000
09-12 18:53:43.635  1901  1901 I Keyboard.Facilitator: onFinishInput()
09-12 18:53:43.636  2037  2098 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-12 18:53:43.636  1513  4516 W SQLiteOpenHelper: Opened config.db in read-only mode
09-12 18:53:43.639   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-12 18:53:43.640   872   884 E PackageManager: Failed to write settings, restoring backup
09-12 18:53:43.640   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-12 18:53:43.640   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-12 18:53:43.640   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-12 18:53:43.640   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-12 18:53:43.640   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-12 18:53:43.640   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:53:43.640   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:53:43.640   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 18:53:43.644   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-12 18:53:43.644   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 18:53:43.644   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 18:53:43.644   872   885 E DropBoxManagerService: 	... 13 more
09-12 18:53:43.648   872   882 I ActivityManager: Start proc 4518:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-12 18:53:43.649  2037  2098 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-12 18:53:43.649  2037  2098 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2037
09-12 18:53:43.649  2037  2098 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 18:53:43.649  2037  2098 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 18:53:43.649  2037  2098 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 18:53:43.649  2037  2098 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 18:53:43.649  2037  2098 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 18:53:43.649  2037  2098 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 18:53:43.649  2037  2098 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-12 18:53:43.649  2037  2098 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-12 18:53:43.649  2037  2098 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 18:53:43.649  2037  2098 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 18:53:43.649  2037  2098 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:53:43.649  2037  2098 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 18:53:43.651   872  2033 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 18:53:43.654  2037  2098 I Process : Sending signal. PID: 2037 SIG: 9
09-12 18:53:43.659  1901  4503 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-12 18:53:43.661   872  4525 E DropBoxManagerService: Can't write: system_app_crash
09-12 18:53:43.661   872  4525 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-12 18:53:43.661   872  4525 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 18:53:43.661   872  4525 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 18:53:43.661   872  4525 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 18:53:43.661   872  4525 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 18:53:43.661   872  4525 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 18:53:43.661   872  4525 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 18:53:43.661   872  4525 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 18:53:43.661   872  4525 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 18:53:43.661   872  4525 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 18:53:43.661   872  4525 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 18:53:43.661   872  4525 E DropBoxManagerService: 	... 5 more
09-12 18:53:43.693  4504  4504 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-12 18:53:43.699  1901  4503 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-12 18:53:43.700  1901  4503 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-12 18:53:43.700  1901  4503 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-12 18:53:43.702  1901  4503 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-12 18:53:43.702  1901  4503 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-12 18:53:43.708  1901  4503 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-12 18:53:43.708  1901  4503 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-12 18:53:43.709  1901  4503 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-12 18:53:43.709  1901  4503 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-12 18:53:43.709  1901  4503 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-12 18:53:43.709  1901  4503 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-12 18:53:43.709  1901  4503 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-12 18:53:43.709  1901  4503 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-12 18:53:43.719  4504  4535 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-12 18:53:43.723   872  1962 I ActivityManager: Start proc 4536:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-12 18:53:43.728   872  1705 D GraphicsStats: Buffer count: 1
09-12 18:53:43.728   872  1704 I WindowState: WIN DEATH: Window{cda021e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-12 18:53:43.739   872  1705 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2037) has died
09-12 18:53:43.740   872  1705 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-12 18:53:43.744   872  1705 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:53:43.746  4504  4523 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:53:43.746  4504  4523 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 18:53:43.760   872  2014 I ActivityManager: Start proc 4549:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 18:53:43.790  4536  4536 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-12 18:53:43.812  1513  1513 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:53:43.812  4549  4549 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 18:53:43.812  4549  4549 D AndroidRuntime: Shutting down VM
09-12 18:53:43.813  1513  1513 D AndroidRuntime: Shutting down VM
09-12 18:53:43.815  1513  1513 E AndroidRuntime: FATAL EXCEPTION: main
09-12 18:53:43.815  1513  1513 E AndroidRuntime: Process: com.google.process.gapps, PID: 1513
09-12 18:53:43.815  1513  1513 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-12 18:53:43.815  1513  1513 E AndroidRuntime: 	... 8 more
09-12 18:53:43.816  1712  4561 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-12 18:53:43.818  1712  4561 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-12 18:53:43.821   872  4565 E DropBoxManagerService: Can't write: system_app_crash
09-12 18:53:43.821   872  4565 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-12 18:53:43.821   872  4565 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 18:53:43.821   872  4565 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 18:53:43.821   872  4565 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 18:53:43.821   872  4565 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 18:53:43.821   872  4565 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 18:53:43.821   872  4565 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 18:53:43.821   872  4565 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 18:53:43.821   872  4565 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 18:53:43.821   872  4565 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 18:53:43.821   872  4565 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 18:53:43.821   872  4565 E DropBoxManagerService: 	... 5 more
09-12 18:53:43.827  4549  4549 E AndroidRuntime: FATAL EXCEPTION: main
09-12 18:53:43.827  4549  4549 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4549
09-12 18:53:43.827  4549  4549 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 18:53:43.827  4549  4549 E AndroidRuntime: 	... 10 more
09-12 18:53:43.828   872   883 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 18:53:43.829  4549  4549 I Process : Sending signal. PID: 4549 SIG: 9
09-12 18:53:43.830   872  4566 E DropBoxManagerService: Can't write: system_app_crash
09-12 18:53:43.830   872  4566 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-12 18:53:43.830   872  4566 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 18:53:43.830   872  4566 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 18:53:43.830   872  4566 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 18:53:43.830   872  4566 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 18:53:43.830   872  4566 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 18:53:43.830   872  4566 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 18:53:43.830   872  4566 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 18:53:43.830   872  4566 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 18:53:43.830   872  4566 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 18:53:43.830   872  4566 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 18:53:43.830   872  4566 E DropBoxManagerService: 	... 5 more
09-12 18:53:43.839  1513  1513 I Process : Sending signal. PID: 1513 SIG: 9
09-12 18:53:43.856  1712  4561 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-12 18:53:43.858  1712  4561 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-12 18:53:43.858   872   882 I ActivityManager: Killing 3802:com.google.android.apps.docs/u0a46 (adj 15): empty #17
09-12 18:53:43.873   872  1318 D WifiService: Client connection lost with reason: 4
09-12 18:53:43.894  4504  4523 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:53:43.898  4504  4535 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-12 18:53:43.898  4504  4535 E AndroidRuntime: Process: android.process.acore, PID: 4504
09-12 18:53:43.898  4504  4535 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 18:53:43.898  4504  4535 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 18:53:43.900  4504  4523 I Process : Sending signal. PID: 4504 SIG: 9
09-12 18:53:43.912   872  2034 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4549) has died
09-12 18:53:43.914   872  2034 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-12 18:53:43.920   872  4567 E DropBoxManagerService: Can't write: system_app_crash
09-12 18:53:43.920   872  4567 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-12 18:53:43.920   872  4567 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 18:53:43.920   872  4567 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 18:53:43.920   872  4567 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 18:53:43.920   872  4567 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 18:53:43.920   872  4567 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 18:53:43.920   872  4567 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 18:53:43.920   872  4567 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 18:53:43.920   872  4567 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 18:53:43.920   872  4567 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 18:53:43.920   872  4567 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 18:53:43.920   872  4567 E DropBoxManagerService: 	... 5 more
09-12 18:53:43.921   872  2033 I ActivityManager: Process com.google.process.gapps (pid 1513) has died
09-12 18:53:43.923   872  2033 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
09-12 18:53:43.923   872  2033 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
09-12 18:53:43.924   872  2033 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
09-12 18:53:43.928   872  1391 I ActivityManager: Process android.process.acore (pid 4504) has died
09-12 18:53:43.928   872  1391 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30995ms
09-12 18:53:43.931  1712  1712 W RocketImpressions: ClearcutLogger connection suspended: 1
09-12 18:53:43.959   872   885 I ActivityManager: Start proc 4568:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL

```
