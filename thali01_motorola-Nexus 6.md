#### Test 8484329609337e6_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-12 16:52:59.123  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:52:59.135  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 16:52:59.136  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 16:52:59.169  1518  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 16:52:59.169  1518  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 16:52:59.169  1518  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:52:59.169  1518  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 16:52:59.189  3646  3646 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 16:52:59.189  3646  3646 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 16:52:59.190  3646  3646 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-12 16:52:59.786  3912  3912 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 16:52:59.791  3912  3912 D AndroidRuntime: CheckJNI is OFF
09-12 16:52:59.834  3912  3912 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 16:52:59.885  3912  3912 I Radio-JNI: register_android_hardware_Radio DONE
09-12 16:52:59.908  3912  3912 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-12 16:52:59.912   877  3279 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-12 16:52:59.971  2060  2428 W SearchService: Abort, client detached.
09-12 16:52:59.975  3912  3912 D AndroidRuntime: Shutting down VM
09-12 16:52:59.978  2060  2381 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2a4ea0b
09-12 16:52:59.979  2060  2060 I HotwordDetector: Closing mic
09-12 16:52:59.981  2060  2390 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-12 16:52:59.999   877  1399 I ActivityManager: Start proc 3921:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-12 16:53:00.044   376  2392 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-12 16:53:00.045   376  2392 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-12 16:53:00.048   376  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-12 16:53:00.050  2060  2386 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-12 16:53:00.051  2060  2389 I MicroRecognitionRnrImpl: Detection finished
09-12 16:53:00.101  3921  3921 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-12 16:53:00.133  3921  3921 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-12 16:53:00.142  3921  3921 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2431-2435)
09-12 16:53:00.142  3921  3921 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 16:53:00.160  3921  3921 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f86a664}
09-12 16:53:00.161  3921  3921 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 16:53:00.161  3921  3921 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 16:53:00.169  3921  3921 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-12 16:53:00.170  3921  3921 E SysUtils: ApplicationContext is null in ApplicationStatus
09-12 16:53:00.195  3921  3921 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 16:53:00.206  3921  3921 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 16:53:00.206  3921  3921 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 16:53:00.206  3921  3921 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 16:53:00.206  3921  3921 I Adreno  : Build Date                       : 10/20/15
09-12 16:53:00.206  3921  3921 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 16:53:00.206  3921  3921 I Adreno  : Local Branch                     : M14
09-12 16:53:00.206  3921  3921 I Adreno  : Remote Branch                    : 
09-12 16:53:00.206  3921  3921 I Adreno  : Remote Branch                    : 
09-12 16:53:00.206  3921  3921 I Adreno  : Reconstruct Branch               : 
,09-12 16:53:00.250   877   894 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4477256:true
,09-12 16:53:00.299  3921  3921 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 16:53:00.315  3921  3921 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-12 16:53:00.380  3921  3959 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-12 16:53:00.398  3921  3946 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-12 16:53:00.432  3921  3959 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 16:53:00.492   877   895 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +518ms
,09-12 16:53:00.497  1877  1877 I Keyboard.Facilitator: onFinishInput()
,09-12 16:53:00.546  3921  3921 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3921
,09-12 16:53:00.694  3921  3921 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 16:53:00.777   877  1309 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-12 16:53:00.811   877   887 I ActivityManager: Killing 2571:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-12 16:53:00.843   877   887 I ActivityManager: Killing 3251:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-12 16:53:00.970  3921  3961 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1681721040
,09-12 16:53:00.976  3921  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 16:53:00.976  3921  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 16:53:00.976  3921  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 16:53:00.976  3921  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 16:53:00.976  3921  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 16:53:00.976  3921  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b32a8 added. We now have 1 listener(s)
,09-12 16:53:00.980  3921  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-12 16:53:00.984  3921  3961 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 16:53:00.986  3921  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 16:53:00.987  3921  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 16:53:00.992  3921  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 16:53:00.992  3921  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 16:53:00.992  3921  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 16:53:00.992  3921  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-12 16:53:00.992  3921  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 16:53:00.992  3921  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 16:53:00.992  3921  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 16:53:00.992  3921  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 16:53:00.992  3921  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 16:53:00.992  3921  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 16:53:00.992  3921  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 16:53:00.992  3921  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 16:53:00.992  3921  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 16:53:00.992  3921  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-12 16:53:00.993  3921  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a58a7 added. We now have 1 listener(s)
,09-12 16:53:00.993  3921  3961 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 16:53:00.998  3921  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 16:53:00.998  3921  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-12 16:53:00.998   877  1311 D WifiService: New client listening to asynchronous messages
,09-12 16:53:00.999  3921  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-12 16:53:00.999  3921  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-12 16:53:00.999  3921  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-12 16:53:01.004  3921  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 16:53:01.004  3921  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-12 16:53:01.018  3921  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-12 16:53:01.018  3921  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 16:53:01.018  3921  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:01.018  3921  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:01.018  3921  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:01.018  3921  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:53:01.018  3921  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:53:01.018  3921  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:53:01.018  3921  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 16:53:01.018  3921  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-12 16:53:01.018  3921  3961 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 16:53:01.019  3921  3961 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 16:53:01.028  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:01.029  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:01.046  3921  3921 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 16:53:01.952  3921  3970 W jxcore-log: Initializing JXcore engine
09-12 16:53:01.952  3921  3970 W jxcore-log: JXcore engine is ready
,09-12 16:53:01.987  3970  3970 W Thread-354: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-12 16:53:01.987  3970  3970 W Thread-354: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9572]" dev="sockfs" ino=9572 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-12 16:53:01.987  3970  3970 W Thread-354: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-12 16:53:01.990  3970  3970 W Thread-354: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[24298]" dev="sockfs" ino=24298 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-12 16:53:02.001  3921  3970 W jxcore-log: Starting JXcore engine
,09-12 16:53:02.114  3921  3970 W jxcore-log: Platform android
09-12 16:53:02.114  3921  3970 W jxcore-log: 
,09-12 16:53:02.114  3921  3970 W jxcore-log: Process ARCH arm
09-12 16:53:02.114  3921  3970 W jxcore-log: 
,09-12 16:53:02.313  3921  3970 I jxcore-log: JXcore Cordova bridge is ready!
09-12 16:53:02.313  3921  3970 I jxcore-log: 
,09-12 16:53:02.313  3921  3970 W jxcore-log: JXcore engine is started
,09-12 16:53:02.318  3921  3961 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 16:53:02.321  3921  3921 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 16:53:09.263  3192  3979 V KeepSync: Connecting to GoogleApiClient
,09-12 16:53:09.264   877  3384 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 16:53:09.328  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:53:09.332  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:53:09.366  1518  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-12 16:53:09.366  1518  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-12 16:53:09.366  1518  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:53:09.366  1518  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:53:09.398  1742  3980 V BaseAuthAsyncOperation: access token request failed
,09-12 16:53:09.399  3192  3979 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 16:53:09.465  1518  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 16:53:09.466  1518  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-12 16:53:09.466  1518  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:53:09.466  1518  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:53:09.495  3192  3979 E KeepSync: IOException
09-12 16:53:09.495  3192  3979 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 16:53:09.495  3192  3979 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 16:53:09.495  3192  3979 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 16:53:09.495  3192  3979 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 16:53:09.495  3192  3979 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 16:53:09.495  3192  3979 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 16:53:09.495  3192  3979 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 16:53:09.495  3192  3979 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 16:53:09.495  3192  3979 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 16:53:09.495  3192  3979 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 16:53:09.495  3192  3979 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 16:53:09.495  3192  3979 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 16:53:09.495  3192  3979 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 16:53:09.495  3192  3979 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 16:53:09.495  3192  3979 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 16:53:09.495  3192  3979 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 16:53:09.495  3192  3979 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 16:53:09.495  3192  3979 E KeepSync: 	... 10 more
,09-12 16:53:09.495  3192  3979 W KeepSync: Sync result 2
,09-12 16:53:09.509   877   889 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 131396, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 16:53:12.661   877  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 16:53:15.699   877  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 16:53:16.527  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 16:53:16.527  3921  3970 I jxcore-log: 
,09-12 16:53:16.529  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 16:53:16.529  3921  3970 I jxcore-log: 
,09-12 16:53:16.543  3921  3970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 16:53:16.543  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:16.543  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:16.543  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:16.543  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:53:16.543  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:53:16.543  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:53:16.543  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 16:53:16.549  3921  3970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 16:53:16.551  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 16:53:16.551  3921  3970 I jxcore-log: 
,09-12 16:53:16.553  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 16:53:16.553  3921  3970 I jxcore-log: 
,09-12 16:53:16.900  3921  3970 I jxcore-log: Running unit tests
09-12 16:53:16.900  3921  3970 I jxcore-log: 
09-12 16:53:16.901  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 16:53:16.901  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39af561 added. We now have 2 listener(s)
,09-12 16:53:16.902  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 16:53:16.902  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 16:53:16.902  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 16:53:16.902  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 16:53:16.902  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c43886 added. We now have 2 listener(s)
,09-12 16:53:16.902  3921  3970 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 16:53:16.903  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 16:53:16.907  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 16:53:16.918  3921  3970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 16:53:16.918  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:16.918  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:16.918  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:16.918  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:53:16.918  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:53:16.918  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:53:16.918  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 16:53:16.923  3921  3970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 16:53:16.923  3921  3970 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 16:53:16.923  3921  3970 D executeNativeTests: Running unit tests
,09-12 16:53:16.928  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:16.938  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:16.989  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 16:53:16.989  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 added. We now have 3 listener(s)
,09-12 16:53:16.990  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 16:53:16.990  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 16:53:16.990  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 16:53:16.990  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 16:53:16.990  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d added. We now have 3 listener(s)
,09-12 16:53:16.990  3921  3970 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 16:53:16.991  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 16:53:17.004  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 16:53:17.016  3921  3970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 16:53:17.016  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:17.016  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:17.016  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:17.016  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:53:17.016  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:53:17.016  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:53:17.016  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 16:53:17.021  3921  3970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 16:53:17.022  3921  3970 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 16:53:17.029  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 16:53:17.029  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 16:53:17.030  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 16:53:17.030  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:17.030  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 16:53:17.032  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:17.034  3921  3970 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-12 16:53:17.035  3921  3970 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 16:53:17.036  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 16:53:17.036  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 16:53:17.036  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 16:53:17.037  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 16:53:17.039  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 16:53:17.040  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:53:17.040  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 16:53:17.041  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:17.041  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:17.041  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 16:53:17.042  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 16:53:17.042  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 removed from the list
09-12 16:53:17.042  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:53:17.043  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d removed from the list
09-12 16:53:17.043  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:53:17.043  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:17.045  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:17.045  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:17.048  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:53:17.048  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:53:17.048  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:17.048  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:17.050  3921  3970 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-12 16:53:17.051  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 16:53:17.052  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:53:17.052  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 16:53:17.052  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:17.052  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:17.052  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:17.052  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:17.052  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:53:17.053  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:17.053  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:53:17.053  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:17.053  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:17.053  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:17.053  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:17.055  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:53:17.055  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 16:53:17.055  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:17.055  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
,09-12 16:53:17.067  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 16:53:17.067  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 16:53:17.067  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-12 16:53:17.068  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 16:53:17.068  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 16:53:17.068  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-12 16:53:17.068  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 16:53:17.068  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 16:53:17.068  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-12 16:53:17.068  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 16:53:17.068  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 16:53:17.068  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-12 16:53:17.069  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 16:53:17.069  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-12 16:53:17.069  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 16:53:17.069  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 16:53:17.069  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-12 16:53:17.069  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 16:53:17.069  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 16:53:17.069  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 16:53:17.070  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 16:53:17.070  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-12 16:53:17.070  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 16:53:17.070  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 16:53:17.070  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 16:53:17.070  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-12 16:53:17.071  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 16:53:17.071  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 16:53:17.071  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-12 16:53:17.071  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 16:53:17.071  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-12 16:53:17.071  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 16:53:17.071  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:53:17.071  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 16:53:17.071  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:17.071  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:17.072  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:17.072  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:17.072  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:17.072  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:17.072  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:53:17.072  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:17.072  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:17.072  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:17.072  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:17.074  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:53:17.074  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:53:17.074  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,09-12 16:53:17.074  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
,09-12 16:53:17.075  3921  3970 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 16:53:17.077  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-12 16:53:17.081  3921  3970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 16:53:17.081  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:17.081  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:17.081  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:17.081  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:53:17.081  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:53:17.081  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:53:17.081  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 16:53:17.084  3921  3970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 16:53:17.084  3921  3970 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 16:53:17.084  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 16:53:17.085  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 16:53:17.085  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 16:53:17.085  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 16:53:17.085  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 16:53:17.087  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:53:17.090  3921  3970 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 16:53:17.091  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 16:53:17.091  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:17.097  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 16:53:17.099  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 16:53:17.100  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 16:53:17.103  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-12 16:53:17.109  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-12 16:53:17.109  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 16:53:17.110  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 16:53:17.112  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 16:53:17.114  3921  3970 D BluetoothAdapter: STATE_ON
,09-12 16:53:17.125  2819  3606 D BtGatt.GattService: registerClient() - UUID=db07738a-e738-46bb-8c90-88381dfd5a13
,09-12 16:53:17.126  2819  2877 D BtGatt.GattService: onClientRegistered() - UUID=db07738a-e738-46bb-8c90-88381dfd5a13, clientIf=5
,09-12 16:53:17.129  3921  3966 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 16:53:17.130  2819  2830 D BtGatt.GattService: start scan with filters
,09-12 16:53:17.136  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 16:53:17.136  2819  2881 D BtGatt.ScanManager: handling starting scan,
,09-12 16:53:17.137  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 16:53:17.137  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 16:53:17.137  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 16:53:17.138  2819  2881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
09-12 16:53:17.140  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 16:53:17.141  3921  3921 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 16:53:17.141  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 16:53:17.143  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 16:53:17.146  2819  2877 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 16:53:17.146  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:53:17.146  3921  3970 I io.jxcore.node.ConnectionHelper: start: OK
09-12 16:53:17.147  2819  2881 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 16:53:17.156  2819  2877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 16:53:17.156  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 16:53:17.157  2819  2881 D BtGatt.ScanManager: Starting BLE batch scan
09-12 16:53:17.157  2819  2881 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 16:53:17.171  2819  2877 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 16:53:17.172  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:53:17.181  2819  2877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 16:53:17.182  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:53:17.643  3921  3921 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 16:53:17.643  3921  3921 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 16:53:17.644  3921  3921 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 16:53:18.689  2819  2819 D BtGatt.ScanManager: awakened up at time 140981
,09-12 16:53:18.691  2819  2881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 16:53:18.744  2819  2877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-12 16:53:18.744  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:53:18.745  2819  2877 D BtGatt.GattService: current time is 141037915049
,09-12 16:53:18.746  2819  2877 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -97, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -92, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -86, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -97, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 16:53:18.750  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 16:53:18.752  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 16:53:18.753  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-12 16:53:18.754  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 16:53:18.755  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 16:53:18.756  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 16:53:20.262  2819  2819 D BtGatt.ScanManager: awakened up at time 142555
,09-12 16:53:20.265  2819  2881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 16:53:20.294  2819  2877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 16:53:20.294  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:53:20.511  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:53:20.527  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:53:20.534  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:53:20.581  1518  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 16:53:20.581  1518  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 16:53:20.582  1518  2307 I GLSUser : [GLSUser] Extracting token using key: Auth,
09-12 16:53:20.582  1518  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:53:20.614  3646  3646 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 16:53:20.614  3646  3646 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 16:53:20.615  3646  3646 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-12 16:53:21.800  2819  2819 D BtGatt.ScanManager: awakened up at time 144092
,09-12 16:53:21.802  2819  2881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 16:53:21.852  2819  2877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-12 16:53:21.852  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 16:53:21.852  2819  2877 D BtGatt.GattService: current time is 144145523015
09-12 16:53:21.854  2819  2877 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -90, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -71, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -88, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -86, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -83, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -104, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-12 16:53:21.855  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-12 16:53:21.855  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-12 16:53:21.856  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-12 16:53:21.857  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 16:53:21.858  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 16:53:21.858  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 16:53:22.153  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 16:53:22.153  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 16:53:22.154  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 16:53:22.154  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:22.154  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 16:53:22.154  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 16:53:22.155  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 16:53:22.155  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 16:53:22.155  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 16:53:22.157  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 16:53:22.157  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 16:53:22.158  3921  3970 D BluetoothAdapter: STATE_ON
,09-12 16:53:22.160  2819  2830 D BtGatt.GattService: stopScan() - queue size =1
09-12 16:53:22.162  2819  3606 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 16:53:22.166  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 16:53:22.166  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 16:53:22.167  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 16:53:22.168  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 16:53:22.168  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 16:53:22.173  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 16:53:22.175  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 16:53:22.175  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 16:53:22.176  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 16:53:22.178  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 16:53:22.182  3921  3921 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 16:53:22.182  3921  3921 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 16:53:22.182  3921  3921 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 16:53:22.183  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 16:53:22.184  2819  2877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 16:53:22.184  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:53:22.183  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:22.185  2819  2881 D BtGatt.ScanManager: stopping BLe Batch
09-12 16:53:22.185  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 16:53:22.185  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:22.186  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:53:22.186  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
,09-12 16:53:22.186  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 16:53:22.186  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:22.196  2819  2877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 16:53:22.196  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:53:22.197  2819  2881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 16:53:22.213  2819  2877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-12 16:53:22.213  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:53:22.217  2819  2877 D BtGatt.GattService: current time is 144510112322
,09-12 16:53:22.217  2819  2877 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -92, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-12 16:53:22.217  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 16:53:22.684  3921  3921 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 16:53:27.189  3921  3970 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 16:53:27.196  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 16:53:27.209  3921  3970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 16:53:27.209  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:27.209  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:27.209  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:27.209  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:53:27.209  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:53:27.209  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:53:27.209  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 16:53:27.216  3921  3970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 16:53:27.216  3921  3970 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 16:53:27.217  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 16:53:27.217  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 16:53:27.218  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 16:53:27.218  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 16:53:27.218  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 16:53:27.224  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:27.229  3921  3970 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 16:53:27.229  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 16:53:27.232  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:27.244  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 16:53:27.246  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 16:53:27.246  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 16:53:27.257  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 16:53:27.258  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 16:53:27.258  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 16:53:27.260  3921  3970 D BluetoothAdapter: STATE_ON
,09-12 16:53:27.268  2819  2831 D BtGatt.GattService: registerClient() - UUID=79b85360-24a8-400d-b9ba-7d78da40e188
,09-12 16:53:27.269  2819  2877 D BtGatt.GattService: onClientRegistered() - UUID=79b85360-24a8-400d-b9ba-7d78da40e188, clientIf=5
09-12 16:53:27.270  3921  3932 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 16:53:27.271  2819  2830 D BtGatt.GattService: start scan with filters
,09-12 16:53:27.280  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 16:53:27.280  2819  2881 D BtGatt.ScanManager: handling starting scan
09-12 16:53:27.281  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 16:53:27.281  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 16:53:27.281  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 16:53:27.293  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 16:53:27.294  3921  3921 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 16:53:27.295  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 16:53:27.301  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 16:53:27.302  2819  2877 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 16:53:27.302  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 16:53:27.302  2819  2881 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 16:53:27.310  3921  3970 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 16:53:27.314  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 16:53:27.315  3921  3970 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 16:53:27.315  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 16:53:27.315  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 16:53:27.315  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:27.316  2819  2877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 16:53:27.316  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 16:53:27.316  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 16:53:27.316  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 16:53:27.316  2819  2881 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 16:53:27.316  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 16:53:27.316  2819  2881 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 16:53:27.316  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 16:53:27.317  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 16:53:27.317  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 16:53:27.317  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 16:53:27.319  3921  3970 D BluetoothAdapter: STATE_ON
,09-12 16:53:27.320  2819  2831 D BtGatt.GattService: stopScan() - queue size =1
,09-12 16:53:27.321  2819  2830 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 16:53:27.322  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 16:53:27.322  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 16:53:27.323  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 16:53:27.323  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 16:53:27.323  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 16:53:27.325  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 16:53:27.325  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 16:53:27.326  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 16:53:27.326  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 16:53:27.327  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 16:53:27.328  3921  3921 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 16:53:27.329  3921  3921 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 16:53:27.329  3921  3921 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 16:53:27.329  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:27.329  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:27.329  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 16:53:27.329  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:27.329  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:53:27.329  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:27.329  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:53:27.329  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:27.330  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:27.330  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:27.331  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:53:27.331  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:53:27.331  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:27.331  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
,09-12 16:53:27.332  3921  3970 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 16:53:27.334  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 16:53:27.338  2819  2877 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 16:53:27.338  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 16:53:27.338  3921  3970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 16:53:27.338  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:27.338  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:27.338  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:27.338  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:53:27.338  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:53:27.338  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:53:27.338  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 16:53:27.341  3921  3970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 16:53:27.341  3921  3970 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 16:53:27.343  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:27.344  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 16:53:27.344  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 16:53:27.344  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 16:53:27.344  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 16:53:27.345  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 16:53:27.345  2819  2877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 16:53:27.345  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 16:53:27.346  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:27.349  3921  3970 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 16:53:27.349  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 16:53:27.353  2819  2877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 16:53:27.353  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 16:53:27.353  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 16:53:27.353  2819  2881 D BtGatt.ScanManager: stopping BLe Batch
,09-12 16:53:27.354  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 16:53:27.354  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 16:53:27.359  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 16:53:27.359  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 16:53:27.359  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 16:53:27.359  2819  2877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 16:53:27.359  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:53:27.360  2819  2881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 16:53:27.360  3921  3970 D BluetoothAdapter: STATE_ON
,09-12 16:53:27.362  2819  2831 D BtGatt.GattService: registerClient() - UUID=79cd3bc4-16d9-460b-8a26-acc293f5b72d
,09-12 16:53:27.362  2819  2877 D BtGatt.GattService: onClientRegistered() - UUID=79cd3bc4-16d9-460b-8a26-acc293f5b72d, clientIf=5
09-12 16:53:27.363  3921  3933 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 16:53:27.363  2819  2830 D BtGatt.GattService: start scan with filters
,09-12 16:53:27.367  2819  2877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 16:53:27.367  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:53:27.371  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 16:53:27.371  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 16:53:27.371  2819  2881 D BtGatt.ScanManager: handling starting scan
,09-12 16:53:27.371  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 16:53:27.371  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 16:53:27.376  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 16:53:27.376  3921  3921 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 16:53:27.376  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 16:53:27.378  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 16:53:27.380  2819  2877 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 16:53:27.380  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 16:53:27.380  2819  2881 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 16:53:27.381  3921  3970 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 16:53:27.387  2819  2877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 16:53:27.387  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 16:53:27.387  2819  2881 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 16:53:27.387  2819  2881 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 16:53:27.401  2819  2877 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 16:53:27.401  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:53:27.408  2819  2877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 16:53:27.408  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:53:27.805   877  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 16:53:27.877  3921  3921 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 16:53:27.878  3921  3921 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 16:53:27.878  3921  3921 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 16:53:28.915  2819  2819 D BtGatt.ScanManager: awakened up at time 151208
09-12 16:53:28.918  2819  2881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 16:53:28.967  2819  2877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-12 16:53:28.967  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:53:28.968  2819  2877 D BtGatt.GattService: current time is 151260743203
09-12 16:53:28.969  2819  2877 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -97, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -86, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -92, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -97, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -83, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 16:53:28.970  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-12 16:53:28.971  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 16:53:28.972  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 16:53:28.973  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-12 16:53:28.974  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 16:53:28.978  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 16:53:30.470  2819  2819 D BtGatt.ScanManager: awakened up at time 152762
,09-12 16:53:30.472  2819  2881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 16:53:30.484  2819  2877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 16:53:30.484  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:53:30.792   877   897 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-12 16:53:30.812  1877  1877 I Keyboard.Facilitator: onFinishInput()
,09-12 16:53:30.819   877   897 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 16:53:30.819   877   897 I Adreno  : Build Date                       : 10/20/15
09-12 16:53:30.819   877   897 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 16:53:30.819   877   897 I Adreno  : Local Branch                     : M14
09-12 16:53:30.819   877   897 I Adreno  : Remote Branch                    : 
09-12 16:53:30.819   877   897 I Adreno  : Remote Branch                    : 
09-12 16:53:30.819   877   897 I Adreno  : Reconstruct Branch               : 
,09-12 16:53:30.834   877  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 16:53:30.852   280  1300 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (180 us)
,09-12 16:53:31.481  3921  3921 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 16:53:31.481  3921  3921 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 16:53:31.540   877   897 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-12 16:53:31.542  3921  3921 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ff23ada Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@e8a71e6, 16908290=android.view.AbsSavedState$1@e8a71e6}, android:focusedViewId=100}]}]
,09-12 16:53:31.543  3921  3921 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-12 16:53:31.544  3921  3921 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 16:53:31.545  3921  3921 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-12 16:53:31.550   877   897 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-12 16:53:31.554   877   895 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-12 16:53:31.555   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,09-12 16:53:31.556   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-12 16:53:31.821   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-12 16:53:31.823   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-12 16:53:31.825   877  1335 D SurfaceControl: Excessive delay in setPowerMode(): 271ms
,09-12 16:53:31.829   877   897 I DreamManagerService: Entering dreamland.
,09-12 16:53:31.830   877   897 I PowerManagerService: Dozing...
09-12 16:53:31.832   877   892 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-12 16:53:31.912   376  1318 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-12 16:53:31.912   376  1318 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-12 16:53:31.916  2819  2819 D BtGatt.ScanManager: awakened up at time 154209
,09-12 16:53:31.918  2819  2881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 16:53:31.927   877  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 16:53:31.936  1943  3989 D NfcService: Discovery configuration equal, not updating.
,09-12 16:53:31.951   877  1309 E native  : do suspend false
,09-12 16:53:31.956  2819  2877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,09-12 16:53:31.956  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:53:31.956  2819  2877 D BtGatt.GattService: current time is 154248882563
09-12 16:53:31.956  2819  2877 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -92, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -81, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -91, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -88, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 16:53:31.956  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-12 16:53:31.957  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 16:53:31.957  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-12 16:53:31.957  2819  2877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 16:53:31.970   877  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 16:53:31.982   877  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 16:53:31.985   877  1309 E native  : do suspend true
,09-12 16:53:32.036   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-12 16:53:32.036   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-12 16:53:32.382  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 16:53:32.382  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 16:53:32.382  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 16:53:32.383  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:32.383  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 16:53:32.383  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 16:53:32.384  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 16:53:32.384  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 16:53:32.384  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 16:53:32.385  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 16:53:32.385  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 16:53:32.387  3921  3970 D BluetoothAdapter: STATE_ON
,09-12 16:53:32.389  2819  2830 D BtGatt.GattService: stopScan() - queue size =1
,09-12 16:53:32.392  2819  3029 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 16:53:32.394  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 16:53:32.395  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 16:53:32.396  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 16:53:32.396  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 16:53:32.397  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 16:53:32.402  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 16:53:32.402  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 16:53:32.402  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 16:53:32.402  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 16:53:32.403  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 16:53:32.405  3921  3921 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 16:53:32.405  3921  3921 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 16:53:32.405  3921  3921 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 16:53:32.406  2819  2877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 16:53:32.406  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 16:53:32.406  2819  2881 D BtGatt.ScanManager: stopping BLe Batch
,09-12 16:53:32.415  2819  2877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 16:53:32.415  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 16:53:32.415  2819  2881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 16:53:32.422  2819  2877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 16:53:32.423  2819  2877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:53:32.434   877  1309 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-12 16:53:32.906  3921  3921 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 16:53:32.907  3921  3921 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 16:53:32.907  3921  3921 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 16:53:37.132  2139  2705 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 16:53:37.406  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 16:53:37.406  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:53:37.407  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 16:53:37.407  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:37.408  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.408  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 16:53:37.408  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:37.409  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:37.409  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
,09-12 16:53:37.409  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 16:53:37.409  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.411  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.412  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:37.415  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:53:37.415  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 16:53:37.416  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:37.416  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:37.418  3921  3970 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-12 16:53:37.420  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 16:53:37.421  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:53:37.421  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 16:53:37.421  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:37.422  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:37.422  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.422  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
,09-12 16:53:37.422  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:37.423  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list,
09-12 16:53:37.423  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 16:53:37.423  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:37.424  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:37.424  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:37.424  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:37.427  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:53:37.427  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 16:53:37.427  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:37.427  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
,09-12 16:53:37.429  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-12 16:53:37.429  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 16:53:37.429  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 16:53:37.429  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 16:53:37.429  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 16:53:37.429  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:37.430  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.430  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
,09-12 16:53:37.430  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:53:37.430  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
,09-12 16:53:37.430  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:53:37.430  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-12 16:53:37.430  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:37.430  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:37.431  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.432  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 16:53:37.432  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:53:37.433  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:37.433  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
,09-12 16:53:37.433  3921  3970 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-12 16:53:37.434  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 16:53:37.434  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:53:37.434  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 16:53:37.434  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:37.434  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:37.435  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:37.435  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:37.435  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:53:37.435  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
,09-12 16:53:37.435  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:53:37.435  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:37.435  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:37.435  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.435  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:37.437  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:53:37.437  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:53:37.437  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:37.437  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
,09-12 16:53:37.438  3921  3970 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-12 16:53:37.438  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 16:53:37.438  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:53:37.439  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 16:53:37.439  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 16:53:37.439  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.439  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.439  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
,09-12 16:53:37.439  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:37.439  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:37.440  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 16:53:37.440  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.440  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.440  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:37.440  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.442  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 16:53:37.442  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:53:37.442  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:53:37.442  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:37.443  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 16:53:37.446  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 16:53:37.446  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
09-12 16:53:37.446  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 16:53:37.446  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 16:53:37.446  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 16:53:37.446  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 16:53:37.447  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 16:53:37.447  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 16:53:37.448  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 16:53:37.448  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 16:53:37.448  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 16:53:37.449  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:37.449  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.449  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.449  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:37.449  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:53:37.450  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:37.450  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:53:37.450  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.450  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.450  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:37.450  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.454  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:53:37.455  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:53:37.455  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:37.456  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:37.458  3921  3970 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 16:53:37.459  3921  3970 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 16:53:37.459  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-12 16:53:37.466  3921  3970 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 16:53:37.466  3921  3970 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 16:53:37.466  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 16:53:37.466  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 16:53:37.466  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 16:53:37.466  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 16:53:37.467  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-12 16:53:37.467  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 16:53:37.467  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 16:53:37.467  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 16:53:37.467  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 16:53:37.467  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-12 16:53:37.467  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 16:53:37.467  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 16:53:37.467  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 16:53:37.467  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 16:53:37.467  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 16:53:37.467  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 16:53:37.467  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 16:53:37.467  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 16:53:37.467  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-12 16:53:37.468  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 16:53:37.468  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 16:53:37.468  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 16:53:37.468  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 16:53:37.468  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 16:53:37.468  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 16:53:37.468  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 16:53:37.468  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 16:53:37.468  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 16:53:37.468  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 16:53:37.468  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-12 16:53:37.468  3921  3970 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 16:53:37.469  3921  3970 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 16:53:37.469  3921  3970 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 16:53:37.469  3921  3970 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 16:53:37.469  3921  3970 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 16:53:37.469  3921  3970 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 16:53:37.469  3921  3970 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 16:53:37.469  3921  3970 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 16:53:37.469  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 16:53:37.472  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-12 16:53:37.472  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-12 16:53:37.473  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-12 16:53:37.473  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 16:53:37.473  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 16:53:37.473  3921  3970 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 16:53:37.473  3921  3970 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 16:53:37.474  3921  3970 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-12 16:53:37.474  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 16:53:37.474  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:53:37.474  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 16:53:37.474  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:37.475  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.475  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.475  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 16:53:37.475  3921  3994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 418)
09-12 16:53:37.476  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:37.476  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:37.476  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:37.476  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:53:37.476  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.476  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:37.476  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.476  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.477  3921  3995 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 418
09-12 16:53:37.480  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 16:53:37.480  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:53:37.480  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:37.480  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:37.481  3921  3970 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-12 16:53:37.482  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 16:53:37.482  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:53:37.482  3921  3994 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 16:53:37.482  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 16:53:37.483  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:37.483  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.483  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.483  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:37.483  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:37.483  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:37.483  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:53:37.483  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.483  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.483  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.483  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.485  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:53:37.485  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:53:37.485  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:37.485  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:37.486  3921  3970 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 16:53:37.486  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 16:53:37.486  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:53:37.486  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 16:53:37.487  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:37.487  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.487  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.487  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the, list
09-12 16:53:37.487  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:37.487  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:37.487  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:53:37.487  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.487  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.488  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.488  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.495  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:53:37.495  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:53:37.495  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:37.495  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:37.496  3921  3970 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 16:53:37.496  3921  3970 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 16:53:37.496  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 16:53:37.496  3921  3970 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 16:53:37.496  3921  3970 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 16:53:37.496  3921  3970 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 16:53:37.496  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 16:53:37.496  3921  3970 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 16:53:37.497  3921  3970 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 16:53:37.497  3921  3970 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 16:53:37.497  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 16:53:37.497  3921  3970 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 16:53:37.497  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 16:53:37.497  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:53:37.497  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 16:53:37.497  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:37.497  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.497  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.497  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:37.497  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:37.497  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:37.497  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:53:37.498  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.498  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.498  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.498  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.499  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:53:37.499  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:53:37.499  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:37.499  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:37.499  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:37.499  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.499  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:37.499  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:37.499  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:37.500  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:37.500  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:53:37.500  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:37.500  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:39.817  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:53:39.824  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:53:39.896  1518  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 16:53:39.897  1518  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 16:53:39.897  1518  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 16:53:39.898  1518  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:53:39.945  3686  3997 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 16:53:39.945  3686  3997 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at jdm.a(PG:82)
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at jcs.o(PG:406)
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at jcn.a(PG:1379)
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at jcs.i(PG:143)
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at blb.a(PG:3937)
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at czp.a(PG:18188)
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at czp.a(PG:9081)
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at czq.run(PG:1686)
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 16:53:39.945  3686  3997 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at jdj.a(PG:4091)
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at jdj.a(PG:1125)
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at jdm.a(PG:77)
09-12 16:53:39.945  3686  3997 E HttpOperation: 	... 12 more
09-12 16:53:39.945  3686  3997 E HttpOperation: Caused by: faj: BadAuthentication
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at fal.a(PG:38)
09-12 16:53:39.945  3686  3997 E HttpOperation: 	at jdj.a(PG:4089)
09-12 16:53:39.945  3686  3997 E HttpOperation: 	... 14 more
,09-12 16:53:40.005  1518  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 16:53:40.006  1518  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 16:53:40.006  1518  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:53:40.006  1518  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:53:40.035  3686  3997 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 16:53:40.035  3686  3997 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at jdm.a(PG:82)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at jcs.o(PG:406)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at jcn.a(PG:1379)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at jcs.i(PG:143)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at hec.a(PG:42)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at hee.a(PG:102)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at czr.a(PG:65)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at kka.a(PG:108)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at czp.a(PG:19176)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at czp.a(PG:9081)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at czq.run(PG:1686)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 16:53:40.035  3686  3997 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at jdj.a(PG:4091)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at jdj.a(PG:1125)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at jdm.a(PG:77)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	... 15 more
09-12 16:53:40.035  3686  3997 E HttpOperation: Caused by: faj: BadAuthentication
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at fal.a(PG:38)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	at jdj.a(PG:4089)
09-12 16:53:40.035  3686  3997 E HttpOperation: 	... 17 more
,09-12 16:53:40.035  3686  3997 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 16:53:40.035  3686  3997 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at hec.a(PG:42)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at hee.a(PG:102)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at czr.a(PG:65)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at kka.a(PG:108)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	... 15 more
09-12 16:53:40.035  3686  3997 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at fal.a(PG:38)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 16:53:40.035  3686  3997 E ExperimentLoader: 	... 17 more
,09-12 16:53:40.166   877   889 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 133493, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-12 16:53:40.729  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:53:40.788   877  1309 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-12 16:53:40.878  1518  4000 I VacuumService: Vacuum at: now=1473692020877 tag=VacuumService
,09-12 16:53:40.887  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:53:40.943  1518  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure,
,09-12 16:53:40.943  1518  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-12 16:53:40.943  1518  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:53:40.944  1518  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:53:40.960  3646  3646 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 16:53:40.960  3646  3646 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 16:53:40.961  3646  3646 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-12 16:53:40.978  1518  4001 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-12 16:53:40.980  1518  4001 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-12 16:53:41.015  1518  4001 W Uploader:  no longer exists, so no auth token.
,09-12 16:53:42.501  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:53:42.501  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
,09-12 16:53:42.502  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:42.502  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:42.502  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:42.503  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:42.503  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 16:53:42.503  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:53:42.504  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 16:53:42.504  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:42.504  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:42.505  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:42.505  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:42.505  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:42.505  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
,09-12 16:53:42.506  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:53:42.506  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:42.506  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:42.507  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:42.507  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:42.511  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:53:42.511  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:53:42.511  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:53:42.512  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:42.516  3921  3970 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 16:53:42.518  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 16:53:42.519  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 16:53:42.520  3921  3970 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 16:53:42.520  3921  3970 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 16:53:42.521  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 16:53:42.521  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 16:53:42.521  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:42.521  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 16:53:42.521  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 16:53:42.522  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 16:53:42.521  3921  3921 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 16:53:42.522  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:42.522  3921  3970 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 16:53:42.522  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:42.522  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:42.522  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 16:53:42.522  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 16:53:42.522  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 16:53:42.522  3921  3921 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 16:53:42.522  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:42.522  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:42.524  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 16:53:42.524  3921  3921 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 16:53:42.524  3921  3921 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 16:53:42.525  3921  3921 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 16:53:42.524  3921  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 16:53:42.525  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:42.525  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 16:53:42.526  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:53:42.526  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 16:53:42.526  3921  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-12 16:53:42.526  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:42.526  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:42.526  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:42.526  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:42.526  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:42.526  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:42.526  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 16:53:42.526  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:42.527  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:42.527  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:42.527  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:42.529  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:53:42.529  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:53:42.529  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:42.529  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
,09-12 16:53:42.530  3921  3970 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 16:53:42.531  3921  3970 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 16:53:42.531  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 16:53:42.531  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 16:53:42.531  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 16:53:42.531  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 16:53:42.531  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 16:53:42.531  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 16:53:42.531  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:42.531  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:42.532  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:42.532  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:42.532  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:42.532  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
,09-12 16:53:42.532  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:53:42.532  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:42.532  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:42.532  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:42.532  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:42.533  3921  3921 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 16:53:42.534  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:53:42.534  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:53:42.534  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:42.534  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
,09-12 16:53:42.541  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 16:53:42.542  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:53:42.542  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 16:53:42.542  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:42.543  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:42.543  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:42.543  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:42.543  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:53:42.544  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:42.544  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 16:53:42.544  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:53:42.544  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:42.545  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:42.545  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:42.547  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 16:53:42.547  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:53:42.547  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:42.548  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
,09-12 16:53:42.550  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 16:53:42.551  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:53:42.551  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 16:53:42.551  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:53:42.551  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:42.552  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:42.552  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3c8fa4 not in the list
09-12 16:53:42.552  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:53:42.553  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
09-12 16:53:42.553  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:53:42.553  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:42.553  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:42.553  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:42.554  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:42.555  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 16:53:42.555  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:53:42.556  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:53:42.556  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@965510d not in the list
,09-12 16:53:42.559  3921  3970 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-12 16:53:42.559  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 16:53:42.560  3921  3970 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 16:53:42.560  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-12 16:53:42.560  3921  3970 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 16:53:42.560  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-12 16:53:42.566  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 16:53:42.566  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-12 16:53:42.567  3921  3970 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 16:53:42.567  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 16:53:42.567  3921  3970 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 16:53:42.567  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-12 16:53:42.567  3921  3970 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 16:53:42.567  3921  3970 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 16:53:42.568  3921  3970 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-12 16:53:42.568  3921  3970 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-12 16:53:42.568  3921  3970 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 16:53:42.569  3921  3970 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-12 16:53:42.569  3921  3970 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 16:53:42.569  3921  3970 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-12 16:53:42.570  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 16:53:42.570  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b529d4 added. We now have 3 listener(s)
09-12 16:53:42.570  3921  3970 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 16:53:42.573  3921  3970 D BluetoothAdapter: enable(): BT is already enabled..!
,09-12 16:53:42.573   877  2002 D WifiService: setWifiEnabled: true pid=3921, uid=10000
09-12 16:53:42.573   877  2002 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 16:53:42.630  2819  3000 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-12 16:53:42.631  2819  3006 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-12 16:53:42.633  3921  3994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 418)
,09-12 16:53:43.025  3921  3921 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 16:53:43.783  1518  4001 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-12 16:53:43.783  1518  4001 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-12 16:53:43.783  1518  4001 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:53:43.783  1518  4001 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:53:43.804  1518  4001 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 16:53:43.804  1518  4001 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 16:53:43.804  1518  4001 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 16:53:43.804  1518  4001 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 16:53:43.804  1518  4001 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 16:53:43.804  1518  4001 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 16:53:43.804  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 16:53:43.804  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 16:53:43.804  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 16:53:43.804  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 16:53:43.804  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 16:53:43.804  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 16:53:43.804  1518  4001 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 16:53:44.141  1518  4001 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-12 16:53:44.141  1518  4001 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-12 16:53:44.142  1518  4001 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:53:44.142  1518  4001 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:53:44.168  1518  4001 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 16:53:44.168  1518  4001 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 16:53:44.168  1518  4001 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 16:53:44.168  1518  4001 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 16:53:44.168  1518  4001 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 16:53:44.168  1518  4001 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 16:53:44.168  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 16:53:44.168  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 16:53:44.168  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 16:53:44.168  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 16:53:44.168  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 16:53:44.168  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 16:53:44.168  1518  4001 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 16:53:44.753  1518  4001 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-12 16:53:44.753  1518  4001 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-12 16:53:44.753  1518  4001 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:53:44.753  1518  4001 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:53:44.776  1518  4001 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 16:53:44.776  1518  4001 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 16:53:44.776  1518  4001 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 16:53:44.776  1518  4001 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 16:53:44.776  1518  4001 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 16:53:44.776  1518  4001 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 16:53:44.776  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 16:53:44.776  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 16:53:44.776  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 16:53:44.776  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 16:53:44.776  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 16:53:44.776  1518  4001 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 16:53:44.776  1518  4001 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 16:53:47.582  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 16:53:47.582  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d9977d added. We now have 4 listener(s)
09-12 16:53:47.583  3921  3970 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 16:53:47.599  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:53:47.600  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d9977d removed from the list
,09-12 16:53:47.600  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 16:53:47.601  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:47.601  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:53:47.605  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 16:53:47.606  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b7bc672 added. We now have 4 listener(s)
,09-12 16:53:47.607  3921  3970 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 16:53:47.611  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:53:47.612  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b7bc672 removed from the list
09-12 16:53:47.612  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:53:47.612  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:53:47.612  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:53:47.615  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 16:53:47.615  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8566ac3 added. We now have 4 listener(s)
,09-12 16:53:47.615  3921  3970 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 16:53:47.623   877  2002 D WifiService: setWifiEnabled: false pid=3921, uid=10000
,09-12 16:53:47.623   877  2002 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 16:53:47.633  2819  2871 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 16:53:47.633  2819  2871 D BluetoothAdapterProperties: Setting state to 13
09-12 16:53:47.633  2819  2871 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 16:53:47.636  2819  2871 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 16:53:47.637  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 16:53:47.639  2819  2871 I BluetoothAdapterState: Entering PendingCommandState
09-12 16:53:47.640  2819  2877 D BluetoothAdapterProperties: Scan Mode:20
09-12 16:53:47.640  2819  2871 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-12 16:53:47.643  2819  2819 D HeadsetService: Received stop request...Stopping profile...
09-12 16:53:47.643  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:47.643  3921  3970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 16:53:47.643  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:47.643  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:47.643  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:47.643  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:47.643  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:53:47.643  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:53:47.643  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 16:53:47.645  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:47.645  3921  3970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 16:53:47.645  3921  3970 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 16:53:47.648  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:47.653  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:47.657  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 16:53:47.657  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:47.657  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:47.657  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:47.657  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:47.657  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:47.657  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:53:47.657  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:53:47.657  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 16:53:47.658  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 16:53:47.658  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 16:53:47.658  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 16:53:47.661  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 16:53:47.661  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:47.661  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:47.661  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:47.661  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:47.661  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:47.661  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:53:47.661  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:53:47.661  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 16:53:47.662   877  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 16:53:47.662  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 16:53:47.662  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 16:53:47.663   877  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-12 16:53:47.663   877  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 16:53:47.664   877  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 16:53:47.666  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:47.670  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:47.675  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:47.678  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:47.680   877  1309 E native  : do suspend true
,09-12 16:53:47.683   877   890 I ActivityManager: Start proc 4018:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-12 16:53:47.684  1367  1380 D BluetoothHeadset: Proxy object disconnected
09-12 16:53:47.684  1367  1367 D HeadsetProfile: Bluetooth service disconnected
09-12 16:53:47.684  1959  2175 D BluetoothHeadset: Proxy object disconnected
,09-12 16:53:47.684  2819  2819 D A2dpService: Received stop request...Stopping profile...
09-12 16:53:47.685   877   877 D BluetoothHeadset: Proxy object disconnected
09-12 16:53:47.685   877   877 D BluetoothHeadset: Proxy object disconnected
,09-12 16:53:47.685   877   877 D BluetoothHeadset: Proxy object disconnected
09-12 16:53:47.686  2819  3012 D A2dpStateMachine: Exit Disconnected: -1
,09-12 16:53:47.688   877   877 D BluetoothA2dp: Proxy object disconnected
,09-12 16:53:47.688  1367  1367 D BluetoothA2dp: Proxy object disconnected
,09-12 16:53:47.688  2819  2819 D BluetoothMapService: onReceive
09-12 16:53:47.688  2819  2819 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 16:53:47.689  2819  2819 D BluetoothMapService: STATE_TURNING_OFF
09-12 16:53:47.689  2819  2819 V BluetoothAdapterState: isTurningOff()=true
09-12 16:53:47.689  2819  2819 V BluetoothAdapterState: isTurningOn()=false
09-12 16:53:47.689  2819  2819 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:53:47.689  2819  2819 V BluetoothAdapterState: isBleTurningOff()=false
09-12 16:53:47.690  2819  2819 D HidService: Received stop request...Stopping profile...
,09-12 16:53:47.690  2819  2819 D HidService: Stopping Bluetooth HidService
09-12 16:53:47.690  1367  1367 D BluetoothInputDevice: Proxy object disconnected
09-12 16:53:47.690  1367  1367 D HidProfile: Bluetooth service disconnected
,09-12 16:53:47.692   877  1855 D DhcpClient: Clearing IP address
,09-12 16:53:47.692   372   875 D CommandListener: Clearing all IP addresses on wlan0
09-12 16:53:47.693  2819  2819 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-12 16:53:47.693  2819  2877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-12 16:53:47.694  2819  3000 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 16:53:47.694  2819  3000 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 16:53:47.694  2819  3000 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 16:53:47.694  2819  2877 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-12 16:53:47.694  2819  2819 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-12 16:53:47.695  2819  2819 D HealthService: Received stop request...Stopping profile...
,09-12 16:53:47.696  2819  2819 V BluetoothAdapterState: isTurningOff()=true
,09-12 16:53:47.696  2819  2819 V BluetoothAdapterState: isTurningOn()=false
,09-12 16:53:47.696  2819  2819 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 16:53:47.696  2819  2819 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 16:53:47.697  1518  2150 V NativeCrypto: Read error: ssl=0xaeb6a600: I/O error during system call, Connection timed out
,09-12 16:53:47.697   372   875 D CommandListener: Setting iface cfg
,09-12 16:53:47.698  2819  2877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-12 16:53:47.698  2819  3000 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 16:53:47.698  2819  3000 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 16:53:47.698  2819  2819 D PanService: Received stop request...Stopping profile...
,09-12 16:53:47.698  2819  3000 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 16:53:47.698  2819  3000 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 16:53:47.698  2819  3000 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 16:53:47.698  2819  3000 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 16:53:47.699  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 16:53:47.699  1367  1367 D PanProfile: Bluetooth service disconnected
,09-12 16:53:47.700  2819  2819 D BluetoothMapService: MAP Service closeService in
,09-12 16:53:47.700  2819  2819 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 16:53:47.700  2819  2819 D ObexServerSockets0: shutdown(block = true)
09-12 16:53:47.700  2819  2819 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-12 16:53:47.700  2819  2819 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 16:53:47.700  2819  3031 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 16:53:47.701   877  1309 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-12 16:53:47.701  2819  3030 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-12 16:53:47.701  2819  2819 I BtOppRfcommListener: stopping Accept Thread
,09-12 16:53:47.701   877  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 16:53:47.701  2819  3614 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-12 16:53:47.701   877  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 16:53:47.701   877  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-12 16:53:47.701   877  1309 E native  : do suspend true
,09-12 16:53:47.701  2819  3614 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 16:53:47.702  2819  3006 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-12 16:53:47.706  2819  2819 V BluetoothAdapterState: isTurningOff()=true
09-12 16:53:47.706  2819  2819 V BluetoothAdapterState: isTurningOn()=false
09-12 16:53:47.706  2819  2819 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 16:53:47.706  2819  2819 V BluetoothAdapterState: isBleTurningOff()=false
09-12 16:53:47.706  2819  2819 D BluetoothMapService: Received stop request...Stopping profile...
09-12 16:53:47.706  2819  2819 D BluetoothMapService: stop()
09-12 16:53:47.707  2819  2819 D BluetoothMapAppObserver: deinitObservers()
,09-12 16:53:47.707  2819  2819 D BluetoothMapAppObserver: removeReceiver()
,09-12 16:53:47.708   877  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-12 16:53:47.709  2819  2819 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 16:53:47.709  2819  2819 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 16:53:47.709  2819  2819 V BluetoothAdapterState: isTurningOff()=true,
09-12 16:53:47.709  2819  2819 V BluetoothAdapterState: isTurningOn()=false
09-12 16:53:47.709  2819  2819 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 16:53:47.709  2819  2819 V BluetoothAdapterState: isBleTurningOff()=false
09-12 16:53:47.709  2819  2819 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-12 16:53:47.709   396   396 E Parcel  : Reading a NULL string not supported here.
09-12 16:53:47.710  2819  2877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 16:53:47.710  2819  2877 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-12 16:53:47.712  2819  2819 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 16:53:47.712  2819  2819 V BluetoothAdapterState: isTurningOff()=true
09-12 16:53:47.712  2819  2819 V BluetoothAdapterState: isTurningOn()=false
09-12 16:53:47.712  2819  2819 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:53:47.712  2819  2819 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 16:53:47.713  2819  2819 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 16:53:47.713  2819  2819 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 16:53:47.714   877  1859 D DhcpClient: Receive thread stopped
,09-12 16:53:47.715  2819  2819 D BluetoothMapService: MAP Service closeService in
09-12 16:53:47.716  2819  2819 V BluetoothAdapterState: isTurningOff()=true
09-12 16:53:47.716  2819  2819 V BluetoothAdapterState: isTurningOn()=false
,09-12 16:53:47.716  2819  2819 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:53:47.716  2819  2819 V BluetoothAdapterState: isBleTurningOff()=false
09-12 16:53:47.717  2819  2871 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 16:53:47.717  2819  2871 D BluetoothAdapterProperties: Setting state to 15
,09-12 16:53:47.717  2819  2871 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 16:53:47.718   877   894 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 16:53:47.718   877   894 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 16:53:47.718  1367  1380 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 16:53:47.718  2819  2871 I BluetoothAdapterState: Entering BleOnState
,09-12 16:53:47.719  1367  1379 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 16:53:47.719  1959  2175 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 16:53:47.719  2819  2819 D BluetoothMapService: cleanup()
09-12 16:53:47.719   877   894 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 16:53:47.719  2819  2819 D BluetoothMapService: MAP Service closeService in
09-12 16:53:47.719   877   894 D BluetoothHeadset: onBluetoothStateChange: up=false,
09-12 16:53:47.720  1367  2174 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 16:53:47.721  1367  1380 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 16:53:47.722  1367  1379 D BluetoothPan: onBluetoothStateChange on: false
09-12 16:53:47.723  1518  2150 V NativeCrypto: SSL shutdown failed: ssl=0xaeb6a600: I/O error during system call, Broken pipe
,09-12 16:53:47.724  1367  1367 D BluetoothMap: Proxy object disconnected
09-12 16:53:47.724  1367  1367 D MapProfile: Bluetooth service disconnected
09-12 16:53:47.725  1367  1380 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 16:53:47.725  2819  2871 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 16:53:47.726  2819  2871 D BluetoothAdapterProperties: Setting state to 16
09-12 16:53:47.726  2819  2871 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-12 16:53:47.727  2819  2871 D BluetoothAdapterProperties: onBleDisable
09-12 16:53:47.727  2819  2871 I BluetoothAdapterState: Entering PendingCommandState
09-12 16:53:47.728  2819  2874 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-12 16:53:47.729  2819  3000 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 16:53:47.729  2819  3000 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 16:53:47.731  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-12 16:53:47.731  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:47.731  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:47.731  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:47.731  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:47.731  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:47.731  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:53:47.731  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:53:47.731  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 16:53:47.732  2819  2877 D BluetoothAdapterProperties: Scan Mode:20
09-12 16:53:47.732  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:47.733  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 16:53:47.734  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:47.734  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:47.734  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:47.734  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:47.734  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:47.734  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:47.734  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:53:47.734  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:53:47.734  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 16:53:47.735  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 16:53:47.735  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 16:53:47.737  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:47.737  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:47.737  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:47.737  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:47.737  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:47.737  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:47.737  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:53:47.737  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:53:47.737  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 16:53:47.738  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:47.738  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 16:53:47.739  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:53:47.740  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:47.741  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:53:47.750  4018  4018 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-12 16:53:47.755   372   875 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-12 16:53:47.759  4018  4018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 16:53:47.766  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 16:53:47.770   877   894 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@93e05b1:true
,09-12 16:53:47.776   372   875 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 16:53:47.776   372   875 D CommandListener: Clearing all IP addresses on wlan0
,09-12 16:53:47.776   877  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-12 16:53:47.777   877  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 16:53:47.778   877  1958 I ActivityManager: Start proc 4035:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-12 16:53:47.780   877   894 D Tethering: MasterInitialState.processMessage what=3
,09-12 16:53:47.784   877  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 16:53:47.787  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:47.788  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:53:47.790  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:53:47.792  3554  3554 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@4b32a8 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-12 16:53:47.793  2060  2060 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-12 16:53:47.801   877  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 16:53:47.805  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 16:53:47.805  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:47.805  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:47.805  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:47.805  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 16:53:47.805  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:47.805  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:53:47.805  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:53:47.805  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 16:53:47.805   877  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 16:53:47.805  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:47.805  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 16:53:47.806  2139  2334 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 16:53:47.807  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:47.807  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:47.807  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:47.807  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:47.807  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 16:53:47.807  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:47.807  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:53:47.807  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:53:47.807  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 16:53:47.807  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:47.808  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 16:53:47.809  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 16:53:47.809  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:47.809  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:47.809  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:47.809  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 16:53:47.809  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:47.809  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:53:47.809  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:53:47.809  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 16:53:47.809  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:47.809  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 16:53:47.818  4018  4018 D LocalBluetoothProfileManager: Adding local MAP profile
,09-12 16:53:47.820  4018  4018 D BluetoothMap: Create BluetoothMap proxy object
09-12 16:53:47.824  4035  4035 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-12 16:53:47.828   372   875 E Netd    : netlink response contains error (No such file or directory)
,09-12 16:53:47.829  4018  4018 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-12 16:53:47.846  4018  4018 D DockEventReceiver: finishStartingService: stopping service
,09-12 16:53:47.856   877  1958 I ActivityManager: Killing 3342:com.google.android.gm/u0a78 (adj 15): empty #17
,09-12 16:53:47.934  2819  2877 I bt_hci  : shut_down
,09-12 16:53:47.934  2819  2882 D bt_hwcfg: hw_epilog_process
,09-12 16:53:47.946  2819  2882 I bt_vendor: low_power_mode_cb
,09-12 16:53:47.972  2819  2882 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 16:53:47.972  2819  2882 I bt_vendor: epilog_cb
,09-12 16:53:47.972  2819  2882 I bt_hci  : epilog_finished_callback
,09-12 16:53:47.978  2819  2877 I bt_hci_h4: hal_close
,09-12 16:53:47.979  2819  2877 I bt_userial_vendor: device fd = 51 close
,09-12 16:53:48.011  4035  4035 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 16:53:48.011  4035  4035 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 16:53:48.011  4035  4035 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 16:53:48.011  4035  4035 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 16:53:48.011  4035  4035 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.r.k.d(PG:583)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 16:53:48.011  4035  4035 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 16:53:48.012  4035  4035 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 16:53:48.012  4035  4035 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 16:53:48.012  4035  4035 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.ActivityThread$H.,handleMessage(ActivityThread.java:1405)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 16:53:48.012  4035  4035 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 16:53:48.018  4018  4018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 16:53:48.029  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 16:53:48.029  4018  4018 D DockEventReceiver: finishStartingService: stopping service
,09-12 16:53:48.035   877  2002 I ActivityManager: Killing 3147:com.google.android.talk/u0a61 (adj 15): empty #17
,09-12 16:53:48.096   877  2002 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver}
09-12 16:53:48.096   877  2002 W BroadcastQueue: android.os.DeadObjectException
09-12 16:53:48.096   877  2002 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 16:53:48.096   877  2002 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-12 16:53:48.096   877  2002 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-12 16:53:48.096   877  2002 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-12 16:53:48.096   877  2002 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-12 16:53:48.096   877  2002 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
09-12 16:53:48.096   877  2002 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-12 16:53:48.096   877  2002 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-12 16:53:48.096   877  2002 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 16:53:48.096   877  2002 W libprocessgroup: failed to open /acct/uid_10061/pid_3147/cgroup.procs: No such file or directory
,09-12 16:53:48.117   877  2002 I ActivityManager: Start proc 4069:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-12 16:53:48.121   877  1958 W ActivityManager: Spurious death for ProcessRecord{f1d5e96 4069:com.google.android.talk/u0a61}, curProc for 3147: null
,09-12 16:53:48.125  2819  2874 D bt_stack_manager: event_shut_down_stack finished.
,09-12 16:53:48.126  2819  2871 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 16:53:48.128  2819  2871 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-12 16:53:48.128  2819  2819 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 16:53:48.129  2819  2819 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 16:53:48.129  2819  2819 D BtGatt.GattService: stop()
09-12 16:53:48.129  2819  2819 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 16:53:48.130  2819  2819 V BluetoothAdapterState: isTurningOff()=false
,09-12 16:53:48.130  2819  2819 V BluetoothAdapterState: isTurningOn()=false
,09-12 16:53:48.130  2819  2819 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:53:48.130  2819  2819 V BluetoothAdapterState: isBleTurningOff()=true
09-12 16:53:48.130  2819  2871 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-12 16:53:48.130  2819  2871 D BluetoothAdapterProperties: Setting state to 10
09-12 16:53:48.130  2819  2871 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 16:53:48.131  2819  2871 I BluetoothAdapterState: Entering OffState
09-12 16:53:48.132   877   894 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-12 16:53:48.147  2819  2819 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-12 16:53:48.147  2819  2819 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 16:53:48.147  2819  2819 I BluetoothServiceJni: cleanupNative: return from cleanup
09-12 16:53:48.148  2819  2874 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 16:53:48.151  2819  2874 D bt_stack_manager: event_clean_up_stack finished.
,09-12 16:53:48.157  2819  2819 I art     : System.exit called, status: 0
,09-12 16:53:48.157  2819  2819 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 16:53:48.176  4069  4069 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-12 16:53:48.231   877  1373 I ActivityManager: Process com.android.bluetooth (pid 2819) has died
,09-12 16:53:48.378  4069  4088 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-12 16:53:48.379  4069  4088 I Babel_SMS: MmsConfig.loadMmsSettings
,09-12 16:53:48.383  4069  4088 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-12 16:53:48.383  4069  4088 I Babel_SMS: MmsConfig.loadFromDatabase
,09-12 16:53:48.421  4069  4088 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-12 16:53:48.421  4069  4088 I Babel_SMS: MmsConfig.loadFromResources
09-12 16:53:48.423  4069  4088 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-12 16:53:48.423  4069  4088 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-12 16:53:48.459  4069  4069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 16:53:48.462  4069  4069 I Babel_Crash: startup - clean
,09-12 16:53:48.488  4069  4069 I Babel_telephony: TeleModule.launchCompleted
,09-12 16:53:48.511   877  1958 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-12 16:53:48.538  4069  4069 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-12 16:53:48.549  4069  4069 W Babel   : BAM#gBA: invalid account id: -1
,09-12 16:53:48.549  4069  4069 W Babel   : BAM#gBA: invalid account id: -1
09-12 16:53:48.549  4069  4069 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-12 16:53:48.565  4069  4095 I Babel   : deleted: false for 0
,09-12 16:53:48.575   877  1958 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-12 16:53:48.591  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 16:53:48.595  1742  1742 D SystemUpdateService: onCreate
,09-12 16:53:48.603  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 16:53:48.610  1742  4097 I SystemUpdateService: active receiver: enabled
,09-12 16:53:48.616  1742  4097 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 16:53:48.620  1742  4097 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 16:53:48.620  1742  4097 I SystemUpdateService: now status is 0 (complete)
09-12 16:53:48.620  1742  4097 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 16:53:48.620  1742  4097 I SystemUpdateService: file has been verified
,09-12 16:53:48.621  1742  4097 I SystemUpdateService: OTA package size = 12249756
,09-12 16:53:48.628  1742  4097 I SystemUpdateService: showing system update notification
,09-12 16:53:48.645  1742  1742 D SystemUpdateService: onDestroy
,09-12 16:53:48.647  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 16:53:48.652  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 16:53:48.654  1742  2299 I iu.UploadsManager: num queued entries: 0,
09-12 16:53:48.654  1742  2299 I iu.UploadsManager: num updated entries: 0
,09-12 16:53:48.656  1742  2299 I iu.SyncManager: NEXT; no task
09-12 16:53:48.656  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 16:53:48.676   877   887 I ActivityManager: Start proc 4099:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-12 16:53:48.696  4069  4069 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 16:53:48.737  4099  4099 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-12 16:53:48.744  4099  4099 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 16:53:48.777  4099  4099 D SprintDMHelper: simOperator: 
,09-12 16:53:48.777  4099  4099 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 16:53:48.804  4069  4069 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-12 16:53:48.808   877  1934 I ActivityManager: Start proc 4111:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-12 16:53:48.814  4069  4069 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 16:53:48.818  4035  4065 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 16:53:48.829  4069  4069 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 16:53:48.833  4069  4069 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 16:53:48.848  4069  4069 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 16:53:48.852   877  3384 I ActivityManager: Killing 3554:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-12 16:53:48.968   877   894 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e0831fc:true
,09-12 16:53:49.055  4069  4069 I vclib   : onServiceConnected
,09-12 16:53:49.089   877  1399 I ActivityManager: Start proc 4126:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-12 16:53:49.091  4069  4125 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-12 16:53:49.094   877  1958 I ActivityManager: Killing 3396:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-12 16:53:49.160  4126  4126 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-12 16:53:49.220  4126  4126 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-12 16:53:49.220  4126  4126 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 16:53:49.220  4126  4126 I GAv4    :   adb logcat -s GAv4
,09-12 16:53:49.236  4126  4126 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 16:53:49.244  4126  4126 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 16:53:49.277  4126  4143 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 16:53:49.382  4126  4126 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-12 16:53:49.416  4126  4126 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-12 16:53:49.428  4126  4126 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 1714-1721)
,09-12 16:53:49.428  4126  4126 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 16:53:49.445  4126  4126 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {40495d8}
,09-12 16:53:49.446  4126  4126 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 16:53:49.446  4126  4126 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 16:53:49.455  4126  4126 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 16:53:49.461  4126  4126 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 16:53:49.481  4126  4126 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 16:53:49.495  4126  4126 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 16:53:49.495  4126  4126 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 16:53:49.495  4126  4126 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 16:53:49.495  4126  4126 I Adreno  : Build Date                       : 10/20/15
09-12 16:53:49.495  4126  4126 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 16:53:49.495  4126  4126 I Adreno  : Local Branch                     : M14
09-12 16:53:49.495  4126  4126 I Adreno  : Remote Branch                    : 
09-12 16:53:49.495  4126  4126 I Adreno  : Remote Branch                    : 
09-12 16:53:49.495  4126  4126 I Adreno  : Reconstruct Branch               : 
,09-12 16:53:49.553  4126  4172 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-12 16:53:49.554  4126  4126 I NSApplication: Starting up...
,09-12 16:53:49.589   877   887 I ActivityManager: Start proc 4177:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-12 16:53:49.591   877   887 I ActivityManager: Killing 3168:android.process.acore/u0a5 (adj 15): empty #17
,09-12 16:53:49.675  4177  4177 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-12 16:53:49.894   877  1934 I ActivityManager: Killing 3779:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-12 16:53:49.963   877  3384 I ActivityManager: Start proc 4191:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-12 16:53:50.052  4191  4191 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-12 16:53:50.111  4191  4191 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-12 16:53:50.127   877  1399 I ActivityManager: Killing 3794:com.android.musicfx/u0a18 (adj 15): empty #17
,09-12 16:53:52.648   877  1958 D WifiService: setWifiEnabled: true pid=3921, uid=10000
09-12 16:53:52.648   877  1958 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 16:53:52.667   877  1309 D WifiConfigStore: Loading config and enabling all networks 
,09-12 16:53:52.669  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:52.670  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:52.670  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:52.670  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:52.670  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:52.670  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:52.670  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:53:52.670  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:53:52.670  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 16:53:52.670  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:52.671  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 16:53:52.675  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 16:53:52.676  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:52.676  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:52.676  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:52.676  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:52.676  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:52.676  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:53:52.676  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:53:52.676  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 16:53:52.676  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 16:53:52.676  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 16:53:52.680  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:52.680  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:52.680  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:52.680  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:52.680  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:52.680  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:52.680  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:53:52.680  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:53:52.680  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 16:53:52.680  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:52.681  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 16:53:52.702   877  1309 D WifiConfigStore: loaded 0 passpoint configs
,09-12 16:53:52.706   877  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-12 16:53:52.707   877  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-12 16:53:52.709   877  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 16:53:52.709   877  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 16:53:52.710   877  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-12 16:53:52.710   877  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 16:53:52.747   372   875 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 16:53:52.747   877  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 16:53:52.749   372   875 D CommandListener: Setting iface cfg
,09-12 16:53:52.757   877  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-12 16:53:52.757   877  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 16:53:52.759   877  1309 E native  : do suspend true
,09-12 16:53:52.767   877  1307 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 16:53:52.774   877  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 16:53:52.776   877  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 16:53:53.807   877  2002 I ActivityManager: Killing 2234:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-12 16:53:53.977   877  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 16:53:54.032   877  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.38 rxSuccessRate=9.38 delta 1000 -> 994
,09-12 16:53:54.037   877  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 16:53:54.037   877  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 16:53:54.058   877  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 16:53:54.134   877  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 16:53:54.136  1462  1462 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 16:53:54.571  1462  1462 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 16:53:54.619  1462  1462 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 16:53:54.621  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 16:53:54.629   877  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 16:53:54.641   877  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-12 16:53:54.641   877  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 16:53:54.641   877  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 16:53:54.659   877  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 16:53:54.669   372   875 D CommandListener: Setting iface cfg
,09-12 16:53:54.670   877  1309 D WifiStateMachine: Start Dhcp Watchdog 2
,09-12 16:53:54.677   877  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 16:53:54.718   877  4226 D DhcpClient: Receive thread started
,09-12 16:53:54.802   877  1309 E native  : do suspend false
,09-12 16:53:54.821   877  1855 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 16:53:54.834   877  4226 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172646, domain null
,09-12 16:53:54.835   877  1855 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172646 seconds
,09-12 16:53:54.838   877  1855 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 16:53:54.851   877  4226 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 16:53:54.852   877  1855 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 16:53:54.857   372   875 D CommandListener: Setting iface cfg
,09-12 16:53:54.869   877  1855 D DhcpClient: Scheduling renewal in 86399s
,09-12 16:53:54.875   877  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 16:53:54.876   877  1309 E native  : do suspend true
,09-12 16:53:54.891   877  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 16:53:54.892   877  1309 D WifiConfigStore: No blacklist allowed without epno enabled
09-12 16:53:54.893   877  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 16:53:54.895   877  1312 D ConnectivityService: Adding iface wlan0 to network 101
,09-12 16:53:54.901   877  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 16:53:54.963   877  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 16:53:54.963   877  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-12 16:53:54.965   877  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-12 16:53:54.967   877  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-12 16:53:54.970   877  1312 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-12 16:53:54.983   877  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 16:53:54.989   877  1312 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-12 16:53:54.989   877  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-12 16:53:54.989   877  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-12 16:53:54.990   877  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 16:53:54.990   877  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-12 16:53:54.990   877  1312 D ConnectivityService:    accepting network in place of null
,09-12 16:53:54.992   877  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 16:53:55.004   877  4225 D NetlinkSocketObserver: NeighborEvent{elapsedMs=177297, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 16:53:55.048   372   875 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 16:53:55.080   877  4224 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-12 16:53:55.109   372   875 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 16:53:55.114   877  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-12 16:53:55.114   877  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 16:53:55.120   877  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-12 16:53:55.123   877   894 D Tethering: MasterInitialState.processMessage what=3
,09-12 16:53:55.138  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 16:53:55.138  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:55.138  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:55.138  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:55.138  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:55.138  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:55.138  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:53:55.138  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:53:55.138  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 16:53:55.138  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 16:53:55.139  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 16:53:55.141  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:55.141  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:55.141  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:55.141  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:55.141  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:55.141  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:55.141  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:53:55.141  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:53:55.141  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 16:53:55.141  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:55.141  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 16:53:55.143  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:55.143  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:55.143  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:55.143  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:55.143  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:55.143  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:55.143  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:53:55.143  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:53:55.143  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 16:53:55.143  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:55.143  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 16:53:55.143  2060  2060 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-12 16:53:55.155  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 16:53:55.159   877  4224 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 14:53:55 GMT], X-Android-Received-Millis=[1473692035158], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473692035137]}
,09-12 16:53:55.162   877  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-12 16:53:55.162   877  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-12 16:53:55.162   877  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 16:53:55.163   877  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 16:53:55.165  1742  1742 D SystemUpdateService: onCreate
,09-12 16:53:55.168  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 16:53:55.176  3877  4238 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 16:53:55.186  1742  4237 I SystemUpdateService: active receiver: enabled
,09-12 16:53:55.193  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 16:53:55.198  1742  4237 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 16:53:55.201  1742  2299 I iu.UploadsManager: num queued entries: 0
,09-12 16:53:55.201  1742  2299 I iu.UploadsManager: num updated entries: 0
,09-12 16:53:55.203  1742  4237 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 16:53:55.203  1742  4237 I SystemUpdateService: now status is 0 (complete)
09-12 16:53:55.203  1742  4237 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 16:53:55.203  1742  4237 I SystemUpdateService: file has been verified
,09-12 16:53:55.203  1742  4237 I SystemUpdateService: OTA package size = 12249756
,09-12 16:53:55.208  1742  2299 I iu.SyncManager: NEXT; no task
,09-12 16:53:55.209  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 16:53:55.211  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 16:53:55.221  4099  4099 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 16:53:55.227  1742  4243 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-12 16:53:55.227  1742  4243 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 16:53:55.229  1742  4243 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 16:53:55.231  4099  4099 D SprintDMHelper: simOperator: 
,09-12 16:53:55.231  4099  4099 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 16:53:55.235  1742  4237 I SystemUpdateService: showing system update notification
,09-12 16:53:55.248  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,09-12 16:53:55.255  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:53:55.269  3877  4245 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 16:53:55.314  1518  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 16:53:55.314  1518  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 16:53:55.314  1518  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 16:53:55.314  1518  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:53:55.358  1518  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 16:53:55.358  1518  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 16:53:55.358  1518  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:53:55.358  1518  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:53:55.375  3877  4245 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 16:53:55.376  3877  4238 E BooksSync: Soft error
09-12 16:53:55.376  3877  4238 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 16:53:55.376  3877  4238 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 16:53:55.376  3877  4238 E BooksSync: Sync error
09-12 16:53:55.376  3877  4238 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 16:53:55.376  3877  4238 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 16:53:55.376  3877  4238 I BooksSync: Finished books sync
,09-12 16:53:55.389   877   889 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 163029, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 16:53:55.403  4069  4246 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 16:53:55.419  1742  1742 D SystemUpdateService: onDestroy
,09-12 16:53:55.425  1518  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 16:53:55.425  1518  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-12 16:53:55.425  1518  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 16:53:55.425  1518  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:53:55.442  1742  4243 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-12 16:53:56.116   877  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-12 16:53:57.655   877  3384 D WifiService: setWifiEnabled: false pid=3921, uid=10000
,09-12 16:53:57.655   877  3384 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 16:53:57.692  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 16:53:57.696   877  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 16:53:57.697   877  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 16:53:57.697   877  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 16:53:57.697   877  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 16:53:57.711   877  1309 E native  : do suspend true
,09-12 16:53:57.730   877  1855 D DhcpClient: Clearing IP address
,09-12 16:53:57.731   372   875 D CommandListener: Clearing all IP addresses on wlan0
,09-12 16:53:57.738  1518  4250 V NativeCrypto: Read error: ssl=0x9a29e400: I/O error during system call, Connection timed out
,09-12 16:53:57.741   372   875 D CommandListener: Setting iface cfg
,09-12 16:53:57.746   877  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-12 16:53:57.747   877  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-12 16:53:57.756   396   396 E Parcel  : Reading a NULL string not supported here.
,09-12 16:53:57.745  1518  4250 V NativeCrypto: SSL shutdown failed: ssl=0x9a29e400: I/O error during system call, Broken pipe
,09-12 16:53:57.756   877  1309 D WifiStateMachine: Start Disconnecting Watchdog 2
09-12 16:53:57.757   877  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 16:53:57.757   877  1309 E native  : do suspend true
,09-12 16:53:57.762   877  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-12 16:53:57.771   877  4226 D DhcpClient: Receive thread stopped
,09-12 16:53:57.799   372   875 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 16:53:57.842   372   875 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 16:53:57.842   372   875 D CommandListener: Clearing all IP addresses on wlan0
09-12 16:53:57.843   877  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-12 16:53:57.843   877  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 16:53:57.846   877   894 D Tethering: MasterInitialState.processMessage what=3
,09-12 16:53:57.856  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 16:53:57.856  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:57.856  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:57.856  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:57.856  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:57.856  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:57.856  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:53:57.856  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:53:57.856  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 16:53:57.856   877  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 16:53:57.856  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 16:53:57.857  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 16:53:57.860  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 16:53:57.861  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:57.861  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:57.861  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:57.861  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:57.861  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:57.861  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:53:57.861  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:53:57.861  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 16:53:57.861  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:57.861  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 16:53:57.864  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:57.864  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:57.864  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:57.864  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:57.864  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:53:57.864  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:57.864  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:53:57.864  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:53:57.864  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 16:53:57.864  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:57.864  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 16:53:57.870  2060  2060 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-12 16:53:57.878  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-12 16:53:57.879   877  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 16:53:57.884  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 16:53:57.885  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:57.885  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:57.885  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:57.885  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 16:53:57.885  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:57.885  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:53:57.885  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:53:57.885  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 16:53:57.885  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:57.885  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 16:53:57.885  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:57.885  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:57.885  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:57.885  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:57.885  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 16:53:57.885  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:57.885  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:53:57.885  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:53:57.885  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 16:53:57.885  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 16:53:57.885  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 16:53:57.886  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:57.886  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:53:57.886  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:53:57.886  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:53:57.886  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 16:53:57.886  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:53:57.886  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:53:57.886  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:53:57.886  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 16:53:57.886  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:53:57.886  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 16:53:57.886   877  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 16:53:57.892  2139  2334 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 16:53:57.895  1742  1742 D SystemUpdateService: onCreate
,09-12 16:53:57.898  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 16:53:57.904  1742  4262 I SystemUpdateService: active receiver: enabled
,09-12 16:53:57.911  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 16:53:57.913  1742  2299 I iu.UploadsManager: num queued entries: 0
,09-12 16:53:57.913  1742  2299 I iu.UploadsManager: num updated entries: 0
,09-12 16:53:57.918  1742  4262 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 16:53:57.919  1742  2299 I iu.SyncManager: NEXT; no task
,09-12 16:53:57.920  1742  4262 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-12 16:53:57.920  1742  4262 I SystemUpdateService: now status is 0 (complete)
09-12 16:53:57.920  1742  4262 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 16:53:57.920  1742  4262 I SystemUpdateService: file has been verified
09-12 16:53:57.920  1742  4262 I SystemUpdateService: OTA package size = 12249756
,09-12 16:53:57.923  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 16:53:57.924  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 16:53:57.926  4099  4099 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 16:53:57.930  4099  4099 D SprintDMHelper: simOperator: 
09-12 16:53:57.930  4099  4099 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 16:53:57.951   372   875 E Netd    : netlink response contains error (No such file or directory)
,09-12 16:53:57.968  1742  4262 I SystemUpdateService: showing system update notification
,09-12 16:53:57.973  4069  4266 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-12 16:53:57.985  1742  1742 D SystemUpdateService: onDestroy
,09-12 16:54:02.698   877   894 I ActivityManager: Start proc 4271:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 16:54:02.833  4271  4271 D AdapterServiceConfig: Adding HeadsetService
,09-12 16:54:02.834  4271  4271 D AdapterServiceConfig: Adding A2dpService
,09-12 16:54:02.835  4271  4271 D AdapterServiceConfig: Adding HidService
09-12 16:54:02.836  4271  4271 D AdapterServiceConfig: Adding HealthService
09-12 16:54:02.836  4271  4271 D AdapterServiceConfig: Adding PanService
09-12 16:54:02.837  4271  4271 D AdapterServiceConfig: Adding GattService
09-12 16:54:02.838  4271  4271 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 16:54:02.860   877   894 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@614137f:true
09-12 16:54:02.860  4271  4271 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 16:54:02.865  4271  4271 I bt_bluedroid: init,
,09-12 16:54:02.866  4271  4283 I BluetoothAdapterState: Entering OffState
,09-12 16:54:02.871  4271  4284 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 16:54:02.871  4271  4284 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 16:54:02.871  4271  4284 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 16:54:02.871  4271  4284 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-12 16:54:02.873  4271  4271 I bt_bluedroid: get_profile_interface socket
,09-12 16:54:02.876  4271  4271 I bt_bluedroid: get_profile_interface sdp
,09-12 16:54:02.880  4271  4282 I bt_bluedroid: config_hci_snoop_log
09-12 16:54:02.881  4271  4287 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-12 16:54:02.882   877   894 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 16:54:02.883  4271  4287 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 16:54:02.892  4271  4283 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 16:54:02.893  4271  4283 D BluetoothAdapterProperties: Setting state to 14
09-12 16:54:02.893  4271  4283 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 16:54:02.896  4271  4283 D BluetoothBondStateMachine: make
,09-12 16:54:02.907  4271  4288 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 16:54:02.913  4271  4271 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 16:54:02.914  4271  4283 I BluetoothAdapterState: Entering PendingCommandState
,09-12 16:54:02.918  4271  4271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
09-12 16:54:02.919  4271  4271 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 16:54:02.920  4271  4271 D BtGatt.GattService: Received start request. Starting profile...
,09-12 16:54:02.920  4271  4271 D BtGatt.GattService: start()
,09-12 16:54:02.920  4271  4271 I bt_bluedroid: get_profile_interface gatt
,09-12 16:54:02.922  4271  4271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
,09-12 16:54:02.922  4271  4271 D BtGatt.AdvertiseManager: advertise manager created
,09-12 16:54:02.934  4271  4271 V BluetoothAdapterState: isTurningOff()=false
,09-12 16:54:02.934  4271  4271 V BluetoothAdapterState: isTurningOn()=false
,09-12 16:54:02.934  4271  4271 V BluetoothAdapterState: isBleTurningOn()=true
,09-12 16:54:02.934  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 16:54:02.935  4271  4283 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-12 16:54:02.935  4271  4283 I bt_bluedroid: enable
,09-12 16:54:02.936  4271  4284 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-12 16:54:02.936  4271  4284 I bt_hci  : start_up
,09-12 16:54:02.946  4271  4284 I bt_vendor: alloc value 0xb3a0a189
,09-12 16:54:02.946  4271  4284 I bt_vendor: init
09-12 16:54:02.946  4271  4284 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 16:54:02.946  4271  4284 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 16:54:02.994   877  1312 D ConnectivityService: handlePromptUnvalidated 101
,09-12 16:54:03.055  4271  4284 D bt_hci  : start_up starting async portion
,09-12 16:54:03.057  4271  4291 I bt_hci  : event_finish_startup
09-12 16:54:03.057  4271  4291 I bt_hci_h4: hal_open
09-12 16:54:03.057  4271  4291 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 16:54:03.075  4271  4291 I bt_userial_vendor: device fd = 51 open
,09-12 16:54:03.098  4271  4291 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 16:54:03.130  4271  4291 D bt_hwcfg: Chipset BCM4354A2
09-12 16:54:03.130  4271  4291 D bt_hwcfg: Target name = [BCM4354A2]
,09-12 16:54:03.131  4271  4291 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 16:54:03.804  4271  4291 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 16:54:03.806  4271  4291 D bt_hwcfg: Settlement delay -- 100 ms
,09-12 16:54:03.806  4271  4291 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 16:54:03.924  4271  4291 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 16:54:03.925  4271  4291 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 16:54:03.953  4271  4291 I bt_hwcfg: vendor lib fwcfg completed
,09-12 16:54:03.953  4271  4291 I bt_vendor: firmware callback
09-12 16:54:03.953  4271  4291 I bt_hci  : firmware_config_callback
,09-12 16:54:03.966  4271  4294 I bt_btu  : btu_task pending for preload complete event
,09-12 16:54:03.966  4271  4294 I bt_btu_task: Bluetooth chip preload is complete
,09-12 16:54:03.967  4271  4294 I bt_btu  : btu_task received preload complete event
,09-12 16:54:03.978  4271  4294 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 16:54:03.978  4271  4294 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 16:54:03.978  4271  4294 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-12 16:54:03.979  4271  4294 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 16:54:03.979  4271  4294 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-12 16:54:03.979  4271  4294 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 16:54:03.979  4271  4294 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 16:54:03.980  4271  4294 I         : BTE_InitTraceLevels -- TRC_BTM
,09-12 16:54:03.980  4271  4294 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 16:54:03.980  4271  4294 I         : BTE_InitTraceLevels -- TRC_PAN
,09-12 16:54:03.980  4271  4294 I         : BTE_InitTraceLevels -- TRC_SDP
,09-12 16:54:03.981  4271  4294 I         : BTE_InitTraceLevels -- TRC_GATT
,09-12 16:54:03.981  4271  4294 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 16:54:03.981  4271  4294 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 16:54:03.981  4271  4294 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 16:54:04.117  4271  4294 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3987d9d
,09-12 16:54:04.117  4271  4294 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3987d9d 
,09-12 16:54:04.140  4271  4287 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 16:54:04.142  4271  4287 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 16:54:04.143  4271  4287 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 16:54:04.146  4271  4287 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 16:54:04.149  4271  4287 D BluetoothAdapterProperties: Scan Mode:20
09-12 16:54:04.151  4271  4287 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 16:54:04.151  4271  4287 D bt_hci  : do_postload posting postload work item
09-12 16:54:04.152  4271  4291 I bt_hci  : event_postload
09-12 16:54:04.152  4271  4291 I bt_vendor: sco_config_cb
09-12 16:54:04.152  4271  4291 I bt_hci  : sco_config_callback postload finished.
,09-12 16:54:04.153  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:54:04.157  4271  4287 D bt_bte_conf: Device ID record 1 : primary
,09-12 16:54:04.157  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:54:04.157  4271  4287 D bt_bte_conf:   vendorId            = 000f
09-12 16:54:04.159  4271  4287 D bt_bte_conf:   vendorIdSource      = 0001
,09-12 16:54:04.159  4271  4291 I bt_vendor: low_power_mode_cb
,09-12 16:54:04.159  4271  4287 D bt_bte_conf:   product             = 1200
09-12 16:54:04.159  4271  4287 D bt_bte_conf:   version             = 1436
09-12 16:54:04.159  4271  4287 D bt_bte_conf:   clientExecutableURL = 
09-12 16:54:04.160  4271  4287 D bt_bte_conf:   serviceDescription  = 
,09-12 16:54:04.160  4271  4287 D bt_bte_conf:   documentationURL    = 
09-12 16:54:04.160  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:54:04.160  4271  4287 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 16:54:04.161  4271  4284 D bt_stack_manager: event_start_up_stack finished
09-12 16:54:04.161  4271  4283 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-12 16:54:04.162  4271  4283 D BluetoothAdapterProperties: Setting state to 15
09-12 16:54:04.162  4271  4283 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 16:54:04.163  4271  4283 I BluetoothAdapterState: Entering BleOnState
,09-12 16:54:04.168  4271  4283 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-12 16:54:04.169  4271  4283 D BluetoothAdapterProperties: Setting state to 11
09-12 16:54:04.169  4271  4283 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 16:54:04.178  4271  4271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
,09-12 16:54:04.180  4271  4271 D HeadsetService: Received start request. Starting profile...
,09-12 16:54:04.183  4271  4271 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-12 16:54:04.183  4271  4271 D HeadsetStateMachine: make
,09-12 16:54:04.192  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:04.195  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:54:04.197  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:54:04.206  4271  4271 D HeadsetStateMachine: max_hf_connections = 1
,09-12 16:54:04.206  4271  4271 I bt_bluedroid: get_profile_interface handsfree
,09-12 16:54:04.206  4271  4287 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 16:54:04.206  4271  4287 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-12 16:54:04.212  4271  4271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
,09-12 16:54:04.213  4271  4271 D A2dpService: Received start request. Starting profile...
,09-12 16:54:04.214  4271  4271 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 16:54:04.215  4271  4271 I bt_bluedroid: get_profile_interface avrcp
09-12 16:54:04.215  4271  4283 I BluetoothAdapterState: Entering PendingCommandState
,09-12 16:54:04.222  4271  4271 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 16:54:04.223  4271  4271 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 16:54:04.223  4271  4271 D A2dpStateMachine: make
,09-12 16:54:04.225  4271  4271 I bt_bluedroid: get_profile_interface a2dp
,09-12 16:54:04.226  4271  4287 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-12 16:54:04.227  4271  4303 D A2dpStateMachine: Enter Disconnected: -2
09-12 16:54:04.229  4271  4271 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 16:54:04.230  4271  4271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
,09-12 16:54:04.234  4018  4018 D BluetoothInputDevice: Proxy object connected
,09-12 16:54:04.234  4271  4271 D HidService: Received start request. Starting profile...
,09-12 16:54:04.235  4271  4271 I bt_bluedroid: get_profile_interface hidhost
,09-12 16:54:04.235  4018  4018 D HidProfile: Bluetooth service connected
,09-12 16:54:04.235  4271  4287 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39693e5
09-12 16:54:04.235  4271  4271 D HidService: setHidService(): set to: null
09-12 16:54:04.235  4271  4287 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-12 16:54:04.238  4271  4271 I BluetoothHealthServiceJni: classInitNative: succeeds
09-12 16:54:04.239  4271  4271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
09-12 16:54:04.239  4271  4271 D HealthService: Received start request. Starting profile...
,09-12 16:54:04.240  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 16:54:04.241  4271  4271 I bt_bluedroid: get_profile_interface health
09-12 16:54:04.242  4271  4271 V BluetoothAdapterState: isTurningOff()=false
09-12 16:54:04.242  4271  4271 V BluetoothAdapterState: isTurningOn()=true
09-12 16:54:04.242  4271  4300 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-12 16:54:04.242  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:54:04.242  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
09-12 16:54:04.245  4271  4271 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 16:54:04.246  4271  4271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
,09-12 16:54:04.248  4271  4271 D PanService: Received start request. Starting profile...
,09-12 16:54:04.248  4271  4271 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-12 16:54:04.248  4271  4271 I bt_bluedroid: get_profile_interface pan
,09-12 16:54:04.249  4271  4287 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 16:54:04.251  4018  4018 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 16:54:04.252  4271  4271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
,09-12 16:54:04.253  4018  4018 D PanProfile: Bluetooth service connected
,09-12 16:54:04.254  4018  4018 D BluetoothMap: Proxy object connected
09-12 16:54:04.254  4271  4271 D BluetoothMapService: Received start request. Starting profile...
09-12 16:54:04.254  4271  4271 D BluetoothMapService: start()
,09-12 16:54:04.255  4018  4018 D MapProfile: Bluetooth service connected
09-12 16:54:04.255  4018  4018 D BluetoothMap: getConnectedDevices()
09-12 16:54:04.257  4018  4018 D BluetoothMap: Bluetooth is Not enabled
09-12 16:54:04.259  4271  4271 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-12 16:54:04.261  4271  4271 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-12 16:54:04.261  4271  4271 D BluetoothMapAppObserver: createReceiver()
09-12 16:54:04.262  4271  4271 D BluetoothMapAppObserver: initObservers()
09-12 16:54:04.262  4271  4271 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 16:54:04.276  4271  4271 V BluetoothAdapterState: isTurningOff()=false
,09-12 16:54:04.276  4271  4271 V BluetoothAdapterState: isTurningOn()=true
09-12 16:54:04.276  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:54:04.276  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
09-12 16:54:04.276  4271  4271 V BluetoothAdapterState: isTurningOff()=false
09-12 16:54:04.276  4271  4271 V BluetoothAdapterState: isTurningOn()=true
,09-12 16:54:04.276  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:54:04.276  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 16:54:04.278  4271  4271 V BluetoothAdapterState: isTurningOff()=false
09-12 16:54:04.278  4271  4271 V BluetoothAdapterState: isTurningOn()=true
,09-12 16:54:04.278  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:54:04.278  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 16:54:04.278  4271  4271 V BluetoothAdapterState: isTurningOff()=false
09-12 16:54:04.278  4271  4271 V BluetoothAdapterState: isTurningOn()=true
09-12 16:54:04.278  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 16:54:04.278  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
09-12 16:54:04.278  4271  4271 V BluetoothAdapterState: isTurningOff()=false
09-12 16:54:04.278  4271  4271 V BluetoothAdapterState: isTurningOn()=true
09-12 16:54:04.278  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:54:04.278  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 16:54:04.279  4271  4283 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-12 16:54:04.279  4271  4283 D BluetoothAdapterProperties: ScanMode =  20
09-12 16:54:04.279  4271  4283 D BluetoothAdapterProperties: State =  11
09-12 16:54:04.279  4271  4283 D BluetoothAdapterProperties: Setting state to 12
09-12 16:54:04.279  4271  4283 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 16:54:04.280  4271  4283 I BluetoothAdapterState: Entering OnState
09-12 16:54:04.280  4018  4029 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 16:54:04.282  4271  4287 D BluetoothAdapterProperties: Scan Mode:21
09-12 16:54:04.282  4271  4287 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 16:54:04.282   877   894 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 16:54:04.282   877   894 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 16:54:04.283  1367  2174 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 16:54:04.286   877   877 D BluetoothA2dp: Proxy object connected
09-12 16:54:04.286  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:54:04.286  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:04.286  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:04.286  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 16:54:04.286  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:54:04.286  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:54:04.286  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:54:04.286  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 16:54:04.287  1367  1367 D BluetoothA2dp: Proxy object connected
09-12 16:54:04.287  4018  4030 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 16:54:04.288  1367  1380 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 16:54:04.289  1367  1367 D BluetoothInputDevice: Proxy object connected
09-12 16:54:04.289  1959  2110 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 16:54:04.289  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 16:54:04.289  1367  1367 D HidProfile: Bluetooth service connected
09-12 16:54:04.289   877   894 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 16:54:04.290   877   894 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 16:54:04.290  1367  2174 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 16:54:04.291  4018  4029 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 16:54:04.292  1367  1380 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 16:54:04.292  4018  4030 D BluetoothPan: onBluetoothStateChange on: true
09-12 16:54:04.292  1367  1379 D BluetoothPan: onBluetoothStateChange on: true
09-12 16:54:04.293  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:54:04.293  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:04.293  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:04.293  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 16:54:04.293  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:54:04.293  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:54:04.293  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:54:04.293  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 16:54:04.294  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 16:54:04.294  1367  1367 D PanProfile: Bluetooth service connected
,09-12 16:54:04.294  1367  1380 D BluetoothMap: onBluetoothStateChange: up=true
09-12 16:54:04.295  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 16:54:04.296  1367  1367 D BluetoothMap: Proxy object connected
09-12 16:54:04.296  1367  1367 D MapProfile: Bluetooth service connected
09-12 16:54:04.296  4271  4271 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 16:54:04.296  1367  1367 D BluetoothMap: getConnectedDevices()
09-12 16:54:04.297  4271  4271 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-12 16:54:04.299   877   877 I Telecom : BluetoothPhoneService: queryPhoneState
09-12 16:54:04.299  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:54:04.299  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:04.299  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:04.299  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 16:54:04.299  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:54:04.299  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:54:04.299  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:54:04.299  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 16:54:04.299  4271  4271 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 16:54:04.300  4018  4018 D LocalBluetoothProfileManager: Adding local A2DP profile
09-12 16:54:04.301  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 16:54:04.301  4271  4271 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 16:54:04.302  4271  4271 D ObexServerSockets: Succeed to create listening sockets 
,09-12 16:54:04.302  4271  4271 D ObexServerSockets0: startAccept()
09-12 16:54:04.302  4271  4271 D ObexServerSockets0: prepareForNewConnect()
09-12 16:54:04.303  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:04.304  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:04.304  4271  4271 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 16:54:04.304  4271  4271 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 16:54:04.305  4271  4271 D BluetoothMapService: onReceive
09-12 16:54:04.305  4271  4271 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-12 16:54:04.305  4271  4271 D BluetoothMapService: STATE_ON
09-12 16:54:04.305  4018  4018 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-12 16:54:04.305  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:04.306  4271  4311 D ObexServerSockets0: Accepting socket connection...
09-12 16:54:04.306  4271  4310 D ObexServerSockets0: Accepting socket connection...
,09-12 16:54:04.311  4018  4018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 16:54:04.313  4018  4018 D BluetoothA2dp: Proxy object connected
,09-12 16:54:04.316  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 16:54:04.318  4018  4018 D DockEventReceiver: finishStartingService: stopping service
,09-12 16:54:04.324  1367  1367 D BluetoothPbap: Proxy object connected
,09-12 16:54:04.325  1367  1367 D PbapServerProfile: Bluetooth service connected
09-12 16:54:04.325  4018  4018 D BluetoothPbap: Proxy object connected
09-12 16:54:04.325  4018  4018 D PbapServerProfile: Bluetooth service connected
,09-12 16:54:04.330  4271  4271 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 16:54:04.330  4271  4271 D ObexServerSockets0: prepareForNewConnect()
09-12 16:54:04.332  4271  4315 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 16:54:04.346  4271  4319 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 16:54:04.346  4271  4319 I BtOppRfcommListener: Accept thread started.
,09-12 16:54:04.390  1959  2107 D BluetoothHeadset: Proxy object connected
,09-12 16:54:04.390   877   894 D BluetoothHeadset: Proxy object connected
09-12 16:54:04.390   877   894 D BluetoothHeadset: Proxy object connected
09-12 16:54:04.390  1367  1379 D BluetoothHeadset: Proxy object connected
,09-12 16:54:04.390  1367  1367 D HeadsetProfile: Bluetooth service connected
,09-12 16:54:04.391  1959  1975 D BluetoothHeadset: Proxy object connected
09-12 16:54:04.392   877   877 D BluetoothHeadset: Proxy object connected,
09-12 16:54:04.392   877   877 D BluetoothHeadset: Proxy object connected
09-12 16:54:04.392   877   877 D BluetoothHeadset: Proxy object connected
09-12 16:54:04.392  1367  2174 D BluetoothHeadset: Proxy object connected
,09-12 16:54:04.394  1367  1367 D HeadsetProfile: Bluetooth service connected
,09-12 16:54:04.408  4018  4029 D BluetoothHeadset: Proxy object connected
09-12 16:54:04.409  4018  4018 D HeadsetProfile: Bluetooth service connected
,09-12 16:54:06.681  1518  2172 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 16:54:06.843  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:54:06.854  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:54:06.858  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:54:06.913  1518  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 16:54:06.914  1518  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 16:54:06.914  1518  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 16:54:06.914  1518  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:54:06.959  3646  3646 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 16:54:06.959  3646  3646 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 16:54:06.960  3646  3646 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-12 16:54:07.675  4271  4283 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 16:54:07.675  4271  4283 D BluetoothAdapterProperties: Setting state to 13
09-12 16:54:07.675  4271  4283 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 16:54:07.677  4271  4283 D BluetoothAdapterProperties: onBluetoothDisable()
,09-12 16:54:07.682  4271  4283 I BluetoothAdapterState: Entering PendingCommandState
,09-12 16:54:07.685  4271  4287 D BluetoothAdapterProperties: Scan Mode:20
,09-12 16:54:07.686  4271  4283 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-12 16:54:07.690  4271  4271 D BluetoothMapService: onReceive
09-12 16:54:07.691  4271  4271 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-12 16:54:07.691  4271  4271 D BluetoothMapService: STATE_TURNING_OFF
09-12 16:54:07.692  4271  4271 D BluetoothMapService: MAP Service closeService in
,09-12 16:54:07.692  4271  4271 D BluetoothMapMasInstance0: MAP Service shutdown
,09-12 16:54:07.692  4271  4271 D ObexServerSockets0: shutdown(block = true)
,09-12 16:54:07.693  4271  4310 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-12 16:54:07.697  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 16:54:07.697  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:54:07.697  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:07.697  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:07.697  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 16:54:07.697  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:54:07.697  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:54:07.697  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:54:07.697  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 16:54:07.697  4271  4271 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 16:54:07.698  4271  4296 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-12 16:54:07.698  4271  4311 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 16:54:07.699  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:54:07.699  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 16:54:07.699  4271  4271 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-12 16:54:07.700  4271  4271 I BtOppRfcommListener: stopping Accept Thread
09-12 16:54:07.701  4271  4319 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 16:54:07.703  4271  4319 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 16:54:07.703  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:54:07.703  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:54:07.703  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:07.703  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:07.703  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 16:54:07.703  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:54:07.703  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:54:07.703  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:54:07.703  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 16:54:07.705  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:54:07.705  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 16:54:07.707  4271  4271 D HeadsetService: Received stop request...Stopping profile...
09-12 16:54:07.708  4018  4018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 16:54:07.710  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:54:07.711  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:54:07.711  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:07.711  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:07.711  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 16:54:07.711  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 16:54:07.711  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:54:07.711  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:54:07.711  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 16:54:07.713  3921  3921 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 16:54:07.713  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 16:54:07.713  4018  4029 D BluetoothHeadset: Proxy object disconnected
09-12 16:54:07.714  1367  1380 D BluetoothHeadset: Proxy object disconnected
09-12 16:54:07.715  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:54:07.715  1959  1972 D BluetoothHeadset: Proxy object disconnected
09-12 16:54:07.716   877   877 D BluetoothHeadset: Proxy object disconnected
09-12 16:54:07.716   877   877 D BluetoothHeadset: Proxy object disconnected
09-12 16:54:07.716  1367  1367 D HeadsetProfile: Bluetooth service disconnected
09-12 16:54:07.716   877   877 D BluetoothHeadset: Proxy object disconnected
09-12 16:54:07.718  4271  4271 D A2dpService: Received stop request...Stopping profile...
09-12 16:54:07.718  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:07.719  4271  4303 D A2dpStateMachine: Exit Disconnected: -1
09-12 16:54:07.720  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:07.720   877   877 D BluetoothA2dp: Proxy object disconnected
09-12 16:54:07.720  1367  1367 D BluetoothA2dp: Proxy object disconnected
,09-12 16:54:07.721  4271  4271 V BluetoothAdapterState: isTurningOff()=true
09-12 16:54:07.721  4271  4271 V BluetoothAdapterState: isTurningOn()=false
09-12 16:54:07.721  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:54:07.721  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
09-12 16:54:07.721  4271  4271 D HidService: Received stop request...Stopping profile...
09-12 16:54:07.721  4271  4271 D HidService: Stopping Bluetooth HidService
09-12 16:54:07.722  1367  1367 D BluetoothInputDevice: Proxy object disconnected
09-12 16:54:07.722  1367  1367 D HidProfile: Bluetooth service disconnected
09-12 16:54:07.724  4271  4271 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 16:54:07.724  4271  4271 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 16:54:07.724  4271  4287 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 16:54:07.725  4271  4294 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 16:54:07.725  4271  4294 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 16:54:07.725  4271  4294 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 16:54:07.725  4271  4287 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-12 16:54:07.726  4271  4271 D HealthService: Received stop request...Stopping profile...
09-12 16:54:07.728  4271  4271 D PanService: Received stop request...Stopping profile...
,09-12 16:54:07.731  4018  4018 D DockEventReceiver: finishStartingService: stopping service
,09-12 16:54:07.731  4271  4271 D BluetoothMapService: Received stop request...Stopping profile...
09-12 16:54:07.731  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 16:54:07.731  1367  1367 D PanProfile: Bluetooth service disconnected
09-12 16:54:07.731  4271  4271 D BluetoothMapService: stop()
,09-12 16:54:07.732  4018  4018 D HeadsetProfile: Bluetooth service disconnected
,09-12 16:54:07.732  4018  4018 D BluetoothA2dp: Proxy object disconnected
09-12 16:54:07.732  4018  4018 D BluetoothInputDevice: Proxy object disconnected
09-12 16:54:07.732  4018  4018 D HidProfile: Bluetooth service disconnected
09-12 16:54:07.733  4018  4018 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 16:54:07.733  4018  4018 D PanProfile: Bluetooth service disconnected
09-12 16:54:07.733  4271  4271 D BluetoothMapAppObserver: deinitObservers()
09-12 16:54:07.733  4271  4271 D BluetoothMapAppObserver: removeReceiver()
,09-12 16:54:07.737  1367  1367 D BluetoothMap: Proxy object disconnected
,09-12 16:54:07.737  1367  1367 D MapProfile: Bluetooth service disconnected
09-12 16:54:07.737  4018  4018 D BluetoothMap: Proxy object disconnected
09-12 16:54:07.737  4018  4018 D MapProfile: Bluetooth service disconnected
,09-12 16:54:07.741  4271  4271 V BluetoothAdapterState: isTurningOff()=true
09-12 16:54:07.741  4271  4271 V BluetoothAdapterState: isTurningOn()=false
09-12 16:54:07.741  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:54:07.742  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 16:54:07.742  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 16:54:07.745  4271  4294 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 16:54:07.745  4271  4294 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 16:54:07.746  4271  4294 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 16:54:07.746  4271  4271 V BluetoothAdapterState: isTurningOff()=true
09-12 16:54:07.746  4271  4271 V BluetoothAdapterState: isTurningOn()=false
09-12 16:54:07.746  4271  4294 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 16:54:07.746  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:54:07.746  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
09-12 16:54:07.746  4271  4294 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 16:54:07.746  4271  4271 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 16:54:07.746  4271  4271 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 16:54:07.746  4271  4294 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 16:54:07.747  4271  4271 V BluetoothAdapterState: isTurningOff()=true
09-12 16:54:07.747  4271  4271 V BluetoothAdapterState: isTurningOn()=false
09-12 16:54:07.747  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:54:07.747  4271  4287 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 16:54:07.747  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
09-12 16:54:07.747  4271  4271 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 16:54:07.747  4271  4287 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 16:54:07.748  4271  4287 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 16:54:07.748  4271  4271 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 16:54:07.748  4271  4271 V BluetoothAdapterState: isTurningOff()=true
09-12 16:54:07.748  4271  4271 V BluetoothAdapterState: isTurningOn()=false
09-12 16:54:07.748  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:54:07.748  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
09-12 16:54:07.748  4271  4271 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 16:54:07.749  4271  4271 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-12 16:54:07.750  4271  4271 D BluetoothMapService: MAP Service closeService in
09-12 16:54:07.750  4271  4271 V BluetoothAdapterState: isTurningOff()=true
09-12 16:54:07.750  4271  4271 V BluetoothAdapterState: isTurningOn()=false
,09-12 16:54:07.750  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 16:54:07.750  4271  4271 V BluetoothAdapterState: isBleTurningOff()=false
09-12 16:54:07.751  4271  4271 D BluetoothMapService: cleanup()
09-12 16:54:07.751  4271  4271 D BluetoothMapService: MAP Service closeService in
,09-12 16:54:07.751  4271  4283 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 16:54:07.752  4271  4283 D BluetoothAdapterProperties: Setting state to 15
,09-12 16:54:07.752  4271  4283 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-12 16:54:07.752  4018  4030 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 16:54:07.753  4018  4029 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 16:54:07.753   877   894 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 16:54:07.753  4018  4030 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 16:54:07.754   877   894 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 16:54:07.754  1367  1367 D BluetoothPbap: Proxy object disconnected
09-12 16:54:07.754  1367  1367 D PbapServerProfile: Bluetooth service disconnected
09-12 16:54:07.754  1367  2174 D BluetoothA2dp: onBluetoothStateChange: up=false,
09-12 16:54:07.755  4018  4029 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 16:54:07.755  4271  4283 I BluetoothAdapterState: Entering BleOnState
09-12 16:54:07.756  1367  1380 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 16:54:07.757  1959  2175 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 16:54:07.759   877   894 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 16:54:07.759   877   894 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 16:54:07.759  1367  1379 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 16:54:07.760  4018  4030 D BluetoothMap: onBluetoothStateChange: up=false
09-12 16:54:07.760  1367  2174 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 16:54:07.760  4018  4029 D BluetoothPan: onBluetoothStateChange on: false
,09-12 16:54:07.761  1367  1380 D BluetoothPan: onBluetoothStateChange on: false
09-12 16:54:07.761  1367  1379 D BluetoothMap: onBluetoothStateChange: up=false
09-12 16:54:07.762  4271  4283 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 16:54:07.762  4271  4283 D BluetoothAdapterProperties: Setting state to 16
,09-12 16:54:07.762  4271  4283 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 16:54:07.762  4271  4283 D BluetoothAdapterProperties: onBleDisable
09-12 16:54:07.762  4271  4283 I BluetoothAdapterState: Entering PendingCommandState
09-12 16:54:07.763  4271  4284 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-12 16:54:07.763  4271  4287 D BluetoothAdapterProperties: Scan Mode:20
09-12 16:54:07.763  4271  4294 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 16:54:07.763  4271  4294 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 16:54:07.766  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:07.767  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-12 16:54:07.768  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:07.769  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-12 16:54:07.770  4018  4018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 16:54:07.770  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:07.771  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:54:07.774  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 16:54:07.782  4018  4018 D DockEventReceiver: finishStartingService: stopping service
,09-12 16:54:07.965  4271  4287 I bt_hci  : shut_down
,09-12 16:54:07.978  4271  4291 I bt_vendor: low_power_mode_cb
,09-12 16:54:07.978  4271  4291 D bt_hwcfg: hw_epilog_process
,09-12 16:54:07.996  4271  4291 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 16:54:07.997  4271  4291 I bt_vendor: epilog_cb
,09-12 16:54:07.997  4271  4291 I bt_hci  : epilog_finished_callback
,09-12 16:54:08.008  4271  4287 I bt_hci_h4: hal_close
,09-12 16:54:08.009  4271  4287 I bt_userial_vendor: device fd = 51 close
,09-12 16:54:08.139  4271  4284 D bt_stack_manager: event_shut_down_stack finished.
,09-12 16:54:08.140  4271  4283 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 16:54:08.147  4271  4283 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-12 16:54:08.147  4271  4271 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 16:54:08.149  4271  4271 D BtGatt.GattService: Received stop request...Stopping profile...
,09-12 16:54:08.149  4271  4271 D BtGatt.GattService: stop()
,09-12 16:54:08.150  4271  4271 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 16:54:08.155  4271  4271 V BluetoothAdapterState: isTurningOff()=false
,09-12 16:54:08.155  4271  4271 V BluetoothAdapterState: isTurningOn()=false
,09-12 16:54:08.156  4271  4271 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 16:54:08.156  4271  4271 V BluetoothAdapterState: isBleTurningOff()=true
,09-12 16:54:08.157  4271  4283 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-12 16:54:08.157  4271  4283 D BluetoothAdapterProperties: Setting state to 10
09-12 16:54:08.158  4271  4283 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 16:54:08.160  4271  4283 I BluetoothAdapterState: Entering OffState
,09-12 16:54:08.161   877   894 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-12 16:54:08.190  4271  4271 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-12 16:54:08.190  4271  4271 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-12 16:54:08.192  4271  4284 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 16:54:08.200  4271  4284 D bt_stack_manager: event_clean_up_stack finished.
,09-12 16:54:08.200  4271  4271 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 16:54:08.202  4271  4271 I art     : System.exit called, status: 0
,09-12 16:54:08.202  4271  4271 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 16:54:08.265   877  1399 I ActivityManager: Process com.android.bluetooth (pid 4271) has died
,09-12 16:54:12.675  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:54:12.675  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:54:12.679  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:54:12.680  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8566ac3 removed from the list
09-12 16:54:12.680  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 16:54:12.680  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:12.681  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:54:12.684  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 16:54:12.684  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ed2e79 added. We now have 4 listener(s)
09-12 16:54:12.685  3921  3970 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 16:54:12.686  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:54:12.687  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ed2e79 removed from the list
,09-12 16:54:12.687  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:54:12.687  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:12.688  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:54:12.690  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 16:54:12.690  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bbd7be added. We now have 4 listener(s)
09-12 16:54:12.690  3921  3970 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 16:54:17.704  3921  3970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:54:17.753   877   894 I ActivityManager: Start proc 4329:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 16:54:17.882  4329  4329 D AdapterServiceConfig: Adding HeadsetService
,09-12 16:54:17.883  4329  4329 D AdapterServiceConfig: Adding A2dpService
09-12 16:54:17.883  4329  4329 D AdapterServiceConfig: Adding HidService
09-12 16:54:17.883  4329  4329 D AdapterServiceConfig: Adding HealthService
,09-12 16:54:17.883  4329  4329 D AdapterServiceConfig: Adding PanService
09-12 16:54:17.883  4329  4329 D AdapterServiceConfig: Adding GattService
09-12 16:54:17.883  4329  4329 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 16:54:17.898   877   894 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28e2dc2:true
09-12 16:54:17.899  4329  4329 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 16:54:17.904  4329  4329 I bt_bluedroid: init
,09-12 16:54:17.905  4329  4341 I BluetoothAdapterState: Entering OffState
,09-12 16:54:17.907  4329  4342 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-12 16:54:17.907  4329  4342 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 16:54:17.907  4329  4342 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 16:54:17.907  4329  4342 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-12 16:54:17.908  4329  4329 I bt_bluedroid: get_profile_interface socket
,09-12 16:54:17.910  4329  4329 I bt_bluedroid: get_profile_interface sdp
,09-12 16:54:17.914  4329  4340 I bt_bluedroid: config_hci_snoop_log
,09-12 16:54:17.914  4329  4345 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 16:54:17.917   877   894 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 16:54:17.917  4329  4345 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 16:54:17.931  4329  4341 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 16:54:17.931  4329  4341 D BluetoothAdapterProperties: Setting state to 14
09-12 16:54:17.932  4329  4341 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 16:54:17.936  4329  4341 D BluetoothBondStateMachine: make
,09-12 16:54:17.940  4329  4346 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 16:54:17.947  4329  4341 I BluetoothAdapterState: Entering PendingCommandState
,09-12 16:54:17.948  4329  4329 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 16:54:17.953  4329  4329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
,09-12 16:54:17.954  4329  4329 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 16:54:17.955  4329  4329 D BtGatt.GattService: Received start request. Starting profile...
09-12 16:54:17.956  4329  4329 D BtGatt.GattService: start()
,09-12 16:54:17.956  4329  4329 I bt_bluedroid: get_profile_interface gatt
,09-12 16:54:17.957  4329  4329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
,09-12 16:54:17.957  4329  4329 D BtGatt.AdvertiseManager: advertise manager created
,09-12 16:54:17.970  4329  4329 V BluetoothAdapterState: isTurningOff()=false
,09-12 16:54:17.971  4329  4329 V BluetoothAdapterState: isTurningOn()=false
,09-12 16:54:17.971  4329  4329 V BluetoothAdapterState: isBleTurningOn()=true
09-12 16:54:17.971  4329  4329 V BluetoothAdapterState: isBleTurningOff()=false
09-12 16:54:17.972  4329  4341 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 16:54:17.973  4329  4341 I bt_bluedroid: enable
,09-12 16:54:17.973  4329  4342 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-12 16:54:17.974  4329  4342 I bt_hci  : start_up
,09-12 16:54:17.988  4329  4342 I bt_vendor: alloc value 0xb3a0a189
09-12 16:54:17.989  4329  4342 I bt_vendor: init
,09-12 16:54:17.989  4329  4342 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 16:54:17.989  4329  4342 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 16:54:18.097  4329  4342 D bt_hci  : start_up starting async portion
,09-12 16:54:18.097  4329  4349 I bt_hci  : event_finish_startup
09-12 16:54:18.097  4329  4349 I bt_hci_h4: hal_open
09-12 16:54:18.098  4329  4349 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 16:54:18.108  4329  4349 I bt_userial_vendor: device fd = 51 open
,09-12 16:54:18.139  4329  4349 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 16:54:18.171  4329  4349 D bt_hwcfg: Chipset BCM4354A2
09-12 16:54:18.171  4329  4349 D bt_hwcfg: Target name = [BCM4354A2]
,09-12 16:54:18.171  4329  4349 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 16:54:19.054  4329  4349 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 16:54:19.056  4329  4349 D bt_hwcfg: Settlement delay -- 100 ms
09-12 16:54:19.056  4329  4349 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 16:54:19.174  4329  4349 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 16:54:19.176  4329  4349 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 16:54:19.203  4329  4349 I bt_hwcfg: vendor lib fwcfg completed
,09-12 16:54:19.204  4329  4349 I bt_vendor: firmware callback
09-12 16:54:19.204  4329  4349 I bt_hci  : firmware_config_callback
,09-12 16:54:19.217  4329  4353 I bt_btu  : btu_task pending for preload complete event
,09-12 16:54:19.217  4329  4353 I bt_btu_task: Bluetooth chip preload is complete
09-12 16:54:19.217  4329  4353 I bt_btu  : btu_task received preload complete event
,09-12 16:54:19.229  4329  4353 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 16:54:19.229  4329  4353 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 16:54:19.229  4329  4353 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-12 16:54:19.230  4329  4353 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-12 16:54:19.230  4329  4353 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-12 16:54:19.230  4329  4353 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 16:54:19.231  4329  4353 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 16:54:19.231  4329  4353 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 16:54:19.231  4329  4353 I         : BTE_InitTraceLevels -- TRC_GAP
,09-12 16:54:19.232  4329  4353 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 16:54:19.232  4329  4353 I         : BTE_InitTraceLevels -- TRC_SDP
,09-12 16:54:19.232  4329  4353 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 16:54:19.232  4329  4353 I         : BTE_InitTraceLevels -- TRC_SMP
,09-12 16:54:19.233  4329  4353 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 16:54:19.233  4329  4353 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 16:54:19.375  4329  4353 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3987d9d
,09-12 16:54:19.375  4329  4353 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3987d9d 
,09-12 16:54:19.388  4329  4345 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 16:54:19.392  4329  4345 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 16:54:19.393  4329  4345 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 16:54:19.396  4329  4345 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 16:54:19.401  4329  4345 D BluetoothAdapterProperties: Scan Mode:20
,09-12 16:54:19.402  4329  4345 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 16:54:19.403  4329  4345 D bt_hci  : do_postload posting postload work item
09-12 16:54:19.403  4329  4349 I bt_hci  : event_postload
09-12 16:54:19.403  4329  4349 I bt_vendor: sco_config_cb
09-12 16:54:19.403  4329  4349 I bt_hci  : sco_config_callback postload finished.
09-12 16:54:19.406  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:54:19.409  4329  4345 D bt_bte_conf: Device ID record 1 : primary
09-12 16:54:19.409  4329  4345 D bt_bte_conf:   vendorId            = 000f
09-12 16:54:19.409  4329  4345 D bt_bte_conf:   vendorIdSource      = 0001
09-12 16:54:19.410  4329  4345 D bt_bte_conf:   product             = 1200
09-12 16:54:19.410  4329  4345 D bt_bte_conf:   version             = 1436
09-12 16:54:19.410  4329  4345 D bt_bte_conf:   clientExecutableURL = 
,09-12 16:54:19.410  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:19.410  4329  4345 D bt_bte_conf:   serviceDescription  = 
09-12 16:54:19.411  4329  4349 I bt_vendor: low_power_mode_cb
09-12 16:54:19.411  4329  4345 D bt_bte_conf:   documentationURL    = 
09-12 16:54:19.411  4329  4345 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 16:54:19.411  4329  4342 D bt_stack_manager: event_start_up_stack finished
09-12 16:54:19.412  4329  4341 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-12 16:54:19.413  4329  4341 D BluetoothAdapterProperties: Setting state to 15
,09-12 16:54:19.414  4329  4341 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-12 16:54:19.415  4329  4341 I BluetoothAdapterState: Entering BleOnState
,09-12 16:54:19.420  4329  4341 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-12 16:54:19.420  4329  4341 D BluetoothAdapterProperties: Setting state to 11
09-12 16:54:19.420  4329  4341 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-12 16:54:19.430  4329  4329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
09-12 16:54:19.431  4329  4329 D HeadsetService: Received start request. Starting profile...
09-12 16:54:19.435  4329  4329 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 16:54:19.435  4329  4329 D HeadsetStateMachine: make
09-12 16:54:19.442  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:19.443  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:54:19.446  4329  4329 D HeadsetStateMachine: max_hf_connections = 1
,09-12 16:54:19.446  4329  4329 I bt_bluedroid: get_profile_interface handsfree
09-12 16:54:19.447  4329  4345 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-12 16:54:19.447  4329  4345 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-12 16:54:19.448  4329  4341 I BluetoothAdapterState: Entering PendingCommandState
,09-12 16:54:19.452  4329  4329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
,09-12 16:54:19.453  4329  4329 D A2dpService: Received start request. Starting profile...
09-12 16:54:19.453  4329  4329 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 16:54:19.453  4329  4329 I bt_bluedroid: get_profile_interface avrcp
,09-12 16:54:19.459  4329  4329 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 16:54:19.459  4329  4329 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 16:54:19.459  4329  4329 D A2dpStateMachine: make
,09-12 16:54:19.460  4329  4329 I bt_bluedroid: get_profile_interface a2dp
09-12 16:54:19.461  4329  4345 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 16:54:19.465  4329  4362 D A2dpStateMachine: Enter Disconnected: -2
,09-12 16:54:19.466  4329  4329 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 16:54:19.466  4329  4329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
,09-12 16:54:19.467  4329  4329 D HidService: Received start request. Starting profile...
09-12 16:54:19.467  4329  4329 I bt_bluedroid: get_profile_interface hidhost
09-12 16:54:19.467  4329  4329 D HidService: setHidService(): set to: null
09-12 16:54:19.467  4329  4345 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39693e5
09-12 16:54:19.468  4329  4329 I BluetoothHealthServiceJni: classInitNative: succeeds
09-12 16:54:19.468  4329  4345 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-12 16:54:19.468  4329  4329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
09-12 16:54:19.469  4329  4329 D HealthService: Received start request. Starting profile...
,09-12 16:54:19.470  4329  4329 I bt_bluedroid: get_profile_interface health
,09-12 16:54:19.472  4329  4329 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 16:54:19.472  4329  4329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
09-12 16:54:19.473  4329  4329 D PanService: Received start request. Starting profile...
09-12 16:54:19.473  4329  4329 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-12 16:54:19.473  4329  4329 I bt_bluedroid: get_profile_interface pan
09-12 16:54:19.474  4329  4345 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 16:54:19.476  4329  4329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
,09-12 16:54:19.477  4329  4329 D BluetoothMapService: Received start request. Starting profile...
09-12 16:54:19.477  4329  4329 D BluetoothMapService: start()
,09-12 16:54:19.480  4329  4329 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-12 16:54:19.480  4329  4329 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 16:54:19.480  4329  4329 D BluetoothMapAppObserver: createReceiver()
,09-12 16:54:19.482  4329  4329 D BluetoothMapAppObserver: initObservers()
,09-12 16:54:19.482  4329  4329 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 16:54:19.491  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 16:54:19.492  4329  4329 V BluetoothAdapterState: isTurningOff()=false
09-12 16:54:19.492  4329  4329 V BluetoothAdapterState: isTurningOn()=true
09-12 16:54:19.492  4329  4329 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:54:19.492  4329  4329 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 16:54:19.494  4329  4329 V BluetoothAdapterState: isTurningOff()=false
09-12 16:54:19.494  4329  4329 V BluetoothAdapterState: isTurningOn()=true
09-12 16:54:19.494  4329  4329 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:54:19.494  4329  4329 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 16:54:19.494  4329  4360 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 16:54:19.494  4329  4329 V BluetoothAdapterState: isTurningOff()=false
09-12 16:54:19.494  4329  4329 V BluetoothAdapterState: isTurningOn()=true
09-12 16:54:19.494  4329  4329 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:54:19.494  4329  4329 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 16:54:19.495  4329  4329 V BluetoothAdapterState: isTurningOff()=false
,09-12 16:54:19.495  4329  4329 V BluetoothAdapterState: isTurningOn()=true
,09-12 16:54:19.495  4329  4329 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:54:19.495  4329  4329 V BluetoothAdapterState: isBleTurningOff()=false
09-12 16:54:19.495  4329  4329 V BluetoothAdapterState: isTurningOff()=false
09-12 16:54:19.495  4329  4329 V BluetoothAdapterState: isTurningOn()=true
,09-12 16:54:19.495  4329  4329 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:54:19.495  4329  4329 V BluetoothAdapterState: isBleTurningOff()=false
09-12 16:54:19.496  4329  4329 V BluetoothAdapterState: isTurningOff()=false
09-12 16:54:19.496  4329  4329 V BluetoothAdapterState: isTurningOn()=true
09-12 16:54:19.496  4329  4329 V BluetoothAdapterState: isBleTurningOn()=false
09-12 16:54:19.496  4329  4329 V BluetoothAdapterState: isBleTurningOff()=false
09-12 16:54:19.496  4329  4341 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 16:54:19.496  4329  4341 D BluetoothAdapterProperties: ScanMode =  20
,09-12 16:54:19.496  4329  4341 D BluetoothAdapterProperties: State =  11
09-12 16:54:19.497  4329  4345 D BluetoothAdapterProperties: Scan Mode:21
09-12 16:54:19.497  4329  4345 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 16:54:19.497  4329  4341 D BluetoothAdapterProperties: Setting state to 12
09-12 16:54:19.497  4329  4341 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 16:54:19.498  4329  4341 I BluetoothAdapterState: Entering OnState
09-12 16:54:19.498  4018  4030 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 16:54:19.501  4018  4029 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 16:54:19.501  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:54:19.501  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:19.501  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:19.501  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 16:54:19.501  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:54:19.501  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:54:19.501  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:54:19.501  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 16:54:19.502   877   894 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 16:54:19.502  4018  4030 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 16:54:19.503  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 16:54:19.505   877   894 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 16:54:19.506   877   877 D BluetoothA2dp: Proxy object connected
09-12 16:54:19.506  1367  1379 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 16:54:19.506  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:54:19.506  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:19.506  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:19.506  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 16:54:19.506  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:54:19.506  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:54:19.506  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:54:19.506  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 16:54:19.508  1367  1367 D BluetoothA2dp: Proxy object connected
,09-12 16:54:19.508  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 16:54:19.509  4018  4030 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 16:54:19.510  4329  4329 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 16:54:19.511  4018  4018 D BluetoothA2dp: Proxy object connected
09-12 16:54:19.511  1367  1380 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 16:54:19.511  4329  4329 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-12 16:54:19.514  4329  4329 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 16:54:19.514  1959  1972 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 16:54:19.515   877   894 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 16:54:19.515   877   894 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 16:54:19.515  1367  2174 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 16:54:19.516  4329  4329 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 16:54:19.517  4329  4329 D ObexServerSockets: Succeed to create listening sockets 
09-12 16:54:19.517  4018  4029 D BluetoothMap: onBluetoothStateChange: up=true
09-12 16:54:19.517  4329  4329 D ObexServerSockets0: startAccept()
,09-12 16:54:19.517  4329  4329 D ObexServerSockets0: prepareForNewConnect()
09-12 16:54:19.519  1367  1379 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 16:54:19.519  4018  4030 D BluetoothPan: onBluetoothStateChange on: true
09-12 16:54:19.519  4329  4329 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 16:54:19.520  4329  4329 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-12 16:54:19.520  4329  4368 D ObexServerSockets0: Accepting socket connection...
09-12 16:54:19.521  4329  4369 D ObexServerSockets0: Accepting socket connection...
09-12 16:54:19.522  1367  1367 D BluetoothInputDevice: Proxy object connected
,09-12 16:54:19.522  1367  1367 D HidProfile: Bluetooth service connected
09-12 16:54:19.523  1367  2174 D BluetoothPan: onBluetoothStateChange on: true
09-12 16:54:19.524  4018  4018 D BluetoothInputDevice: Proxy object connected
09-12 16:54:19.525  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 16:54:19.525  1367  1367 D PanProfile: Bluetooth service connected
,09-12 16:54:19.525  1367  1380 D BluetoothMap: onBluetoothStateChange: up=true
09-12 16:54:19.524  4018  4018 D HidProfile: Bluetooth service connected
,09-12 16:54:19.527  1367  1367 D BluetoothMap: Proxy object connected
09-12 16:54:19.527  1367  1367 D MapProfile: Bluetooth service connected
09-12 16:54:19.527  1367  1367 D BluetoothMap: getConnectedDevices()
,09-12 16:54:19.528  4018  4018 D BluetoothMap: Proxy object connected
,09-12 16:54:19.528  4018  4018 D MapProfile: Bluetooth service connected
09-12 16:54:19.528  4018  4018 D BluetoothMap: getConnectedDevices()
,09-12 16:54:19.528   877   877 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 16:54:19.530  4329  4329 D BluetoothMapService: onReceive
,09-12 16:54:19.530  4329  4329 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-12 16:54:19.530  4329  4329 D BluetoothMapService: STATE_ON
,09-12 16:54:19.531  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:19.532  4018  4018 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 16:54:19.532  4018  4018 D PanProfile: Bluetooth service connected
,09-12 16:54:19.533  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:54:19.537  4018  4018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 16:54:19.541  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 16:54:19.543  4018  4018 D DockEventReceiver: finishStartingService: stopping service
,09-12 16:54:19.547  4018  4018 D BluetoothPbap: Proxy object connected
09-12 16:54:19.547  4018  4018 D PbapServerProfile: Bluetooth service connected
,09-12 16:54:19.549  4329  4373 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 16:54:19.554  1367  1367 D BluetoothPbap: Proxy object connected
,09-12 16:54:19.554  1367  1367 D PbapServerProfile: Bluetooth service connected
,09-12 16:54:19.563  4329  4329 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 16:54:19.563  4329  4329 D ObexServerSockets0: prepareForNewConnect()
,09-12 16:54:19.567  4329  4379 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 16:54:19.568  4329  4379 I BtOppRfcommListener: Accept thread started.
,09-12 16:54:19.604  4018  4029 D BluetoothHeadset: Proxy object connected
,09-12 16:54:19.605  4018  4018 D HeadsetProfile: Bluetooth service connected
09-12 16:54:19.605  1367  2174 D BluetoothHeadset: Proxy object connected
09-12 16:54:19.605  1367  1367 D HeadsetProfile: Bluetooth service connected
,09-12 16:54:19.606  1959  2175 D BluetoothHeadset: Proxy object connected
09-12 16:54:19.607   877   877 D BluetoothHeadset: Proxy object connected
,09-12 16:54:19.607   877   877 D BluetoothHeadset: Proxy object connected
09-12 16:54:19.607   877   877 D BluetoothHeadset: Proxy object connected
,09-12 16:54:19.615  1959  2110 D BluetoothHeadset: Proxy object connected
,09-12 16:54:19.616   877   894 D BluetoothHeadset: Proxy object connected
09-12 16:54:19.616   877   894 D BluetoothHeadset: Proxy object connected
,09-12 16:54:19.619  1367  1379 D BluetoothHeadset: Proxy object connected
,09-12 16:54:19.619  1367  1367 D HeadsetProfile: Bluetooth service connected
,09-12 16:54:22.725  3921  3970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:54:22.725  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:22.725  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:22.725  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 16:54:22.725  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:54:22.725  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:54:22.725  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:54:22.725  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 16:54:22.732  3921  3970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 16:54:22.733  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:54:22.734  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bbd7be removed from the list
09-12 16:54:22.734  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 16:54:22.734  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:22.735  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:54:22.738  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 16:54:22.738  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@daaf01f added. We now have 4 listener(s)
09-12 16:54:22.738  3921  3970 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 16:54:22.742   877  1399 D WifiService: setWifiEnabled: false pid=3921, uid=10000
,09-12 16:54:22.742   877  1399 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 16:54:27.755  3921  3970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:54:27.756   877  3384 D WifiService: setWifiEnabled: true pid=3921, uid=10000
09-12 16:54:27.757   877  3384 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 16:54:27.770   877  1309 D WifiConfigStore: Loading config and enabling all networks 
,09-12 16:54:27.788  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:54:27.788  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:27.788  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:27.788  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:54:27.788  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:54:27.788  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:54:27.788  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:54:27.788  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 16:54:27.795  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 16:54:27.805  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:54:27.805  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:27.805  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:27.805  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:54:27.805  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:54:27.805  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 16:54:27.805  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 16:54:27.805  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 16:54:27.808   877  1309 D WifiConfigStore: loaded 0 passpoint configs
,09-12 16:54:27.809   877  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 16:54:27.810   877  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-12 16:54:27.810  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 16:54:27.811   877  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 16:54:27.811   877  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 16:54:27.811   877  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-12 16:54:27.811   877  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 16:54:27.825   877  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 16:54:27.825   372   875 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 16:54:27.828   372   875 D CommandListener: Setting iface cfg
,09-12 16:54:27.877   877  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-12 16:54:27.877   877  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 16:54:27.884   877  1309 E native  : do suspend true
,09-12 16:54:27.899   877  1307 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 16:54:27.900   877  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 16:54:27.919   877  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 16:54:29.128   877  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 16:54:29.266   877  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.25 rxSuccessRate=10.88 delta 1000 -> 994
,09-12 16:54:29.267   877  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 16:54:29.267   877  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 16:54:29.281   877  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 16:54:29.325   877  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 16:54:29.327  1462  1462 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 16:54:29.774  1462  1462 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 16:54:29.823  1462  1462 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 16:54:29.824  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
09-12 16:54:29.829   877  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 16:54:29.844   877  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 16:54:29.846   877  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 16:54:29.846   877  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 16:54:29.865   877  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 16:54:29.878   372   875 D CommandListener: Setting iface cfg
09-12 16:54:29.878   877  1309 D WifiStateMachine: Start Dhcp Watchdog 3
,09-12 16:54:29.889   877  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 16:54:29.909   877  4387 D DhcpClient: Receive thread started
,09-12 16:54:30.003   877  1309 E native  : do suspend false
,09-12 16:54:30.029   877  1855 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 16:54:30.044   877  4387 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-12 16:54:30.045   877  1855 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-12 16:54:30.049   877  1855 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 16:54:30.066   877  4387 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 16:54:30.067   877  1855 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 16:54:30.072   372   875 D CommandListener: Setting iface cfg
,09-12 16:54:30.084   877  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 16:54:30.085   877  1855 D DhcpClient: Scheduling renewal in 86399s
09-12 16:54:30.088   877  1309 E native  : do suspend true
,09-12 16:54:30.111   877  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 16:54:30.113   877  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 16:54:30.115   877  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 16:54:30.118   877  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 16:54:30.119   877  1312 D ConnectivityService: Adding iface wlan0 to network 102
,09-12 16:54:30.158   877  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 16:54:30.159   877  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-12 16:54:30.160   877  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-12 16:54:30.161   877  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-12 16:54:30.162   877  1312 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-12 16:54:30.170   877  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 16:54:30.175   877  1312 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-12 16:54:30.175   877  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-12 16:54:30.176   877  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-12 16:54:30.176   877  1312 D ConnectivityService:    accepting network in place of null
09-12 16:54:30.176   877  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-12 16:54:30.177   877  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 16:54:30.177   877  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 16:54:30.184   877  4386 D NetlinkSocketObserver: NeighborEvent{elapsedMs=212477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 16:54:30.224   372   875 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 16:54:30.255   877  4385 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-12 16:54:30.282   372   875 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 16:54:30.287   877  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-12 16:54:30.287   877  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 16:54:30.288   877  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-12 16:54:30.293   877   894 D Tethering: MasterInitialState.processMessage what=3
,09-12 16:54:30.318  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:54:30.318  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:30.318  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:30.318  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:54:30.318  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:54:30.318  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:54:30.318  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:54:30.318  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 16:54:30.320  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 16:54:30.326  2060  2060 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-12 16:54:30.326  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:54:30.326  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:30.326  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:30.326  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:54:30.326  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:54:30.326  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:54:30.326  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:54:30.326  3921  3921 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 16:54:30.329  3921  3921 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 16:54:30.332  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 16:54:30.340  1742  1742 D SystemUpdateService: onCreate
,09-12 16:54:30.345  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 16:54:30.363  1742  4396 I SystemUpdateService: active receiver: enabled
,09-12 16:54:30.368  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 16:54:30.370  1742  2299 I iu.UploadsManager: num queued entries: 0
09-12 16:54:30.370  1742  2299 I iu.UploadsManager: num updated entries: 0
,09-12 16:54:30.375  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 16:54:30.377  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 16:54:30.378  1742  4396 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 16:54:30.378  1742  2299 I iu.SyncManager: NEXT; no task
,09-12 16:54:30.384  4099  4099 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 16:54:30.389  1742  4398 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-12 16:54:30.389  1742  4398 W BaseAppContext: Using Auth Proxy for data requests.
09-12 16:54:30.391  4099  4099 D SprintDMHelper: simOperator: 
09-12 16:54:30.391  4099  4099 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-12 16:54:30.394  1742  4398 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
09-12 16:54:30.406   877  4385 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 14:54:30 GMT], X-Android-Received-Millis=[1473692070405], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473692070381]}
09-12 16:54:30.407   877  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-12 16:54:30.407   877  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed,
09-12 16:54:30.407   877  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-12 16:54:30.408   877  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 16:54:30.419  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:54:30.420  1742  4396 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-12 16:54:30.420  1742  4396 I SystemUpdateService: now status is 0 (complete)
09-12 16:54:30.420  1742  4396 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 16:54:30.420  1742  4396 I SystemUpdateService: file has been verified
,09-12 16:54:30.420  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:54:30.422  1742  4396 I SystemUpdateService: OTA package size = 12249756
,09-12 16:54:30.429  3877  4402 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 16:54:30.461  1518  2089 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 16:54:30.461  1518  2089 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-12 16:54:30.461  1518  2089 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 16:54:30.461  1518  2089 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:54:30.466  1742  4396 I SystemUpdateService: showing system update notification
,09-12 16:54:30.473  3877  4407 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 16:54:30.505  1518  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 16:54:30.506  1518  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 16:54:30.506  1518  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 16:54:30.506  1518  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:54:30.553  4069  4401 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 16:54:30.556  1518  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 16:54:30.556  1518  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 16:54:30.557  1518  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 16:54:30.557  1518  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:54:30.598  3877  4407 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 16:54:30.599  3877  4402 E BooksSync: Soft error
09-12 16:54:30.599  3877  4402 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 16:54:30.599  3877  4402 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 16:54:30.599  3877  4402 E BooksSync: Sync error
09-12 16:54:30.599  3877  4402 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 16:54:30.599  3877  4402 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 16:54:30.599  3877  4402 I BooksSync: Finished books sync
,09-12 16:54:30.606  1742  4398 E MDM     : [183] SitrepService.a: Error sending sitrep.
,09-12 16:54:30.627   877   889 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 208610, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 16:54:30.633  1742  1742 D SystemUpdateService: onDestroy
,09-12 16:54:30.831  1877  1993 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-12 16:54:30.831  1877  1993 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-12 16:54:30.878  1518  1518 I ConfigService: onCreate
,09-12 16:54:31.289   877  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-12 16:54:32.783  3921  3970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 16:54:32.783  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:32.783  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:32.783  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:54:32.783  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:54:32.783  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:54:32.783  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:54:32.783  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 16:54:32.790  3921  3970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 16:54:32.791  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:54:32.792  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@daaf01f removed from the list
09-12 16:54:32.792  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:54:32.792  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:54:32.793  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:54:32.805  3921  4411 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-12 16:54:32.805  3921  4411 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 16:54:35.813  3921  4411 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-12 16:54:35.815  3921  4413 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-12 16:54:35.816  3921  4413 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-12 16:54:35.816  3921  4411 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-12 16:54:35.817  3921  4413 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 16:54:35.817  3921  4411 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 16:54:35.819  3921  4413 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 16:54:35.819  3921  4411 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 16:54:35.822  3921  4415 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 449, name: IncomingSocketThread/Sender)
09-12 16:54:35.823  3921  4411 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-12 16:54:35.823  3921  4413 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-12 16:54:35.825  3921  4416 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 450, name: OutgoingSocketThread/Sender)
09-12 16:54:35.828  3921  4417 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 452, name: OutgoingSocketThread/Receiver)
09-12 16:54:35.828  3921  4418 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 451, name: IncomingSocketThread/Receiver)
09-12 16:54:35.828  3921  4418 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 451, thread name: IncomingSocketThread/Receiver)
09-12 16:54:35.829  3921  4418 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-12 16:54:35.829  3921  4418 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 451, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-12 16:54:35.829  3921  4417 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 452, thread name: OutgoingSocketThread/Receiver)
09-12 16:54:35.829  3921  4417 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-12 16:54:35.829  3921  4417 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 452, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-12 16:54:35.959  1518  1518 I ConfigService: onDestroy
,09-12 16:54:38.183   877  1312 D ConnectivityService: handlePromptUnvalidated 102
,09-12 16:54:38.812  3921  3970 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-12 16:54:38.814  3921  3970 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 16:54:38.823  3921  3970 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ff23ada Bundle[{}]
,09-12 16:54:38.823  3921  3970 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 16:54:38.824  3921  3970 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-12 16:54:38.824  3921  3970 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-12 16:54:38.825  3921  3970 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 16:54:38.825  3921  3970 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-12 16:54:38.826  3921  3970 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 16:54:38.830  3921  3970 I System.out: Running OutgoingSocketThread
,09-12 16:54:38.833  3921  4419 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-12 16:54:38.833  3921  4419 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 16:54:41.842  3921  4420 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-12 16:54:41.843  3921  4420 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-12 16:54:41.843  3921  4420 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 16:54:41.844  3921  4419 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-12 16:54:41.844  3921  4419 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-12 16:54:41.844  3921  4420 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 16:54:41.845  3921  4419 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 16:54:41.848  3921  4422 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: IncomingSocketThread/Sender)
,09-12 16:54:41.849  3921  4420 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-12 16:54:41.853  3921  4423 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 462, name: IncomingSocketThread/Receiver)
09-12 16:54:41.854  3921  4419 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 16:54:41.854  3921  4423 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 462, thread name: IncomingSocketThread/Receiver)
09-12 16:54:41.854  3921  4423 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-12 16:54:41.855  3921  4423 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 462, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-12 16:54:41.855  3921  4419 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-12 16:54:41.859  3921  4424 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 463, name: OutgoingSocketThread/Sender)
,09-12 16:54:41.861  3921  4425 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 464, name: OutgoingSocketThread/Receiver)
09-12 16:54:41.861  3921  4425 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 464, thread name: OutgoingSocketThread/Receiver)
,09-12 16:54:41.861  3921  4425 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-12 16:54:41.861  3921  4425 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 464, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-12 16:54:44.845  3921  3970 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 473)
,09-12 16:54:44.847  3921  3970 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-12 16:54:44.848  3921  3970 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 474)
,09-12 16:54:44.856  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 16:54:44.857  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@debdf6c added. We now have 3 listener(s)
,09-12 16:54:44.865  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 16:54:44.865  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 16:54:44.866  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 16:54:44.866  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 16:54:44.866  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5093935 added. We now have 4 listener(s)
09-12 16:54:44.866  3921  3970 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 16:54:44.867  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 16:54:44.869  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 16:54:44.882  3921  3970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 16:54:44.882  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:44.882  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:44.882  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:54:44.882  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:54:44.882  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:54:44.882  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:54:44.882  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 16:54:44.888  3921  3970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 16:54:44.888  3921  3970 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 16:54:44.889  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 16:54:44.890  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:54:44.890  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 16:54:44.890  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:54:44.890  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:44.891  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 16:54:44.891  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 16:54:44.891  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@debdf6c removed from the list
09-12 16:54:44.891  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:54:44.892  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5093935 removed from the list
09-12 16:54:44.892  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:54:44.895  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:44.896  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:54:44.896  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:54:44.897  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:44.897  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:54:44.899  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 16:54:44.899  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:54:44.899  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:54:44.899  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5093935 not in the list
09-12 16:54:44.899  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:44.899  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:54:44.900  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:54:44.900  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:54:44.900  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:54:44.900  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5093935 not in the list
,09-12 16:54:44.900  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:54:44.900  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:44.900  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:54:44.900  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@debdf6c not in the list
09-12 16:54:44.901  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 16:54:44.901  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e986f3b added. We now have 3 listener(s)
09-12 16:54:44.903  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 16:54:44.903  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 16:54:44.903  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 16:54:44.903  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 16:54:44.903  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d8658 added. We now have 4 listener(s)
09-12 16:54:44.904  3921  3970 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 16:54:44.904  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 16:54:44.906  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 16:54:44.912  3921  3970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 16:54:44.912  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:44.912  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:44.912  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:54:44.912  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:54:44.912  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:54:44.912  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:54:44.912  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 16:54:44.916  3921  3970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 16:54:44.916  3921  3970 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 16:54:44.917  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 16:54:44.918  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 16:54:44.918  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 16:54:44.918  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 16:54:44.918  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 16:54:44.920  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:44.922  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:54:44.925  3921  3970 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 16:54:44.926  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 16:54:44.937  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 16:54:44.939  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 16:54:44.939  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 16:54:44.947  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 16:54:44.947  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 16:54:44.948  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 16:54:44.949  3921  3970 D BluetoothAdapter: STATE_ON
,09-12 16:54:44.960  4329  4339 D BtGatt.GattService: registerClient() - UUID=96edd733-5c9c-4473-8391-02b57c8196b4
,09-12 16:54:44.963  4329  4345 D BtGatt.GattService: onClientRegistered() - UUID=96edd733-5c9c-4473-8391-02b57c8196b4, clientIf=5
,09-12 16:54:44.964  3921  3932 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 16:54:44.967  4329  4340 D BtGatt.GattService: start scan with filters
,09-12 16:54:44.976  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 16:54:44.977  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 16:54:44.977  4329  4348 D BtGatt.ScanManager: handling starting scan
,09-12 16:54:44.977  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 16:54:44.977  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 16:54:44.982  4329  4348 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@892efce
,09-12 16:54:44.986  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 16:54:44.986  3921  3921 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 16:54:44.987  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 16:54:44.992  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 16:54:45.002  4329  4345 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 16:54:45.002  3921  3970 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 16:54:45.002  4329  4345 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 16:54:45.002  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 16:54:45.002  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 16:54:45.003  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:45.003  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 16:54:45.003  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 16:54:45.003  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 16:54:45.004  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 16:54:45.004  4329  4348 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 16:54:45.004  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 16:54:45.004  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 16:54:45.005  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 16:54:45.007  3921  3970 D BluetoothAdapter: STATE_ON
09-12 16:54:45.009  4329  4340 D BtGatt.GattService: stopScan() - queue size =1
,09-12 16:54:45.010  4329  4371 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 16:54:45.011  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 16:54:45.012  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 16:54:45.012  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 16:54:45.013  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 16:54:45.013  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 16:54:45.016  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 16:54:45.016  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 16:54:45.016  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 16:54:45.016  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 16:54:45.018  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 16:54:45.021  3921  3921 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 16:54:45.021  3921  3921 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 16:54:45.021  3921  3921 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 16:54:45.025  4329  4345 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 16:54:45.025  4329  4345 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:54:45.026  4329  4348 D BtGatt.ScanManager: Starting BLE batch scan
09-12 16:54:45.026  4329  4348 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 16:54:45.043  4329  4345 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 16:54:45.043  4329  4345 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:54:45.053  4329  4345 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 16:54:45.053  4329  4345 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:54:45.063  4329  4345 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 16:54:45.064  4329  4345 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:54:45.064  4329  4348 D BtGatt.ScanManager: stopping BLe Batch
,09-12 16:54:45.077  4329  4345 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 16:54:45.077  4329  4345 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:54:45.077  4329  4348 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 16:54:45.089  4329  4345 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 16:54:45.089  4329  4345 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:54:45.523  3921  3921 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 16:54:45.523  3921  3921 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 16:54:45.524  3921  3921 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 16:54:48.022  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 16:54:48.023  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:54:48.023  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 16:54:48.025  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 16:54:48.025  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 16:54:48.025  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 16:54:48.026  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 16:54:48.026  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e986f3b removed from the list
09-12 16:54:48.026  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:54:48.027  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d8658 removed from the list
09-12 16:54:48.027  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:54:48.027  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:54:48.029  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:48.029  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:54:48.033  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:54:48.033  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:54:48.033  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:54:48.034  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d8658 not in the list
,09-12 16:54:48.034  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:48.034  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:54:48.038  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 16:54:48.038  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:54:48.038  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:54:48.039  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d8658 not in the list
,09-12 16:54:48.039  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:54:48.039  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:48.040  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:54:48.040  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e986f3b not in the list
,09-12 16:54:48.042  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 16:54:48.042  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e459ed added. We now have 3 listener(s)
,09-12 16:54:48.044  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 16:54:48.044  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 16:54:48.045  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 16:54:48.045  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 16:54:48.045  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eeb022 added. We now have 4 listener(s)
09-12 16:54:48.045  3921  3970 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 16:54:48.046  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 16:54:48.048  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 16:54:48.053  3921  3970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 16:54:48.053  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:48.053  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:48.053  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:54:48.053  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:54:48.053  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:54:48.053  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:54:48.053  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 16:54:48.055  3921  3970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 16:54:48.055  3921  3970 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 16:54:48.055  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 16:54:48.057  3921  3970 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-12 16:54:48.057  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-12 16:54:48.057  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 16:54:48.057  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-12 16:54:48.057  3921  3970 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-12 16:54:48.057  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 16:54:48.058  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:48.060  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 16:54:48.060  3921  3970 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 16:54:48.060  3921  3970 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-12 16:54:48.061  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 16:54:48.061  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-12 16:54:48.061  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 16:54:48.061  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 16:54:48.061  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:48.061  3921  3921 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 16:54:48.063  3921  4426 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 16:54:48.064  3921  3970 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 16:54:48.064  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 16:54:48.068  3921  4426 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-12 16:54:48.070  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 16:54:48.070  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 16:54:48.071  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 16:54:48.073  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-12 16:54:48.073  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 16:54:48.073  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-12 16:54:48.075  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-12 16:54:48.075  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 16:54:48.075  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-12 16:54:48.076  3921  3970 D BluetoothAdapter: STATE_ON
,09-12 16:54:48.079  4329  4339 D BtGatt.GattService: registerClient() - UUID=56b19f5e-d2a4-485a-aa16-cb49e89fdd22
,09-12 16:54:48.080  4329  4345 D BtGatt.GattService: onClientRegistered() - UUID=56b19f5e-d2a4-485a-aa16-cb49e89fdd22, clientIf=5
,09-12 16:54:48.080  3921  3932 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-12 16:54:48.082  4329  4347 D BtGatt.AdvertiseManager: message : 0
,09-12 16:54:48.085  4329  4347 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 16:54:48.104  4329  4345 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-12 16:54:48.117  4329  4345 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-12 16:54:48.118  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-12 16:54:48.119  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 16:54:48.122  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 16:54:48.124  3921  3921 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 16:54:48.125  3921  3921 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-12 16:54:48.125  3921  3921 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-12 16:54:48.125  3921  3921 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-12 16:54:48.125  3921  3921 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-12 16:54:48.125  3921  3921 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-12 16:54:48.131  3921  3921 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 16:54:48.131  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 16:54:48.131  3921  3970 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-12 16:54:48.132  3921  3921 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 16:54:48.633  3921  3921 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-12 16:54:51.133  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 16:54:51.133  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-12 16:54:51.133  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 16:54:51.134  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-12 16:54:51.134  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-12 16:54:51.135  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 16:54:51.136  3921  4426 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-12 16:54:51.136  3921  4426 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 16:54:51.136  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 16:54:51.136  3921  4426 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-12 16:54:51.136  3921  3970 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 16:54:51.137  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 16:54:51.137  3921  3921 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 16:54:51.138  3921  3921 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 16:54:51.137  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 16:54:51.139  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 16:54:51.139  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 16:54:51.140  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 16:54:51.142  3921  3970 D BluetoothAdapter: STATE_ON
09-12 16:54:51.143  3921  3970 D BluetoothLeScanner: could not find callback wrapper
09-12 16:54:51.143  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 16:54:51.143  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-12 16:54:51.146  4329  4347 D BtGatt.AdvertiseManager: message : 1
09-12 16:54:51.148  4329  4347 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-12 16:54:51.157  4329  4345 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-12 16:54:51.157  4329  4345 D BtGatt.GattService: Client app is not null!
,09-12 16:54:51.158  4329  4367 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 16:54:51.159  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 16:54:51.159  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-12 16:54:51.159  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-12 16:54:51.160  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-12 16:54:51.160  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-12 16:54:51.161  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
09-12 16:54:51.161  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 16:54:51.161  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 16:54:51.162  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 16:54:51.164  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 16:54:51.164  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:51.164  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 16:54:51.164  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
09-12 16:54:51.164  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e459ed removed from the list
09-12 16:54:51.164  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:54:51.164  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eeb022 removed from the list
09-12 16:54:51.165  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 16:54:51.165  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:54:51.165  3921  3921 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 16:54:51.165  3921  3921 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 16:54:51.165  3921  3921 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 16:54:51.165  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:51.166  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:54:51.167  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:54:51.167  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:54:51.167  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:54:51.167  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eeb022 not in the list
,09-12 16:54:51.168  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:51.168  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:54:51.169  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:54:51.170  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:54:51.170  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 16:54:51.170  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eeb022 not in the list
09-12 16:54:51.170  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:54:51.171  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:51.171  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:54:51.171  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e459ed not in the list
,09-12 16:54:51.173  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 16:54:51.173  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a761f0f added. We now have 3 listener(s)
,09-12 16:54:51.179  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 16:54:51.180  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 16:54:51.180  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 16:54:51.180  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 16:54:51.181  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65bfb9c added. We now have 4 listener(s)
09-12 16:54:51.181  3921  3970 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 16:54:51.182  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 16:54:51.187  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 16:54:51.194  3921  3970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 16:54:51.194  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:51.194  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:51.194  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:54:51.194  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:54:51.194  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:54:51.194  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:54:51.194  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 16:54:51.197  3921  3970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 16:54:51.198  3921  3970 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 16:54:51.199  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 16:54:51.199  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 16:54:51.199  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 16:54:51.199  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 16:54:51.199  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 16:54:51.202  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:51.203  3921  3970 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 16:54:51.203  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 16:54:51.206  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 16:54:51.213  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 16:54:51.214  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 16:54:51.214  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 16:54:51.220  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 16:54:51.220  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 16:54:51.221  3921  3970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 16:54:51.222  3921  3970 D BluetoothAdapter: STATE_ON
,09-12 16:54:51.225  4329  4358 D BtGatt.GattService: registerClient() - UUID=043ff744-8bd3-4c2f-8926-3016f3d83869
,09-12 16:54:51.225  4329  4345 D BtGatt.GattService: onClientRegistered() - UUID=043ff744-8bd3-4c2f-8926-3016f3d83869, clientIf=5
09-12 16:54:51.225  3921  3933 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 16:54:51.226  4329  4367 D BtGatt.GattService: start scan with filters
,09-12 16:54:51.230  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 16:54:51.230  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 16:54:51.231  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 16:54:51.231  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 16:54:51.231  4329  4348 D BtGatt.ScanManager: handling starting scan
,09-12 16:54:51.236  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 16:54:51.236  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 16:54:51.236  3921  3921 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 16:54:51.238  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 16:54:51.247  4329  4345 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 16:54:51.247  4329  4345 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:54:51.248  4329  4348 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 16:54:51.263  4329  4345 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 16:54:51.263  4329  4345 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 16:54:51.264  4329  4348 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 16:54:51.264  4329  4348 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 16:54:51.292  4329  4345 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 16:54:51.292  4329  4345 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:54:51.309  4329  4345 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 16:54:51.310  4329  4345 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:54:51.667  3921  3921 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 16:54:51.737  3921  3921 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 16:54:51.737  3921  3921 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 16:54:51.738  3921  3921 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 16:54:52.813  4329  4329 D BtGatt.ScanManager: awakened up at time 235106
,09-12 16:54:52.815  4329  4348 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 16:54:52.863  4329  4345 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
09-12 16:54:52.863  4329  4345 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 16:54:52.864  4329  4345 D BtGatt.GattService: current time is 235157278137
,09-12 16:54:52.866  4329  4345 D BtGatt.GattService: Batch record : [87, 45, 110, 28, -13, -4, 1, -128, -71, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85, 0, -126, -22, -96, 83, -39, -56, 1, -128, -83, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65, 0, 71, -122, -77, 84, 69, -12, 1, -128, -97, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -92, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -106, -31, 36, -126, -97, 98, 1, -128, -54, 26, 0, 0, 0, -106, -31, 36, -126, -97, 98, 1, -128, -53, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 81, 34, 97, 112, -14, -5, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 16:54:52.869  4329  4345 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85]
,09-12 16:54:52.870  4329  4345 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65]
,09-12 16:54:52.870  4329  4345 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 16:54:52.871  4329  4345 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-12 16:54:52.871  4329  4345 D BtGatt.GattService: ScanRecord : []
09-12 16:54:52.871  4329  4345 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96],
09-12 16:54:52.871  4329  4345 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 16:54:52.872  4329  4345 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-12 16:54:52.874  3921  3921 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 1
09-12 16:54:52.875  3921  3921 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 1], added - the peer count is 2
,09-12 16:54:52.875  3921  3921 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:75:41 1], added - the peer count is 3
09-12 16:54:52.876  3921  3921 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
09-12 16:54:52.876  3921  3921 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
,09-12 16:54:52.877  3921  3921 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:75:41 1], Bluetooth address: 08:EC:A9:50:75:41, device name: '', device address: ''
,09-12 16:54:54.251  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 16:54:54.251  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 16:54:54.252  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 16:54:54.252  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:54.252  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 16:54:54.252  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 16:54:54.253  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 16:54:54.253  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 16:54:54.253  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 16:54:54.254  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 16:54:54.254  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 16:54:54.257  3921  3970 D BluetoothAdapter: STATE_ON
,09-12 16:54:54.259  4329  4371 D BtGatt.GattService: stopScan() - queue size =1
,09-12 16:54:54.262  4329  4358 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 16:54:54.263  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 16:54:54.263  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 16:54:54.263  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 16:54:54.264  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 16:54:54.264  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 16:54:54.267  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 16:54:54.267  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 16:54:54.268  3921  3970 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 16:54:54.268  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
09-12 16:54:54.269  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 16:54:54.270  3921  3970 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-12 16:54:54.271  4329  4329 D BtGatt.ScanManager: awakened up at time 236563
,09-12 16:54:54.272  3921  3921 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 16:54:54.273  3921  3921 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 16:54:54.273  3921  3921 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 16:54:54.273  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 16:54:54.274  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:54.274  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 16:54:54.275  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
09-12 16:54:54.275  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a761f0f removed from the list
09-12 16:54:54.275  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:54:54.275  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65bfb9c removed from the list
09-12 16:54:54.276  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:54:54.276  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:54:54.277  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:54.277  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:54:54.281  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 16:54:54.281  4329  4345 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 16:54:54.281  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:54:54.282  4329  4345 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 16:54:54.282  4329  4348 D BtGatt.ScanManager: stopping BLe Batch
,09-12 16:54:54.282  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:54:54.283  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65bfb9c not in the list
09-12 16:54:54.283  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:54.283  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:54:54.285  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:54:54.285  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:54:54.285  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:54:54.286  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65bfb9c not in the list,
09-12 16:54:54.286  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:54:54.286  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:54.286  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:54:54.287  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a761f0f not in the list
,09-12 16:54:54.288  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 16:54:54.289  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d22234 added. We now have 3 listener(s)
,09-12 16:54:54.294  4329  4345 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 16:54:54.294  4329  4345 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 16:54:54.294  4329  4348 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 16:54:54.296  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 16:54:54.296  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 16:54:54.296  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 16:54:54.297  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 16:54:54.297  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c985d added. We now have 4 listener(s)
,09-12 16:54:54.298  3921  3970 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 16:54:54.298  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 16:54:54.304  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 16:54:54.309  3921  3970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 16:54:54.309  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 16:54:54.309  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 16:54:54.309  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 16:54:54.309  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 16:54:54.309  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 16:54:54.309  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 16:54:54.309  3921  3970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 16:54:54.312  3921  3970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 16:54:54.312  3921  3970 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 16:54:54.312  4329  4345 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
09-12 16:54:54.312  4329  4345 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 16:54:54.312  3921  3970 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 16:54:54.313  4329  4345 D BtGatt.GattService: current time is 236605670090
09-12 16:54:54.313  4329  4345 D BtGatt.GattService: Batch record : [-106, -31, 36, -126, -97, 98, 1, -128, -61, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0]
09-12 16:54:54.313  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 16:54:54.313  3921  3970 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 16:54:54.313  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 16:54:54.313  4329  4345 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
09-12 16:54:54.313  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:54.314  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 16:54:54.314  3921  3970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 16:54:54.314  3921  3970 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d22234 removed from the list
,09-12 16:54:54.314  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:54:54.314  3921  3970 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c985d removed from the list
09-12 16:54:54.315  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:54.315  3921  3970 D io.jxcore.node.ConnectivityMonitor: stop
09-12 16:54:54.315  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:54:54.315  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:54.316  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:54:54.316  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 16:54:54.317  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:54:54.317  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:54:54.317  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c985d not in the list
,09-12 16:54:54.317  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:54.317  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 16:54:54.318  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 16:54:54.318  3921  3921 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 16:54:54.318  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 16:54:54.318  3921  3970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 16:54:54.318  3921  3970 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c985d not in the list
09-12 16:54:54.318  3921  3970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 16:54:54.318  3921  3970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 16:54:54.319  3921  3970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 16:54:54.319  3921  3970 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d22234 not in the list
09-12 16:54:54.320  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 16:54:54.320  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 16:54:54.320  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 16:54:54.320  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 16:54:54.320  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 16:54:54.320  3921  3970 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 16:54:54.774  3921  3921 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 16:54:56.335  3921  4428 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 483, name: My test thread name)
,09-12 16:54:58.333  3921  3970 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 483
,09-12 16:54:58.333  3921  3970 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 483, name: My test thread name)
,09-12 16:54:58.339  3921  4429 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 484, name: My test thread name)
,09-12 16:54:58.340  3921  4429 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 484, thread name: My test thread name)
09-12 16:54:58.340  3921  4429 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 484, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-12 16:54:58.344  3921  3970 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 16:54:58.352  3921  4428 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 483, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-12 16:54:58.355  3921  4430 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 488, name: My test thread name)
,09-12 16:54:58.356  3921  4430 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 488, thread name: My test thread name): Test exception.
09-12 16:54:58.357  3921  4430 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 488, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-12 16:54:58.364  3921  3970 I jxcore-log: Total number of executed tests:  82
09-12 16:54:58.364  3921  3970 I jxcore-log: 
,09-12 16:54:58.365  3921  3970 I jxcore-log: Number of passed tests:  82
09-12 16:54:58.365  3921  3970 I jxcore-log: 
09-12 16:54:58.366  3921  3970 I jxcore-log: Number of failed tests:  0
09-12 16:54:58.366  3921  3970 I jxcore-log: 
,09-12 16:54:58.367  3921  3970 I jxcore-log: Number of ignored tests:  0
09-12 16:54:58.367  3921  3970 I jxcore-log: 
09-12 16:54:58.367  3921  3970 I jxcore-log: Total duration:  101372
09-12 16:54:58.367  3921  3970 I jxcore-log: 
,09-12 16:54:58.377  3921  3970 I jxcore-log: Unit Test app is loaded
09-12 16:54:58.377  3921  3970 I jxcore-log: 
,09-12 16:54:58.395  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.395  3921  3970 I jxcore-log: 
,09-12 16:54:58.401  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.401  3921  3970 I jxcore-log: 
,09-12 16:54:58.402  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.402  3921  3970 I jxcore-log: 
,09-12 16:54:58.403  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.403  3921  3970 I jxcore-log: 
09-12 16:54:58.404  3921  3921 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-12 16:54:58.405  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 16:54:58.405  3921  3970 I jxcore-log: 
09-12 16:54:58.407  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 16:54:58.407  3921  3970 I jxcore-log: 
,09-12 16:54:58.409  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.409  3921  3970 I jxcore-log: 
,09-12 16:54:58.412  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.412  3921  3970 I jxcore-log: 
,09-12 16:54:58.413  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 16:54:58.413  3921  3970 I jxcore-log: 
,09-12 16:54:58.414  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 16:54:58.414  3921  3970 I jxcore-log: 
09-12 16:54:58.415  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 16:54:58.415  3921  3970 I jxcore-log: 
,09-12 16:54:58.416  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.416  3921  3970 I jxcore-log: 
09-12 16:54:58.416  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.416  3921  3970 I jxcore-log: 
09-12 16:54:58.417  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.417  3921  3970 I jxcore-log: 
,09-12 16:54:58.418  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 16:54:58.418  3921  3970 I jxcore-log: 
09-12 16:54:58.419  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 16:54:58.419  3921  3970 I jxcore-log: 
,09-12 16:54:58.420  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 16:54:58.420  3921  3970 I jxcore-log: 
09-12 16:54:58.421  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 16:54:58.421  3921  3970 I jxcore-log: 
,09-12 16:54:58.422  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 16:54:58.422  3921  3970 I jxcore-log: 
09-12 16:54:58.423  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 16:54:58.423  3921  3970 I jxcore-log: 
,09-12 16:54:58.424  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 16:54:58.424  3921  3970 I jxcore-log: 
09-12 16:54:58.425  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 16:54:58.425  3921  3970 I jxcore-log: 
,09-12 16:54:58.426  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 16:54:58.426  3921  3970 I jxcore-log: 
09-12 16:54:58.426  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.426  3921  3970 I jxcore-log: 
,09-12 16:54:58.427  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.427  3921  3970 I jxcore-log: 
09-12 16:54:58.428  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.428  3921  3970 I jxcore-log: 
,09-12 16:54:58.429  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 16:54:58.429  3921  3970 I jxcore-log: 
09-12 16:54:58.430  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 16:54:58.430  3921  3970 I jxcore-log: 
,09-12 16:54:58.431  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 16:54:58.431  3921  3970 I jxcore-log: 
09-12 16:54:58.432  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 16:54:58.432  3921  3970 I jxcore-log: 
09-12 16:54:58.432  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 16:54:58.432  3921  3970 I jxcore-log: 
,09-12 16:54:58.433  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 16:54:58.433  3921  3970 I jxcore-log: 
09-12 16:54:58.433  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 16:54:58.433  3921  3970 I jxcore-log: 
09-12 16:54:58.434  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 16:54:58.434  3921  3970 I jxcore-log: 
,09-12 16:54:58.434  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 16:54:58.434  3921  3970 I jxcore-log: 
09-12 16:54:58.435  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 16:54:58.435  3921  3970 I jxcore-log: 
09-12 16:54:58.435  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 16:54:58.435  3921  3970 I jxcore-log: 
,09-12 16:54:58.436  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 16:54:58.436  3921  3970 I jxcore-log: 
09-12 16:54:58.436  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 16:54:58.436  3921  3970 I jxcore-log: 
09-12 16:54:58.437  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 16:54:58.437  3921  3970 I jxcore-log: 
,09-12 16:54:58.437  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 16:54:58.437  3921  3970 I jxcore-log: 
09-12 16:54:58.438  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 16:54:58.438  3921  3970 I jxcore-log: 
09-12 16:54:58.438  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 16:54:58.438  3921  3970 I jxcore-log: 
,09-12 16:54:58.439  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.439  3921  3970 I jxcore-log: 
09-12 16:54:58.439  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.439  3921  3970 I jxcore-log: 
09-12 16:54:58.440  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.440  3921  3970 I jxcore-log: 
09-12 16:54:58.440  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.440  3921  3970 I jxcore-log: 
,09-12 16:54:58.441  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.441  3921  3970 I jxcore-log: 
09-12 16:54:58.441  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 16:54:58.441  3921  3970 I jxcore-log: 
09-12 16:54:58.442  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.442  3921  3970 I jxcore-log: 
09-12 16:54:58.442  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-12 16:54:58.442  3921  3970 I jxcore-log: 
,09-12 16:54:58.443  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.443  3921  3970 I jxcore-log: 
09-12 16:54:58.443  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 16:54:58.443  3921  3970 I jxcore-log: 
09-12 16:54:58.444  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 16:54:58.444  3921  3970 I jxcore-log: 
,09-12 16:54:58.445  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-12 16:54:58.445  3921  3970 I jxcore-log: 
09-12 16:54:58.445  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-12 16:54:58.445  3921  3970 I jxcore-log: 
09-12 16:54:58.446  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-12 16:54:58.446  3921  3970 I jxcore-log: 
,09-12 16:54:58.446  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 16:54:58.446  3921  3970 I jxcore-log: 
09-12 16:54:58.447  3921  3970 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 16:54:58.447  3921  3970 I jxcore-log: 
,09-12 16:54:58.452  3921  3970 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-12 16:54:58.452  3921  3970 I jxcore-log:   bluetooth: 'on',
09-12 16:54:58.452  3921  3970 I jxcore-log:   wifi: 'on',
09-12 16:54:58.452  3921  3970 I jxcore-log:   cellular: 'doNotCare',
09-12 16:54:58.452  3921  3970 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-12 16:54:58.452  3921  3970 I jxcore-log: 
,09-12 16:54:58.456  3921  3970 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-12 16:54:58.456  3921  3970 I jxcore-log:   bluetooth: 'on',
09-12 16:54:58.456  3921  3970 I jxcore-log:   wifi: 'on',
09-12 16:54:58.456  3921  3970 I jxcore-log:   cellular: 'doNotCare',
09-12 16:54:58.456  3921  3970 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-12 16:54:58.456  3921  3970 I jxcore-log: 
,09-12 16:54:58.457  3921  3970 I jxcore-log: My device name is: motorola-Nexus 6
09-12 16:54:58.457  3921  3970 I jxcore-log: 
09-12 16:54:58.458  3921  3970 I jxcore-log: Running for WIFI network type
09-12 16:54:58.458  3921  3970 I jxcore-log: 
,09-12 16:55:01.006  3921  3970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThatAlwaysPass.js
09-12 16:55:01.006  3921  3970 I jxcore-log: 
,09-12 16:55:01.019  3921  3970 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-12 16:55:01.020  3921  3970 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-12 16:55:01.020  3921  3970 I jxcore-log: 
,09-12 16:55:01.022  3921  3970 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-12 16:55:01.022  3921  3970 I jxcore-log: 
,09-12 16:55:01.023  3921  3970 I jxcore-log: ThaliTape :: Started ThaliTape
09-12 16:55:01.023  3921  3970 I jxcore-log: 
,09-12 16:55:01.027  3921  3970 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-12 16:55:01.027  3921  3970 I jxcore-log: 
,09-12 16:55:01.111  3921  3970 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 16:55:01.111  3921  3970 I jxcore-log: 
,09-12 16:55:01.111  3921  3970 I jxcore-log: websocket error
09-12 16:55:01.111  3921  3970 I jxcore-log: 
09-12 16:55:01.111  3921  3970 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 16:55:01.111  3921  3970 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 16:55:01.111  3921  3970 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 16:55:01.111  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:01.111  3921  3970 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 16:55:01.111  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:01.111  3921  3970 I jxcore-log: 
,09-12 16:55:01.959  3921  3970 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 16:55:01.959  3921  3970 I jxcore-log: 
,09-12 16:55:01.962  3921  3970 I jxcore-log: websocket error
09-12 16:55:01.962  3921  3970 I jxcore-log: 
,09-12 16:55:01.962  3921  3970 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 16:55:01.962  3921  3970 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 16:55:01.962  3921  3970 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 16:55:01.962  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:01.962  3921  3970 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 16:55:01.962  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:01.962  3921  3970 I jxcore-log: 
,09-12 16:55:03.039  3877  4431 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 16:55:03.067  3877  4432 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 16:55:03.085  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:55:03.090  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:55:03.135  1518  2089 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 16:55:03.135  1518  2089 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 16:55:03.135  1518  2089 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:55:03.135  1518  2089 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:55:03.183  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:55:03.188  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:55:03.238  1518  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 16:55:03.239  1518  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 16:55:03.239  1518  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 16:55:03.239  1518  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:55:03.272  3877  4432 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 16:55:03.274  3877  4431 E BooksSync: Soft error
09-12 16:55:03.274  3877  4431 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 16:55:03.274  3877  4431 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 16:55:03.278  3877  4431 E BooksSync: Sync error
09-12 16:55:03.278  3877  4431 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 16:55:03.278  3877  4431 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 16:55:03.278  3877  4431 I BooksSync: Finished books sync
,09-12 16:55:03.290   877   889 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 245264, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 16:55:04.025  3921  3970 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 16:55:04.025  3921  3970 I jxcore-log: 
,09-12 16:55:04.026  3921  3970 I jxcore-log: websocket error
09-12 16:55:04.026  3921  3970 I jxcore-log: 
,09-12 16:55:04.026  3921  3970 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 16:55:04.026  3921  3970 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 16:55:04.026  3921  3970 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 16:55:04.026  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:04.026  3921  3970 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 16:55:04.026  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:04.026  3921  3970 I jxcore-log: 
,09-12 16:55:09.078  3921  3970 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 16:55:09.078  3921  3970 I jxcore-log: 
09-12 16:55:09.078  3921  3970 I jxcore-log: websocket error
09-12 16:55:09.078  3921  3970 I jxcore-log: 
09-12 16:55:09.078  3921  3970 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 16:55:09.078  3921  3970 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 16:55:09.078  3921  3970 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 16:55:09.078  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:09.078  3921  3970 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 16:55:09.078  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:09.078  3921  3970 I jxcore-log: 
,09-12 16:55:12.765   877  4386 D NetlinkSocketObserver: NeighborEvent{elapsedMs=255057, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 16:55:14.136  3921  3970 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 16:55:14.136  3921  3970 I jxcore-log: 
,09-12 16:55:14.136  3921  3970 I jxcore-log: websocket error
09-12 16:55:14.136  3921  3970 I jxcore-log: 
,09-12 16:55:14.136  3921  3970 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 16:55:14.136  3921  3970 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 16:55:14.136  3921  3970 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 16:55:14.136  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:14.136  3921  3970 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 16:55:14.136  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:14.136  3921  3970 I jxcore-log: 
,09-12 16:55:19.118   877  4386 D NetlinkSocketObserver: NeighborEvent{elapsedMs=261410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 16:55:19.188  3921  3970 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 16:55:19.188  3921  3970 I jxcore-log: 
09-12 16:55:19.189  3921  3970 I jxcore-log: websocket error
09-12 16:55:19.189  3921  3970 I jxcore-log: 
,09-12 16:55:19.189  3921  3970 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 16:55:19.189  3921  3970 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 16:55:19.189  3921  3970 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 16:55:19.189  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:19.189  3921  3970 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 16:55:19.189  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:19.189  3921  3970 I jxcore-log: 
,09-12 16:55:24.251  3921  3970 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 16:55:24.251  3921  3970 I jxcore-log: 
09-12 16:55:24.251  3921  3970 I jxcore-log: websocket error
09-12 16:55:24.251  3921  3970 I jxcore-log: 
09-12 16:55:24.252  3921  3970 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 16:55:24.252  3921  3970 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 16:55:24.252  3921  3970 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 16:55:24.252  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:24.252  3921  3970 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 16:55:24.252  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:24.252  3921  3970 I jxcore-log: 
,09-12 16:55:29.313  3921  3970 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 16:55:29.313  3921  3970 I jxcore-log: 
,09-12 16:55:29.314  3921  3970 I jxcore-log: websocket error
09-12 16:55:29.314  3921  3970 I jxcore-log: 
09-12 16:55:29.314  3921  3970 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 16:55:29.314  3921  3970 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 16:55:29.314  3921  3970 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 16:55:29.314  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:29.314  3921  3970 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 16:55:29.314  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:29.314  3921  3970 I jxcore-log: 
,09-12 16:55:33.542  3192  4435 V KeepSync: Connecting to GoogleApiClient
,09-12 16:55:33.543   877  2002 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 16:55:33.608  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:55:33.614  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:55:33.647  1518  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 16:55:33.648  1518  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 16:55:33.648  1518  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:55:33.648  1518  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:55:33.671  1742  4436 V BaseAuthAsyncOperation: access token request failed
,09-12 16:55:33.673  3192  4435 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 16:55:33.742  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 16:55:33.742  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 16:55:33.742  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:55:33.742  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:55:33.767  3192  4435 E KeepSync: IOException
09-12 16:55:33.767  3192  4435 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 16:55:33.767  3192  4435 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 16:55:33.767  3192  4435 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 16:55:33.767  3192  4435 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 16:55:33.767  3192  4435 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 16:55:33.767  3192  4435 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 16:55:33.767  3192  4435 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 16:55:33.767  3192  4435 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 16:55:33.767  3192  4435 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 16:55:33.767  3192  4435 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 16:55:33.767  3192  4435 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 16:55:33.767  3192  4435 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 16:55:33.767  3192  4435 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 16:55:33.767  3192  4435 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 16:55:33.767  3192  4435 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 16:55:33.767  3192  4435 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 16:55:33.767  3192  4435 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 16:55:33.767  3192  4435 E KeepSync: 	... 10 more
,09-12 16:55:33.768  3192  4435 W KeepSync: Sync result 2
,09-12 16:55:33.780   877   889 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 256670, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 16:55:34.372  3921  3970 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 16:55:34.372  3921  3970 I jxcore-log: 
09-12 16:55:34.372  3921  3970 I jxcore-log: websocket error
09-12 16:55:34.372  3921  3970 I jxcore-log: 
,09-12 16:55:34.373  3921  3970 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 16:55:34.373  3921  3970 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 16:55:34.373  3921  3970 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 16:55:34.373  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:34.373  3921  3970 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 16:55:34.373  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:34.373  3921  3970 I jxcore-log: 
,09-12 16:55:39.431  3921  3970 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 16:55:39.431  3921  3970 I jxcore-log: 
,09-12 16:55:39.431  3921  3970 I jxcore-log: websocket error
09-12 16:55:39.431  3921  3970 I jxcore-log: 
,09-12 16:55:39.431  3921  3970 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 16:55:39.431  3921  3970 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 16:55:39.431  3921  3970 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 16:55:39.431  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:39.431  3921  3970 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 16:55:39.431  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:39.431  3921  3970 I jxcore-log: 
,09-12 16:55:44.512  3921  3970 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 16:55:44.512  3921  3970 I jxcore-log: 
09-12 16:55:44.512  3921  3970 I jxcore-log: websocket error
09-12 16:55:44.512  3921  3970 I jxcore-log: 
09-12 16:55:44.513  3921  3970 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 16:55:44.513  3921  3970 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 16:55:44.513  3921  3970 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 16:55:44.513  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:44.513  3921  3970 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 16:55:44.513  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:44.513  3921  3970 I jxcore-log: 
,09-12 16:55:49.573  3921  3970 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 16:55:49.573  3921  3970 I jxcore-log: 
,09-12 16:55:49.574  3921  3970 I jxcore-log: websocket error
09-12 16:55:49.574  3921  3970 I jxcore-log: 
09-12 16:55:49.575  3921  3970 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 16:55:49.575  3921  3970 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 16:55:49.575  3921  3970 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 16:55:49.575  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:49.575  3921  3970 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 16:55:49.575  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:49.575  3921  3970 I jxcore-log: 
,09-12 16:55:54.634  3921  3970 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 16:55:54.634  3921  3970 I jxcore-log: 
,09-12 16:55:54.634  3921  3970 I jxcore-log: websocket error
09-12 16:55:54.634  3921  3970 I jxcore-log: 
09-12 16:55:54.635  3921  3970 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 16:55:54.635  3921  3970 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 16:55:54.635  3921  3970 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 16:55:54.635  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:54.635  3921  3970 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 16:55:54.635  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:54.635  3921  3970 I jxcore-log: 
,09-12 16:55:59.685  3921  3970 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 16:55:59.685  3921  3970 I jxcore-log: 
,09-12 16:55:59.685  3921  3970 I jxcore-log: websocket error
09-12 16:55:59.685  3921  3970 I jxcore-log: 
,09-12 16:55:59.686  3921  3970 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 16:55:59.686  3921  3970 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 16:55:59.686  3921  3970 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 16:55:59.686  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:59.686  3921  3970 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 16:55:59.686  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:55:59.686  3921  3970 I jxcore-log: 
,09-12 16:56:01.332   877  4386 D NetlinkSocketObserver: NeighborEvent{elapsedMs=303624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 16:56:04.167  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:56:04.172  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:56:04.229  1518  2089 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 16:56:04.230  1518  2089 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 16:56:04.230  1518  2089 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:56:04.230  1518  2089 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:56:04.247  3686  4444 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 16:56:04.247  3686  4444 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at jdm.a(PG:82)
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at jcs.o(PG:406)
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at jcn.a(PG:1379)
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at jcs.i(PG:143)
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at blb.a(PG:3937)
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at czp.a(PG:18188)
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at czp.a(PG:9081)
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at czq.run(PG:1686)
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 16:56:04.247  3686  4444 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at jdj.a(PG:4091)
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at jdj.a(PG:1125)
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at jdm.a(PG:77)
09-12 16:56:04.247  3686  4444 E HttpOperation: 	... 12 more
09-12 16:56:04.247  3686  4444 E HttpOperation: Caused by: faj: BadAuthentication
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at fal.a(PG:38)
09-12 16:56:04.247  3686  4444 E HttpOperation: 	at jdj.a(PG:4089)
09-12 16:56:04.247  3686  4444 E HttpOperation: 	... 14 more
,09-12 16:56:04.325  1518  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-12 16:56:04.325  1518  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 16:56:04.325  1518  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:56:04.326  1518  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:56:04.353  3686  4444 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 16:56:04.353  3686  4444 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at jdm.a(PG:82)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at jcs.o(PG:406)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at jcn.a(PG:1379)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at jcs.i(PG:143)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at hec.a(PG:42)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at hee.a(PG:102)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at czr.a(PG:65)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at kka.a(PG:108)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at czp.a(PG:19176)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at czp.a(PG:9081)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at czq.run(PG:1686)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 16:56:04.353  3686  4444 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at jdj.a(PG:4091)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at jdj.a(PG:1125)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at jdm.a(PG:77)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	... 15 more
09-12 16:56:04.353  3686  4444 E HttpOperation: Caused by: faj: BadAuthentication
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at fal.a(PG:38)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	at jdj.a(PG:4089)
09-12 16:56:04.353  3686  4444 E HttpOperation: 	... 17 more
09-12 16:56:04.354  3686  4444 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 16:56:04.354  3686  4444 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at hec.a(PG:42)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at hee.a(PG:102)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at czr.a(PG:65)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at kka.a(PG:108)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	... 15 more
09-12 16:56:04.354  3686  4444 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at fal.a(PG:38)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 16:56:04.354  3686  4444 E ExperimentLoader: 	... 17 more
,09-12 16:56:04.495   877   889 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 291303, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-12 16:56:04.748  3921  3970 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 16:56:04.748  3921  3970 I jxcore-log: 
09-12 16:56:04.749  3921  3970 I jxcore-log: websocket error
09-12 16:56:04.749  3921  3970 I jxcore-log: 
,09-12 16:56:04.749  3921  3970 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 16:56:04.749  3921  3970 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 16:56:04.749  3921  3970 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 16:56:04.749  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:56:04.749  3921  3970 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 16:56:04.749  3921  3970 I jxcore-log: emit@events.js:82:1
09-12 16:56:04.749  3921  3970 I jxcore-log: 
,09-12 16:56:09.732   877  4386 D NetlinkSocketObserver: NeighborEvent{elapsedMs=312024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 16:56:09.867  3921  3970 I jxcore-log: ThaliTape :: Reconnected to the test server
09-12 16:56:09.867  3921  3970 I jxcore-log: 
,09-12 16:56:09.882  3921  3970 I jxcore-log: ThaliTape :: Connected to the test server
09-12 16:56:09.882  3921  3970 I jxcore-log: 
,09-12 16:56:34.592  3877  4457 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 16:56:34.638  3877  4458 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 16:56:34.658  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:56:34.661  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:56:34.679  3192  4456 V KeepSync: Connecting to GoogleApiClient
,09-12 16:56:34.680   877  1373 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 16:56:34.711  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 16:56:34.711  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 16:56:34.711  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 16:56:34.711  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:56:34.774  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:56:34.776  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:56:34.869  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 16:56:34.869  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-12 16:56:34.869  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:56:34.869  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:56:34.878  1518  2089 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 16:56:34.878  1518  2089 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 16:56:34.878  1518  2089 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 16:56:34.878  1518  2089 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:56:34.913  1742  4459 V BaseAuthAsyncOperation: access token request failed
,09-12 16:56:34.917  3192  4456 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 16:56:34.919  3877  4458 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 16:56:34.920  3877  4457 E BooksSync: Soft error
09-12 16:56:34.920  3877  4457 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 16:56:34.920  3877  4457 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 16:56:34.920  3877  4457 E BooksSync: Sync error
09-12 16:56:34.920  3877  4457 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 16:56:34.920  3877  4457 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 16:56:34.920  3877  4457 I BooksSync: Finished books sync
,09-12 16:56:34.929   877   889 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 310271, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 16:56:34.971  1518  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 16:56:34.971  1518  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-12 16:56:34.971  1518  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:56:34.971  1518  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:56:34.985  3192  4456 E KeepSync: IOException
09-12 16:56:34.985  3192  4456 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 16:56:34.985  3192  4456 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 16:56:34.985  3192  4456 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 16:56:34.985  3192  4456 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 16:56:34.985  3192  4456 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 16:56:34.985  3192  4456 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 16:56:34.985  3192  4456 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 16:56:34.985  3192  4456 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 16:56:34.985  3192  4456 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 16:56:34.985  3192  4456 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 16:56:34.985  3192  4456 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 16:56:34.985  3192  4456 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 16:56:34.985  3192  4456 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 16:56:34.985  3192  4456 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 16:56:34.985  3192  4456 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 16:56:34.985  3192  4456 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 16:56:34.985  3192  4456 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 16:56:34.985  3192  4456 E KeepSync: 	... 10 more
,09-12 16:56:34.986  3192  4456 W KeepSync: Sync result 2
,09-12 16:56:35.019   877   889 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 306931, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 16:56:42.282  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:56:42.294  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:56:42.297  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:56:42.333  1518  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 16:56:42.334  1518  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-12 16:56:42.334  1518  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 16:56:42.334  1518  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:56:42.359  1518  2294 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 16:56:42.359  1518  2294 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 16:56:42.359  1518  2294 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 16:56:42.359  1518  2294 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-12 16:56:42.359  1518  2294 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-12 16:56:42.359  1518  2294 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-12 16:56:42.359  1518  2294 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 16:56:42.368  3646  3677 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 16:56:42.368  3646  3677 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-12 16:56:42.368  3646  3677 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-12 16:56:42.368  3646  3677 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-12 16:56:42.368  3646  3677 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-12 16:56:42.368  3646  3677 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-12 16:56:42.368  3646  3677 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 16:57:05.344  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:57:05.345  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:57:05.391  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 16:57:05.391  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 16:57:05.392  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:57:05.392  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:57:05.410  3686  4465 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 16:57:05.410  3686  4465 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at jdm.a(PG:82)
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at jcs.o(PG:406)
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at jcn.a(PG:1379)
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at jcs.i(PG:143)
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at blb.a(PG:3937)
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at czp.a(PG:18188)
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at czp.a(PG:9081)
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at czq.run(PG:1686)
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 16:57:05.410  3686  4465 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at jdj.a(PG:4091)
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at jdj.a(PG:1125)
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at jdm.a(PG:77)
09-12 16:57:05.410  3686  4465 E HttpOperation: 	... 12 more
09-12 16:57:05.410  3686  4465 E HttpOperation: Caused by: faj: BadAuthentication
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at fal.a(PG:38)
09-12 16:57:05.410  3686  4465 E HttpOperation: 	at jdj.a(PG:4089)
09-12 16:57:05.410  3686  4465 E HttpOperation: 	... 14 more
,09-12 16:57:05.504  1518  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 16:57:05.504  1518  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 16:57:05.504  1518  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 16:57:05.504  1518  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:57:05.528  3686  4465 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 16:57:05.528  3686  4465 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at jdm.a(PG:82)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at jcs.o(PG:406)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at jcn.a(PG:1379)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at jcs.i(PG:143)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at hec.a(PG:42)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at hee.a(PG:102)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at czr.a(PG:65)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at kka.a(PG:108)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at czp.a(PG:19176)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at czp.a(PG:9081)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at czq.run(PG:1686)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 16:57:05.528  3686  4465 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at jdj.a(PG:4091)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at jdj.a(PG:1125)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at jdm.a(PG:77)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	... 15 more
09-12 16:57:05.528  3686  4465 E HttpOperation: Caused by: faj: BadAuthentication
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at fal.a(PG:38)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	at jdj.a(PG:4089)
09-12 16:57:05.528  3686  4465 E HttpOperation: 	... 17 more
,09-12 16:57:05.529  3686  4465 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 16:57:05.529  3686  4465 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at hec.a(PG:42)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at hee.a(PG:102)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at czr.a(PG:65)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at kka.a(PG:108)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	... 15 more
09-12 16:57:05.529  3686  4465 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at fal.a(PG:38)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 16:57:05.529  3686  4465 E ExperimentLoader: 	... 17 more
,09-12 16:57:05.662   877   889 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 339609, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-12 16:57:36.846  3192  4468 V KeepSync: Connecting to GoogleApiClient
09-12 16:57:36.847   877   887 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 16:57:36.914  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:57:36.917  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:57:36.969  1518  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 16:57:36.969  1518  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 16:57:36.969  1518  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:57:36.969  1518  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:57:37.009  1742  4469 V BaseAuthAsyncOperation: access token request failed
09-12 16:57:37.011  3192  4468 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 16:57:37.083  1518  2089 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-12 16:57:37.083  1518  2089 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 16:57:37.083  1518  2089 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:57:37.083  1518  2089 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:57:37.106  3192  4468 E KeepSync: IOException
09-12 16:57:37.106  3192  4468 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 16:57:37.106  3192  4468 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 16:57:37.106  3192  4468 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 16:57:37.106  3192  4468 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 16:57:37.106  3192  4468 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 16:57:37.106  3192  4468 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 16:57:37.106  3192  4468 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 16:57:37.106  3192  4468 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 16:57:37.106  3192  4468 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 16:57:37.106  3192  4468 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 16:57:37.106  3192  4468 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 16:57:37.106  3192  4468 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 16:57:37.106  3192  4468 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 16:57:37.106  3192  4468 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 16:57:37.106  3192  4468 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 16:57:37.106  3192  4468 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 16:57:37.106  3192  4468 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 16:57:37.106  3192  4468 E KeepSync: 	... 10 more
09-12 16:57:37.106  3192  4468 W KeepSync: Sync result 2
,09-12 16:57:37.125   877   889 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 399028, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 16:58:11.646  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:58:11.648  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 16:58:11.698  1518  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-12 16:58:11.699  1518  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 16:58:11.699  1518  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:58:11.699  1518  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:58:11.729  3686  4472 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 16:58:11.729  3686  4472 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at jdm.a(PG:82)
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at jcs.o(PG:406)
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at jcn.a(PG:1379)
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at jcs.i(PG:143)
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at blb.a(PG:3937)
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at czp.a(PG:18188)
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at czp.a(PG:9081)
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at czq.run(PG:1686)
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 16:58:11.729  3686  4472 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at jdj.a(PG:4091)
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at jdj.a(PG:1125)
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at jdm.a(PG:77)
09-12 16:58:11.729  3686  4472 E HttpOperation: 	... 12 more
09-12 16:58:11.729  3686  4472 E HttpOperation: Caused by: faj: BadAuthentication
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at fal.a(PG:38)
09-12 16:58:11.729  3686  4472 E HttpOperation: 	at jdj.a(PG:4089)
09-12 16:58:11.729  3686  4472 E HttpOperation: 	... 14 more
,09-12 16:58:11.817  1518  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-12 16:58:11.817  1518  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 16:58:11.817  1518  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 16:58:11.817  1518  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 16:58:11.835  3686  4472 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 16:58:11.835  3686  4472 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at jdm.a(PG:82)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at jcs.o(PG:406)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at jcn.a(PG:1379)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at jcs.i(PG:143)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at hec.a(PG:42)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at hee.a(PG:102)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at czr.a(PG:65)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at kka.a(PG:108)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at czp.a(PG:19176)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at czp.a(PG:9081)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at czq.run(PG:1686)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 16:58:11.835  3686  4472 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at jdj.a(PG:4091)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at jdj.a(PG:1125)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at jdm.a(PG:77)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	... 15 more
09-12 16:58:11.835  3686  4472 E HttpOperation: Caused by: faj: BadAuthentication
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at fal.a(PG:38)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	at jdj.a(PG:4089)
09-12 16:58:11.835  3686  4472 E HttpOperation: 	... 17 more
,09-12 16:58:11.836  3686  4472 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 16:58:11.836  3686  4472 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at hec.a(PG:42)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at hee.a(PG:102)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at czr.a(PG:65)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at kka.a(PG:108)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	... 15 more
09-12 16:58:11.836  3686  4472 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at fal.a(PG:38)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 16:58:11.836  3686  4472 E ExperimentLoader: 	... 17 more
,09-12 16:58:12.042   877   889 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 433597, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-12 16:58:13.344  3921  3970 I jxcore-log: TAP version 13
09-12 16:58:13.344  3921  3970 I jxcore-log: 
,09-12 16:58:13.348  3921  3970 I jxcore-log: # setup
09-12 16:58:13.348  3921  3970 I jxcore-log: 
,09-12 16:58:14.458  3921  3970 I jxcore-log: ok 1 (unnamed assert)
09-12 16:58:14.458  3921  3970 I jxcore-log: 
,09-12 16:58:14.464  3921  3970 I jxcore-log: # 1. The test that always pass
09-12 16:58:14.464  3921  3970 I jxcore-log: 
,09-12 16:58:15.266  3921  3970 I jxcore-log: ok 2 (unnamed assert)
09-12 16:58:15.266  3921  3970 I jxcore-log: 
,09-12 16:58:15.274  3921  3970 I jxcore-log: # teardown
09-12 16:58:15.274  3921  3970 I jxcore-log: 
,09-12 16:58:15.673  3921  3970 I jxcore-log: ok 3 (unnamed assert)
09-12 16:58:15.673  3921  3970 I jxcore-log: 
,09-12 16:58:16.515  3921  3970 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-12 16:58:16.515  3921  3970 I jxcore-log: 
,09-12 16:58:17.189  4475  4475 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-12 16:58:17.195  4475  4475 D AndroidRuntime: CheckJNI is OFF
,09-12 16:58:17.237  4475  4475 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-12 16:58:17.286  4475  4475 I Radio-JNI: register_android_hardware_Radio DONE
,09-12 16:58:17.309  4475  4475 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-12 16:58:17.320   877   890 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-12 16:58:17.321   877   890 I ActivityManager: Killing 3921:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-12 16:58:17.446   877   900 W PackageSettings: Skipping PackageSetting{43ac723 com.example.hello/10273} due to missing metadata
,09-12 16:58:17.483   877  2002 D GraphicsStats: Buffer count: 2
,09-12 16:58:17.483   877  1399 I WindowState: WIN DEATH: Window{c3f1d06 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-12 16:58:17.485   877  1311 D WifiService: Client connection lost with reason: 4
,09-12 16:58:17.492   877   900 I art     : Starting a blocking GC Explicit
,09-12 16:58:17.543   877   890 E libprocessgroup: failed to kill 1 processes for processgroup 3921
,09-12 16:58:17.544   877   890 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-12 16:58:17.544   877   890 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-12 16:58:17.545   877   890 E ActivityManager: Failure starting process com.test.thalitest
09-12 16:58:17.545   877   890 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-12 16:58:17.545   877   890 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-12 16:58:17.545   877   890 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-12 16:58:17.545   877   890 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-12 16:58:17.545   877   890 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-12 16:58:17.545   877   890 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-12 16:58:17.545   877   890 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-12 16:58:17.545   877   890 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-12 16:58:17.545   877   890 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-12 16:58:17.545   877   890 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-12 16:58:17.545   877   890 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-12 16:58:17.545   877   890 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-12 16:58:17.545   877   890 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-12 16:58:17.545   877   890 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-12 16:58:17.545   877   890 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-12 16:58:17.545   877   890 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 16:58:17.545   877   890 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:58:17.545   877   890 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 16:58:17.545   877   890 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 16:58:17.546   877   890 I ActivityManager:   Force finishing activity ActivityRecord{c8c63ef u0 com.test.thalitest/.MainActivity t4}
09-12 16:58:17.550   877  2002 W ActivityManager: Spurious death for ProcessRecord{f624ee2 0:com.test.thalitest/u0a0}, curProc for 3921: null
,09-12 16:58:17.555   877   900 I art     : Explicit concurrent mark sweep GC freed 52035(3MB) AllocSpace objects, 9(180KB) LOS objects, 33% free, 29MB/43MB, paused 948us total 58.128ms
,09-12 16:58:17.579   877   900 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-12 16:58:17.582  4475  4475 I art     : System.exit called, status: 0
09-12 16:58:17.582  4475  4475 I AndroidRuntime: VM exiting with result code 0.
,09-12 16:58:17.588   877   900 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-12 16:58:17.602   877   890 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-12 16:58:17.605  4329  4329 D BluetoothMapAppObserver: onReceive
,09-12 16:58:17.606  4329  4329 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-12 16:58:17.611  2139  2283 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-12 16:58:17.616   877  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-12 16:58:17.616  3765  3765 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-12 16:58:17.630  1877  1877 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-12 16:58:17.636  1877  4487 I Keyboard.Facilitator.DecoderInitializer: run()
,09-12 16:58:17.638  1877  4487 I Decoder : createOrResetDecoder
,09-12 16:58:17.653  1959  1959 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-12 16:58:17.656   877  3279 I ActivityManager: Start proc 4489:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-12 16:58:17.673  1518  1518 I ConfigService: onCreate
,09-12 16:58:17.691  1877  4487 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-12 16:58:17.695   877   877 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-12 16:58:17.717  1877  4487 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-12 16:58:17.719  1877  4487 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-12 16:58:17.719  1877  4487 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-12 16:58:17.720   877   887 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3921 uid 10000
,09-12 16:58:17.721  1877  1877 I Keyboard.Facilitator: onFinishInput()
09-12 16:58:17.721  1973  2077 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-12 16:58:17.723   877   889 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-12 16:58:17.724   877   889 E PackageManager: Failed to write settings, restoring backup
09-12 16:58:17.724   877   889 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-12 16:58:17.724   877   889 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-12 16:58:17.724   877   889 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-12 16:58:17.724   877   889 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-12 16:58:17.724   877   889 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-12 16:58:17.724   877   889 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 16:58:17.724   877   889 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:58:17.724   877   889 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 16:58:17.726  4489  4489 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-12 16:58:17.727  1877  4487 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-12 16:58:17.728  1877  4487 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-12 16:58:17.728  1877  4487 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-12 16:58:17.728  1877  4487 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-12 16:58:17.728   877   890 E DropBoxManagerService: Can't write: system_server_wtf
09-12 16:58:17.728   877   890 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 16:58:17.728   877   890 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 16:58:17.728   877   890 E DropBoxManagerService: 	... 13 more
09-12 16:58:17.729  1877  4487 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-12 16:58:17.729  1877  4487 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-12 16:58:17.729  1877  4487 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-12 16:58:17.729  1877  4487 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,09-12 16:58:17.729  1877  4487 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,09-12 16:58:17.729  1877  4487 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-12 16:58:17.734   877  2000 I ActivityManager: Start proc 4504:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-12 16:58:17.735  1973  2077 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-12 16:58:17.735  1973  2077 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1973
09-12 16:58:17.735  1973  2077 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 16:58:17.735  1973  2077 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 16:58:17.735  1973  2077 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 16:58:17.735  1973  2077 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 16:58:17.735  1973  2077 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 16:58:17.735  1973  2077 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 16:58:17.735  1973  2077 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-12 16:58:17.735  1973  2077 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-12 16:58:17.735  1973  2077 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 16:58:17.735  1973  2077 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 16:58:17.735  1973  2077 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:58:17.735  1973  2077 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 16:58:17.737   877  1373 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 16:58:17.737   877  4509 E DropBoxManagerService: Can't write: system_app_crash
09-12 16:58:17.737   877  4509 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-12 16:58:17.737   877  4509 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 16:58:17.737   877  4509 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 16:58:17.737   877  4509 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 16:58:17.737   877  4509 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 16:58:17.737   877  4509 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 16:58:17.737   877  4509 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 16:58:17.737   877  4509 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 16:58:17.737   877  4509 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 16:58:17.737   877  4509 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 16:58:17.737   877  4509 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 16:58:17.737   877  4509 E DropBoxManagerService: 	... 5 more
,09-12 16:58:17.740  1973  2077 I Process : Sending signal. PID: 1973 SIG: 9
,09-12 16:58:17.782  4489  4489 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-12 16:58:17.791   877  3279 D GraphicsStats: Buffer count: 1
,09-12 16:58:17.791   877  1958 I WindowState: WIN DEATH: Window{b6d25c4 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-12 16:58:17.801   877  1942 I ActivityManager: Start proc 4521:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-12 16:58:17.825  4489  4520 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-12 16:58:17.829   877  2000 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1973) has died
,09-12 16:58:17.829  4489  4518 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	,at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:58:17.829  4489  4518 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 16:58:17.829   877  2000 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms,
09-12 16:58:17.830   877  2000 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-12 16:58:17.848   877   890 I ActivityManager: Start proc 4534:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:58:17.877  4489  4518 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 16:58:17.880  4521  4521 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-12 16:58:17.892  4534  4534 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 16:58:17.892  4534  4534 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 16:58:17.893  4534  4534 D AndroidRuntime: Shutting down VM
,09-12 16:58:17.902  4534  4534 E AndroidRuntime: FATAL EXCEPTION: main
09-12 16:58:17.902  4534  4534 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4534
09-12 16:58:17.902  4534  4534 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 16:58:17.902  4534  4534 E AndroidRuntime: 	... 10 more
,09-12 16:58:17.906   877  3384 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 16:58:17.907  4534  4534 I Process : Sending signal. PID: 4534 SIG: 9
,09-12 16:58:17.914   877  4548 E DropBoxManagerService: Can't write: system_app_crash
09-12 16:58:17.914   877  4548 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-12 16:58:17.914   877  4548 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 16:58:17.914   877  4548 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 16:58:17.914   877  4548 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 16:58:17.914   877  4548 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 16:58:17.914   877  4548 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 16:58:17.914   877  4548 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 16:58:17.914   877  4548 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 16:58:17.914   877  4548 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 16:58:17.914   877  4548 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 16:58:17.914   877  4548 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 16:58:17.914   877  4548 E DropBoxManagerService: 	... 5 more
,09-12 16:58:17.924  1742  4547 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-12 16:58:17.925  1742  4547 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-12 16:58:17.929  1742  4547 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-12 16:58:17.930  1742  4547 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-12 16:58:17.939  1518  1518 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-12 16:58:17.943  1518  1518 D AndroidRuntime: Shutting down VM
,09-12 16:58:17.946  1518  1518 E AndroidRuntime: FATAL EXCEPTION: main
09-12 16:58:17.946  1518  1518 E AndroidRuntime: Process: com.google.process.gapps, PID: 1518
09-12 16:58:17.946  1518  1518 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-12 16:58:17.946  1518  1518 E AndroidRuntime: 	... 8 more
,09-12 16:58:17.947   877  1373 I ActivityManager: Killing 3825:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-12 16:58:17.972  4489  4518 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-12 16:58:17.977  4489  4520 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:58:17.977  4489  4520 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 16:58:17.978  4489  4520 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-12 16:58:17.978  4489  4520 E AndroidRuntime: Process: android.process.acore, PID: 4489
09-12 16:58:17.978  4489  4520 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 16:58:17.978  4489  4520 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 16:58:17.979  4489  4518 I Process : Sending signal. PID: 4489 SIG: 9
,09-12 16:58:17.989   877  1934 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4534) has died
,09-12 16:58:17.990   877  1934 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-12 16:58:18.002   877  4552 E DropBoxManagerService: Can't write: system_app_crash
09-12 16:58:18.002   877  4552 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-12 16:58:18.002   877  4552 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 16:58:18.002   877  4552 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 16:58:18.002   877  4552 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 16:58:18.002   877  4552 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 16:58:18.002   877  4552 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 16:58:18.002   877  4552 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 16:58:18.002   877  4552 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 16:58:18.002   877  4552 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 16:58:18.002   877  4552 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 16:58:18.002   877  4552 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 16:58:18.002   877  4552 E DropBoxManagerService: 	... 5 more
,09-12 16:58:18.024   877   890 I ActivityManager: Start proc 4553:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 16:58:18.027   877  1958 I ActivityManager: Process android.process.acore (pid 4489) has died
,09-12 16:58:18.028   877  1958 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-12 16:58:18.034  1518  1518 I Process : Sending signal. PID: 1518 SIG: 9
09-12 16:58:18.036   877  4558 E DropBoxManagerService: Can't write: system_app_crash
09-12 16:58:18.036   877  4558 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-12 16:58:18.036   877  4558 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 16:58:18.036   877  4558 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 16:58:18.036   877  4558 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 16:58:18.036   877  4558 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 16:58:18.036   877  4558 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 16:58:18.036   877  4558 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 16:58:18.036   877  4558 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 16:58:18.036   877  4558 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 16:58:18.036   877  4558 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 16:58:18.036   877  4558 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 16:58:18.036   877  4558 E DropBoxManagerService: 	... 5 more
,09-12 16:58:18.090   877  1311 D WifiService: Client connection lost with reason: 4

```
